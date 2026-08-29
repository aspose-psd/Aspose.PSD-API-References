---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα LayerMaskData. Λαμβάνει ή ορίζει το Rectangle της μάσκας στρώσης στο αρχείο PSD. Παίρνει τις ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί Rectangle."
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Λαμβάνει ή ορίζει τη μάσκα [`Rectangle`](../../../aspose.psd/rectangle/) της μάσκας στρώσης στο αρχείο PSD. Παίρνει τις ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί [`Rectangle`](../../../aspose.psd/rectangle/).

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

Το rectangle της μάσκας.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λαμβάνετε, ενημερώνετε, αφαιρείτε και προσθέτετε raster μάσκες στρώσης στο αρχείο Adobe® Photoshop® προγραμματιστικά.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Λαμβάνει την τιμή int μετατρεπόμενη σε σειρά byte big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Λαμβάνει την τιμή μετατρεπόμενη από big-endian σε Int32.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// Λαμβάνει μια raster μάσκα από τη στρώση μιας εικόνας PSD και την αποθηκεύει σε αρχείο.
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// Προσθέτει μια raster μάσκα από το αρχείο στη στρώση και την αποθηκεύει ως εικόνα μορφής PSD.
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // Η απλή προσθήκη του LayerMaskData δεν είναι αρκετή για σωστή αποθήκευση επειδή τα κανάλια δεν ενημερώνονται;
    // layer.LayerMaskData = mask; // Αυτό δεν προσθέτει το κανάλι μάσκας

    // Προσθήκη (ή ενημέρωση) της μάσκας
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Αυτό το παράδειγμα δείχνει πώς να λαμβάνετε, ενημερώνετε, αφαιρείτε και προσθέτετε raster μάσκες στρώσης στο αρχείο Adobe® Photoshop® προγραμματιστικά.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Λάβετε μια raster μάσκα από τη στρώση και αποθηκεύστε την σε αρχείο
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Αλλάξτε τη μάσκα στρώσης (αντιστροφή) και αποθηκεύστε την εικόνα
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Η απλή αλλαγή του LayerMaskData είναι αρκετή για να επηρεάσει την απόδοση
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Αλλά η απλή αλλαγή του LayerMaskData δεν είναι αρκετή για σωστή αποθήκευση επειδή τα κανάλια δεν ενημερώνονται;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Αφαιρέστε μια raster μάσκα από τη στρώση και αποθηκεύστε την εικόνα
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Προσθέστε μια raster μάσκα από το αρχείο στη στρώση και αποθηκεύστε την εικόνα
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Δείτε επίσης

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)



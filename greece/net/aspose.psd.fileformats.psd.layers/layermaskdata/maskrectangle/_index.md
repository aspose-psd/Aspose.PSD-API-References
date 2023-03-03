---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD για Αναφορά API .NET
description: LayerMaskData ιδιοκτησία. Παίρνει ή ρυθμίζει τη μάσκαRectangleτης μάσκας στρώματος στο αρχείο PSD. Παίρνει ιδιότητες αριστερά δεξιά πάνω και κάτω και δημιουργείRectangle
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Παίρνει ή ρυθμίζει τη μάσκα[`Rectangle`](../../../aspose.psd/rectangle/)της μάσκας στρώματος στο αρχείο PSD. Παίρνει ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Αξία περιουσίας

Το ορθογώνιο της μάσκας.

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς μπορείτε να λάβετε, να ενημερώσετε, να αφαιρέσετε και να προσθέσετε μάσκες επιπέδου ράστερ στο αρχείο Adobe® Photoshop® μέσω προγραμματισμού.

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

// Μετατρέπει την τιμή int σε σειρά byte big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Λαμβάνει την τιμή που μετατρέπεται από το μεγάλο endian σε Int32.
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

// Λαμβάνει μια μάσκα ράστερ από το επίπεδο μιας εικόνας PSD και την αποθηκεύει σε ένα αρχείο
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

// Προσθέτει μια μάσκα ράστερ από το αρχείο στο επίπεδο και αποθηκεύει την εικόνα μορφής PSD
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

    // Η απλή προσθήκη LayerMaskData δεν αρκεί για τη σωστή αποθήκευση επειδή τα κανάλια δεν ενημερώνονται.
    // layer.LayerMaskData = μάσκα; // Αυτό δεν προσθέτει το κανάλι μάσκας

    // Προσθήκη (ή ενημέρωση) της μάσκας
    layer.AddLayerMask(maskData); // Αλλά αυτό προσθέτει / ενημερώνει τόσο τη μάσκα όσο και τα κανάλια!
}

// Αυτό το παράδειγμα δείχνει πώς μπορείτε να λάβετε, να ενημερώσετε, να αφαιρέσετε και να προσθέσετε μάσκες επιπέδου ράστερ στο αρχείο Adobe® Photoshop® μέσω προγραμματισμού.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Λάβετε μια μάσκα ράστερ από το επίπεδο και αποθηκεύστε την σε ένα αρχείο
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Αλλάξτε τη μάσκα στρώματος (αντιστροφή) και αποθηκεύστε την εικόνα
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Αρκεί η αλλαγή του LayerMaskData για να πραγματοποιηθεί η απόδοση
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Αλλά μόνο η αλλαγή του LayerMaskData δεν αρκεί για σωστή αποθήκευση επειδή τα κανάλια δεν ενημερώνονται.
    layer.LayerMaskData = mask; // Ούτε αυτό λειτουργεί
    layer.AddLayerMask(mask); // Αλλά αυτό ενημερώνει τόσο τη μάσκα όσο και τα κανάλια!
    image.Save("FourWithMasksUpdated2.psd");

    // Αφαιρέστε μια μάσκα ράστερ από το επίπεδο και αποθηκεύστε την εικόνα
    layer.LayerMaskData = null; // Απλώς η αφαίρεση LayerMaskData αρκεί για να πραγματοποιηθεί η απόδοση, αλλά όχι για αποθήκευση σε μορφή PSD
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Αλλά αυτό αφαιρεί τόσο τη μάσκα όσο και το κανάλι μάσκας!
    image.Save("FourWithMasksRemoved2.psd");

    // Προσθέστε μια μάσκα ράστερ από το αρχείο στο επίπεδο και αποθηκεύστε την εικόνα
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Δείτε επίσης

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* συνέλευση [Aspose.PSD](../../../)



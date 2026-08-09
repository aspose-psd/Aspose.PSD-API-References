---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété LayerMaskData. Obtient ou définit le Rectangle du masque du calque dans le fichier PSD. Elle prend les propriétés gauche, droite, haut et bas et crée un Rectangle"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Obtient ou définit le masque [`Rectangle`](../../../aspose.psd/rectangle/) du masque de calque dans le fichier PSD. Elle prend les propriétés gauche, droite, haut et bas et crée un [`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

Le rectangle du masque.

## Exemples

Cet exemple montre comment obtenir, mettre à jour, supprimer et ajouter des masques de calque raster dans le fichier Adobe® Photoshop® de manière programmatique.

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

// Obtient la valeur int convertie en ordre d'octets big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Obtient la valeur convertie du big-endian en Int32.
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

// Obtient un masque raster à partir du calque d'une image PSD et l'enregistre dans un fichier
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

// Ajoute un masque raster du fichier au calque et l'enregistre dans l'image au format PSD
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

    // Le simple ajout de LayerMaskData n'est pas suffisant pour un enregistrement correct car les canaux ne sont pas mis à jour;
    // layer.LayerMaskData = mask; // Cela n'ajoute pas le canal du masque

    // Ajouter (ou mettre à jour) le masque
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Cet exemple montre comment obtenir, mettre à jour, supprimer et ajouter des masques de calque raster dans le fichier Adobe® Photoshop® de manière programmatique.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Obtenir un masque raster du calque et l'enregistrer dans un fichier
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Modifier le masque de calque (inverser) et enregistrer l'image
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Le simple changement de LayerMaskData suffit à affecter le rendu
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Mais le simple changement de LayerMaskData n'est pas suffisant pour un enregistrement correct car les canaux ne sont pas mis à jour;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Supprimer un masque raster du calque et enregistrer l'image
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Ajouter un masque raster du fichier au calque et enregistrer l'image
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Voir aussi

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)



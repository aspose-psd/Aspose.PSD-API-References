---
title: MaskRectangle
second_title: Référence de l'API Aspose.PSD pour .NET
description: Obtient ou définit le masqueRectangleaspose.psd/rectangledu masque de calque dans le fichier PSD. Il prend les propriétés gauche droite haut et bas et créeRectangleaspose.psd/rectangle
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Obtient ou définit le masque[`Rectangle`](../../../aspose.psd/rectangle)du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, haut et bas et crée[`Rectangle`](../../../aspose.psd/rectangle)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Valeur de la propriété

Le rectangle de masque.

### Exemples

Cet exemple montre comment obtenir, mettre à jour, supprimer et ajouter par programmation des masques de calque raster dans le fichier Adobe® Photoshop®.

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

string dataDir = "PSDNET640_1" + Path.DirectorySeparatorChar;

// Obtient la valeur int convertie en ordre d'octets gros-boutien.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Obtient la valeur convertie du gros boutien en Int32.
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

// Ajoute un masque raster du fichier au calque et l'enregistre au format PSD
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

    // Le simple fait d'ajouter LayerMaskData n'est pas suffisant pour une sauvegarde correcte car les canaux ne sont pas mis à jour ;
    // couche.LayerMaskData = masque ; // Cela n'ajoute pas le canal de masque

    // Ajoute (ou met à jour) le masque
    layer.AddLayerMask(maskData); // Mais cela ajoute/met à jour à la fois le masque et les canaux !
}

// Cet exemple montre comment obtenir, mettre à jour, supprimer et ajouter par programmation des masques de calque raster dans le fichier Adobe® Photoshop®.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
Directory.CreateDirectory(dataDir);
var sourceFilePath = dataDir + "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Récupère un masque raster du calque et l'enregistre dans un fichier
    SaveRasterMask(dataDir + "FourWithMasks2.msk", layer);

    // Changer le masque de calque (inverser) et enregistrer l'image
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Il suffit de changer LayerMaskData pour effectuer le rendu
    image.Save(dataDir + "FourWithMasksUpdated2.png", pngOptions);

    // Mais le simple fait de changer LayerMaskData n'est pas suffisant pour une sauvegarde correcte car les canaux ne sont pas mis à jour ;
    layer.LayerMaskData = mask; // Cela ne marche pas non plus
    layer.AddLayerMask(mask); // Mais cela met à jour à la fois le masque et les canaux !
    image.Save(dataDir + "FourWithMasksUpdated2.psd");

    // Supprime un masque raster du calque et enregistre l'image
    layer.LayerMaskData = null; // Il suffit de supprimer LayerMaskData pour effectuer le rendu mais pas pour enregistrer au format PSD
    image.Save(dataDir + "FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Mais cela supprime à la fois le masque et le canal de masque !
    image.Save(dataDir + "FourWithMasksRemoved2.psd");

    // Ajoute un masque raster du fichier au calque et enregistre l'image
    AddRasterMask(layer, dataDir + "raster.msk");
    image.Save(dataDir + "FourWithMasksAdded2.png", pngOptions);
    image.Save(dataDir + "FourWithMasksAdded2.psd");
}
```

### Voir également

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [LayerMaskData](../../layermaskdata)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

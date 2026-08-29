---
title: "LinkResource.Item"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "LinkResource propriété. Obtient le LinkDataSource à l'index spécifié qui est l'identifiant unique de la source de données de lien"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
{{< psd/tize >}}
## LinkResource indexer

Obtient le [`LinkDataSource`](../../linkdatasource/) à l'index spécifié qui est l'identifiant unique de la source de données de lien..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| Paramètre | Description |
| --- | --- |
| index | L'index en tant qu'identifiant unique de la source de données de lien. |

### Valeur de retour

L'instance du [`LinkDataSource`](../../linkdatasource/).

### Property Value

Le [`LinkDataSource`](../../linkdatasource/).

## Exemples

Le code suivant démontre la prise en charge des objets dynamiques intégrés.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Cet exemple montre comment modifier le calque d'objet dynamique dans le fichier PSD et exporter / mettre à jour le contenu intégré original de l'objet dynamique.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Exportons l'image d'objet dynamique intégré depuis le calque d'objet dynamique du PSD
        smartObjectLayer.ExportContents(exportPath);

        // Vérifions si l'image originale est enregistrée correctement
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Inversons l'image originale de l'objet dynamique
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Remplaçons l'image d'objet dynamique intégré dans le calque PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Vérifions si l'image mise à jour est enregistrée correctement
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Voir aussi

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)



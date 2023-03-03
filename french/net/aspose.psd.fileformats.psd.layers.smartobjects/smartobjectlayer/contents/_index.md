---
title: SmartObjectLayer.Contents
second_title: Référence de l'API Aspose.PSD pour .NET
description: SmartObjectLayer propriété. Obtient ou définit le contenu de la couche dobjet intelligent. Le contenu de lobjet intelligent intégré est le fichier dimage brute intégré Data et ses propriétés. Le contenu de lobjet intelligent lié est le contenu brut du fichier image lié sil est disponible et ses propriétés LiFeDataSource . Nous ne prenons pas en charge le chargement à partir de la bibliothèque graphique Adobe Photoshop  lorsqueIsLibraryLink est vrai. Pour les fichiers de liens réguliers nous utilisons dabordRelativePath pour rechercher le fichier relativement au chemin de limage sourceSourceImagePath  sil nest pas disponible nous regardonsFullPath  sinon alors nous cherchons le fichier de lien dans le même répertoire où se trouve notre image SourceImagePath .
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Obtient ou définit le contenu de la couche d'objet intelligent. Le contenu de l'objet intelligent intégré est le fichier d'image brute intégré :[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) et ses propriétés. Le contenu de l'objet intelligent lié est le contenu brut du fichier image lié s'il est disponible et ses propriétés :[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Nous ne prenons pas en charge le chargement à partir de la bibliothèque graphique Adobe� Photoshop� �� lorsque[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) est vrai. Pour les fichiers de liens réguliers, nous utilisons d'abord[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) pour rechercher le fichier relativement au chemin de l'image sourceSourceImagePath , s'il n'est pas disponible nous regardons[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , sinon alors nous cherchons le fichier de lien dans le même répertoire où se trouve notre image :SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Valeur de la propriété

Lebyte[] contenu de la couche d'objets intelligents.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Impossible d'obtenir le contenu de la bibliothèque Adobe� Photoshop� ��. |

### Exemples

Le code suivant illustre la prise en charge des objets intelligents intégrés.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Cet exemple montre comment modifier le calque d'objet intelligent dans le fichier PSD et exporter/mettre à jour le contenu intégré d'origine de l'objet intelligent.
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

        // Exportons l'image de l'objet intelligent intégré à partir du calque d'objet intelligent PSD
        smartObjectLayer.ExportContents(exportPath);

        // Vérifions si l'image d'origine est correctement enregistrée
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Inversons l'image originale de l'objet intelligent
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Remplaçons l'image de l'objet intelligent intégré dans la couche PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Vérifions si l'image mise à jour est correctement enregistrée
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Voir également

* class [SmartObjectLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* Assemblée [Aspose.PSD](../../../)



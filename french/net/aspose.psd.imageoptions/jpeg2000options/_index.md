---
title: Jpeg2000Options
second_title: Référence de l'API Aspose.PSD pour .NET
description: Les options de format de fichier Jpeg2000.
type: docs
weight: 4760
url: /fr/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Les options de format de fichier Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Initialise une nouvelle instance du[`Jpeg2000Options`](../jpeg2000options) classe. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Initialise une nouvelle instance du[`Jpeg2000Options`](../jpeg2000options) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec) { get; set; } | Obtient ou définit le codec JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments) { get; set; } | Obtient ou définit les marqueurs de commentaire Jpeg. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios) { get; set; } | Obtient ou définit le tableau de taux de compression. Différents taux de compression pour les couches successives. Le taux spécifié pour chaque niveau de qualité est le facteur de compression souhaité. Diminution des taux requis. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation au format raster, si la police de calque existante dans le fichier PSD n'est pas présentée dans le système). Pour prendre le nom propre de la police par défaut, vous pouvez utiliser le prochain extrait de code : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible) { get; set; } | Obtient ou définit une valeur indiquant si vous utilisez la compression DWT 9-7 irréversible (vrai) ou utilisez la compression DWT 5-3 sans perte (par défaut). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Supprime l'instance actuelle. |

### Exemples

Cet exemple illustre l'utilisation de différentes classes de l'espace de noms SaveOptions à des fins d'exportation. Une image de type Psd est chargée dans une instance de Image puis exportée vers plusieurs formats.

```csharp
[C#]

//Charger une image existante dans une instance de la classe Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Exporter au format de fichier BMP en utilisant les options par défaut
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    // Exporter au format de fichier JPEG en utilisant les options par défaut
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    // Exporter au format de fichier JPEG 2000 en utilisant les options par défaut
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    // Exporter au format de fichier PNG en utilisant les options par défaut
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    // Exporter au format de fichier TIFF en utilisant les options par défaut
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* espace de noms [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

---
title: Class GifOptions
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.ImageOptions.GifOptions classe. Les options de création de format de fichier gif.
type: docs
weight: 4810
url: /fr/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Les options de création de format de fichier gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Initialise une nouvelle instance du`GifOptions` classe. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Initialise une nouvelle instance du`GifOptions` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Obtient ou définit l'index de couleur d'arrière-plan GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Obtient ou définit la résolution de couleur GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation au format raster, si la police de calque existante dans le fichier PSD n'est pas présentée dans le système). Pour prendre le nom propre de la police par défaut, vous pouvez utiliser le prochain extrait de code : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Obtient ou définit une valeur indiquant si le GIF a une bande-annonce. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Vrai si l'image doit être entrelacée. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Obtient ou définit une valeur indiquant si les entrées de la palette sont triées. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Obtient ou définit la différence de pixels maximale autorisée. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression optimale avec perte est de 80. 30 est une compression très légère, 200 est lourde. Cela fonctionne mieux lorsque seule une faible perte est introduite, et en raison de la limitation de l'algorithme de compression des niveaux de perte très élevés ne donneront pas autant de gain. La plage de valeurs autorisées est [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Obtient ou définit le format des pixels GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |

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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* espace de noms [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* Assemblée [Aspose.PSD](../../)



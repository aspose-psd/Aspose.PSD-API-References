---
title: "Classe GifOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageOptions.GifOptions. Les options de création du format de fichier gif"
type: docs
weight: 5300
url: /fr/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

Les options de création du format de fichier GIF.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Initialise une nouvelle instance de la classe `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Initialise une nouvelle instance de la classe `GifOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Obtient ou définit l'index de couleur d'arrière-plan du GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Obtient ou définit la résolution de couleur du GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Obtient ou définit une valeur indiquant si le GIF possède un segment final. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Vrai si l'image doit être entrelacée. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Obtient ou définit une valeur indiquant si les entrées de palette sont triées. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Obtient ou définit la différence maximale autorisée entre les pixels. Si elle est supérieure à zéro, une compression avec perte sera utilisée. La valeur recommandée pour une compression avec perte optimale est de 80. 30 correspond à une compression très légère, 200 à une compression lourde. Elle fonctionne mieux lorsqu'une perte minime est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain. L'intervalle des valeurs autorisées est [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Obtient ou définit le rapport d'aspect des pixels du GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de rasterisation vectorielle. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

## Exemples

Cet exemple montre l'utilisation de différentes classes du namespace SaveOptions à des fins d'exportation. Une image de type Psd est chargée dans une instance de Image, puis exportée vers plusieurs formats.

```csharp
[C#]

//Chargez une image existante dans une instance de la classe Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exportez au format de fichier BMP en utilisant les options par défaut
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exportez au format de fichier JPEG en utilisant les options par défaut
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exportez au format de fichier JPEG 2000 en utilisant les options par défaut
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exportez au format de fichier PNG en utilisant les options par défaut
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exportez au format de fichier TIFF en utilisant les options par défaut
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Voir aussi

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



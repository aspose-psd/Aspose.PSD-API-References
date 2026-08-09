---
title: "Classe JpegOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageOptions.JpegOptions. Les options de création du format de fichier jpeg"
type: docs
weight: 5330
url: /fr/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

Les options de création du format de fichier jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Initialise une nouvelle instance de la classe `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Initialise une nouvelle instance de la classe `JpegOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Obtient ou définit le nombre de bits par canal pour une image jpeg sans perte. Nous supportons désormais de 2 à 8 bits par canal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Le profil couleur CMYK de destination pour les images jpeg CMYK. Utilisé pour enregistrer les images. Doit être associé à RGBColorProfile pour une conversion de couleur correcte. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Obtient ou définit le type de couleur pour l'image jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Obtient ou définit le commentaire du fichier jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Obtient ou définit le type de compression. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Obtient ou définit la limite d'allocation mémoire par défaut. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Obtenir ou définir le conteneur de données exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Obtient ou définit les sous-échantillonnages horizontaux pour chaque composant. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Obtient ou définit le jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Obtient ou définit la borne de différence JPEG-LS pour le codage quasi-sans perte (paramètre NEAR de la spécification JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Obtient ou définit le mode d'entrelacement JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Obtient ou définit les paramètres prédéfinis JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Obtient ou définit une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière-plan, si le canal alpha est présent. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Obtient ou définit la qualité de l'image. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Obtient ou définit les paramètres de l'optimiseur RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Obtient ou définit l'unité de résolution. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Le profil de couleur RGB de destination pour les images JPEG CMYK. À utiliser lors de l'enregistrement des images. Doit être associé à CMYKColorProfile pour une conversion de couleur correcte. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Obtient ou définit le mode d'arrondi d'échantillon pour adapter une valeur de 8 bits à une valeur de n bits. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | La qualité mise à l'échelle. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de rasterisation vectorielle. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Obtient ou définit les sous-échantillonnages verticaux pour chaque composant. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

## Exemples

Cet exemple montre l'utilisation de Aspose.PSD pour l'API .Net afin de convertir des images au format JPEG. Pour atteindre cet objectif, cet exemple charge une image existante puis la convertit au format de fichier JPEG.

```csharp
[C#]

//Crée une instance de la classe image et l'initialise avec un fichier existant via le chemin du fichier.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Créez une instance de la classe PsdOptions.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Définissez la qualité à 50 % pour réduire la taille de l'image de sortie.
    jpegOptions.Quality = 50;

    //Définissez les commentaires EXIF.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Enregistrez l'image à l'emplacement disque avec les paramètres JpegOptions fournis.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Cet exemple montre l'utilisation de System.IO.Stream pour créer un nouveau fichier Image.

```csharp
[C#]

//Crée une instance de PsdOptions et définit ses différentes propriétés.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créez une instance de System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Définissez la propriété source pour l'instance de PsdOptions.
//Le deuxième paramètre booléen détermine si le Stream est libéré une fois sorti de la portée.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crée une instance d'Image et appelle la méthode Create avec PsdOptions comme paramètre pour initialiser l'objet Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Effectuez un traitement d'image.
}
```

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



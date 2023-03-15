---
title: Class TiffOptions
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.ImageOptions.TiffOptions classe. Les options de format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de limage par les paramètres de largeur et de hauteur il nest donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut mais cela ne signifie pas que cette option est définie explicitement en tant que valeur de balise. Pour vérifier que la balise est présente utilisez la propriété Tags ou la méthode IsTagPresent correspondante.
type: docs
weight: 4940
url: /fr/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Les options de format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de l'image par les paramètres de largeur et de hauteur, il n'est donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut, mais cela ne signifie pas que cette option est définie explicitement en tant que valeur de balise. Pour vérifier que la balise est présente, utilisez la propriété Tags ou la méthode IsTagPresent correspondante.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initialise une nouvelle instance du`TiffOptions` classe. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initialise une nouvelle instance du`TiffOptions` classe. Par défaut, la convention Little Endian est utilisée. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initialise une nouvelle instance du`TiffOptions` classe. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialise une nouvelle instance du`TiffOptions` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Obtient ou définit l'option de stockage alpha. Options autres queUnspecified sont utilisés lorsqu'il y a plus de 3[`SamplesPerPixel`](./samplesperpixel/) défini. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Obtient ou définit l'artiste. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Obtient les bits par pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Obtient ou définit les bits par échantillon. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Obtient ou définit une valeur indiquant l'ordre des octets tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Obtient ou définit la qualité de l'image compressée. Utilisé avec la compression Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Obtient ou définit la compression. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Obtient ou définit le copyright. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Obtient ou définit la date et l'heure. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation au format raster, si la police de calque existante dans le fichier PSD n'est pas présentée dans le système). Pour prendre le nom propre de la police par défaut, vous pouvez utiliser le prochain extrait de code : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Obtient ou définit le nom du document. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Obtient ou définit le pointeur sur EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Obtient ou définit les options de télécopie t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Obtient ou définit la norme de fichier TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [plein cadre]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Obtient ou définit les indices de demi-teintes. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Obtient ou définit le flux de profil Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Obtient ou définit la description de l'image. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Obtient ou définit la longueur de l'image. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Obtient ou définit la largeur de l'image. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Obtient ou définit les noms d'encre. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Obtient une valeur indiquant si l'image est en mosaïque. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Obtient une valeur indiquant si le`TiffOptions` ont été correctement configurés. Utilisez la méthode Validate as pour trouver la raison de l'échec. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Obtient ou définit la valeur maximale de l'échantillon. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Obtient ou définit la valeur minimale de l'échantillon. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Obtient ou définit l'orientation. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Obtient ou définit le nom de la page. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Obtient ou définit la balise de numéro de page. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Obtient ou définit la photométrie. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Obtient ou définit la configuration planaire. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Obtient ou définit le prédicteur pour la compression LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Obtient ou définit l'unité de résolution. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Obtient ou définit les lignes par bande. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Obtient ou définit le format de l'échantillon. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Obtient les échantillons par pixel. Pour modifier cette valeur de propriété, utilisez le[`BitsPerSample`](./bitspersample/) propriété setter. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Obtient ou définit le fabricant du scanner. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Obtient ou définit le modèle du scanner. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Obtient ou définit la valeur maximale de l'échantillon. La valeur a un type de champ qui correspond le mieux aux exemples de données (type Byte, Short ou Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Obtient ou définit la valeur minimale de l'échantillon. La valeur a un type de champ qui correspond le mieux aux exemples de données (type Byte, Short ou Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Obtient ou définit le type de logiciel. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Obtient ou définit le nombre d'octets de bande. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Obtient ou définit les décalages de bande. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Obtient ou définit les balises. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Obtient ou définit l'imprimante cible. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Obtient ou définit le seuil. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Obtient ou définit le nombre d'octets de mosaïque. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Obtient ou définit la longueur des tuiles. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Obtient ou définit les décalages de mosaïque. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Obtient ou définit la largeur des tuiles. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Obtient le nombre total de pages. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Obtient le nombre de balises valides. Il ne s'agit pas du nombre total de balises mais du nombre de balises pouvant être conservées. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de pixellisation vectorielle. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Obtient ou définit l'auteur de l'image, qui est utilisé par l'Explorateur Windows. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Obtient ou définit un commentaire sur l'image, qui est utilisé par l'Explorateur Windows. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Obtient ou définit l'image du sujet, qui est utilisée par l'Explorateur Windows. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Obtient ou définit la position x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Obtient ou définit des informations sur l'image, utilisées par l'Explorateur Windows. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Obtient ou définit des informations sur l'image, utilisées par l'Explorateur Windows. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Obtient ou définit la résolution x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Obtient ou définit les YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Obtient ou définit la position y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Obtient ou définit la résolution y. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Ajoute une nouvelle balise. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Ajoute les balises. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Obtient l'instance de la balise par type. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Détermine si le tag est présent ou non dans les options. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Supprime la balise. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Valide si les options ont une combinaison valide de balises |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Obtient le nombre de balises valides. |

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

Ces exemples utilisent GraphicsPath et la classe Graphics pour créer et manipuler des figures sur une surface Image. L'exemple crée une nouvelle image et dessine des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour restituer les chemins sur la surface. Enfin, l'image est exportée au format de fichier Tiff.

```csharp
[C#]

//Créer une instance de Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créer et initialiser une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Effacer la surface graphique
    graphics.Clear(Color.Wheat);

    //Créer une instance de la classe GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créer une instance de la classe Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Ajouter des formes à l'objet Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Ajouter un objet Figure à GraphicsPath
    graphicspath.AddFigure(figure);

    // Dessine un chemin avec un objet Pen de couleur noire
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Créer une instance de TiffOptions et définir ses différentes propriétés
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Enregistrer toutes les modifications.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Voir également

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* espace de noms [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* Assemblée [Aspose.PSD](../../)



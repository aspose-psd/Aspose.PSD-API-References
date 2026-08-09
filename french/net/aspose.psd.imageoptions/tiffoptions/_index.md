---
title: "Classe TiffOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageOptions.TiffOptions. Les options du format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de l'image par les paramètres de largeur et de hauteur, il n'est donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut, mais cela ne signifie pas que cette option est définie explicitement comme valeur de balise. Pour vérifier que la balise est présente, utilisez la propriété Tags ou la méthode correspondante IsTagPresent."
type: docs
weight: 5430
url: /fr/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

Les options du format de fichier tiff. Notez que les balises de largeur et de hauteur seront écrasées lors de la création de l'image par les paramètres de largeur et de hauteur, il n'est donc pas nécessaire de les spécifier directement. Notez que de nombreuses options renvoient une valeur par défaut, mais cela ne signifie pas que cette option est définie explicitement comme une valeur de balise. Pour vérifier que la balise est présente, utilisez la propriété Tags ou la méthode correspondante IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Initialise une nouvelle instance de la classe `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Initialise une nouvelle instance de la classe `TiffOptions`. Par défaut, la convention little endian est utilisée. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Initialise une nouvelle instance de la classe `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialise une nouvelle instance de la classe `TiffOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Obtient ou définit l'option de stockage alpha. Les options autres que Unspecified sont utilisées lorsqu'il y a plus de 3 [`SamplesPerPixel`](./samplesperpixel/) définis. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Obtient ou définit l'artiste. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Obtient les bits par pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Obtient ou définit les bits par échantillon. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Obtient ou définit une valeur indiquant l'ordre des octets tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Obtient ou définit la table de couleurs. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Obtient ou définit la qualité d'image compressée. Utilisé avec la compression Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Obtient ou définit la compression. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Obtient ou définit le droit d'auteur. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Obtient ou définit la date et l'heure. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Obtient ou définit la limite d'allocation mémoire par défaut. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Obtient ou définit le nom du document. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Obtient ou définit le pointeur vers l'IFD EXIF. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Obtient ou définit les options fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Obtient ou définit la norme du fichier TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Obtient ou définit les indications de tramage. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Obtient ou définit le flux du profil Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Obtient ou définit la description de l'image. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Obtient ou définit la longueur de l'image. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Obtient ou définit la largeur de l'image. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Obtient ou définit les noms d'encre. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Obtient une valeur indiquant si l'image est découpée en tuiles. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Obtient une valeur indiquant si le `TiffOptions` a été correctement configuré. Utilisez la méthode Validate pour trouver la raison de l'échec. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Obtient ou définit la valeur maximale de l'échantillon. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Obtient ou définit la valeur minimale de l'échantillon. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Obtient ou définit l'orientation. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Obtient ou définit le nom de la page. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Obtient ou définit le tag du numéro de page. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Obtient ou définit le photométrique. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Obtient ou définit la configuration planaire. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Obtient ou définit le prédicteur pour la compression LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Obtient ou définit l'unité de résolution. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Obtient ou définit le nombre de lignes par bande. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Obtient ou définit le format d'échantillon. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Obtient les échantillons par pixel. Pour modifier la valeur de cette propriété, utilisez le mutateur de propriété [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Obtient ou définit le fabricant du scanner. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Obtient ou définit le modèle du scanner. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Obtient ou définit la valeur d'échantillon maximale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Obtient ou définit la valeur d'échantillon minimale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Obtient ou définit le type de logiciel. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Obtient ou définit le nombre d'octets par bande. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Obtient ou définit les décalages de bande. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Obtient ou définit les balises. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Obtient ou définit l'imprimante cible. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Obtient ou définit le seuillage. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Obtient ou définit le nombre d'octets par tuile. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Obtient ou définit la longueur de la tuile. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Obtient ou définit les décalages de tuile. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Obtient ou définit la largeur de la tuile. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Obtient le nombre total de pages. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Obtient le nombre de balises valides. Ce n'est pas le nombre total de balises mais le nombre de balises pouvant être conservées. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de rasterisation vectorielle. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Obtient ou définit l'auteur de l'image, utilisé par Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Obtient ou définit le commentaire de l'image, utilisé par Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Obtient ou définit le sujet de l'image, utilisé par Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Obtient ou définit la position x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Obtient ou définit les informations sur l'image, utilisée par Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Obtient ou définit les informations sur l'image, utilisée par Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Obtient ou définit la résolution x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Obtient ou définit les YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Obtient ou définit les facteurs de sous-échantillonnage pour la photométrie YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Obtient ou définit la position y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Obtient ou définit la résolution y. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Ajoute une nouvelle balise. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Ajoute les balises. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Obtient l'instance de la balise par type. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Détermine si la balise est présente dans les options ou non. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Supprime la balise. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Valide si les options ont une combinaison valide de balises. |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Obtient le nombre d'étiquettes valides. |

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

Ces exemples utilisent les classes GraphicsPath et Graphics pour créer et manipuler des Figures sur une surface Image. L'exemple crée une nouvelle Image et trace des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour rendre les chemins sur la surface. Enfin, l'image est exportée au format de fichier Tiff.

```csharp
[C#]

//Créez une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Créez une instance de la classe GraphicsPath.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créez une instance de la classe Figure.
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Ajoutez des formes à l'objet Figure.
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Ajoutez l'objet Figure à GraphicsPath.
    graphicspath.AddFigure(figure);

    //Dessinez le chemin avec l'objet Pen de couleur Noir.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Créez une instance de TiffOptions et définissez ses différentes propriétés.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Enregistrez toutes les modifications.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Voir aussi

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



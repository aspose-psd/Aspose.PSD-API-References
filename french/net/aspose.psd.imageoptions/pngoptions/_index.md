---
title: "Classe PngOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageOptions.PngOptions. Les options de création du format de fichier png"
type: docs
weight: 5370
url: /fr/net/aspose.psd.imageoptions/pngoptions/
---
{{< psd/tize >}}
## PngOptions class

Les options de création du format de fichier png.

```csharp
public class PngOptions : ImageOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | Initialise une nouvelle instance de la classe `PngOptions`. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | Initialise une nouvelle instance de la classe `PngOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | La profondeur de bits. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | Obtient ou définit le type de la couleur. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | Le niveau de compression de l'image png dans la plage 0-9, où 9 représente la compression maximale et 0 le mode stockage. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | Obtient ou définit le type de filtre utilisé lors du processus d'enregistrement du fichier png. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | Obtient ou définit une valeur indiquant si ce `PngOptions` est progressif. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de rasterisation vectorielle. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

## Champs

| Nom | Description |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | Le niveau de compression par défaut. |

## Exemples

L'exemple suivant montre comment vous pouvez exporter un fichier AI au format PSD et PNG dans Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
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

L'exemple suivant montre comment vous pouvez utiliser le mode de fusion de calque PassThrough dans Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

L'exemple suivant montre que la progression de la conversion de document fonctionne correctement et sans exception.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface de l'Image. Pour démontrer l'opération, l'exemple crée une nouvelle Image au format PSD et dessine des formes primitives sur la surface de l'Image en utilisant les méthodes Draw exposées par la classe Graphics, puis l'exporte au format de fichier PSD.

```csharp
[C#]

//Créez une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
    //un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dessinez une courbe de Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dessinez une courbe en spécifiant l'objet Pen de couleur verte et un tableau de points
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dessinez une ellipse en utilisant l'objet Pen et un rectangle entourant
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dessinez une ligne 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dessinez un segment de secteur
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dessinez un polygone en spécifiant l'objet Pen de couleur rouge et un tableau de points
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dessinez un rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Créez un objet SolidBrush et définissez ses différentes propriétés
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dessinez une chaîne en utilisant l'objet SolidBrush et la police, à un point spécifique
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Créez une instance de PngOptions et définissez ses différentes propriétés
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Enregistrez toutes les modifications.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Voir aussi

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



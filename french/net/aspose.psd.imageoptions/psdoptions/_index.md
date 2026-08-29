---
title: "Classe PsdOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageOptions.PsdOptions. Les options de création du format de fichier PSD."
type: docs
weight: 5390
url: /fr/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

Les options de création du format de fichier psd.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Initialise une nouvelle instance de la classe `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Initialise une nouvelle instance de la classe `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Initialise une nouvelle instance de la classe `PsdOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | Obtient ou définit la couleur d'arrière-plan. Elle peut être vue sous les objets transparents. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Obtient ou définit le nombre de bits par canal de couleur. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Obtient ou définit le nombre de canaux de couleur. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Obtient ou définit le mode couleur du PSD. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Obtient ou définit la méthode de compression du PSD. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Obtient ou définit la version du format de fichier. Il peut s'agir de PSD ou PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD. Veuillez noter que le rendu des calques de texte dans la mise en page finale n'est pas pris en charge sur la plateforme Compact Framework. |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer dans le fichier ouvert avec Photoshop : Menu \"Text\" -&gt; \"Process absent fonts\". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner des modifications de la mise en page finale. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Obtient ou définit les ressources du PSD. Si la valeur : NULL - alors enregistrer les ImageResources d'origine (comportement par défaut) Non vide - alors enregistrer les ressources passées à cette propriété + [required resources] Vide - alors seules les [required resources] seront enregistrées. Ressources requises : ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | Obtient ou définit une valeur indiquant si [update metadata]. Si la valeur est vraie, les métadonnées seront mises à jour lors de l'enregistrement de l'image. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de rasterisation vectorielle. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Obtient ou définit la version du fichier PSD. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Obtenir ou définir le conteneur de données XMP |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

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

Cet exemple crée un nouveau fichier Image à un emplacement disque spécifié par la propriété Source de l'instance PsdOptions. Plusieurs propriétés de l'instance PsdOptions sont définies avant la création de l'image réelle. En particulier la propriété Source, qui fait référence à l'emplacement disque réel dans ce cas.

```csharp
[C#]

//Créez une instance de PsdOptions et définissez ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créez une instance de FileCreateSource et assignez‑la comme Source pour l'instance de PsdOptions
//Le deuxième paramètre booléen détermine si le fichier à créer est temporaire (IsTemporal) ou non
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Créez une instance d'Image et initialisez‑la avec une instance de PsdOptions en appelant la méthode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Effectuez un traitement d'image.

    // enregistrez toutes les modifications
    image.Save();
}
```

L'exemple suivant montre que la lecture et l'enregistrement des fichiers PSD en niveaux de gris 16 bits vers du RGB 16 bits par canal fonctionnent correctement et sans exception.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Il ne devrait y avoir aucune exception ici.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

L'exemple suivant montre que la lecture et l'enregistrement des fichiers PSD en niveaux de gris 16 bits vers du niveaux de gris 8 bits par canal fonctionnent correctement et sans exception.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Il ne devrait y avoir aucune exception ici.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
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

Cet exemple montre comment charger les informations de pixels dans un tableau de type Color, manipuler le tableau et le réaffecter à l'image. Pour effectuer ces opérations, cet exemple crée un nouveau fichier Image (au format PSD) en utilisant l'objet MemoryStream.

```csharp
[C#]

//Créez une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créez une instance de PsdOptions et définissez ses différentes propriétés, y compris la propriété Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Créez une instance d'Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Obtenez les pixels de l'image en spécifiant la zone comme limite de l'image
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Parcourez le tableau et définissez la couleur du pixel indexé alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Définissez la couleur du pixel indexé sur jaune
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Définissez la couleur du pixel indexé sur bleu
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Appliquez les modifications de pixels à l'image
        image.SavePixels(image.Bounds, pixels);

        // Enregistrez toutes les modifications.
        image.Save();
    }

    //Écrivez le MemoryStream dans un fichier
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

L'exemple suivant montre que la lecture et l'enregistrement des fichiers PSD en niveaux de gris 16 bits fonctionnent correctement et sans exception.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // Il ne devrait y avoir aucune exception ici.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### Voir aussi

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



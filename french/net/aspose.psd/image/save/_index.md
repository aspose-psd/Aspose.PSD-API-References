---
title: "Image.Save"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Image. Enregistre les données de l'image dans le flux sous-jacent"
type: docs
weight: 240
url: /fr/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

Enregistre les données de l'image dans le flux sous-jacent.

```csharp
public void Save()
```

### Voir aussi

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |

## Exemples

L'exemple suivant montre comment vous pouvez exporter des fichiers Adobe Illustrator au format PDF dans Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

L'exemple suivant montre que AsposePSD prend en charge l'exportation des fichiers PSB vers le format PSD.

```csharp
[C#]

// Prise en charge de l'enregistrement des PSB en PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Le code suivant enregistre PsdImage en document PDF avec du texte sélectionnable.

```csharp
[C#]

// Enregistrer un PSD en PDF ne fournit pas de texte sélectionnable
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

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

L'exemple suivant montre que l'alignement du texte via ITextPortion pour les langues de droite à gauche fonctionne correctement.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

Cet exemple montre les étapes simples pour enregistrer une image. Pour démontrer cette opération, nous chargeons un fichier existant depuis un emplacement disque, effectuons une rotation de l'image et enregistrons l'image au format Jpeg en utilisant File Path.

```csharp
[C#]

//Créez une instance de la classe image et initialisez‑la avec un fichier existant via File path.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Faire pivoter l'image de 180 degrés autour de l'axe X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Enregistrez l'image au format Jpeg dans File Path avec les paramètres par défaut de JpegOptions.
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

L'exemple suivant montre comment vous pouvez modifier la visibilité du LayerGroup dans Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// apportez des modifications aux noms des calques et enregistrez-le
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Désactivez tout à l'intérieur d'un groupe
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

L'exemple suivant montre comment vous pouvez dessiner sur une couche nouvellement créée si la version simple du constructeur est utilisée dans Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // dessinez un rectangle avec l'outil Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dessinez un autre rectangle avec Solid Brush en couleur bleue
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| options | ImageOptionsBase | Les options. |
| boundsRectangle | Rectangle | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | options |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Échec de l'enregistrement de l'image. |

### Voir aussi

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux où enregistrer les données de l'image. |
| optionsBase | ImageOptionsBase | Les options d'enregistrement. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Impossible d'enregistrer au format spécifié car il n'est pas pris en charge pour le moment.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Échec de l'exportation de l'image. |

## Exemples

Cet exemple montre le processus d'enregistrement d'une image dans un MemoryStream. Pour démontrer cette opération, l'exemple charge un fichier existant depuis un emplacement disque, effectue une rotation de l'image et enregistre l'image au format Gif.

```csharp
[C#]

//Créez une instance de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Créez une instance de la classe image et initialisez‑la avec un fichier existant via File path.
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Faire pivoter l'image de 180 degrés autour de l'axe X
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Enregistrez l'image au format PSD dans un MemoryStream avec les paramètres par défaut de GifOptions.
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Voir aussi

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux où enregistrer les données de l'image. |
| optionsBase | ImageOptionsBase | Les options d'enregistrement. |
| boundsRectangle | Rectangle | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Impossible d'enregistrer au format spécifié car il n'est pas pris en charge pour le moment.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Échec de l'exportation de l'image. |

### Voir aussi

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



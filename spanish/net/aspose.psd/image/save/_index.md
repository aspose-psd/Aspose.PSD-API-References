---
title: "Image.Save"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Image. Guarda los datos de la imagen en el flujo subyacente"
type: docs
weight: 240
url: /es/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

Guarda los datos de la imagen en el flujo subyacente.

```csharp
public void Save()
```

### Ver también

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| opciones | ImageOptionsBase | Las opciones. |

## Ejemplos

El siguiente ejemplo muestra cómo puedes exportar archivos de Adobe Illustrator al formato PDF en Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

El siguiente ejemplo demuestra que AsposePSD admite la exportación de archivos PSB a formato PSD.

```csharp
[C#]

// Soporta guardar PSB como PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

El siguiente código guarda PsdImage como documento PDF con texto seleccionable.

```csharp
[C#]

// Guardar PSD en PDF no proporciona texto seleccionable
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

El siguiente ejemplo muestra cómo puede exportar un archivo AI a formato PSD y PNG en Aspose.PSD

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

El siguiente ejemplo demuestra que la alineación de texto mediante ITextPortion para idiomas de derecha a izquierda funciona correctamente.

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

Este ejemplo muestra los pasos simples para Save una Image. Para demostrar esta operación, cargamos un archivo existente desde alguna ubicación del disco, realizamos la operación Rotate en la Image y Save la Image en formato Jpeg usando File Path

```csharp
[C#]

//Crea una instancia de la clase image e inicialízala con un archivo existente mediante File path
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Girar la imagen 180 grados alrededor del eje X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Guarda la Image como Jpeg en File Path con la configuración predeterminada de JpegOptions
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

El siguiente ejemplo muestra cómo puedes cambiar la visibilidad de LayerGroup en Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// realiza cambios en los nombres de las capas y guárdalo
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Desactiva todo dentro de un grupo
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

El siguiente ejemplo muestra cómo puedes dibujar en una capa recién creada si se usa la versión simple del constructor en Aspose.PSD

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

    // dibujar un rectángulo con la herramienta Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dibujar otro rectángulo con Solid Brush en color azul
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

El siguiente ejemplo demuestra que leer y guardar los archivos PSD en escala de grises de 16 bits a RGB de 16 bits por canal funciona correctamente y sin excepciones.

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
    // Aquí no debería haber ninguna excepción.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

El siguiente ejemplo demuestra que leer y guardar los archivos PSD en escala de grises de 16 bits a escala de grises de 8 bits por canal funciona correctamente y sin excepciones.

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
    // Aquí no debería haber ninguna excepción.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

El siguiente ejemplo muestra cómo puede usar el modo de fusión de capa PassThrough en Aspose.PSD

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

El siguiente ejemplo demuestra que el progreso de conversión del documento funciona correctamente y sin excepciones.

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

El siguiente ejemplo demuestra que la lectura y el guardado de los archivos Grayscale 16 bit PSD files funciona correctamente y sin una excepción.

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
        // Aquí no debería haber ninguna excepción.
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

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| opciones | ImageOptionsBase | Las opciones. |
| boundsRectangle | Rectangle | El rectángulo de límites de la image de destino. Establece el rectángulo vacío para usar los límites de origen. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | opciones |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Error al guardar la imagen. |

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo al que guardar los datos de la imagen. |
| optionsBase | ImageOptionsBase | Las opciones de guardado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | No se puede guardar en el formato especificado porque no está soportado en este momento.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Error al exportar la imagen. |

## Ejemplos

Este ejemplo muestra el proceso de guardar una Imagen en MemoryStream. Para demostrar esta operación, el ejemplo carga un archivo existente desde alguna ubicación del disco, realiza la operación Rotate en la imagen y guarda la imagen en formato Gif.

```csharp
[C#]

//Cree una instancia de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea una instancia de la clase image e inicialízala con un archivo existente mediante File path
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Girar la imagen 180 grados alrededor del eje X
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Guarde la Imagen como PSD en MemoryStream con la configuración predeterminada de GifOptions.
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo al que guardar los datos de la imagen. |
| optionsBase | ImageOptionsBase | Las opciones de guardado. |
| boundsRectangle | Rectangle | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | No se puede guardar en el formato especificado porque no está soportado en este momento.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Error al exportar la imagen. |

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



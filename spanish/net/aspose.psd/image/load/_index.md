---
title: Image.Load
second_title: Referencia de API de Aspose.PSD para .NET
description: Image método. Carga una nueva imagen del archivo especificado.
type: docs
weight: 20
url: /es/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

Carga una nueva imagen del archivo especificado.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde el que cargar la imagen. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Valor_devuelto

La imagen cargada.

### Ver también

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

Carga una nueva imagen del archivo especificado.

```csharp
public static Image Load(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde el que cargar la imagen. |

### Valor_devuelto

La imagen cargada.

### Ejemplos

Este ejemplo demuestra la carga de un archivo de imagen existente en una instancia de Aspose.PSD.Image usando la ruta de archivo especificada

```csharp
[C#]

//Crea una instancia de imagen e inicialízala con un archivo de imagen existente desde la ubicación del disco
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    //hacer un poco de procesamiento de imagen
}
```

El siguiente ejemplo demuestra que la alineación de texto a través de ITextPortion para idiomas de derecha a izquierda funciona correctamente.

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

El siguiente ejemplo demuestra que leer y guardar los archivos PSD de escala de grises de 16 bits en RGB de 16 bits por canal funciona correctamente y sin excepción.

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
    // Aquí no debería haber una excepción.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

El siguiente ejemplo demuestra que leer y guardar los archivos PSD de escala de grises de 16 bits en escala de grises de 8 bits por canal funciona correctamente y sin excepción.

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
    // Aquí no debería haber una excepción.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

El siguiente ejemplo demuestra que el progreso de conversión de documentos funciona correctamente y sin excepción.

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

El siguiente ejemplo demuestra que leer y guardar los archivos PSD de escala de grises de 16 bits funciona correctamente y sin excepción.

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
        // Aquí no debería haber una excepción.
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

* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Carga una nueva imagen del flujo especificado.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar la imagen. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Valor_devuelto

La imagen cargada.

### Ver también

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

Carga una nueva imagen del flujo especificado.

```csharp
public static Image Load(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo desde el que cargar la imagen. |

### Valor_devuelto

La imagen cargada.

### Ejemplos

Este ejemplo demuestra el uso de objetos System.IO.Stream para cargar un archivo de imagen existente

```csharp
[C#]

//Crear una instancia de FileStream
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Cree una instancia de la clase Image y cargue un archivo existente a través del objeto FileStream llamando al método Load
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //hacer un poco de procesamiento de imagen.
    }
}
```

### Ver también

* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)



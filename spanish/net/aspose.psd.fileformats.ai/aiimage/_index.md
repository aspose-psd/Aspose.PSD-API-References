---
title: "Clase AiImage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Ai.AiImage clase. La imagen AI de Adobe Illustrator"
type: docs
weight: 1270
url: /es/net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

La imagen de Adobe Illustrator (AI).

```csharp
public sealed class AiImage : Image
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AiImage](aiimage/)() | Inicializa una nueva instancia de la clase `AiImage`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | Obtiene o establece el índice de la página activa. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtiene el contenedor de [`Image`](../../aspose.psd/image/). |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Obtiene la sección de datos. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Obtiene un valor del formato de archivo. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Obtiene la sección de finalización. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Obtiene el encabezado. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Obtiene la altura de la imagen. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtiene o establece el monitor de interrupciones. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Obtiene las secciones de capa. |
| [PageCount](../../aspose.psd.fileformats.ai/aiimage/pagecount/) { get; } | El número de páginas. Para las imágenes del formato AI antiguo siempre es 0. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Obtiene la sección de configuración. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtiene el tamaño de la imagen. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtiene un valor que indica si se usa la paleta de la imagen. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Obtiene la versión del formato Adobe Illustrator. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Obtiene el ancho de la imagen. |
| [XmpData](../../aspose.psd.fileformats.ai/aiimage/xmpdata/) { get; } | Obtiene los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Agrega la sección de capa AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) subyacente. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [`Save`](../../aspose.psd/datastreamsupporter/save/), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [`Save`](../../aspose.psd/image/save/) como segundo parámetro. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensiona la imagen. Se utiliza el NearestNeighbourResample predeterminado. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Redimensiona la imagen. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Redimensiona la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensiona la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensiona el ancho proporcionalmente. Se utiliza el NearestNeighbourResample predeterminado. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensiona el ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensiona el ancho proporcionalmente. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Rota, voltea o rota y voltea la imagen. |
| [Save](../../aspose.psd/image/save/)() | Guarda los datos de la imagen en el flujo subyacente. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Establece la paleta de la imagen. |

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

El siguiente ejemplo demuestra el soporte de la exportación del formato Ai a los formatos PSD, PNG, JPG, GIF y TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Ver también

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



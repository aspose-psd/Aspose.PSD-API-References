---
title: "Clase RasterCachedImage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.RasterCachedImage. Representa una imagen raster que soporta operaciones gráficas raster. Esta imagen almacena en caché los datos de píxeles cuando es necesario."
type: docs
weight: 5810
url: /es/net/aspose.psd/rastercachedimage/
---
{{< psd/tize >}}
## RasterCachedImage class

Representa una imagen raster que soporta operaciones gráficas raster. Esta imagen almacena en caché los datos de píxel cuando se requiere.

```csharp
public abstract class RasterCachedImage : RasterImage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtiene el contenedor [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtiene un valor del formato de archivo |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Obtiene un valor que indica si esta instancia tiene alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Obtiene la altura de la imagen. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este [`RasterImage`](../rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtiene la opacidad de esta imagen. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtiene o establece el monitor de interrupciones. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtiene o establece el índice de reserva a usar cuando el índice de paleta está fuera de los límites. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color indexado. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtiene el tamaño de línea sin procesar en bytes. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtiene el tamaño de la imagen. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtiene el color transparente de la imagen. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtiene un valor que indica si se usa la paleta de la imagen. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este [`RasterImage`](../rasterimage/). |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Obtiene el ancho de la imagen. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Ajuste de brillo de la imagen. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Contraste de la imagen. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbral de imagen integral. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbral de imagen integral. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarización de una imagen con umbralización de Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Almacena en caché los datos y asegura que no se carguen datos adicionales desde el [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) subyacente. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recortar la imagen con desplazamientos. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtiene la fecha y hora en que la imagen de recurso fue modificada por última vez. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [`Save`](../datastreamsupporter/save/), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [`Save`](../image/save/) como segundo parámetro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtiene un píxel de la imagen. Advertencia de rendimiento: Evite usar este método para iterar sobre todos los píxeles de la imagen, ya que puede provocar problemas de rendimiento significativos. Para una manipulación de píxeles más eficiente, use el método `LoadArgb32Pixels` para recuperar toda la matriz de píxeles simultáneamente. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformación de una imagen a su representación en escala de grises |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Carga píxeles en formato CMYK. Este método está obsoleto. Por favor, utilice de forma más eficaz el método [`LoadCmyk32Pixels`](../rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carga parcialmente píxeles ARGB de 32 bits por paquetes. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo. Este método utiliza los métodos [`GetSkewAngle`](../rasterimage/getskewangle/) y [`Rotate`](../rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo. Este método utiliza los métodos [`GetSkewAngle`](../rasterimage/getskewangle/) y [`Rotate`](../rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensiona la imagen. Se utiliza el NearestNeighbourResample predeterminado. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | Redimensiona la imagen. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | Redimensiona la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensiona la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensiona el ancho proporcionalmente. Se utiliza el NearestNeighbourResample predeterminado. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensiona el ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensiona el ancho proporcionalmente. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Rota la imagen alrededor del centro. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | Rota la imagen alrededor del centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Rota, voltea o rota y voltea la imagen. |
| [Save](../../aspose.psd/image/save/)() | Guarda los datos de la imagen en el flujo subyacente. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Guarda los píxeles ARGB de 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Guarda los píxeles. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Guarda los píxeles. Este método está obsoleto. Por favor, utilice de forma más eficaz el método [`SaveCmyk32Pixels`](../rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Guarda los píxeles. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Guarda los datos sin procesar. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Establece un píxel de la imagen para la posición especificada. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Establece la resolución para este [`RasterImage`](../rasterimage/). |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convierte la imagen raster a bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

## Ejemplos

El siguiente código demuestra la capacidad de recortar la imagen mediante un rectángulo específico.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // Guardar psd
    image.Save(exportPath, new PsdOptions());

    // Guardar png
    image.Save(exportPathPng, new PngOptions());
}
```

### Ver también

* class [RasterImage](../rasterimage/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



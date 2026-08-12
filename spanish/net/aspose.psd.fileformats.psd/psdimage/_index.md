---
title: "Clase PsdImage"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.PsdImage. Define la clase PsdImage que proporciona la capacidad de cargar, editar y guardar archivos PSD, así como actualizar propiedades, añadir marcas de agua, realizar operaciones gráficas o convertir un formato de archivo a otro. Aspose.PSD admite la importación como capa y la exportación a los siguientes formatos: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, junto con la exportación a Pdf con texto seleccionable."
type: docs
weight: 4050
url: /es/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Define la clase PsdImage que brinda la capacidad de cargar, editar y guardar archivos PSD, así como actualizar propiedades, añadir marcas de agua, realizar operaciones gráficas o convertir un formato de archivo a otro. Aspose.PSD admite la importación como capa y la exportación a los siguientes formatos: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, junto con la exportación a Pdf con texto seleccionable.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Inicializa una nueva instancia de la clase `PsdImage` a partir de una imagen raster existente (no una imagen psd) con modo de color RGB, 4 canales, 8 bits por canal y sin compresión. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Inicializa una nueva instancia de la clase `PsdImage` a partir de la ruta especificada de una imagen raster (no una imagen psd en flujo). Se usa para inicializar una imagen psd con parámetros predeterminados: modo de color - rgb, 4 canales, 8 bits por canal, compresión - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Inicializa una nueva instancia de la clase `PsdImage` a partir de la ruta especificada de una imagen raster (no una imagen psd en ruta). Se usa para inicializar una imagen psd con parámetros predeterminados: modo de color - rgb, 4 canales, 8 bits por canal, compresión - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Inicializa una nueva instancia de la clase `PsdImage` con el ancho y alto especificados. Se usa para inicializar una imagen psd vacía. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia de la clase `PsdImage` a partir de una imagen raster existente (no una imagen psd) con parámetros del constructor. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia de la clase `PsdImage` a partir de la ruta especificada de una imagen raster (no una imagen psd en flujo) con parámetros del constructor. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia de la clase `PsdImage` a partir de la ruta especificada de una imagen raster (no una imagen psd en ruta) con parámetros del constructor. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia de la clase `PsdImage` con el ancho, alto, paleta, modo de color, número de canales y longitud de bits de los canales, y los parámetros del modo de compresión especificados. Se usa para inicializar una imagen psd vacía. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Obtiene o establece la capa activa. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Obtiene los bits por canal. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Obtiene el recuento de canales PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Obtiene o establece el perfil de color CMYK para imágenes PSD CMYK. Debe estar emparejado con RgbColorProfile para una conversión de color correcta. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Obtiene o establece el modo de color. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Obtiene el método de compresión. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtiene el contenedor de [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Obtiene un valor del formato de archivo |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Obtiene o establece el ángulo global. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Obtiene la información de la máscara de capa global. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Obtiene o establece los recursos de capa global. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Obtiene o establece el perfil de color GRAY (monocromo) para imágenes PSD en escala de grises. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Obtiene o establece un valor que indica si el primer canal alfa contiene los datos de transparencia para el resultado fusionado al especificar datos de capas. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Obtiene la altura de la imagen. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este `PsdImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtiene la opacidad de esta imagen. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Obtiene o establece los recursos de la imagen PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtiene o establece el monitor de interrupciones. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Obtiene un valor que indica si la imagen psd está aplanada. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Obtiene o establece las capas PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Obtiene el administrador de capas vinculadas. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtiene o establece el índice de reserva a usar cuando el índice de paleta está fuera de los límites. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color indexado. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtiene el tamaño de línea sin procesar en bytes. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Obtiene o establece el perfil de color RGB para imágenes PSD CMYK. Debe estar emparejado con CmykColorProfile para una conversión de color correcta. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtiene el tamaño de la imagen. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Obtiene el proveedor de objetos inteligentes. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Obtiene el [`Timeline`](./timeline/) de este `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtiene el color transparente de la imagen. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtiene un valor que indica si se usa la paleta de la imagen. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Obtiene o establece la versión. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este `PsdImage`. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Obtiene el ancho de la imagen. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Añade la capa de ajuste blanco y negro. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Añade la capa de ajuste de brillo/contraste. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Añade la capa de ajuste de mezclador de canales con parámetros predeterminados |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Añade la capa de ajuste de balance de color. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Añade la capa de ajuste de curvas. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Añade la capa de ajuste de exposición. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Añade la capa de ajuste GradientMap. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Añade la capa de ajuste de tono/saturación. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Añade una capa de ajuste de inversión. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Añade la capa. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Agrega el grupo de capas. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Añade la capa de ajuste de niveles. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Añade la capa PhotoFilter. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Añade la capa de ajuste Posterize. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Añade una nueva capa regular. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Añade la capa de ajuste de color selectivo. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Añade una capa Shape vacía. Sin rutas. Deben añadirse a la capa shape antes de guardar. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Añade una nueva capa Text. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Añade la capa de ajuste de umbral. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Añade la capa de ajuste de vibrancia. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Ajuste de brillo de la imagen. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Contraste de la imagen. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbral de imagen integral. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbral de imagen integral. |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarización de una imagen con umbralización de Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) subyacente. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Convierte el formato de esta imagen al especificado en las opciones. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recortar la imagen con desplazamientos. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Aplana todas las capas. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtiene la fecha y hora en que la imagen de recurso fue modificada por última vez. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [`Save`](../../aspose.psd/datastreamsupporter/save/), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [`Save`](../../aspose.psd/image/save/) como segundo parámetro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtiene un píxel de la imagen. Advertencia de rendimiento: Evite usar este método para iterar sobre todos los píxeles de la imagen, ya que puede provocar problemas de rendimiento significativos. Para una manipulación de píxeles más eficiente, use el método `LoadArgb32Pixels` para recuperar toda la matriz de píxeles simultáneamente. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformación de una imagen a su representación en escala de grises |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Carga píxeles en formato CMYK. Este método está obsoleto. Por favor, use el método más eficaz [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carga parcialmente píxeles ARGB de 32 bits por paquetes. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Fusiona las capas. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo. Este método utiliza los métodos [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo. Este método utiliza los métodos [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensiona la imagen. Se utiliza el NearestNeighbourResample predeterminado. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Redimensiona la imagen. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Redimensiona la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensiona la altura proporcionalmente. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Redimensiona la altura proporcionalmente. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Redimensiona la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensiona el ancho proporcionalmente. Se utiliza el NearestNeighbourResample predeterminado. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Redimensiona el ancho proporcionalmente. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Redimensiona el ancho proporcionalmente. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Rota la imagen alrededor del centro. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Rota la imagen alrededor del centro. |
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
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Guarda los píxeles. Este método está obsoleto. Por favor, use de manera más eficaz el método [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Guarda los píxeles. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Guarda los datos sin procesar. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Establece un píxel de la imagen para la posición especificada. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Establece la resolución para este `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convierte la imagen raster a bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | La versión predeterminada de PSD. |

## Ejemplos

El siguiente código demuestra la capacidad de rotar la imagen por un valor de ángulo específico.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotación de la imagen completa
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Rotación de capa
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Ver también

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



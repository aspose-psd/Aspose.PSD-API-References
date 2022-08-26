---
title: PsdImage
second_title: Referencia de API de Aspose.PSD para .NET
description: Define la clase PsdImage que brinda la capacidad de cargar editar guardar archivos PSD así como actualizar propiedades agregar marcas de agua realizar operaciones gráficas o convertir un formato de archivo a otro. Aspose.PSD admite la importación como una capa y la exportación a la siguientes formatos Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb junto con exportación a Pdf con texto seleccionable
type: docs
weight: 3530
url: /es/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Define la clase PsdImage que brinda la capacidad de cargar, editar, guardar archivos PSD, así como actualizar propiedades, agregar marcas de agua, realizar operaciones gráficas o convertir un formato de archivo a otro. Aspose.PSD admite la importación como una capa y la exportación a la siguientes formatos: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb junto con exportación a Pdf con texto seleccionable

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsdImage](psdimage#constructor)(RasterImage) | Inicializa una nueva instancia del[`PsdImage`](../psdimage)clase de imagen ráster existente (no imagen psd) con modo de color RGB con 4 canales de 8 bits/canal y sin compresión. |
| [PsdImage](psdimage#constructor_4)(Stream) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase de la ruta especificada de la imagen ráster (no la imagen psd en la transmisión). Se utiliza para inicializar la imagen psd con los parámetros predeterminados - Modo de color - rgb, 4 canales, 8 bits por canal, Compresión - Raw. |
| [PsdImage](psdimage#constructor_6)(string) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase de la ruta especificada de la imagen ráster (no la imagen psd en la ruta). Se utiliza para inicializar la imagen psd con los parámetros predeterminados - Modo de color - rgb, 4 canales, 8 bits por canal, Compresión - Raw. |
| [PsdImage](psdimage#constructor_2)(int, int) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase con ancho y alto especificados. Se utiliza para inicializar la imagen psd vacía. |
| [PsdImage](psdimage#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase de imagen ráster existente (no imagen psd) con parámetros de constructor. |
| [PsdImage](psdimage#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase de la ruta especificada de la imagen ráster (no la imagen psd en la transmisión) con parámetros de constructor. |
| [PsdImage](psdimage#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase de la ruta especificada de la imagen ráster (no la imagen psd en la ruta) con parámetros de constructor. |
| [PsdImage](psdimage#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Inicializa una nueva instancia del[`PsdImage`](../psdimage) clase con ancho, alto, paleta, modo de color, número de canales y longitud de bits de canales especificados y parámetros de modo de compresión especificados. Se utiliza para inicializar la imagen psd vacía. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer) { get; set; } | Obtiene o establece la capa activa. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel) { get; } | Obtiene los bits por canal. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount) { get; } | Obtiene el conteo de canales PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile) { get; set; } | Obtiene o establece el perfil de color CMYK para imágenes PSD CMYK. Debe estar en pareja con RgbColorProfile para una conversión de color correcta. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode) { get; set; } | Obtiene o establece el modo de color. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression) { get; } | Obtiene el método de compresión. |
| [Container](../../aspose.psd/image/container) { get; } | Obtiene el[`Image`](../../aspose.psd/image) contenedor. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle) { get; set; } | Obtiene o establece el ángulo global. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo) { get; } | Obtiene la información de la máscara de capa global. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources) { get; set; } | Obtiene o establece los recursos de la capa global. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile) { get; set; } | Obtiene o establece el perfil de color GRIS (monocromo) para imágenes PSD en escala de grises. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha) { get; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata) { get; set; } | Obtiene o establece un valor que indica si el primer canal alfa contiene los datos de transparencia para el resultado combinado al especificar datos de capas. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height) { get; } | Obtiene la altura de la imagen. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`PsdImage`](../psdimage) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | Obtiene la opacidad de esta imagen. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources) { get; set; } | Obtiene o establece los recursos de la imagen PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | Obtiene un valor que indica si los datos de la imagen se almacenan en caché actualmente. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten) { get; } | Obtiene un valor que indica si la imagen psd está aplanada. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers) { get; set; } | Obtiene o establece las capas PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager) { get; } | Obtiene el administrador de capas enlazadas. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen se deben premultiplicar. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | Obtiene la configuración actual de datos sin procesar. Tenga en cuenta que al usar esta configuración, los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | Obtiene o establece el índice alternativo que se utilizará cuando el índice de la paleta esté fuera de los límites |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | Obtiene o establece el convertidor de color indexado |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | Obtiene el tamaño de línea sin formato en bytes. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile) { get; set; } | Obtiene o establece el perfil de color RGB para imágenes PSD CMYK. Debe estar en pareja con CmykColorProfile para una conversión de color correcta. |
| [Size](../../aspose.psd/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider) { get; } | Obtiene el proveedor de objetos inteligentes. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | Obtiene la imagen en color transparente. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | Obtiene o establece un valor que indica si se deben actualizar los metadatos XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version) { get; set; } | Obtiene o establece la versión. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`PsdImage`](../psdimage) . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width) { get; } | Obtiene el ancho de la imagen. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer)() | Agrega la capa de ajuste de blanco y negro. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer)(int, int) | Agrega la capa de ajuste de brillo/contraste. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer)() | Agrega la capa de ajuste del mezclador de canales con los parámetros predeterminados |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer)() | Agrega la capa de ajuste de balance de color. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer)() | Agrega la capa Ajuste de curvas. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer)(float, float, float) | Agrega la capa de ajuste de exposición. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer)() | Agrega la capa de ajuste de tono/saturación. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer)() | Agrega una capa de ajuste de inversión. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer)(Layer) | Agrega la capa. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup)(string, int, bool) | Agrega el grupo de capas. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer)() | Agrega la capa de ajuste de Niveles. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer)(Color) | Agrega la capa PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer)() | Agrega una nueva capa regular. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer)(string, Rectangle) | Agrega una nueva capa de Texto. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer)() | Agrega la capa de ajuste de Intensidad. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness)(int) | Ajuste de un brillo para la imagen. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast)(float) | Contraste de imagen |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma_1)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley_1)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu)() | Binarización de una imagen con umbral Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert)(PsdOptions) | Convierte este formato de imagen al especificado en opciones. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop#crop)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage)() | Aplana todas las capas. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | Obtiene una imagen ARGB pixel de 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz de píxeles predeterminada usando un cargador de píxeles parcial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada mediante el cargador de píxeles parciales. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | Obtiene la fecha y la hora en que se modificó por última vez la imagen del recurso. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.psd/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.psd/image/save)método como el segundo parámetro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | Obtiene un píxel de imagen. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale)() | Transformación de una imagen a su representación en escala de grises |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers)(Layer, Layer) | Fusiona las capas. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) y[`Rotate`](../../aspose.psd/rasterimage/rotate) métodos. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) y[`Rotate`](../../aspose.psd/rasterimage/rotate) métodos. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor#replacecolor_1)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán con uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán con uno solo. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoLeftTopToLeftTopse usa. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate)(float) | Rotar imagen alrededor del centro. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate_1)(float, bool, Color) | Rotar imagen alrededor del centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.psd/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [Save](../../aspose.psd/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | Guarda los píxeles ARGB de 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Guarda los píxeles. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | Guarda los píxeles. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Guarda los datos sin procesar. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | Establece un píxel ARGB de 32 bits de imagen para la posición especificada. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | Establece un píxel de imagen para la posición especificada. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | Establece la resolución para este[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | Convierte la imagen ráster al mapa de bits. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion) | La versión PSD predeterminada. |

### Ejemplos

El siguiente código demuestra la capacidad de rotar la imagen por un valor de ángulo específico.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Imagen completa girando
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

// Capa rotando
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

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

---
title: Class CurvesLayer
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.CurvesLayer clase. Capa de ajuste de curvas
type: docs
weight: 1730
url: /es/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/
---
## CurvesLayer class

Capa de ajuste de curvas

```csharp
public class CurvesLayer : AdjustmentLayer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Obtiene las opciones de fusión. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Obtiene o establece la clave del modo de combinación. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Obtiene la firma del modo de mezcla. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Obtiene o establece la posición de la capa inferior. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Obtiene o establece la información del canal. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Obtiene el conteo de canales de la capa. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Obtiene o establece el recorte de la capa. 0 = base, 1 = no base. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtiene el[`Image`](../../aspose.psd/image/) contenedor. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Obtiene o establece el nombre para mostrar de la capa. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Obtiene la longitud de la información extra de la capa en bytes. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtiene un valor de formato de archivo |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Obtiene o establece el relleno de la capa. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Obtiene o establece la opacidad de relleno. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Obtiene o establece los indicadores de capa. bit 0 = transparencia protegida; bit 1 = visible; bit 2 = obsoleto; bit 3 = 1 para Photoshop 5.0 y posterior, indica si el bit 4 tiene información útil; bit 4 = datos de píxeles irrelevantes para la apariencia del documento. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Obtiene un valor que indica si esta instancia tiene alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Obtiene la altura de la imagen. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtiene la opacidad de esta imagen. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtiene un valor que indica si los datos de la imagen se almacenan en caché actualmente. |
| [IsContinuousManagerUsed](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/iscontinuousmanagerused/) { get; set; } | Obtiene o establece un valor que indica si esta instancia se usa continuamente como administrador. |
| [IsDiscreteManagerUsed](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/isdiscretemanagerused/) { get; set; } | Obtiene o establece un valor que indica si esta instancia es un administrador discreto utilizado. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Obtiene o establece un valor que indica si la capa es visible |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Obtiene un valor que indica si esta instancia está visible en el grupo (si la capa no está en el grupo, significa grupo raíz). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Obtiene o establece los datos de rangos de fusión de capas. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Obtiene o establece la fecha y hora de creación de la capa. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Obtiene o establece el bloqueo de capa. Tenga en cuenta que si se establece el indicador LayerFlags.TransparencyProtected, se sobrescribirá con el indicador de bloqueo de capa. Para devolver el indicador LayerFlags.TransparencyProtected, debe solicitar la opción de capa layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Obtiene o establece los datos de la máscara de capa. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Obtiene las opciones de capa. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Obtiene o establece la posición de la capa izquierda. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Obtiene la longitud total de la capa en bytes. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Obtiene o establece el nombre de la capa. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Obtiene o establece la opacidad de la capa. 0 = transparente, 255 = opaco. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen se deben premultiplicar. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtiene la configuración actual de datos sin procesar. Tenga en cuenta que al usar esta configuración, los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtiene o establece el índice alternativo que se utilizará cuando el índice de la paleta esté fuera de los límites |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color indexado |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtiene el tamaño de línea sin formato en bytes. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Obtiene o establece los recursos de la capa. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Obtiene o establece la posición correcta de la capa. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Obtiene o establece el resaltado de color de la hoja decorativa en la lista de capas |
| [Size](../../aspose.psd/image/size/) { get; } | Obtiene el tamaño de la imagen. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Obtiene o establece la posición de la capa superior. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtiene la imagen en color transparente. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtiene o establece un valor que indica si se deben actualizar los metadatos XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Obtiene el ancho de la imagen. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Agrega la máscara a la capa actual. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Ajuste de un brillo para la imagen. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Contraste de imagen |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarización de una imagen con umbral Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Dibuja la imagen en la capa. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtiene una imagen ARGB pixel de 32 bits. |
| [GetCurvesManager](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/getcurvesmanager/)() | Obtiene el administrador de curvas. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz de píxeles predeterminada usando un cargador de píxeles parcial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada mediante el cargador de píxeles parciales. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Devuelve un código hash para esta instancia. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtiene la fecha y la hora en que se modificó por última vez la imagen del recurso. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.psd/datastreamsupporter/save/) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.psd/image/save/)método como el segundo parámetro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtiene un píxel de imagen. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformación de una imagen a su representación en escala de grises |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | Fusiona la capa con la capa especificada |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y[`Rotate`](../../aspose.psd/rasterimage/rotate/) métodos. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y[`Rotate`](../../aspose.psd/rasterimage/rotate/) métodos. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán con uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán con uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Cambia el tamaño de la imagen. El valor por defectoLeftTopToLeftTopse usa. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Rotar imagen alrededor del centro. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Rotar imagen alrededor del centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.psd/image/save/)() | Guarda los datos de la imagen en el flujo subyacente. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Guarda los píxeles ARGB de 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Guarda los píxeles. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Guarda los píxeles. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Guarda los datos sin procesar. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Establece un píxel ARGB de 32 bits de imagen para la posición especificada. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Establece un píxel de imagen para la posición especificada. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Establece la resolución para este[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Crea una copia superficial de la Capa actual. Por favor[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) para explicación. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convierte la imagen ráster al mapa de bits. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

### Ver también

* class [AdjustmentLayer](../adjustmentlayer/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* asamblea [Aspose.PSD](../../)



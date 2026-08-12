---
title: "Clase SmartObjectLayer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer class. Define la clase SmartObjectLayer que contiene un objeto inteligente incrustado en el archivo PSD o un objeto inteligente vinculado en un archivo externo. Con Smart Objects puedes realizar transformaciones no destructivas. Puedes escalar, rotar, sesgar, distorsionar, transformar en perspectiva o deformar una capa sin perder los datos de imagen originales ni la calidad porque las transformaciones no afectan los datos originales. Trabaja con datos vectoriales como arte vectorial de Illustrator que de otro modo se rasterizaría. Realiza filtrado no destructivo. Puedes editar los filtros aplicados a Smart Objects en cualquier momento. Edita un Smart Object y actualiza automáticamente todas sus instancias vinculadas. Aplica una máscara de capa que esté vinculada o desvinculada a la capa del Smart Object. Prueba varios diseños con imágenes de marcador de posición de baja resolución que luego reemplazarás con versiones finales. En Adobe Photoshop puedes incrustar el contenido de una imagen en un documento PSD. Más información aquí https//helpx.adobe.com/photoshop/using/createsmartobjects.html Una capa con un smart object incrustado contiene recursos PlLd y SoLd colocados con propiedades de smart object. El recurso PlLd puede estar solo para versiones de PSD anteriores a 10. Estos recursos contienen UniqueId del LiFdDataSource en el recurso global Lnk2Resource con el nombre de archivo incrustado y otros parámetros, incluido el contenido del archivo incrustado en el formato original como una matriz de bytes"
type: docs
weight: 3910
url: /es/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
{{< psd/tize >}}
## SmartObjectLayer class

Define la clase SmartObjectLayer que contiene un objeto inteligente incrustado en el archivo PSD o vinculado en un archivo externo. Con Smart Objects, puedes: Realizar transformaciones no destructivas. Puedes escalar, rotar, sesgar, distorsionar, aplicar transformaciones de perspectiva o deformar una capa sin perder los datos de imagen originales ni la calidad porque las transformaciones no afectan los datos originales. Trabajar con datos vectoriales, como arte vectorial de Illustrator, que de otro modo se rasterizaría. Realizar filtrado no destructivo. Puedes editar los filtros aplicados a Smart Objects en cualquier momento. Editar un Smart Object y actualizar automáticamente todas sus instancias vinculadas. Aplicar una máscara de capa que esté vinculada o desvinculada de la capa Smart Object. Probar varios diseños con imágenes de marcador de posición de baja resolución que luego reemplazas con versiones finales. En Adobe Photoshop, puedes incrustar el contenido de una imagen en un documento PSD. Más información aquí: [https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Una capa con un objeto inteligente incrustado contiene recursos placed (PlLd) y SoLd con propiedades del objeto inteligente. El recurso PlLd puede estar solo para versiones de PSD anteriores a la 10. Estos recursos contienen UniqueId del LiFdDataSource en el recurso global Lnk2Resource con el nombre de archivo incrustado y otros parámetros, incluido el contenido del archivo incrustado en el formato original como una matriz de bytes.

```csharp
public class SmartObjectLayer : Layer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SmartObjectLayer](smartobjectlayer/)(Stream) | Inicializa una nueva instancia de la clase `SmartObjectLayer`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Obtiene o establece la fusión del elemento recortado. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Obtiene las opciones de fusión. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Obtiene o establece la clave del modo de fusión. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Obtiene la firma del modo de fusión. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Obtiene o establece la posición de la capa inferior. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Obtiene o establece la información del canal. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Obtiene el recuento de canales de la capa. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Obtiene o establece el recorte de la capa. 0 = base, 1 = no base. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtiene el contenedor de [`Image`](../../aspose.psd/image/). |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Obtiene o establece el contenido de la capa de objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) y sus propiedades. El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible y sus propiedades: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). No admitimos la carga desde la Biblioteca Gráfica de Adobe® Photoshop® cuando [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) es verdadero. Para archivos vinculados normales, primero usamos [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) para buscar el archivo de forma relativa a la ruta de la imagen fuente SourceImagePath; si no está disponible, buscamos en [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), y si tampoco, buscamos el archivo vinculado en el mismo directorio donde está nuestra imagen: SourceImagePath. |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Obtiene o establece los límites del contenido del objeto inteligente. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Obtiene o establece la fuente del contenido del objeto inteligente. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Obtiene el tipo del contenido de la capa de objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/). El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). No admitimos la carga desde la Biblioteca Gráfica de Adobe® Photoshop® cuando [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) es verdadero. Para archivos vinculados normales, primero usamos [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) para buscar el archivo de forma relativa a la ruta de la imagen fuente SourceImagePath; si no está disponible, buscamos en [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), y si tampoco, buscamos el archivo vinculado en el mismo directorio donde está nuestra imagen: SourceImagePath. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Obtiene o establece el nombre para mostrar de la capa. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Obtiene la longitud de la información adicional de la capa en bytes. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtiene un valor del formato de archivo |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Obtiene o establece el relleno de la capa. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Obtiene o establece la opacidad del relleno. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Obtiene o establece los indicadores de capa. bit 0 = protección de transparencia; bit 1 = visible; bit 2 = obsoleto; bit 3 = 1 para Photoshop 5.0 y posteriores, indica si el bit 4 tiene información útil; bit 4 = datos de píxel irrelevantes para la apariencia del documento. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Obtiene un valor que indica si esta instancia tiene alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Obtiene la altura de la imagen. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtiene la opacidad de esta imagen. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtiene o establece el monitor de interrupciones. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Obtiene o establece un valor que indica si la capa es visible |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Obtiene un valor que indica si esta instancia es visible en el grupo(Si la capa no está en un grupo significa que es el grupo raíz). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Obtiene o establece los datos de rangos de fusión de la capa. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Obtiene o establece la fecha y hora de creación de la capa. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Obtiene o establece el bloqueo de capa. Tenga en cuenta que si la bandera LayerFlags.TransparencyProtected está establecida, será sobrescrita por la bandera de bloqueo de capa. Para devolver la bandera LayerFlags.TransparencyProtected es necesario aplicarla a la opción de capa layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Obtiene o establece los datos de máscara de capa. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Obtiene las opciones de capa. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Obtiene o establece la posición izquierda de la capa. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Obtiene la longitud total de la capa en bytes. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Obtiene o establece el nombre de la capa. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Obtiene o establece la opacidad de la capa. 0 = transparente, 255 = opaco. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtiene o establece el índice de reserva a usar cuando el índice de paleta está fuera de los límites. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtiene o establece el convertidor de color indexado. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtiene el tamaño de línea sin procesar en bytes. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Obtiene o establece los recursos de capa. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Obtiene o establece la posición de la capa derecha. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Obtiene o establece el resaltado de color de hoja decorativa en la lista de capas. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtiene el tamaño de la imagen. |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Obtiene los filtros inteligentes. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Obtiene el proveedor de objetos inteligentes. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Obtiene o establece la posición de la capa superior. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtiene el color transparente de la imagen. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtiene un valor que indica si se usa la paleta de la imagen. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este [`RasterImage`](../../aspose.psd/rasterimage/). |
| [WarpSettings](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/warpsettings/) { get; set; } | Obtiene o establece los parámetros Warp que se establecieron o obtuvieron del recurso (por defecto). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Obtiene el ancho de la imagen. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Agrega la máscara a la capa actual. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Ajuste de brillo de la imagen. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Contraste de la imagen. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Corrección gamma de una imagen. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Aplica la máscara de capa a la capa, luego elimina la máscara. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbral de imagen integral. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbral de imagen integral. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarización de una imagen con umbralización de Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) subyacente. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Convierte este objeto inteligente incrustado en un objeto inteligente vinculado. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recortar la imagen con desplazamientos. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Dibuja la imagen en la capa. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Crea una nueva capa de objeto inteligente copiando esta. Observe que para los objetos inteligentes incrustados la imagen incrustada se comparte. Si desea copiar la imagen incrustada, use el método [`NewSmartObjectViaCopy`](./newsmartobjectviacopy/). |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Incrusta el objeto inteligente vinculado en esta capa. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Exporta el contenido incrustado o vinculado a un archivo. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Devuelve un código hash para esta instancia. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtiene la fecha y hora en que la imagen de recurso fue modificada por última vez. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [`Save`](../../aspose.psd/datastreamsupporter/save/), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [`Save`](../../aspose.psd/image/save/) como segundo parámetro. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtiene un píxel de la imagen. Advertencia de rendimiento: Evite usar este método para iterar sobre todos los píxeles de la imagen, ya que puede provocar problemas de rendimiento significativos. Para una manipulación de píxeles más eficiente, use el método `LoadArgb32Pixels` para recuperar toda la matriz de píxeles simultáneamente. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformación de una imagen a su representación en escala de grises |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Carga píxeles en formato CMYK. Este método está obsoleto. Por favor, use el método más eficaz [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Obtiene el contenido de imagen incrustado o vinculado de la capa de objeto inteligente. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carga parcialmente píxeles ARGB de 32 bits por paquetes. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Fusiona la capa con la capa especificada |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Crea una nueva capa de objeto inteligente copiando esta. Reproduce la funcionalidad `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` de Adobe� Photoshop�. Observe que solo está habilitado para objetos inteligentes incrustados porque la imagen incrustada también se copia. Si desea compartir la imagen incrustada, use el método [`DuplicateLayer`](./duplicatelayer/). |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo. Este método utiliza los métodos [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la inclinación del escaneo. Este método utiliza los métodos [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Vuelve a vincular el objeto inteligente vinculado a un nuevo archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Reemplaza el contenido del objeto inteligente incrustado en la capa de objeto inteligente. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Reemplaza el contenido con un archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Reemplaza el contenido del objeto inteligente incrustado en la capa de objeto inteligente. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_5)(string, bool) | Reemplaza el contenido con un archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Reemplaza el contenido con un archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_4)(string, ResolutionSetting, bool) | Reemplaza el contenido con un archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno solo. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensiona la imagen. Se utiliza el NearestNeighbourResample predeterminado. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Redimensiona la imagen. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Redimensiona la imagen. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensiona la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensiona la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensiona el ancho proporcionalmente. Se utiliza el NearestNeighbourResample predeterminado. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensiona el ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensiona el ancho proporcionalmente. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Rota la imagen alrededor del centro. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Rota la imagen alrededor del centro. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Rota, voltea o rota y voltea la imagen. |
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
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Guarda los píxeles. Este método está obsoleto. Por favor, use de manera más eficaz el método [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Guarda los píxeles. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Guarda los datos sin procesar. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Establece un píxel de la imagen para la posición especificada. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Establece la resolución para este [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Crea una copia superficial de la capa actual. Por favor, consulte [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) para obtener una explicación. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convierte la imagen raster a bitmap. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Actualiza la caché de imágenes de la capa de objeto inteligente con el contenido modificado. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

## Ejemplos

El siguiente código demuestra el soporte de objetos inteligentes incrustados.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Este ejemplo demuestra cómo cambiar la capa de objeto inteligente en el archivo PSD y exportar/actualizar el contenido original incrustado del objeto inteligente.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Exportemos la imagen del objeto inteligente incrustado de la capa de objeto inteligente del PSD
        smartObjectLayer.ExportContents(exportPath);

        // Verifiquemos si la imagen original se guarda correctamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Invertamos la imagen original del objeto inteligente
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Reemplacemos la imagen del objeto inteligente incrustada en la capa del PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Verifiquemos si la imagen actualizada se guarda correctamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../)



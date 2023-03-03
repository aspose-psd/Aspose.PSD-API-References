---
title: Class SmartObjectLayer
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer clase. Define la clase SmartObjectLayer que contiene incrustado en el archivo PSD o el objeto inteligente vinculado en el archivo externo. Con Objetos inteligentes puede Realizar transformaciones no destructivas. Puede escalar rotar sesgar distorsionar transformar la perspectiva o deformar una capa sin perder los datos o la calidad de la imagen original porque las transformaciones no afectan los datos originales. Trabaje con datos vectoriales como ilustraciones vectoriales de Illustrator que de otro modo se rasterizaría. Realice un filtrado no destructivo. Puede editar los filtros aplicados a los objetos inteligentes en cualquier momento. Edite un objeto inteligente y actualice automáticamente todas sus instancias vinculadas. Aplique una máscara de capa que esté vinculada o no vinculada a la capa del objeto inteligente. Pruebe varios diseños con imágenes de marcador de posición de resolución que luego reemplaza con versiones finales. En Adobe Photoshop puede incrustar el contenido de una imagen en un documento PSD. Más información está aquíhttps//helpx.adobe.com/photoshop/using/createsmartobjects.html Una capa con un objeto inteligente incrustado contiene recursos colocados PlLd y SoLd con propiedades de objeto inteligente. El recurso PlLd puede estar solo para versiones de PSD anteriores a la 10. Estos recursos contienen UniqueId de LiFdDataSource en el Lnk2Resource global con el incrustado filename y otros parámetros incluido el contenido del archivo incrustado en el formato original como una matriz de bytes.
type: docs
weight: 3490
url: /es/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

Define la clase SmartObjectLayer que contiene incrustado en el archivo PSD o el objeto inteligente vinculado en el archivo externo. Con Objetos inteligentes, puede: Realizar transformaciones no destructivas. Puede escalar, rotar, sesgar, distorsionar, transformar la perspectiva o deformar una capa sin perder los datos o la calidad de la imagen original porque las transformaciones no afectan los datos originales. Trabaje con datos vectoriales, como ilustraciones vectoriales de Illustrator, que de otro modo se rasterizaría. Realice un filtrado no destructivo. Puede editar los filtros aplicados a los objetos inteligentes en cualquier momento. Edite un objeto inteligente y actualice automáticamente todas sus instancias vinculadas. Aplique una máscara de capa que esté vinculada o no vinculada a la capa del objeto inteligente. Pruebe varios diseños con imágenes de marcador de posición de resolución que luego reemplaza con versiones finales. En Adobe� Photoshop�, puede incrustar el contenido de una imagen en un documento PSD. Más información está aquí:[https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Una capa con un objeto inteligente incrustado contiene recursos colocados (PlLd) y SoLd con propiedades de objeto inteligente. El recurso PlLd puede estar solo para versiones de PSD anteriores a la 10. Estos recursos contienen UniqueId de LiFdDataSource en el Lnk2Resource global con el incrustado filename y otros parámetros, incluido el contenido del archivo incrustado en el formato original como una matriz de bytes.

```csharp
public class SmartObjectLayer : Layer
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
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Obtiene o establece el contenido de la capa del objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) y sus propiedades. El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado si está disponible y sus propiedades:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . No admitimos la carga desde Adobe� Photoshop� �� Biblioteca de gráficos cuando[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) es verdadero. Para archivos de enlace regulares, al principio, usamos[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) para buscar el archivo relativamente en la ruta de la imagen de origenSourceImagePath , si no está disponible miramos[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , si no es así entonces buscamos el archivo de enlace en el mismo directorio donde está nuestra imagen:SourceImagePath . |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Obtiene o establece los límites del contenido del objeto inteligente. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Obtiene o establece la fuente del contenido del objeto inteligente. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Obtiene el tipo de contenido de la capa del objeto inteligente. El contenido del objeto inteligente incrustado es el archivo de imagen sin procesar incrustado:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) . El contenido del objeto inteligente vinculado es el contenido sin procesar del archivo de imagen vinculado, si está disponible:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . No admitimos la carga desde Adobe� Photoshop� �� Biblioteca de gráficos cuando[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) es verdadero. Para archivos de enlace regulares, al principio, usamos[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) para buscar el archivo relativamente en la ruta de la imagen de origenSourceImagePath , si no está disponible miramos[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , si no es así entonces buscamos el archivo de enlace en el mismo directorio donde está nuestra imagen:SourceImagePath . |
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
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Obtiene los filtros inteligentes. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Obtiene el proveedor de objetos inteligentes. |
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
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Convierte este objeto inteligente incrustado en un objeto inteligente vinculado. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Dibuja la imagen en la capa. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Crea una nueva capa de objeto inteligente copiando esta. Tenga en cuenta que para los objetos inteligentes incrustados se comparte la imagen incrustada. Si desea copiar la imagen incrustada, utilice[`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) método. |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Incrusta el objeto inteligente vinculado en esta capa. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Exporta el contenido incrustado o vinculado a un archivo. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtiene una imagen ARGB pixel de 32 bits. |
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
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Obtiene el contenido de la imagen incrustada o vinculada de la capa del objeto inteligente. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Fusiona la capa con la capa especificada |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Crea una nueva capa de objeto inteligente copiando esta. Reproduce la funcionalidad `Capa -&gt; Objetos inteligentes -&gt; Nuevo objeto inteligente a través de la copia` de Adobe� Photoshop�. Tenga en cuenta que está habilitado solo para objetos inteligentes incrustados porque la imagen incrustada también se copia. Si desea compartir la imagen incrustada, use[`DuplicateLayer`](./duplicatelayer/) método. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y[`Rotate`](../../aspose.psd/rasterimage/rotate/) métodos. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) y[`Rotate`](../../aspose.psd/rasterimage/rotate/) métodos. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Vuelve a vincular el objeto inteligente vinculado a un nuevo archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Reemplaza el contenido del objeto inteligente incrustado en la capa del objeto inteligente. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Reemplaza el contenido con un archivo. No es necesario llamar al método UpdateModifiedContent después. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Reemplaza el contenido del objeto inteligente incrustado en la capa del objeto inteligente. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Reemplaza el contenido con un archivo. No es necesario llamar al método UpdateModifiedContent después. |
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
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Actualiza la caché de imágenes de la capa de objeto inteligente con el contenido modificado. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

### Ejemplos

El código siguiente demuestra la compatibilidad con los objetos inteligentes integrados.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Este ejemplo demuestra cómo cambiar la capa del objeto inteligente en el archivo PSD y exportar/actualizar el contenido incrustado original del objeto inteligente.
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

        // Exportemos la imagen del objeto inteligente incrustado desde la capa de objetos inteligentes PSD
        smartObjectLayer.ExportContents(exportPath);

        // Verifiquemos si la imagen original se guardó correctamente
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Vamos a invertir la imagen original del objeto inteligente
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Reemplacemos la imagen del objeto inteligente incrustado en la capa PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Verifiquemos si la imagen actualizada se guardó correctamente
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ver también

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* asamblea [Aspose.PSD](../../)



---
title: "SectionDividerLayer"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La capa divisora de sección para marcar los límites del grupo de capas de carpeta."
type: docs
weight: 28
url: /es/java/com.aspose.psd.fileformats.psd.layers/sectiondividerlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
```
public class SectionDividerLayer extends Layer
```

La capa divisor de sección para marcar los límites de la carpeta (grupo de capas).
## Campos

| Campo | Descripción |
| --- | --- |
| [BlendSignature](#BlendSignature) | Representa la firma del modo de fusión. |
| [LayerHeaderSize](#LayerHeaderSize) | El tamaño del encabezado de la capa. |
| [OnCreate_internalized](#OnCreate-internalized) | Ocurre cuando se cargó la imagen |
| [OnLoad_internalized](#OnLoad-internalized) | Ocurre cuando la imagen se cargó mediante createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Ocurre cuando la imagen se cargó o guardó |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Ocurre cuando se utilizó el crédito |
| [resources_internalized](#resources-internalized) | Los recursos |
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Obtiene el recurso asociado con el tipo especificado. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Añade la máscara a la capa actual. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Añade el recurso. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste de brillo para la imagen. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste de imagen |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Corrección gamma de una imagen. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Corrección gamma de una imagen. |
| [applyLayerMask()](#applyLayerMask--) | Aplica la máscara de capa a la capa, luego elimina la máscara. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Aplica la configuración de estilo de capa de la entrada [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) a la instancia de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) actual. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Inicia el proceso de redimensionamiento. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarización de una imagen con umbral predefinido |
| [binarizeOtsu()](#binarizeOtsu--) | Binarización de una imagen con umbralizado de Otsu |
| [cacheData()](#cacheData--) | Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el subyacente DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Determina si la imagen puede cargarse desde el flujo especificado y opcionalmente usando las loadOptions especificadas. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y opcionalmente usando las opciones de apertura especificadas. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Convierte a aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crea una nueva imagen usando las opciones de creación especificadas. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [createInstance_internalized(PsdHeader psdHeader, IColorPalette colorPalette)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-) |  |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Crea la nueva instancia de la clase [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createInstance_internalized(PsdHeader psdHeader, IColorPalette colorPalette, int layerNestedLevel)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-int-) | Inicializa una nueva instancia de la clase [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) con recursos predeterminados. |
| [createLayerState_internalized()](#createLayerState-internalized--) | Crea la nueva instancia de [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basada en los valores actuales de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Recortando la imagen. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recortar la imagen con desplazamientos. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Aplica dithering a la imagen actual. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Aplica dithering a la imagen actual. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Recortando la imagen. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona la imagen. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Rota, voltea o rota y voltea la imagen. |
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Dibuja la imagen en la capa. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el Object especificado es igual a esta instancia. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtra el rectángulo especificado. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Encuentra el recurso asignable. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Encuentra el  PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Encuentra el recurso por clave única. |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Obtiene o establece los límites absolutos. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Obtiene un píxel de imagen ARGB de 32 bits. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Obtiene un valor que indica si la paleta se ajusta automáticamente. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene o establece un valor para el color de fondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene el recuento de bits por píxel de la imagen. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Obtiene o establece la mezcla del elemento recortado. |
| [getBlendModeKey()](#getBlendModeKey--) | Obtiene o establece la clave del modo de mezcla. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Obtiene la firma del modo de mezcla. |
| [getBlendingOptions()](#getBlendingOptions--) | Obtiene las opciones de mezcla. |
| [getBottom()](#getBottom--) | Obtiene o establece la posición de la capa inferior. |
| [getBounds()](#getBounds--) | Obtiene los límites de la imagen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Obtiene los bytes por fila para el modo de máscara completa. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Obtiene los bytes por fila. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Obtiene los bytes por fila. |
| [getChannelInformation()](#getChannelInformation--) | Obtiene o establece la información del canal. |
| [getChannelsCount()](#getChannelsCount--) | Obtiene el recuento de canales de la capa. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Obtiene o establece el recorte de la capa. |
| [getContainer()](#getContainer--) | Obtiene el  Image  contenedor. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtiene el flujo de datos del objeto. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Obtiene la paleta de ajuste profundo. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtiene las opciones predeterminadas. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Obtiene la matriz de píxeles predeterminada usando el cargador parcial de píxeles. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Obtiene la matriz de datos sin procesar predeterminada. |
| [getDisplayName()](#getDisplayName--) | Obtiene el nombre para mostrar de la capa. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getExtraLength()](#getExtraLength--) | Obtiene la longitud de la información extra de la capa en bytes. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Obtiene el formato de archivo. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtiene el formato de archivo. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtiene el formato de archivo. |
| [getFillOpacity()](#getFillOpacity--) | Obtiene o establece la opacidad del relleno. |
| [getFiller()](#getFiller--) | Obtiene o establece el rellenador de la capa. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [getFlags()](#getFlags--) | Obtiene o establece las banderas de la capa. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Obtiene la lista de la jerarquía de carpetas de [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) de la capa actual. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Obtiene la paleta de lugares específicos del formato. |
| [getGUID_internalized()](#getGUID-internalized--) | Obtiene el identificador único de esta instancia de Layer. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtiene o establece el encabezado. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Obtiene la opacidad de esta imagen. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Obtiene el transformador interno de datos. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtiene el monitor de interrupciones. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Obtiene o establece los datos de rangos de fusión de la capa. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Obtiene o establece la fecha y hora de creación de la capa. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Obtiene o establece el bloqueo de la capa. |
| [getLayerMaskData()](#getLayerMaskData--) | Obtiene o establece los datos de máscara de la capa. |
| [getLayerOptions()](#getLayerOptions--) | Obtiene las opciones de la capa. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Obtiene o establece la paleta de la capa. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Obtiene el tipo de la capa. |
| [getLeft()](#getLeft--) | Obtiene o establece la posición izquierda de la capa. |
| [getLength()](#getLength--) | Obtiene la longitud total de la capa en bytes. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Obtiene o establece la asignación máxima permitida para el guardado de rotación parcial. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Obtiene el administrador de memoria. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Obtiene la fecha y hora en que la imagen de recurso fue modificada por última vez. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Obtiene o establece el nombre de la capa. |
| [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad de la capa. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Obtiene la opacidad total. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones basadas en la configuración original del archivo. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Obtiene la imagen pintable. |
| [getPalette()](#getPalette--) | Obtiene la paleta de colores. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtiene un píxel de imagen. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crea la caché de fuentes privada. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene la información del controlador del evento de progreso. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Obtiene la información del controlador del evento de progreso. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Obtiene una altura proporcional. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Obtiene un ancho proporcional. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Obtiene o establece el convertidor de color personalizado |
| [getRawDataFormat()](#getRawDataFormat--) | Obtiene el formato de datos sin procesar. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Obtiene o establece el convertidor de color indexado |
| [getRawLineSize()](#getRawLineSize--) | Obtiene el tamaño bruto de la línea en bytes. |
| [getRelatedLayerGroup()](#getRelatedLayerGroup--) | Obtiene el [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) que está relacionado con esta instancia de [SectionDividerLayer](../../com.aspose.psd.fileformats.psd.layers/sectiondividerlayer). |
| [getResources()](#getResources--) | Obtiene o establece los recursos de capa. |
| [getRight()](#getRight--) | Obtiene o establece la posición derecha de la capa. |
| [getRotateMode()](#getRotateMode--) | Obtiene o establece el modo de rotación. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Obtiene o establece el resaltado de color de hoja decorativa en la lista de capas |
| [getSize()](#getSize--) | Obtiene el tamaño de la imagen. |
| [getSkewAngle()](#getSkewAngle--) | Obtiene el ángulo de sesgo. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtiene la ruta del archivo de la imagen fuente si existe. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Obtiene la raíz de sincronización. |
| [getTop()](#getTop--) | Obtiene o establece la posición superior de la capa. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente de la imagen. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtiene un valor que indica si el objeto usa la estrategia de optimización de memoria |
| [getUseRawData()](#getUseRawData--) | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Obtiene la paleta utilizada. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Obtiene la licencia de la empresa. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este RasterImage. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getXmpData()](#getXmpData--) | Obtiene o establece los metadatos XMP. |
| [grayscale()](#grayscale--) | Transformación de una imagen a su representación en escala de grises |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene canal alfa. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtiene un valor que indica si la imagen tiene color de fondo. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si la imagen tiene color transparente. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Obtiene o establece el valor máximo del progreso |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica el progreso. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Inserta un recurso en la colección Resources. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Detecta si la capa es válida para guardarse en un archivo. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [isUsePalette()](#isUsePalette--) | Obtiene un valor que indica si se usa la paleta de la imagen. |
| [isVisible()](#isVisible--) | Obtiene o establece un valor que indica si la capa es visible |
| [isVisibleInGroup()](#isVisibleInGroup--) | Obtiene un valor que indica si esta instancia es visible en el grupo (Si la capa no está en un grupo, significa que es el grupo raíz). |
| [load(InputStream stream)](#load-java.io.InputStream-) | Carga una nueva imagen desde el flujo especificado. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el flujo especificado. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Carga una nueva imagen desde el flujo especificado. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el flujo especificado. |
| [load(String filePath)](#load-java.lang.String-) | Carga una nueva imagen desde el archivo especificado. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el archivo especificado. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Carga píxeles ARGB de 32 bits. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Carga píxeles ARGB de 64 bits. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Carga píxeles en formato CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Carga píxeles en formato CMYK. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Carga parcialmente píxeles ARGB de 32 bits por paquetes. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Carga píxeles parcialmente por paquetes. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Carga píxeles. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Carga datos de imagen sin procesar usando el mecanismo de procesamiento parcial. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Carga datos sin procesar. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Carga una nueva imagen desde el flujo especificado. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el flujo especificado. |
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Fusiona la capa con la capa especificada |
| [normalizeAngle()](#normalizeAngle--) | Normaliza el ángulo. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliza el ángulo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoca cuando se estableció el contenedor de esta Imagen. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Elimina el recurso. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para guardar bordes suaves. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para guardar bordes suaves. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para guardar bordes suaves. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para guardar bordes suaves. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Redimensiona los datos de los canales |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Redimensiona la altura proporcionalmente. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona la altura proporcionalmente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensiona la altura proporcionalmente. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Redimensiona el ancho proporcionalmente. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona el ancho proporcionalmente. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensiona el ancho proporcionalmente. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Redimensiona la capa con la escala inversa especificada. |
| [rotate(float angle)](#rotate-float-) | Rota la imagen alrededor del centro. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Rota la imagen alrededor del centro. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Guarda los datos de la imagen en el flujo subyacente. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Guarda los datos del objeto en el flujo especificado. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Guarda los datos del objeto en el flujo especificado. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save(String filePath)](#save-java.lang.String-) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Guarda los píxeles ARGB de 32 bits. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Guarda los píxeles. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Guarda los píxeles. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Guarda los píxeles. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Guarda los datos sin procesar. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Guarda datos en el contenedor de flujo especificado. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Obtiene o establece los límites absolutos. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Establece un píxel de imagen de 32 bits ARGB para la posición especificada. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Establece un valor que indica si se ajusta automáticamente la paleta. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Obtiene o establece un valor para el color de fondo. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Obtiene o establece la mezcla del elemento recortado. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Obtiene o establece la clave del modo de mezcla. |
| [setBottom(int value)](#setBottom-int-) | Obtiene o establece la posición de la capa inferior. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Obtiene o establece la información del canal. |
| [setClipping(byte value)](#setClipping-byte-) | Obtiene o establece el recorte de la capa. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Establece el contenedor Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Establece el cargador de datos directamente. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Establece el flujo de datos del objeto. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Obtiene o establece el nombre para mostrar de la capa. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Obtiene la opacidad de relleno. |
| [setFiller(byte value)](#setFiller-byte-) | Obtiene o establece el rellenador de la capa. |
| [setFlags(byte value)](#setFlags-byte-) | Obtiene o establece las banderas de la capa. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Establece la paleta en lugares específicos del formato. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtiene o establece el encabezado. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Establece un valor que indica si [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Establece el transformador interno de datos. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Establece el monitor de interrupciones. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Obtiene o establece los datos de rangos de fusión de la capa. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Obtiene o establece la fecha y hora de creación de la capa. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Obtiene o establece el bloqueo de capa (Nota que si la bandera LayerFlags.TransparencyProtected está establecida, será sobrescrita por la bandera de bloqueo de capa). |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Obtiene o establece los datos de máscara de la capa. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Obtiene o establece la paleta de la capa. |
| [setLeft(int value)](#setLeft-int-) | Obtiene o establece la posición izquierda de la capa. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Obtiene o establece la asignación máxima permitida para el guardado de rotación parcial. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Establece el administrador de memoria. |
| [setName(String name)](#setName-java.lang.String-) | Establece el nombre de la capa. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Obtiene o establece el nombre de la capa. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtiene o establece la opacidad de la capa. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Establece la paleta de colores. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Establece la paleta de la imagen. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Establece un píxel de imagen para la posición especificada. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Obtiene o establece el convertidor de color personalizado |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Obtiene o establece el convertidor de color indexado |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establece la resolución para este RasterImage. |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Obtiene o establece los recursos de capa. |
| [setRight(int value)](#setRight-int-) | Obtiene o establece la posición derecha de la capa. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Obtiene o establece el modo de rotación. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Obtiene o establece el resaltado de color de hoja decorativa en la lista de capas |
| [setTop(int value)](#setTop-int-) | Obtiene o establece la posición superior de la capa. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtiene un valor que indica si la imagen tiene color transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Obtiene el color transparente de la imagen. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Todos los productos Aspose deberían implementar este método. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este RasterImage. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece un valor que indica si la capa es visible |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtiene o establece los metadatos XMP. |
| [shallowCopy()](#shallowCopy--) | Crea una copia superficial de la capa actual. |
| [toBitmap()](#toBitmap--) | Convierte la imagen raster a bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Actualiza las opciones de fusión después de que cambien la capa o los recursos globales. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Representa la firma del modo de fusión.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


El tamaño del encabezado de la capa.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Ocurre cuando se cargó la imagen

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Ocurre cuando la imagen se cargó mediante createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Ocurre cuando la imagen se cargó o guardó

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Ocurre cuando se utilizó el crédito

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Los recursos

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Obtiene el recurso asociado con el tipo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | Cuando este método devuelve, contiene el recurso asociado con el tipo de clave especificado, si se encuentra la clave; de lo contrario, devuelve null. |

T : El tipo de clave del valor a obtener. |

**Returns:**
boolean -   si contiene un recurso con el tipo especificado; de lo contrario,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Añade la máscara a la capa actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | La máscara de capa. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Añade el recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | El recurso. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste de brillo para la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brillo | int | Valor de brillo. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Contraste de imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraste | float | Valor de contraste (en el rango [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Corrección gamma de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Corrección gamma de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Coeficiente gamma para el canal rojo |
| gammaGreen | float | Coeficiente gamma para el canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Aplica la máscara de capa a la capa, luego elimina la máscara.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Aplica la configuración de estilo de capa de la entrada [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) a la instancia de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | El estado de capa con nuevo estilo. |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Inicia el proceso de redimensionamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho de imagen. |
| newHeight | int | La nueva altura de la imagen. |

**Returns:**
com.aspose.internal.IResizeController - El controlador de redimensionamiento.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| windowSize | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarización de una imagen con umbral predefinido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor de umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255, 0 en caso contrario. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarización de una imagen con umbralizado de Otsu

### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el subyacente DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Determina si la imagen puede cargarse desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo desde el cual cargar. |

**Returns:**
boolean -  true  si la imagen se puede cargar desde el flujo especificado; de lo contrario,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Determina si la imagen puede cargarse desde el flujo especificado y opcionalmente usando las loadOptions especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo desde el cual cargar. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
boolean -  true  si la imagen se puede cargar desde el flujo especificado; de lo contrario,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Determina si la imagen puede cargarse desde la ruta de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |

**Returns:**
boolean -  true  si la imagen se puede cargar desde el archivo especificado; de lo contrario,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Determina si la imagen puede cargarse desde la ruta de archivo especificada y opcionalmente usando las opciones de apertura especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
boolean -  true  si la imagen se puede cargar desde el archivo especificado; de lo contrario,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de guardado a usar. |

**Returns:**
boolean -  true  si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado proporcionadas; de lo contrario,  false .
### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Convierte a aps.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones. |
| mode | int | El modo. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de recorte. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - La página APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Crea una nueva imagen usando las opciones de creación especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de imagen. |
| ancho | int | El ancho. |
| alto | int | El alto. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Crea una nueva imagen usando las imágenes especificadas como páginas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Las imágenes. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Crea una nueva imagen con las imágenes especificadas como páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Las imágenes. |
| disposeImages | boolean | si se establece a  true  [dispose images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, IColorPalette colorPalette) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-}
```
public static SectionDividerLayer createInstance_internalized(PsdHeader psdHeader, IColorPalette colorPalette)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

**Returns:**
[SectionDividerLayer](../../com.aspose.psd.fileformats.psd.layers/sectiondividerlayer)
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Crea la nueva instancia de la clase [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encabezado | com.aspose.internal.fileformats.psd.sections.PsdHeader | El encabezado. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | El LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createInstance_internalized(PsdHeader psdHeader, IColorPalette colorPalette, int layerNestedLevel) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-int-}
```
public static SectionDividerLayer createInstance_internalized(PsdHeader psdHeader, IColorPalette colorPalette, int layerNestedLevel)
```


Inicializa una nueva instancia de la clase [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) con recursos predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | El encabezado psd. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |
| layerNestedLevel | int | Nivel anidado de la capa. |

**Returns:**
[SectionDividerLayer](../../com.aspose.psd.fileformats.psd.layers/sectiondividerlayer) - The new instance of the [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) class with default resources.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Crea la nueva instancia de [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basada en los valores actuales de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| redimensionador | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| ancho | int |  |
| alto | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recortando la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recortar la imagen con desplazamientos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento a la derecha. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |

### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Aplica dithering a la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Aplica dithering a la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta personalizada para el tramado. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Recortando la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | La configuración de redimensionado. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Rota, voltea o rota y voltea la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Dibuja la imagen en la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | La ubicación. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el Object especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El Object para comparar con esta instancia. |

**Returns:**
boolean -  true  si el Object especificado es igual a esta instancia; de lo contrario,  false .
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtra el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Las opciones. |

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Encuentra el recurso asignable.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | El tipo. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Encuentra el  PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Encuentra el recurso por clave única.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeToolKey | int | La clave de la herramienta de tipo. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Obtiene o establece los límites absolutos.

Valor: Los límites absolutos.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Obtiene un píxel de imagen ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns:**
int - El píxel ARGB de 32 bits para la ubicación especificada.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Obtiene un valor que indica si la paleta se ajusta automáticamente.

**Returns:**
boolean -  true  si habilita el ajuste automático de la paleta; de lo contrario,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene o establece un valor para el color de fondo.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene el recuento de bits por píxel de la imagen.

Valor: El recuento de bits por píxel de la imagen.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Obtiene o establece la mezcla del elemento recortado.

Valor: La fusión del elemento recortado.

**Returns:**
boolean
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Obtiene o establece la clave del modo de mezcla.

Valor: La clave del modo de fusión.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Obtiene la firma del modo de mezcla.

Valor: La firma del modo de fusión.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Obtiene las opciones de mezcla.

Valor: Las opciones de fusión.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtiene o establece la posición de la capa inferior.

Valor: La posición de la capa inferior.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtiene los límites de la imagen.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int - la sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos.
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Obtiene los bytes por fila para el modo de máscara completa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitDepth | int | La profundidad de bits. |

**Returns:**
int - Bytes necesarios para almacenar 1 fila
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Obtiene los bytes por fila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitDepth | int | La profundidad de bits. |

**Returns:**
int - Bytes necesarios para almacenar 1 fila
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Obtiene los bytes por fila.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitDepth | int | La profundidad de bits. |

**Returns:**
int - Bytes necesarios para almacenar 1 fila
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Obtiene o establece la información del canal.

Valor: La información del canal.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Obtiene el recuento de canales de la capa.

Valor: El recuento de canales de la capa.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Obtiene o establece el recorte de la capa. 0 = base, 1 = no-base.

Valor: El recorte de la capa.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Obtiene el  Image  contenedor.

Valor: El contenedor de Image.

Si esta propiedad no es nula, indica que la imagen está contenida dentro de otra imagen.

**Returns:**
[Image](../../com.aspose.psd/image)
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Obtiene el flujo de datos del objeto.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Obtiene la paleta de ajuste profundo.

**Returns:**
boolean - La paleta de ajuste profundo.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Obtiene la matriz de píxeles ARGB de 32 bits predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo para obtener píxeles. |

**Returns:**
int[] - La matriz de píxeles predeterminada.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtiene las opciones predeterminadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | java.lang.Object[] | Los argumentos. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Obtiene la matriz de píxeles predeterminada usando el cargador parcial de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo para obtener píxeles. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | El cargador parcial de píxeles. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo para obtener píxeles. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | El cargador parcial de datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | La configuración de datos sin procesar. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Obtiene la matriz de datos sin procesar predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo para obtener datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | La configuración de datos sin procesar. |

**Returns:**
byte[] - La matriz de datos sin procesar predeterminada.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Obtiene el nombre para mostrar de la capa.

Valor: El nombre para mostrar de la capa.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Obtiene la longitud de la información extra de la capa en bytes.

Valor: La longitud extra de la capa.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtiene un valor del formato de archivo

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Obtiene el formato de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | El flujo. |

--------------------

El formato de archivo determinado no significa que la imagen especificada pueda cargarse. Use una de las sobrecargas del método CanLoad para determinar si stream puede cargarse. |

**Returns:**
long - El formato de archivo determinado.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Obtiene el formato de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | stream | java.io.InputStream | El flujo. |

El formato de archivo determinado no significa que la imagen especificada pueda cargarse. Use una de las sobrecargas del método CanLoad para determinar si stream puede cargarse. |

**Returns:**
long - El formato de archivo determinado.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Obtiene el formato de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo. |

El formato de archivo determinado no significa que la imagen especificada pueda cargarse. Use una de las sobrecargas del método CanLoad para determinar si el archivo puede cargarse. |

**Returns:**
long - El formato de archivo determinado.
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Obtiene o establece la opacidad del relleno.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Obtiene o establece el rellenador de la capa.

Valor: El relleno de capa.

**Returns:**
byte
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Obtiene el rectángulo que se ajusta a la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo para obtener el rectángulo que encaje. |
| ancho | int | El ancho del objeto. |
| alto | int | La altura del objeto. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Obtiene el rectángulo que se ajusta a la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo para obtener el rectángulo que encaje. |
| píxeles | int[] | Los píxeles ARGB de 32 bits. |
| ancho | int | El ancho del objeto. |
| alto | int | La altura del objeto. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Obtiene o establece los indicadores de capa. bit 0 = transparencia protegida; bit 1 = visible; bit 2 = obsoleto; bit 3 = 1 para Photoshop 5.0 y posteriores, indica si el bit 4 tiene información útil; bit 4 = datos de píxel irrelevantes para la apariencia del documento.

Valor: Los indicadores de capa.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Obtiene la lista de la jerarquía de carpetas de [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) de la capa actual.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Devuelve la lista de la jerarquía de carpetas de [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) de la capa actual.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Obtiene la paleta de lugares específicos del formato.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Obtiene el identificador único de esta instancia de Layer.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

Valor: La altura de la imagen.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este RasterImage.

**Returns:**
double - La resolución horizontal.

Nota: por defecto este valor es siempre 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtiene la opacidad de esta imagen.

**Returns:**
float - El valor de opacidad entre 0.0 (totalmente transparente) y 1.0 (totalmente opaco).
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Obtiene el transformador interno de datos.

Valor: El transformador interno de datos.

**Returns:**
com.aspose.internal.IInnerDataTransformer - el transformador interno de datos.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Obtiene el monitor de interrupciones.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Obtiene o establece los datos de rangos de fusión de la capa.

Valor: Los datos de rangos de fusión de capa.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Obtiene o establece la fecha y hora de creación de la capa.

Valor: La fecha y hora de creación de la capa. Si no hay datos sobre la fecha y hora de creación, entonces devuelve la primera época del tiempo Unix.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Obtiene o establece el bloqueo de capa. Nota que si la bandera LayerFlags.TransparencyProtected está establecida será sobrescrita por la bandera de bloqueo de capa. Para devolver la bandera LayerFlags.TransparencyProtected es necesario aplicarla en la opción de capa layer.Flags |= LayerFlags.TransparencyProtected

Valor: El bloqueo de capa.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Obtiene o establece los datos de máscara de la capa.

Valor: Los datos de máscara de capa.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Obtiene las opciones de la capa.

Valor: Las opciones de capa.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Obtiene o establece la paleta de la capa.

Valor: La paleta de capas.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Obtiene el tipo de la capa.

Valor: El tipo de la capa.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtiene o establece la posición izquierda de la capa.

Valor: La posición izquierda de la capa.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Obtiene la longitud total de la capa en bytes.

**Returns:**
long
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Obtiene o establece la asignación máxima permitida para el guardado de rotación parcial.

**Returns:**
int - La asignación máxima permitida para guardar rotación parcial.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Obtiene el administrador de memoria.

Valor: El gestor de memoria.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - el gestor de memoria.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Obtiene la fecha y hora en que la imagen de recurso fue modificada por última vez.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useDefault | boolean | si se establece en  true  usa la información de FileInfo como valor predeterminado. |

**Returns:**
java.util.Date - La fecha y hora en que la imagen del recurso fue modificada por última vez.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getName() {#getName--}
```
public final String getName()
```


Obtiene o establece el nombre de la capa.

Valor: El nombre de la capa.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Obtiene o establece la opacidad de la capa. 0 = transparente, 255 = opaco.

Valor: La opacidad de la capa.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Obtiene la opacidad total. La opacidad total es la multiplicación de la Opacidad de la Capa y la Opacidad de Relleno de la Capa. Se usa para la fusión de capas.

Valor: La opacidad total.

**Returns:**
byte
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método  DataStreamSupporter.Save(string) , se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método  Image.Save(string, ImageOptionsBase)  como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Obtiene la imagen pintable.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtiene la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Obtiene un píxel de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados.

**Returns:**
boolean -  true  si los componentes de la imagen deben estar premultiplicados; de lo contrario,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Crea la caché de fuentes privada.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - La caché de fuentes privada.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtiene la información del controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Obtiene la información del controlador del evento de progreso.

Valor: La información del manejador de eventos de progreso.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Obtiene una altura proporcional.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int | El ancho. |
| alto | int | El alto. |
| newWidth | int | El nuevo ancho. |

**Returns:**
int - La altura proporcional.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Obtiene un ancho proporcional.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho | int | El ancho. |
| alto | int | El alto. |
| newHeight | int | El nuevo alto. |

**Returns:**
int - La anchura proporcional.
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Obtiene o establece el convertidor de color personalizado

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Obtiene el formato de datos sin procesar.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración los datos se cargan sin conversión.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites

**Returns:**
int - El índice de reserva a usar cuando el índice de la paleta está fuera de los límites
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Obtiene o establece el convertidor de color indexado

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Obtiene el tamaño bruto de la línea en bytes.

**Returns:**
int - El tamaño de línea sin procesar en bytes.
### getRelatedLayerGroup() {#getRelatedLayerGroup--}
```
public final LayerGroup getRelatedLayerGroup()
```


Obtiene el [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) que está relacionado con esta instancia de [SectionDividerLayer](../../com.aspose.psd.fileformats.psd.layers/sectiondividerlayer).

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - The [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) instance.
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Obtiene o establece los recursos de capa.

Valor: Los recursos de la capa.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Obtiene o establece la posición derecha de la capa.

Valor: La posición de la capa derecha.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Obtiene o establece el modo de rotación.

**Returns:**
int - El modo de rotación.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Obtiene o establece el resaltado de color de hoja decorativa en la lista de capas

Valor: El resaltado de color de la hoja.

**Returns:**
short
### getSize() {#getSize--}
```
public Size getSize()
```


Obtiene el tamaño de la imagen.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Obtiene el ángulo de sesgo. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear.

**Returns:**
float - El ángulo de sesgo, en grados.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtiene la ruta del archivo de la imagen fuente si existe. Devuelve una cadena vacía si no se puede encontrar la ruta fuente.

**Returns:**
java.lang.String - La ruta del archivo de la imagen fuente.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Obtiene la raíz de sincronización.

Valor: La raíz de sincronización.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Obtiene o establece la posición superior de la capa.

Valor: La posición de la capa superior.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtiene el color transparente de la imagen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP.

**Returns:**
boolean -  true  si actualiza los metadatos XMP; de lo contrario,  false .
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Obtiene un valor que indica si el objeto usa la estrategia de optimización de memoria

Valor:  true  si el objeto usa la estrategia de optimización de memoria; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si el objeto usa la estrategia de optimización de memoria
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible.

**Returns:**
boolean -  true  si se usa la carga de datos sin procesar cuando está disponible.; de lo contrario,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Obtiene la paleta utilizada.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Obtiene la licencia de la empresa.

**Returns:**
java.lang.Object - La licencia Teh venture como objeto.
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtiene o establece la resolución vertical, en píxeles por pulgada, de este RasterImage.

**Returns:**
double - La resolución vertical.

Nota: por defecto este valor es siempre 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

Valor: El ancho de la imagen.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtiene o establece los metadatos XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformación de una imagen a su representación en escala de grises

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene canal alfa.

Valor:  true  si esta instancia tiene alfa; de lo contrario,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtiene un valor que indica si la imagen tiene color de fondo.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar.

**Returns:**
boolean -  true  si esta instancia tiene la imagen modificada; de lo contrario,  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtiene un valor que indica si la imagen tiene color transparente.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Obtiene o establece el valor máximo del progreso

Valor: El valor máximo de progreso

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Indica el progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Inserta un recurso en la colección Resources.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del recurso que debe insertarse. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | El recurso que debe insertarse. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente.

**Returns:**
boolean -  true  si los datos de la imagen están en caché; de lo contrario,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Detecta si la capa es válida para guardarse en un archivo.

**Returns:**
boolean -
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Obtiene un valor que indica si la carga de datos sin procesar está disponible.

**Returns:**
boolean -  true  si esta carga de datos sin procesar está disponible; de lo contrario,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Obtiene un valor que indica si se usa la paleta de la imagen.

Valor:  true  si la paleta se usa en la imagen; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si se usa la paleta de la imagen.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Obtiene o establece un valor que indica si la capa es visible

Valor:  true  si esta instancia es visible; de lo contrario,  false .

**Returns:**
boolean
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Obtiene un valor que indica si esta instancia es visible en el grupo (Si la capa no está en un grupo, significa que es el grupo raíz).

Valor:  true  si esta instancia es visible en el grupo; de lo contrario,  false .

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Carga una nueva imagen desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo desde el cual cargar la imagen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Carga una nueva imagen desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo desde el cual cargar la imagen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Carga una nueva imagen desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El archivo desde el cual cargar la imagen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Carga una nueva imagen desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El archivo desde el cual cargar la imagen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Carga una nueva imagen desde el archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo desde la cual cargar la imagen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Carga una nueva imagen desde el archivo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo desde la cual cargar la imagen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Carga píxeles ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar los píxeles. |

**Returns:**
int[] - La matriz de píxeles ARGB de 32 bits cargada.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Carga píxeles ARGB de 64 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar los píxeles. |

**Returns:**
long[] - La matriz de píxeles ARGB de 64 bits cargada.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Carga píxeles en formato CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar los píxeles. |

**Returns:**
int[] - Los píxeles CMYK cargados presentados como valores enteros de 32 bits.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Carga píxeles en formato CMYK. Este método está obsoleto. Por favor, use el método más eficaz loadCmyk32Pixels(Rectangle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar los píxeles. |

**Returns:**
com.aspose.psd.CmykColor[] - La matriz de píxeles CMYK cargada.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Carga parcialmente píxeles ARGB de 32 bits por paquetes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo deseado. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | El cargador de píxeles ARGB de 32 bits. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Carga píxeles parcialmente por paquetes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo deseado. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | El cargador de píxeles. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Carga píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar los píxeles. |

**Returns:**
com.aspose.psd.Color[] - La matriz de píxeles cargada.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carga datos de imagen sin procesar usando el mecanismo de procesamiento parcial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El área rectangular deseada de la imagen desde la cual cargar datos. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | La configuración de datos sin procesar. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | El cargador de datos sin procesar. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carga datos sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar datos sin procesar. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen de destino. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Los ajustes de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará una conversión de datos. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | El cargador de datos sin procesar. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Carga una nueva imagen desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | El flujo desde el cual cargar la imagen. |
| posicionInicial | long | La posición inicial desde la cual cargar la imagen. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Carga una nueva imagen desde el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | El flujo desde el cual cargar la imagen. |
| posicionInicial | long | La posición inicial desde la cual cargar la imagen. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Fusiona la capa con la capa especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | La capa en la que fusionar. |

### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la escaneado sesgado. Este método usa [.getSkewAngle](../../null/\#getSkewAngle) y [.rotate(float)](../../null/\#rotate-float-) métodos.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la escaneado sesgado. Este método usa [.getSkewAngle](../../null/\#getSkewAngle) y [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) métodos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeProportionally | boolean | si se establece en true, el tamaño de su imagen cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en caso contrario, se dejarán las dimensiones sin cambios y solo se rotará el contenido interno de la imagen. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Color del fondo. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Invoca cuando se estableció el contenedor de esta Imagen.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |

**Returns:**
int[] - La matriz de valores de color ARGB de 32 bits de la línea de escaneo.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |

**Returns:**
com.aspose.psd.Color[] - La matriz de valores de color de píxel de la línea de escaneo.
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Elimina el recurso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | El recurso. |

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para guardar bordes suaves.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Color antiguo a reemplazar. |
| oldColorDiff | byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| newColor | [Color](../../com.aspose.psd/color) | Nuevo color con el que reemplazar el color antiguo. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para guardar bordes suaves.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldColorArgb | int | Valor ARGB del color antiguo a reemplazar. |
| oldColorDiff | byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| newColorArgb | int | Valor ARGB del nuevo color con el que reemplazar el color antiguo. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Reemplaza todos los colores no transparentes con el nuevo color y preserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Nuevo color con el que reemplazar los colores no transparentes. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Reemplaza todos los colores no transparentes con el nuevo color y preserva el valor alfa original para mantener bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores se reemplazarán por uno único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorArgb | int | Valor ARGB del nuevo color con el que reemplazar los colores no transparentes. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Redimensiona la imagen. Se utiliza el valor predeterminado ResizeType.LeftTopToLeftTop.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | La configuración de redimensionado. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Redimensiona los datos de los canales

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Redimensiona la altura proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Redimensiona la altura proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Los ajustes de redimensionamiento de la imagen. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Redimensiona la altura proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| resizeType | int | Tipo de redimensionamiento. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Redimensiona el ancho proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Redimensiona el ancho proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Los ajustes de redimensionamiento de la imagen. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Redimensiona el ancho proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| resizeType | int | Tipo de redimensionamiento. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Redimensiona la capa con la escala inversa especificada. (nueva anchura = anchura antigua / escala; nueva altura = altura antigua / escala)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | double | La escala X. |
| scaleY | double | La escala Y. |
| resizeType | int | Tipo de redimensionamiento. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rota la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rota la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en true, el tamaño de su imagen cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en caso contrario, se dejarán las dimensiones sin cambios y solo se rotará el contenido interno de la imagen. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Color del fondo. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rota, voltea o rota y voltea la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Guarda los datos de la imagen en el flujo subyacente.

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Guarda los datos del objeto en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo donde guardar los datos del objeto. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo donde guardar los datos de la imagen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de guardado. |

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstStream | java.io.OutputStream | El flujo donde guardar los datos de la imagen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de guardado. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Guarda los datos del objeto en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El flujo donde guardar los datos del objeto. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El archivo donde guardar los datos de la imagen. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| archivo | java.io.RandomAccessFile | El archivo donde guardar los datos de la imagen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de guardado. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del objeto. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del objeto. |
| overWrite | boolean | Si se establece en true sobrescribirá el contenido del archivo, de lo contrario se producirá una anexión. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Guarda los píxeles ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Guarda los píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Guarda los píxeles. Este método está obsoleto. Por favor, use el método más eficaz saveCmyk32Pixels(Rectangle, int[]).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | La matriz de píxeles CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Guarda los píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | La matriz de píxeles. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Guarda los datos sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos sin procesar. |
| dataOffset | int | El desplazamiento inicial de datos sin procesar. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | La configuración de datos sin procesar en la que se encuentran los datos. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | El flujo donde guardar los datos de la imagen. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de guardado. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Guarda datos en el contenedor de flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| psdVersion | int | La versión PSD. |
| bitDepth | int | La profundidad de bits. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Obtiene o establece los límites absolutos.

Valor: Los límites absolutos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Establece un píxel de imagen de 32 bits ARGB para la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| argb32Color | int | El píxel ARGB de 32 bits para la posición especificada. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Establece un valor que indica si se ajusta automáticamente la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true si se habilita el ajuste automático de la paleta; de lo contrario, false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Obtiene o establece un valor que indica si la imagen tiene color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Obtiene o establece un valor para el color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Obtiene o establece la mezcla del elemento recortado.

Valor: La fusión del elemento recortado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Obtiene o establece la clave del modo de mezcla.

Valor: La clave del modo de fusión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtiene o establece la posición de la capa inferior.

Valor: La posición de la capa inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos. |

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Obtiene o establece la información del canal.

Valor: La información del canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Obtiene o establece el recorte de la capa. 0 = base, 1 = no-base.

Valor: El recorte de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Establece el contenedor Image.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | El contenedor Image. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Establece el cargador de datos directamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | El cargador de datos. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Establece el flujo de datos del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | El flujo de datos del objeto. |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Obtiene o establece el nombre para mostrar de la capa.

Valor: El nombre para mostrar de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Obtiene la opacidad de relleno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Obtiene o establece el rellenador de la capa.

Valor: El relleno de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Obtiene o establece los indicadores de capa. bit 0 = transparencia protegida; bit 1 = visible; bit 2 = obsoleto; bit 3 = 1 para Photoshop 5.0 y posteriores, indica si el bit 4 tiene información útil; bit 4 = datos de píxel irrelevantes para la apariencia del documento.

Valor: Los indicadores de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Establece la paleta en lugares específicos del formato.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Nueva paleta ARGB de 32 bits. |

**Returns:**
boolean
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtiene o establece el encabezado.

Valor: El encabezado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este RasterImage.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución horizontal. |

Nota: por defecto este valor es siempre 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Establece un valor que indica si [ignore after save].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true si [ignore after save]; de lo contrario, false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true si esta instancia tiene la imagen modificada; de lo contrario, false. |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Establece el transformador interno de datos.

Valor: El transformador interno de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.internal.IInnerDataTransformer | El transformador interno de datos. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Establece el monitor de interrupciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | El monitor de interrupciones. |

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Obtiene o establece los datos de rangos de fusión de la capa.

Valor: Los datos de rangos de fusión de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Obtiene o establece la fecha y hora de creación de la capa.

Valor: La fecha y hora de creación de la capa. Si no hay datos sobre la fecha y hora de creación, entonces devuelve la primera época del tiempo Unix.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Obtiene o establece el bloqueo de capa (Nota que si la bandera LayerFlags.TransparencyProtected está establecida será sobrescrita por la bandera de bloqueo de capa. Para devolver la bandera LayerFlags.TransparencyProtected es necesario aplicarla en la opción de capa layer.Flags |= LayerFlags.TransparencyProtected

Valor: El bloqueo de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Obtiene o establece los datos de máscara de la capa.

Valor: Los datos de máscara de capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Obtiene o establece la paleta de la capa.

Valor: La paleta de capas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtiene o establece la posición izquierda de la capa.

Valor: La posición izquierda de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Obtiene o establece la asignación máxima permitida para el guardado de rotación parcial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La asignación máxima permitida para guardado de rotación parcial. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Establece el administrador de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | El administrador de memoria. |
| needDispose | boolean | si se establece en  true  [need dispose]. |

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Establece el nombre de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nombre de la capa. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Obtiene o establece el nombre de la capa.

Valor: El nombre de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Obtiene o establece la opacidad de la capa. 0 = transparente, 255 = opaco.

Valor: La opacidad de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Establece la paleta de colores. La paleta de colores no se usa cuando los píxeles se representan directamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Establece la paleta de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en  true  los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Establece un píxel de imagen para la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| color | [Color](../../com.aspose.psd/color) | El color del píxel para la posición especificada. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si los componentes de la imagen deben estar premultiplicados; de lo contrario,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Obtiene o establece el convertidor de color personalizado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | El convertidor de color personalizado |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El índice de reserva a usar cuando el índice de la paleta está fuera de los límites |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Obtiene o establece el convertidor de color indexado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | El convertidor de color indexado |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Establece la resolución para este RasterImage.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpiX | double | La resolución horizontal, en puntos por pulgada, del  RasterImage . |
| dpiY | double | La resolución vertical, en puntos por pulgada, del  RasterImage . |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Obtiene o establece los recursos de capa.

Valor: Los recursos de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Obtiene o establece la posición derecha de la capa.

Valor: La posición de la capa derecha.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Obtiene o establece el modo de rotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de rotación. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Obtiene o establece el resaltado de color de hoja decorativa en la lista de capas

Valor: El resaltado de color de la hoja.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtiene o establece la posición superior de la capa.

Valor: La posición de la capa superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Obtiene un valor que indica si la imagen tiene color transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Obtiene el color transparente de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si se actualiza la metadata XMP; de lo contrario,  false . |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si se usa la carga de datos sin procesar cuando la carga de datos sin procesar está disponible.; de lo contrario,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Todos los productos Aspose deben implementar este método. Es llamado por un producto GroupDocs para indicar si GroupDocs está licenciado o no y especificar una marca de agua personalizada. Cuando GroupDocs está licenciado, esta instancia de documento debe comportarse como licenciada también aunque el producto Aspose no esté licenciado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtiene o establece la resolución vertical, en píxeles por pulgada, de este RasterImage.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución vertical. |

Nota: por defecto este valor es siempre 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtiene o establece un valor que indica si la capa es visible

Valor:  true  si esta instancia es visible; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtiene o establece los metadatos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Los metadatos XMP. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Crea una copia superficial de la capa actual. Por favor   para explicación.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Convierte la imagen raster a bitmap.

**Returns:**
java.awt.image.BufferedImage - El mapa de bits
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Actualiza las opciones de fusión después de que cambien la capa o los recursos globales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |
| argb32Pixels | int[] | La matriz de colores ARGB de 32 bits para escribir. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | La matriz de colores de píxeles para escribir. |


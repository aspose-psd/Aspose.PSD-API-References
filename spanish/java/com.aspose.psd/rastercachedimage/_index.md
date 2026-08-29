---
title: "RasterCachedImage"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa una imagen raster que admite operaciones de gráficos raster."
type: docs
weight: 85
url: /es/java/com.aspose.psd/rastercachedimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Representa una imagen raster que admite operaciones gráficas raster. Esta imagen almacena en caché los datos de píxeles cuando es necesario.
## Campos

| Campo | Descripción |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Ocurre cuando se cargó la imagen |
| [OnLoad_internalized](#OnLoad-internalized) | Ocurre cuando la imagen se cargó mediante createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Ocurre cuando la imagen se cargó o guardó |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Ocurre cuando se utilizó el crédito |
## Métodos

| Método | Descripción |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste de brillo para la imagen. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste de imagen |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Corrección gamma de una imagen. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Corrección gamma de una imagen. |
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
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtra el rectángulo especificado. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Obtiene un píxel de imagen ARGB de 32 bits. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Obtiene un valor que indica si la paleta se ajusta automáticamente. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene o establece un valor para el color de fondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene el recuento de bits por píxel de la imagen. |
| [getBounds()](#getBounds--) | Obtiene los límites de la imagen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Obtiene el  Image  contenedor. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtiene el flujo de datos del objeto. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Obtiene la paleta de ajuste profundo. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtiene las opciones predeterminadas. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Obtiene la matriz de píxeles predeterminada usando el cargador parcial de píxeles. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Obtiene la matriz de datos sin procesar predeterminada. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Obtiene el formato de archivo. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtiene el formato de archivo. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtiene el formato de archivo. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Obtiene la paleta de lugares específicos del formato. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Obtiene la opacidad de esta imagen. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Obtiene el transformador interno de datos. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtiene el monitor de interrupciones. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Obtiene o establece la asignación máxima permitida para el guardado de rotación parcial. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Obtiene el administrador de memoria. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Obtiene la fecha y hora en que la imagen de recurso fue modificada por última vez. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
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
| [getRotateMode()](#getRotateMode--) | Obtiene o establece el modo de rotación. |
| [getSize()](#getSize--) | Obtiene el tamaño de la imagen. |
| [getSkewAngle()](#getSkewAngle--) | Obtiene el ángulo de sesgo. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtiene la ruta del archivo de la imagen fuente si existe. |
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
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Obtiene o establece el valor máximo del progreso |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica el progreso. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [isUsePalette()](#isUsePalette--) | Obtiene un valor que indica si se usa la paleta de la imagen. |
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
| [normalizeAngle()](#normalizeAngle--) | Normaliza el ángulo. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normaliza el ángulo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoca cuando se estableció el contenedor de esta [Image](../../com.aspose.psd/image). |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para guardar bordes suaves. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Reemplaza un color por otro con diferencia permitida y preserva el valor alfa original para guardar bordes suaves. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para guardar bordes suaves. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Reemplaza todos los colores no transparentes con un nuevo color y preserva el valor alfa original para guardar bordes suaves. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
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
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Guarda los datos del objeto en el flujo especificado. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
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
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Establece un píxel de imagen de 32 bits ARGB para la posición especificada. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Establece un valor que indica si se ajusta automáticamente la paleta. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Obtiene o establece un valor para el color de fondo. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Establece el contenedor Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Establece el cargador de datos directamente. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Establece el flujo de datos del objeto. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Establece la paleta en lugares específicos del formato. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Establece un valor que indica si [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Establece el transformador interno de datos. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Establece el monitor de interrupciones. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Obtiene o establece la asignación máxima permitida para el guardado de rotación parcial. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Establece el administrador de memoria. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Establece la paleta de colores. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Establece la paleta de la imagen. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Establece un píxel de imagen para la posición especificada. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Obtiene o establece el convertidor de color personalizado |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Obtiene o establece el convertidor de color indexado |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establece la resolución para este RasterImage. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Obtiene o establece el modo de rotación. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtiene un valor que indica si la imagen tiene color transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Obtiene el color transparente de la imagen. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Todos los productos Aspose deberían implementar este método. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este RasterImage. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtiene o establece los metadatos XMP. |
| [toBitmap()](#toBitmap--) | Convierte la imagen raster a bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
public abstract int getBitsPerPixel()
```


Obtiene el recuento de bits por píxel de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
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
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Obtiene la paleta de lugares específicos del formato.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtiene la altura de la imagen.

**Returns:**
int - La altura de la imagen.
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
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Obtiene o establece el modo de rotación.

**Returns:**
int - El modo de rotación.
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
public abstract int getWidth()
```


Obtiene el ancho de la imagen.

**Returns:**
int - El ancho de la imagen.
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

**Returns:**
boolean -  true  si esta instancia tiene alfa; de lo contrario,  false .
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
public native int hashCode()
```




**Returns:**
int
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

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente.

**Returns:**
boolean -  true  si los datos de la imagen están en caché; de lo contrario,  false .
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


Invoca cuando se estableció el contenedor de esta [Image](../../com.aspose.psd/image).

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

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo donde guardar los datos de la imagen. |
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

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Obtiene o establece el modo de rotación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El modo de rotación. |

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

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtiene o establece los metadatos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Los metadatos XMP. |

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


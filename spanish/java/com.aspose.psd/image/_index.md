---
title: "Imagen"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La imagen es la clase base para todo tipo de imágenes."
type: docs
weight: 54
url: /es/java/com.aspose.psd/image/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.psd.IObjectWithBounds](../../com.aspose.psd/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler
```

La imagen es la clase base para todo tipo de imágenes.
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
| [cacheData()](#cacheData--) | Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el subyacente DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Determina si la imagen puede cargarse desde el flujo especificado y opcionalmente usando las loadOptions especificadas. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y opcionalmente usando las opciones de apertura especificadas. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Convierte a aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crea una nueva imagen usando las opciones de creación especificadas. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crea una nueva imagen con las imágenes especificadas como páginas. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Obtiene un valor que indica si la paleta se ajusta automáticamente. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene o establece un valor para el color de fondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene el recuento de bits por píxel de la imagen. |
| [getBounds()](#getBounds--) | Obtiene los límites de la imagen. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Obtiene el  Image  contenedor. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtiene el flujo de datos del objeto. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Obtiene la paleta de ajuste profundo. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtiene las opciones predeterminadas. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Obtiene el formato de archivo. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtiene el formato de archivo. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtiene el formato de archivo. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtiene el monitor de interrupciones. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Obtiene el administrador de memoria. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones basadas en la configuración original del archivo. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Obtiene la imagen pintable. |
| [getPalette()](#getPalette--) | Obtiene la paleta de colores. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crea la caché de fuentes privada. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene la información del controlador del evento de progreso. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Obtiene la información del controlador del evento de progreso. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Obtiene una altura proporcional. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Obtiene un ancho proporcional. |
| [getSize()](#getSize--) | Obtiene el tamaño de la imagen. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtiene la ruta del archivo de la imagen fuente si existe. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtiene un valor que indica si el objeto usa la estrategia de optimización de memoria |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Obtiene la licencia de la empresa. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtiene un valor que indica si la imagen tiene color de fondo. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Obtiene o establece el valor máximo del progreso |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indica el progreso. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos. |
| [isUsePalette()](#isUsePalette--) | Obtiene un valor que indica si se usa la paleta de la imagen. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Carga una nueva imagen desde el flujo especificado. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el flujo especificado. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Carga una nueva imagen desde el flujo especificado. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el flujo especificado. |
| [load(String filePath)](#load-java.lang.String-) | Carga una nueva imagen desde el archivo especificado. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el archivo especificado. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Carga una nueva imagen desde el flujo especificado. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Carga una nueva imagen desde el flujo especificado. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoca cuando se estableció el contenedor de esta [Image](../../com.aspose.psd/image). |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Redimensiona la altura proporcionalmente. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona la altura proporcionalmente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensiona la altura proporcionalmente. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Redimensiona el ancho proporcionalmente. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensiona el ancho proporcionalmente. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensiona el ancho proporcionalmente. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rota, voltea o rota y voltea la imagen. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) |  |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Establece un valor que indica si se ajusta automáticamente la paleta. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Obtiene o establece un valor para el color de fondo. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Establece el contenedor Image. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Establece el flujo de datos del objeto. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Establece un valor que indica si [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Obtiene o establece un valor que indica si esta instancia de la imagen ha cambiado después de cargar. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Establece el monitor de interrupciones. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Establece el administrador de memoria. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Establece la paleta de colores. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Establece la paleta de la imagen. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Todos los productos Aspose deberían implementar este método. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cacheData() {#cacheData--}
```
public abstract void cacheData()
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

### convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public abstract ApsPage convertToAps_internalized(ImageOptionsBase imageOptions, int mode, Rectangle clippingRectangle)
```


Convierte a aps.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Las opciones de imagen. |
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
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtiene la altura de la imagen.

**Returns:**
int - La altura de la imagen.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Obtiene el monitor de interrupciones.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Obtiene el administrador de memoria.

Valor: El gestor de memoria.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - el gestor de memoria.
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
### getSize() {#getSize--}
```
public Size getSize()
```


Obtiene el tamaño de la imagen.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtiene la ruta del archivo de la imagen fuente si existe. Devuelve una cadena vacía si no se puede encontrar la ruta fuente.

**Returns:**
java.lang.String - La ruta del archivo de la imagen fuente.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Obtiene un valor que indica si el objeto usa la estrategia de optimización de memoria

Valor:  true  si el objeto usa la estrategia de optimización de memoria; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si el objeto usa la estrategia de optimización de memoria
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Obtiene la licencia de la empresa.

**Returns:**
java.lang.Object - La licencia Teh venture como objeto.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Obtiene el ancho de la imagen.

**Returns:**
int - El ancho de la imagen.
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
public abstract boolean isCached()
```


Obtiene un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos.

**Returns:**
boolean - un valor que indica si los datos del objeto están en caché actualmente y no se requiere lectura de datos.
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
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
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
public abstract void resize(int newWidth, int newHeight, int resizeType)
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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Rota, voltea o rota y voltea la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | Tipo de la rotación y volteo. |

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




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Establece el flujo de datos del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | El flujo de datos del objeto. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Establece el monitor de interrupciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | El monitor de interrupciones. |

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
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Establece la paleta de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en  true  los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas de paleta correspondientes. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Todos los productos Aspose deben implementar este método. Es llamado por un producto GroupDocs para indicar si GroupDocs está licenciado o no y especificar una marca de agua personalizada. Cuando GroupDocs está licenciado, esta instancia de documento debe comportarse como licenciada también aunque el producto Aspose no esté licenciado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ventureLicense | java.lang.Object |  |

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


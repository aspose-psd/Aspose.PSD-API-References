---
title: "PsdOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones de creación del formato de archivo psd."
type: docs
weight: 21
url: /es/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Las opciones de creación del formato de archivo psd.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Inicializa una nueva instancia de la clase [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Inicializa una nueva instancia de la clase [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Inicializa una nueva instancia de la clase [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Obtiene o establece el color de fondo. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Obtiene o establece el recuento de bits por canal de color. |
| [getChannelsCount()](#getChannelsCount--) | Obtiene o establece el recuento de canales de color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Obtiene o establece el modo de color PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Obtiene o establece el método de compresión PSD. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getFullFrame()](#getFullFrame--) | Obtiene un valor que indica si [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Las opciones multipágina |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene o establece el controlador del evento de progreso. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene o establece la versión del formato de archivo. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Obtiene o establece un valor que indica si [refresh image preview data] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Obtiene o establece un valor que indica si - Eliminar el recurso global del motor de texto - Utilizado para algunos archivos PSD con capas de texto, en el único caso en que no pueden abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes). |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene o establece la configuración de resolución. |
| [getResources()](#getResources--) | Obtiene o establece los recursos PSD. |
| [getSource()](#getSource--) | Obtiene o establece la fuente en la que crear la imagen. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Obtiene o establece un valor que indica si [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtiene o establece las opciones de rasterización vectorial. |
| [getVersion()](#getVersion--) | Obtiene o establece la versión del archivo PSD. |
| [getXmpData()](#getXmpData--) | Obtener o establecer el contenedor de datos XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Muestra si la propiedad ColorMode ha sido asignada. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtiene o establece el color de fondo. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Obtiene o establece el recuento de bits por canal de color. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Obtiene o establece el recuento de canales de color. |
| [setColorMode(short value)](#setColorMode-short-) | Obtiene o establece el modo de color PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Obtiene o establece el método de compresión PSD. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Establece un valor que indica si [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Las opciones multipágina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtiene o establece la paleta de colores. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtiene o establece el controlador del evento de progreso. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Obtiene o establece la versión del formato de archivo. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Obtiene o establece un valor que indica si [refresh image preview data] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Obtiene o establece un valor que indica si - Eliminar el recurso global del motor de texto - Utilizado para algunos archivos PSD con capas de texto, en el único caso en que no pueden abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtiene o establece la configuración de resolución. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Obtiene o establece los recursos PSD. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtiene o establece la fuente en la que crear la imagen. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Obtiene o establece un valor que indica si [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtiene o establece las opciones de rasterización vectorial. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece la versión del archivo PSD. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtener o establecer el contenedor de datos XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Inicializa una nueva instancia de la clase [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Inicializa una nueva instancia de la clase [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Las opciones. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Inicializa una nueva instancia de la clase [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | La imagen. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona esta instancia.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Obtiene o establece el color de fondo. Se puede ver bajo objetos transparentes.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Obtiene o establece el recuento de bits por canal de color.

Valor: El recuento de bits por canal de color.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Obtiene o establece el recuento de canales de color.

Valor: El recuento de canales de color.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Obtiene o establece el modo de color PSD.

Valor: El modo de color.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Obtiene o establece el método de compresión PSD.

Valor: El método de compresión.

**Returns:**
short
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valor: La fuente de reemplazo predeterminada.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtiene un valor que indica si [full frame].

Valor:  true  si [full frame]; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Obtiene o establece un valor que indica si se ignora después del evento de creación.

Valor:  true  si se ignora después del evento de creación; de lo contrario,  false .

**Returns:**
boolean
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Las opciones multipágina

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtiene o establece la paleta de colores.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtiene o establece el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Obtiene o establece la versión del formato de archivo. Puede ser PSD o PSB.

Valor: La versión del formato de archivo.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Obtiene o establece un valor que indica si [refresh image preview data] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. Tenga en cuenta que el dibujo de capas de texto en el diseño final no es compatible con la plataforma Compact Framework.

Valor:  true  si [refresh image preview data]; de lo contrario,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Obtiene o establece un valor que indica si - Eliminar el recurso global del motor de texto - Utilizado para algunos archivos PSD con capas de texto, en el único caso en que no pueden abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes). Después de usar esta opción, el usuario debe realizar lo siguiente en el archivo abierto en Photoshop: Menú "Text" -> "Process absent fonts". Después de esa operación, todo el texto volverá a aparecer. Tenga en cuenta que esta operación puede causar algunos cambios en el diseño final.

Valor:  true  si [remove global text engine resource]; de lo contrario,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtiene o establece la configuración de resolución.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Obtiene o establece los recursos PSD. Si el valor: NULL - entonces guarda los ImageResources originales (comportamiento predeterminado) No vacío - entonces guarda los recursos pasados a esta propiedad + [required resources] Vacío - entonces solo se guardarán [required resources]. Recursos requeridos: ResolutionInfoResource, XmpResource.

Valor: Los recursos PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtiene o establece la fuente en la que crear la imagen.

Valor: La fuente en la que crear la imagen.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Obtiene o establece un valor que indica si [update metadata]. Si el valor es true, los metadatos se actualizarán al guardar una imagen.

Valor:  true  si [update metadata]; de lo contrario,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtiene o establece las opciones de rasterización vectorial.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtiene o establece la versión del archivo PSD.

Valor: La versión del archivo PSD.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtener o establecer el contenedor de datos XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Muestra si la propiedad ColorMode ha sido asignada.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


Obtiene o establece el color de fondo. Se puede ver bajo objetos transparentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Obtiene o establece el recuento de bits por canal de color.

Valor: El recuento de bits por canal de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Obtiene o establece el recuento de canales de color.

Valor: El recuento de canales de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Obtiene o establece el modo de color PSD.

Valor: El modo de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Obtiene o establece el método de compresión PSD.

Valor: El método de compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valor: La fuente de reemplazo predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Establece un valor que indica si [full frame].

Valor:  true  si [full frame]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [full frame]. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Obtiene o establece un valor que indica si se ignora después del evento de creación.

Valor:  true  si se ignora después del evento de creación; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Las opciones multipágina

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtiene o establece la paleta de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Obtiene o establece el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Obtiene o establece la versión del formato de archivo. Puede ser PSD o PSB.

Valor: La versión del formato de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Obtiene o establece un valor que indica si [refresh image preview data] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. Tenga en cuenta que el dibujo de capas de texto en el diseño final no es compatible con la plataforma Compact Framework.

Valor:  true  si [refresh image preview data]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Obtiene o establece un valor que indica si - Eliminar el recurso global del motor de texto - Utilizado para algunos archivos PSD con capas de texto, en el único caso en que no pueden abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes). Después de usar esta opción, el usuario debe realizar lo siguiente en el archivo abierto en Photoshop: Menú "Text" -> "Process absent fonts". Después de esa operación, todo el texto volverá a aparecer. Tenga en cuenta que esta operación puede causar algunos cambios en el diseño final.

Valor:  true  si [remove global text engine resource]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtiene o establece la configuración de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Obtiene o establece los recursos PSD. Si el valor: NULL - entonces guarda los ImageResources originales (comportamiento predeterminado) No vacío - entonces guarda los recursos pasados a esta propiedad + [required resources] Vacío - entonces solo se guardarán [required resources]. Recursos requeridos: ResolutionInfoResource, XmpResource.

Valor: Los recursos PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Obtiene o establece la fuente en la que crear la imagen.

Valor: La fuente en la que crear la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Obtiene o establece un valor que indica si [update metadata]. Si el valor es true, los metadatos se actualizarán al guardar una imagen.

Valor:  true  si [update metadata]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtiene o establece las opciones de rasterización vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtiene o establece la versión del archivo PSD.

Valor: La versión del archivo PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtener o establecer el contenedor de datos XMP

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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


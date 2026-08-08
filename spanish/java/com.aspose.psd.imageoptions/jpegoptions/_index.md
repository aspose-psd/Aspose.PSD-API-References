---
title: "JpegOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones de creación del formato de archivo jpeg."
type: docs
weight: 15
url: /es/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

Las opciones de creación del formato de archivo jpeg.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Inicializa una nueva instancia de la clase  JpegOptions . |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Inicializa una nueva instancia de la clase  JpegOptions . |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Obtiene los bits por canal para una imagen jpeg sin pérdida. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | El perfil de color CMYK de destino para imágenes jpeg CMYK. |
| [getColorType()](#getColorType--) | Obtiene el tipo de color para la imagen jpeg. |
| [getComment()](#getComment--) | Obtiene el comentario del archivo jpeg. |
| [getCompressionType()](#getCompressionType--) | Obtiene el tipo de compresión. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtiene el límite de asignación de memoria predeterminado. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getExifData()](#getExifData--) | Obtener o establecer el contenedor de datos exif |
| [getFullFrame()](#getFullFrame--) | Obtiene un valor que indica si [full frame]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Obtiene los submuestreos horizontales para cada componente. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [getJfif()](#getJfif--) | Obtiene el jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Obtiene el límite de diferencia JPEG-LS para codificación casi sin pérdidas (parámetro NEAR de la especificación JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Obtiene el modo de entrelazado JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Obtiene los parámetros preestablecidos JPEG-LS. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Las opciones multipágina |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Obtiene un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si está presente el canal alfa. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene o establece el controlador del evento de progreso. |
| [getQuality()](#getQuality--) | Obtiene la calidad de la imagen. |
| [getRdOptSettings()](#getRdOptSettings--) | Obtiene la configuración del optimizador RD. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene o establece la configuración de resolución. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtiene la unidad de resolución. |
| [getRgbColorProfile()](#getRgbColorProfile--) | El perfil de color RGB de destino para imágenes jpeg CMYK. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Obtiene el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. |
| [getScaledQuality()](#getScaledQuality--) | La calidad escalada. |
| [getSource()](#getSource--) | Obtiene o establece la fuente en la que crear la imagen. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtiene o establece las opciones de rasterización vectorial. |
| [getVerticalSampling()](#getVerticalSampling--) | Obtiene los submuestreos verticales para cada componente. |
| [getXmpData()](#getXmpData--) | Obtiene el contenedor de metadatos XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Establece los bits por canal para la imagen jpeg sin pérdidas. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | El perfil de color CMYK de destino para imágenes jpeg CMYK. |
| [setColorType(int value)](#setColorType-int-) | Establece el tipo de color para la imagen jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Establece el comentario del archivo jpeg. |
| [setCompressionType(int value)](#setCompressionType-int-) | Establece el tipo de compresión. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Establece el límite de asignación de memoria predeterminado. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Obtener o establecer el contenedor de datos exif |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Establece un valor que indica si [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Establece los submuestreos horizontales para cada componente. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Establece el jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Establece el límite de diferencia JPEG-LS para codificación casi sin pérdidas (parámetro NEAR de la especificación JPEG-LS). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Establece el modo de entrelazado JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Establece los parámetros predefinidos JPEG-LS. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Las opciones multipágina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtiene o establece la paleta de colores. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Establece un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si el canal alfa está presente. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtiene o establece el controlador del evento de progreso. |
| [setQuality(int value)](#setQuality-int-) | Establece la calidad de la imagen. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Establece la configuración del optimizador RD. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtiene o establece la configuración de resolución. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Establece la unidad de resolución. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | El perfil de color RGB de destino para imágenes jpeg CMYK. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtiene o establece la fuente en la que crear la imagen. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtiene o establece las opciones de rasterización vectorial. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Establece los submuestreos verticales para cada componente. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Establece el contenedor de metadatos XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Inicializa una nueva instancia de la clase  JpegOptions .

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Inicializa una nueva instancia de la clase  JpegOptions .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | Las opciones JPEG. |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Obtiene bits por canal para imagen jpeg sin pérdidas. Ahora soportamos de 2 a 8 bits por canal.

**Returns:**
byte
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


El perfil de color CMYK de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con RGBColorProfile para una conversión de color correcta.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtiene el tipo de color para la imagen jpeg.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Obtiene el comentario del archivo jpeg.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Obtiene el tipo de compresión.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtiene el límite de asignación de memoria predeterminado.

**Returns:**
int - El límite predeterminado de asignación de memoria.
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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Obtener o establecer el contenedor de datos exif

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtiene un valor que indica si [full frame].

Valor:  true  si [full frame]; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Obtiene los submuestreos horizontales para cada componente.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Obtiene o establece un valor que indica si se ignora después del evento de creación.

Valor:  true  si se ignora después del evento de creación; de lo contrario,  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Obtiene el jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Obtiene el límite de diferencia JPEG-LS para codificación casi sin pérdidas (parámetro NEAR de la especificación JPEG-LS).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Obtiene el modo de entrelazado JPEG-LS.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Obtiene los parámetros preestablecidos JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
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
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Obtiene un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si está presente el canal alfa.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtiene o establece el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Obtiene la calidad de la imagen.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Obtiene la configuración del optimizador RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtiene o establece la configuración de resolución.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Obtiene la unidad de resolución.

**Returns:**
byte - la unidad de resolución.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


El perfil de color RGB de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con CMYKColorProfile para una conversión de color correcta.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Obtiene el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


La calidad escalada.

**Returns:**
int
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtiene o establece la fuente en la que crear la imagen.

Valor: La fuente en la que crear la imagen.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtiene o establece las opciones de rasterización vectorial.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Obtiene los submuestreos verticales para cada componente.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtiene el contenedor de metadatos XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Establece bits por canal para imagen jpeg sin pérdidas. Ahora soportamos de 2 a 8 bits por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


El perfil de color CMYK de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con RGBColorProfile para una conversión de color correcta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Establece el tipo de color para la imagen jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Establece el comentario del archivo jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Establece el tipo de compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Establece el límite de asignación de memoria predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El límite predeterminado de asignación de memoria. |

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Obtener o establecer el contenedor de datos exif

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Establece los submuestreos horizontales para cada componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Establece el jfif.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Establece el límite de diferencia JPEG-LS para codificación casi sin pérdidas (parámetro NEAR de la especificación JPEG-LS).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Establece el modo de entrelazado JPEG-LS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Establece los parámetros predefinidos JPEG-LS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

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

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Establece un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si el canal alfa está presente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Establece la calidad de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Establece la configuración del optimizador RD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | La configuración del optimizador RD. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtiene o establece la configuración de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Establece la unidad de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | la unidad de resolución. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


El perfil de color RGB de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con CMYKColorProfile para una conversión de color correcta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtiene o establece las opciones de rasterización vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Establece los submuestreos verticales para cada componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Establece el contenedor de metadatos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | El contenedor de datos XMP. |

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


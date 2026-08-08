---
title: "GifOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones de creación del formato de archivo gif."
type: docs
weight: 12
url: /es/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Las opciones de creación del formato de archivo gif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializa una nueva instancia de la clase GifOptions. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Inicializa una nueva instancia de la clase GifOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Obtiene o establece el índice de color de fondo del GIF. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Obtiene o establece la resolución de color del GIF. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [getFullFrame()](#getFullFrame--) | Obtiene un valor que indica si [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [getInterlaced()](#getInterlaced--) | True si la imagen debe estar entrelazada. |
| [getMaxDiff()](#getMaxDiff--) | Obtiene o establece la diferencia máxima de píxeles permitida. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Las opciones multipágina |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Obtiene o establece la relación de aspecto de píxeles del GIF. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene o establece el controlador del evento de progreso. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene o establece la configuración de resolución. |
| [getSource()](#getSource--) | Obtiene o establece la fuente en la que crear la imagen. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtiene o establece las opciones de rasterización vectorial. |
| [getXmpData()](#getXmpData--) | Obtiene o establece el contenedor de metadatos XMP. |
| [hasTrailer()](#hasTrailer--) | Obtiene o establece un valor que indica si el GIF tiene trailer. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Obtiene o establece el índice de color de fondo del GIF. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Obtiene o establece la resolución de color del GIF. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Establece un valor que indica si [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True si la imagen debe estar entrelazada. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Obtiene o establece la diferencia máxima de píxeles permitida. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Las opciones multipágina |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtiene o establece la paleta de colores. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Obtiene o establece la relación de aspecto de píxeles del GIF. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtiene o establece el controlador del evento de progreso. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtiene o establece la configuración de resolución. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtiene o establece la fuente en la que crear la imagen. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Obtiene o establece un valor que indica si el GIF tiene trailer. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtiene o establece las opciones de rasterización vectorial. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtiene o establece el contenedor de metadatos XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inicializa una nueva instancia de la clase GifOptions.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Inicializa una nueva instancia de la clase GifOptions.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | Las opciones del GIF. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Obtiene o establece el índice de color de fondo del GIF.

**Returns:**
byte - El índice de color de fondo del GIF.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Obtiene o establece la resolución de color del GIF.

**Returns:**
byte - La resolución de color.

Color Resolution - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente usados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina de origen.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Obtiene o establece un valor que indica si se aplica la corrección de paleta.

**Returns:**
boolean -  true  si se aplica la corrección de paleta; de lo contrario,  false .

La corrección de paleta significa que siempre que la imagen se exporta a GIF, los colores de la imagen original serán analizados para construir la paleta que mejor coincida (en caso de que la paleta de la imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen de salida tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True si la imagen debe estar entrelazada.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Obtiene o establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio. El rango de valores permitidos es [0, 1000].

**Returns:**
int - El rango de valores permitidos.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Obtiene o establece la relación de aspecto de píxeles del GIF.

Pixel Aspect Ratio - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula basándose en la fórmula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. El Pixel Aspect Ratio se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor usado en el cálculo.

**Returns:**
byte - La relación de aspecto del píxel del GIF.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtiene o establece el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtiene o establece la configuración de resolución.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
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
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtiene o establece el contenedor de metadatos XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Obtiene o establece un valor que indica si el GIF tiene trailer.

**Returns:**
boolean -  true  si el GIF tiene trailer; de lo contrario,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas.

**Returns:**
boolean -  true  si las entradas de la paleta están ordenadas; de lo contrario,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Obtiene o establece el índice de color de fondo del GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | El índice de color de fondo del GIF. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Obtiene o establece la resolución de color del GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte | La resolución de color. |

Color Resolution - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente usados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina de origen. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Obtiene o establece un valor que indica si se aplica la corrección de paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  si se aplica la corrección de paleta; de lo contrario,  false . |

La corrección de paleta significa que siempre que la imagen se exporta a GIF, los colores de la imagen original serán analizados para construir la paleta que mejor coincida (en caso de que la paleta de la imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen de salida tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True si la imagen debe estar entrelazada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Obtiene o establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio. El rango de valores permitidos es [0, 1000].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El rango de valores permitidos. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si las entradas de la paleta están ordenadas; de lo contrario,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Obtiene o establece la relación de aspecto de píxeles del GIF.

Pixel Aspect Ratio - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula basándose en la fórmula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. El Pixel Aspect Ratio se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor usado en el cálculo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | La relación de aspecto del píxel del GIF. |

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

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtiene o establece la configuración de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Obtiene o establece un valor que indica si el GIF tiene trailer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si el GIF tiene trailer; de lo contrario,  false . |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtiene o establece las opciones de rasterización vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtiene o establece el contenedor de metadatos XMP.

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


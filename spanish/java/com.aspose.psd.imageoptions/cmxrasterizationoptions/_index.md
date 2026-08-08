---
title: "CmxRasterizationOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones del exportador CMX."
type: docs
weight: 11
url: /es/java/com.aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase), [com.aspose.psd.imageoptions.VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
```
public class CmxRasterizationOptions extends VectorRasterizationOptions
```

Las opciones del exportador CMX.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions--) | Inicializa una nueva instancia de la clase [CmxRasterizationOptions](../../com.aspose.psd.imageoptions/cmxrasterizationoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Copia a. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene un color de fondo. |
| [getBorderX()](#getBorderX--) | Obtiene o establece el borde X. |
| [getBorderY()](#getBorderY--) | Obtiene o establece el borde Y. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getCenterDrawing()](#getCenterDrawing--) | Obtiene un valor que indica si el dibujo está centrado. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getDrawColor()](#getDrawColor--) | Obtiene un color de primer plano. |
| [getFullFrame()](#getFullFrame--) | Obtiene un valor que indica si [full frame]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Las opciones multipágina |
| [getPageHeight()](#getPageHeight--) | Obtiene la altura de la página. |
| [getPageSize()](#getPageSize--) | Obtiene el tamaño de la página. |
| [getPageWidth()](#getPageWidth--) | Obtiene el ancho de la página. |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores. |
| [getPositioning()](#getPositioning--) | Obtiene la posición. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene o establece el controlador del evento de progreso. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene o establece la configuración de resolución. |
| [getSmoothingMode()](#getSmoothingMode--) | Obtiene el modo de suavizado. |
| [getSource()](#getSource--) | Obtiene o establece la fuente en la que crear la imagen. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Obtiene la sugerencia de renderizado de texto. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtiene o establece las opciones de rasterización vectorial. |
| [getXmpData()](#getXmpData--) | Obtiene o establece el contenedor de metadatos XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Establece un color de fondo. |
| [setBorderX(float value)](#setBorderX-float-) | Obtiene o establece el borde X. |
| [setBorderY(float value)](#setBorderY-float-) | Obtiene o establece el borde Y. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Establece un valor que indica si el dibujo está centrado. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | Establece un color de primer plano. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Establece un valor que indica si [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Las opciones multipágina |
| [setPageHeight(float value)](#setPageHeight-float-) | Establece la altura de la página. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Establece el tamaño de la página. |
| [setPageWidth(float value)](#setPageWidth-float-) | Establece el ancho de la página. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtiene o establece la paleta de colores. |
| [setPositioning(int value)](#setPositioning-int-) | Establece la posición. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtiene o establece el controlador del evento de progreso. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtiene o establece la configuración de resolución. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Establece el modo de suavizado. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtiene o establece la fuente en la que crear la imagen. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Establece la sugerencia de renderizado de texto. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtiene o establece las opciones de rasterización vectorial. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtiene o establece el contenedor de metadatos XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmxRasterizationOptions() {#CmxRasterizationOptions--}
```
public CmxRasterizationOptions()
```


Inicializa una nueva instancia de la clase [CmxRasterizationOptions](../../com.aspose.psd.imageoptions/cmxrasterizationoptions).

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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Copia a.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | Las opciones de rasterización vectorial. |

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene un color de fondo.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Obtiene o establece el borde X.

**Returns:**
float - El borde X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Obtiene o establece el borde Y.

**Returns:**
float - El borde Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Obtiene un valor que indica si el dibujo está centrado.

**Returns:**
boolean - un valor que indica si el dibujo está centrado.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Obtiene un color de primer plano.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
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
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Obtiene la altura de la página.

**Returns:**
float - la altura de la página.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Obtiene el tamaño de la página.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Obtiene el ancho de la página.

**Returns:**
float - el ancho de la página.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtiene o establece la paleta de colores.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Obtiene la posición.

Valor: La posición.

**Returns:**
int - la posición.
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
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Obtiene el modo de suavizado.

**Returns:**
int - el modo de suavizado.
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtiene o establece la fuente en la que crear la imagen.

Valor: La fuente en la que crear la imagen.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Obtiene la sugerencia de renderizado de texto.

Valor: la sugerencia de renderizado de texto.

**Returns:**
int - la sugerencia de renderizado de texto.
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

Valor: El contenedor de datos XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Establece un color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | un color de fondo. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Obtiene o establece el borde X.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El borde X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Obtiene o establece el borde Y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El borde Y. |

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

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Establece un valor que indica si el dibujo está centrado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si el dibujo está centrado. |

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

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


Establece un color de primer plano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | un color de primer plano. |

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

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Establece la altura de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | la altura de la página. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


Establece el tamaño de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | el tamaño de la página. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Establece el ancho de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | el ancho de la página. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtiene o establece la paleta de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Establece la posición.

Valor: La posición.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la posición. |

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

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Establece el modo de suavizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el modo de suavizado. |

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

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Establece la sugerencia de renderizado de texto.

Valor: la sugerencia de renderizado de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la sugerencia de renderizado de texto. |

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

Valor: El contenedor de datos XMP.

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


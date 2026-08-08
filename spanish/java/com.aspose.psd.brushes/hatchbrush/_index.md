---
title: "HatchBrush"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Define un brush rectangular con un estilo de trama, un color de primer plano y un color de fondo."
type: docs
weight: 10
url: /es/java/com.aspose.psd.brushes/hatchbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class HatchBrush extends Brush
```

Define un brush rectangular con un estilo de trama, un color de primer plano y un color de fondo. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nueva clonación profunda del Brush actual. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de los espacios entre las líneas de trama. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getForegroundColor()](#getForegroundColor--) | Obtiene el color de las líneas de trama. |
| [getHatchStyle()](#getHatchStyle--) | Obtiene el estilo de trama de este brush. |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad del pincel. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Establece el color de los espacios entre las líneas de trama. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.psd.Color-) | Establece el color de las líneas de trama. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Establece el estilo de trama de este pincel. |
| [setOpacity(float value)](#setOpacity-float-) | Establece la opacidad del pincel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crea una nueva clonación profunda del Brush actual.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
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


Obtiene el color de los espacios entre las líneas de trama.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of spaces between the hatch lines.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Obtiene el color de las líneas de trama.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of hatch lines.
### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Obtiene el estilo de trama de este brush.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtiene la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Returns:**
float - El valor de opacidad del pincel.
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


Establece el color de los espacios entre las líneas de trama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | El color de los espacios entre las líneas de trama. |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.psd.Color-}
```
public void setForegroundColor(Color value)
```


Establece el color de las líneas de trama.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | El color de las líneas de trama. |

### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Establece el estilo de trama de este pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | El valor de opacidad del pincel. |

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


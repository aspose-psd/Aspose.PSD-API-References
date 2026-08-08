---
title: "SolidBrush"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El pincel sólido está destinado a dibujar continuamente con un color específico."
type: docs
weight: 17
url: /es/java/com.aspose.psd.brushes/solidbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class SolidBrush extends Brush
```

El pincel sólido está destinado a dibujar continuamente con un color específico. Esta clase no puede heredarse.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Inicializa una nueva instancia de la clase SolidBrush. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.psd.Color-) | Inicializa una nueva instancia de la clase SolidBrush. |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Crea una nueva clonación profunda del Brush actual. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene o establece el color del pincel. |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad del pincel. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtiene o establece el color del pincel. |
| [setOpacity(float value)](#setOpacity-float-) | Establece la opacidad del pincel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Inicializa una nueva instancia de la clase SolidBrush.

### SolidBrush(Color color) {#SolidBrush-com.aspose.psd.Color-}
```
public SolidBrush(Color color)
```


Inicializa una nueva instancia de la clase SolidBrush.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | El color del pincel sólido. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Obtiene o establece el color del pincel.

Valor: El color del pincel.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
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




### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Obtiene o establece el color del pincel.

Valor: El color del pincel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

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


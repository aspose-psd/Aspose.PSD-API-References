---
title: "BaseGradientFillSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase base de definición de degradado."
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Clase de definición de gradiente base. Contiene propiedades comunes para ambos tipos de gradiente (Sólido y Ruido).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Inicializa una nueva instancia de la clase [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings). |
## Campos

| Campo | Descripción |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtiene o establece un valor que indica si [align with layer]. |
| [getAngle()](#getAngle--) | Obtiene o establece el ángulo. |
| [getClass()](#getClass--) |  |
| [getDither()](#getDither--) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither. |
| [getFillType()](#getFillType--) | El tipo de relleno. |
| [getGradientMode()](#getGradientMode--) | Obtiene el modo de este gradiente. |
| [getGradientName()](#getGradientName--) | Obtiene o establece el nombre del gradiente. |
| [getGradientType()](#getGradientType--) | Obtiene o establece el tipo de degradado. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| [getReverse()](#getReverse--) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido. |
| [getScale()](#getScale--) | Obtiene o establece la escala. |
| [getVerticalOffset()](#getVerticalOffset--) | Obtiene o establece el desplazamiento vertical en porcentaje. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera el cambio de valor. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtiene o establece un valor que indica si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtiene o establece el ángulo. |
| [setDither(boolean value)](#setDither-boolean-) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Obtiene el modo de este gradiente. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Obtiene o establece el nombre del gradiente. |
| [setGradientType(int value)](#setGradientType-int-) | Obtiene o establece el tipo de degradado. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido. |
| [setScale(int value)](#setScale-int-) | Obtiene o establece la escala. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtiene o establece el desplazamiento vertical en porcentaje. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Inicializa una nueva instancia de la clase [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Obtiene o establece un valor que indica si [align with layer].

Valor:  true  si [align with layer]; de lo contrario,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Obtiene o establece el ángulo.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither.

Valor:  true  si dithering; de lo contrario,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


El tipo de relleno.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Obtiene el modo de este gradiente. Determina 'Tipo de gradiente' = 'Sólido/Ruido' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Obtiene o establece el nombre del gradiente.

Valor: El nombre del gradiente.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Obtiene o establece el tipo de degradado.

Valor: El tipo de degradado.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Obtiene o establece el desplazamiento horizontal en porcentaje.

Valor: El desplazamiento horizontal.

**Returns:**
double
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Obtiene o establece la escala.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Obtiene o establece el desplazamiento vertical en porcentaje.

Valor: El desplazamiento vertical.

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Genera el cambio de valor.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Obtiene o establece un valor que indica si [align with layer].

Valor:  true  si [align with layer]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Obtiene o establece el ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está con dither.

Valor:  true  si dithering; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Obtiene el modo de este gradiente. Determina 'Tipo de gradiente' = 'Sólido/Ruido' (0/1).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Obtiene o establece el nombre del gradiente.

Valor: El nombre del gradiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Obtiene o establece el tipo de degradado.

Valor: El tipo de degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Obtiene o establece el desplazamiento horizontal en porcentaje.

Valor: El desplazamiento horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Obtiene o establece un valor que indica si este [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Obtiene o establece la escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Obtiene o establece el desplazamiento vertical en porcentaje.

Valor: El desplazamiento vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

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


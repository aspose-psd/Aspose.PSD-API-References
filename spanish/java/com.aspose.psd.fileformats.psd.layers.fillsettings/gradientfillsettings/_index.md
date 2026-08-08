---
title: "GradientFillSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Configuración del efecto de relleno de degradado."
type: docs
weight: 14
url: /es/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Configuración del efecto de relleno de degradado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Inicializa una nueva instancia de la clase [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Obtiene o establece los límites del contenedor de capas para calcular correctamente la posición del degradado. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Calcula y devuelve la escala de degradado **denormalized** (Escala UI) correspondiente al valor actual de Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) tiene dithering. |
| [getFillType()](#getFillType--) | El tipo de relleno. |
| [getGradient()](#getGradient--) | Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido). |
| [getGradientType()](#getGradientType--) | Obtiene o establece el tipo de degradado. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Obtiene o establece el método de interpolación para el degradado. |
| [getReverse()](#getReverse--) | Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) está invertido. |
| [getScale()](#getScale--) | Obtiene o establece la escala de degradado **normalized** (en porcentaje) |
| [getVerticalOffset()](#getVerticalOffset--) | Obtiene o establece el desplazamiento vertical en porcentaje. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera el cambio de valor. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtiene o establece un valor que indica si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtiene o establece el ángulo. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Obtiene o establece los límites del contenedor de capas para calcular correctamente la posición del degradado. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Convierte el valor de escala desnormalizada (UI) especificado a su equivalente **normalized** y lo asigna a Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) tiene dithering. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido). |
| [setGradientType(int value)](#setGradientType-int-) | Obtiene o establece el tipo de degradado. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Obtiene o establece el método de interpolación para el degradado. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) está invertido. |
| [setScale(int value)](#setScale-int-) | Obtiene o establece la escala de degradado **normalized** (en porcentaje) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtiene o establece el desplazamiento vertical en porcentaje. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Inicializa una nueva instancia de la clase [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Obtiene o establece los límites del contenedor de capas para calcular correctamente la posición del degradado.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Calcula y devuelve la escala de degradado **denormalized** (Escala UI) correspondiente al valor actual de Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Los límites del degradado. |

**Returns:**
int - La escala desnormalizada (UI) en porcentaje tal como se muestra en Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) tiene dithering.

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
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Obtiene o establece el método de interpolación para el degradado.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Obtiene o establece la escala de degradado **normalized** (en porcentaje)

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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Obtiene o establece los límites del contenedor de capas para calcular correctamente la posición del degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Convierte el valor de escala desnormalizada (UI) especificado a su equivalente **normalized** y lo asigna a Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). La conversión aplica el ángulo actual del degradado\\\\u2019s Angle ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) y el fillArea proporcionado para calcular el factor de normalización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La escala desnormalizada, Escala UI en porcentaje tal como se muestra en Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | Los límites del degradado. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) tiene dithering.

Valor:  true  si dithering; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Obtiene o establece el método de interpolación para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Obtiene o establece un valor que indica si este [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Obtiene o establece la escala de degradado **normalized** (en porcentaje)

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


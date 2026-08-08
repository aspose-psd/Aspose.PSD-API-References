---
title: "IGradientFillSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Interfaz base para la configuración de relleno de degradado."
type: docs
weight: 23
url: /es/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Interfaz base para la configuración de relleno de degradado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Obtiene o establece un valor que indica si [align with layer]. |
| [getAngle()](#getAngle--) | Obtiene o establece el ángulo. |
| [getDither()](#getDither--) | Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está dithereado. |
| [getGradient()](#getGradient--) | Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido). |
| [getGradientType()](#getGradientType--) | Obtiene o establece el tipo de degradado. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Obtiene o establece el desplazamiento horizontal. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Obtiene o establece el método de interpolación para el degradado. |
| [getReverse()](#getReverse--) | Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está invertido. |
| [getScale()](#getScale--) | Obtiene o establece la escala de degradado **normalized** (en porcentaje). |
| [getVerticalOffset()](#getVerticalOffset--) | Obtiene o establece el desplazamiento vertical. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Obtiene o establece un valor que indica si [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Obtiene o establece el ángulo. |
| [setDither(boolean value)](#setDither-boolean-) | Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está dithereado. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido). |
| [setGradientType(int value)](#setGradientType-int-) | Obtiene o establece el tipo de degradado. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Obtiene o establece el desplazamiento horizontal. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Obtiene o establece el método de interpolación para el degradado. |
| [setReverse(boolean value)](#setReverse-boolean-) | Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está invertido. |
| [setScale(int value)](#setScale-int-) | Obtiene o establece la escala de degradado **normalized** (en porcentaje). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Obtiene o establece el desplazamiento vertical. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Obtiene o establece un valor que indica si [align with layer].

Valor:  true  si [align with layer]; de lo contrario,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Obtiene o establece el ángulo.

Valor: El ángulo.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está dithereado.

Valor:  true  si dithering; de lo contrario,  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Obtiene o establece el tipo de degradado.

Valor: El tipo de degradado.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Obtiene o establece el desplazamiento horizontal.

Valor: El desplazamiento horizontal.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Obtiene o establece el método de interpolación para el degradado.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Obtiene o establece la escala de degradado **normalized** (en porcentaje).

Valor: La escala.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Obtiene o establece el desplazamiento vertical.

Valor: El desplazamiento vertical.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Obtiene o establece un valor que indica si [align with layer].

Valor:  true  si [align with layer]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Obtiene o establece el ángulo.

Valor: El ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está dithereado.

Valor:  true  si dithering; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Obtiene o establece una instancia de definición de degradado específica (Sólido/Ruido).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Obtiene o establece el tipo de degradado.

Valor: El tipo de degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Obtiene o establece el desplazamiento horizontal.

Valor: El desplazamiento horizontal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Obtiene o establece el método de interpolación para el degradado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Obtiene o establece un valor que indica si este [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) está invertido.

Valor:  true  si invertido; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Obtiene o establece la escala de degradado **normalized** (en porcentaje).

Valor: La escala.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Obtiene o establece el desplazamiento vertical.

Valor: El desplazamiento vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |


---
title: "IGradientFillSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Interfaccia di base per le impostazioni di riempimento gradiente."
type: docs
weight: 23
url: /it/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Interfaccia di base per le impostazioni di riempimento gradiente.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Ottiene o imposta un valore che indica se [align with layer]. |
| [getAngle()](#getAngle--) | Ottiene o imposta l'angolo. |
| [getDither()](#getDither--) | Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è dither. |
| [getGradient()](#getGradient--) | Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Ottiene o imposta il tipo di gradiente. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Ottiene o imposta lo spostamento orizzontale. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [getReverse()](#getReverse--) | Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è reverse. |
| [getScale()](#getScale--) | Ottiene o imposta la scala del gradiente **normalized** (in percentuale). |
| [getVerticalOffset()](#getVerticalOffset--) | Ottiene o imposta lo spostamento verticale. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Ottiene o imposta un valore che indica se [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Ottiene o imposta l'angolo. |
| [setDither(boolean value)](#setDither-boolean-) | Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Ottiene o imposta il tipo di gradiente. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Ottiene o imposta lo spostamento orizzontale. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [setReverse(boolean value)](#setReverse-boolean-) | Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è reverse. |
| [setScale(int value)](#setScale-int-) | Ottiene o imposta la scala del gradiente **normalized** (in percentuale). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Ottiene o imposta lo spostamento verticale. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Ottiene o imposta un valore che indica se [align with layer].

Valore:  true  se [align with layer]; altrimenti,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Ottiene o imposta l'angolo.

Valore: L'angolo.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è dither.

Valore:  true  se dither; altrimenti,  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Ottiene o imposta il tipo di gradiente.

Valore: Il tipo di gradiente.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Ottiene o imposta lo spostamento orizzontale.

Valore: Lo spostamento orizzontale.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Ottiene o imposta il metodo di interpolazione per il gradiente.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è reverse.

Valore:  true  se invertito; altrimenti,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Ottiene o imposta la scala del gradiente **normalized** (in percentuale).

Valore: La scala.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Ottiene o imposta lo spostamento verticale.

Valore: Lo spostamento verticale.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Ottiene o imposta un valore che indica se [align with layer].

Valore:  true  se [align with layer]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Ottiene o imposta l'angolo.

Valore: L'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è dither.

Valore:  true  se dither; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Ottiene o imposta il tipo di gradiente.

Valore: Il tipo di gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Ottiene o imposta lo spostamento orizzontale.

Valore: Lo spostamento orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Ottiene o imposta il metodo di interpolazione per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Ottiene o imposta un valore che indica se questo [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) è reverse.

Valore:  true  se invertito; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Ottiene o imposta la scala del gradiente **normalized** (in percentuale).

Valore: La scala.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Ottiene o imposta lo spostamento verticale.

Valore: Lo spostamento verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |


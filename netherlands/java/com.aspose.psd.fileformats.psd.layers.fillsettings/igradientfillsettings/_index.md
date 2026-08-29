---
title: "IGradientFillSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Basisinterface voor gradientvul-instellingen."
type: docs
weight: 23
url: /nl/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Basisinterface voor gradientvul-instellingen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| [getAngle()](#getAngle--) | Haalt de hoek op of stelt deze in. |
| [getDither()](#getDither--) | Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) geditherd is. |
| [getGradient()](#getGradient--) | Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Haalt het type van de gradient op of stelt het in. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Haalt de horizontale offset op of stelt deze in. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Haalt de interpolatiemethode voor de gradient op of stelt deze in. |
| [getReverse()](#getReverse--) | Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) omgekeerd is. |
| [getScale()](#getScale--) | Haalt op of stelt de **normalized** gradiëntschaal in (in procent). |
| [getVerticalOffset()](#getVerticalOffset--) | Haalt de verticale offset op of stelt deze in. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Haalt de hoek op of stelt deze in. |
| [setDither(boolean value)](#setDither-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) geditherd is. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Haalt het type van de gradient op of stelt het in. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Haalt de horizontale offset op of stelt deze in. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Haalt de interpolatiemethode voor de gradient op of stelt deze in. |
| [setReverse(boolean value)](#setReverse-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) omgekeerd is. |
| [setScale(int value)](#setScale-int-) | Haalt op of stelt de **normalized** gradiëntschaal in (in procent). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Haalt de verticale offset op of stelt deze in. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer].

Waarde:  true  als [align with layer]; anders,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Haalt de hoek op of stelt deze in.

Waarde: De hoek.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) geditherd is.

Waarde:  true  als dither; anders,  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Haalt het type van de gradient op of stelt het in.

Waarde: Het type van de gradient.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Haalt de horizontale offset op of stelt deze in.

Waarde: De horizontale offset.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Haalt de interpolatiemethode voor de gradient op of stelt deze in.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Haalt op of stelt de **normalized** gradiëntschaal in (in procent).

Waarde: De schaal.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Haalt de verticale offset op of stelt deze in.

Waarde: De verticale offset.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer].

Waarde:  true  als [align with layer]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Haalt de hoek op of stelt deze in.

Waarde: De hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) geditherd is.

Waarde:  true  als dither; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Haalt het type van de gradient op of stelt het in.

Waarde: Het type van de gradient.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Haalt de horizontale offset op of stelt deze in.

Waarde: De horizontale offset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Haalt de interpolatiemethode voor de gradient op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Haalt op of stelt de **normalized** gradiëntschaal in (in procent).

Waarde: De schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Haalt de verticale offset op of stelt deze in.

Waarde: De verticale offset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |


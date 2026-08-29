---
title: "IGradientFillSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Basgränssnitt för gradientfyllningsinställningar."
type: docs
weight: 23
url: /sv/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Basgränssnitt för gradientfyllningsinställningar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Hämtar eller anger ett värde som visar om [justera med lager]. |
| [getAngle()](#getAngle--) | Hämtar eller anger vinkeln. |
| [getDither()](#getDither--) | Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är dither. |
| [getGradient()](#getGradient--) | Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Hämtar eller anger typen av gradienten. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Hämtar eller anger den horisontella förskjutningen. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Hämtar eller anger interpolationsmetoden för gradienten. |
| [getReverse()](#getReverse--) | Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är omvänd. |
| [getScale()](#getScale--) | Hämtar eller anger den  **normaliserade**  gradientskalan (i procent). |
| [getVerticalOffset()](#getVerticalOffset--) | Hämtar eller anger den vertikala förskjutningen. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Hämtar eller anger ett värde som visar om [justera med lager]. |
| [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln. |
| [setDither(boolean value)](#setDither-boolean-) | Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Hämtar eller anger typen av gradienten. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Hämtar eller anger den horisontella förskjutningen. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Hämtar eller anger interpolationsmetoden för gradienten. |
| [setReverse(boolean value)](#setReverse-boolean-) | Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är omvänd. |
| [setScale(int value)](#setScale-int-) | Hämtar eller anger den  **normaliserade**  gradientskalan (i procent). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Hämtar eller anger den vertikala förskjutningen. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Hämtar eller anger ett värde som visar om [justera med lager].

Värde:  true  om [align with layer]; annars,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Hämtar eller anger vinkeln.

Värde: Vinkeln.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är dither.

Värde:  true  om dither; annars,  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Hämtar eller anger typen av gradienten.

Värde: Typen av gradienten.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Hämtar eller anger den horisontella förskjutningen.

Värde: Den horisontella förskjutningen.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Hämtar eller anger interpolationsmetoden för gradienten.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Hämtar eller anger den  **normaliserade**  gradientskalan (i procent).

Värde: Skalan.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Hämtar eller anger den vertikala förskjutningen.

Värde: Den vertikala förskjutningen.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Hämtar eller anger ett värde som visar om [justera med lager].

Värde:  true  om [align with layer]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Hämtar eller anger vinkeln.

Värde: Vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är dither.

Värde:  true  om dither; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Hämtar eller anger typen av gradienten.

Värde: Typen av gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Hämtar eller anger den horisontella förskjutningen.

Värde: Den horisontella förskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Hämtar eller anger interpolationsmetoden för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Hämtar eller anger den  **normaliserade**  gradientskalan (i procent).

Värde: Skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Hämtar eller anger den vertikala förskjutningen.

Värde: Den vertikala förskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |


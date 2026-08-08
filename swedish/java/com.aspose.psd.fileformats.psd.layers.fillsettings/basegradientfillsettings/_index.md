---
title: "BaseGradientFillSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Basgradientdefinitionsklass."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Basisklass för gradientdefinition. Den innehåller gemensamma egenskaper för båda typerna av gradient (Solid och Brus).
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Initierar en ny instans av klassen [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Hämtar eller anger ett värde som visar om [justera med lager]. |
| [getAngle()](#getAngle--) | Hämtar eller anger vinkeln. |
| [getClass()](#getClass--) |  |
| [getDither()](#getDither--) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither. |
| [getFillType()](#getFillType--) | Fyllningstypen. |
| [getGradientMode()](#getGradientMode--) | Hämtar läget för denna gradient. |
| [getGradientName()](#getGradientName--) | Hämtar eller anger namnet på gradienten. |
| [getGradientType()](#getGradientType--) | Hämtar eller anger typen av gradienten. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Hämtar eller anger den horisontella förskjutningen i procent. |
| [getReverse()](#getReverse--) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd. |
| [getScale()](#getScale--) | Hämtar eller anger skalan. |
| [getVerticalOffset()](#getVerticalOffset--) | Hämtar eller anger den vertikala förskjutningen i procent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Utlöser värdeändring. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Hämtar eller anger ett värde som visar om [justera med lager]. |
| [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln. |
| [setDither(boolean value)](#setDither-boolean-) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Hämtar läget för denna gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Hämtar eller anger namnet på gradienten. |
| [setGradientType(int value)](#setGradientType-int-) | Hämtar eller anger typen av gradienten. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Hämtar eller anger den horisontella förskjutningen i procent. |
| [setReverse(boolean value)](#setReverse-boolean-) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd. |
| [setScale(int value)](#setScale-int-) | Hämtar eller anger skalan. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Hämtar eller anger den vertikala förskjutningen i procent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Initierar en ny instans av klassen [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Hämtar eller anger ett värde som visar om [justera med lager].

Värde:  true  om [align with layer]; annars,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Hämtar eller anger vinkeln.

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


Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither.

Värde:  true  om dither; annars,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Fyllningstypen.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Hämtar läget för denna gradient. Bestämmer 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Hämtar eller anger namnet på gradienten.

Värde: Gradientens namn.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Hämtar eller anger typen av gradienten.

Värde: Typen av gradienten.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Hämtar eller anger den horisontella förskjutningen i procent.

Värde: Den horisontella förskjutningen.

**Returns:**
double
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Hämtar eller anger skalan.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Hämtar eller anger den vertikala förskjutningen i procent.

Värde: Den vertikala förskjutningen.

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


Utlöser värdeändring.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Hämtar eller anger ett värde som visar om [justera med lager].

Värde:  true  om [align with layer]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Hämtar eller anger vinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither.

Värde:  true  om dither; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Hämtar läget för denna gradient. Bestämmer 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Hämtar eller anger namnet på gradienten.

Värde: Gradientens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Hämtar eller anger typen av gradienten.

Värde: Typen av gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Hämtar eller anger den horisontella förskjutningen i procent.

Värde: Den horisontella förskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Hämtar eller anger skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Hämtar eller anger den vertikala förskjutningen i procent.

Värde: Den vertikala förskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


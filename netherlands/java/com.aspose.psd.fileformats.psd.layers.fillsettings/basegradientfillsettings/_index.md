---
title: "BaseGradientFillSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Basisgradientdefinitieklasse."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Base gradient definitieklasse. Het bevat gemeenschappelijke eigenschappen voor beide gradienttypen (Solid en Noise).
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Initialiseert een nieuw exemplaar van de [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| [getAngle()](#getAngle--) | Haalt de hoek op of stelt deze in. |
| [getClass()](#getClass--) |  |
| [getDither()](#getDither--) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is. |
| [getFillType()](#getFillType--) | Het vultype. |
| [getGradientMode()](#getGradientMode--) | Haalt de modus op voor deze gradient. |
| [getGradientName()](#getGradientName--) | Haalt de naam van de gradient op of stelt deze in. |
| [getGradientType()](#getGradientType--) | Haalt het type van de gradient op of stelt het in. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Haalt de horizontale offset in percentage op of stelt deze in. |
| [getReverse()](#getReverse--) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is. |
| [getScale()](#getScale--) | Geeft of stelt de schaal in. |
| [getVerticalOffset()](#getVerticalOffset--) | Haalt de verticale offset in percentage op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Activeert de waarde gewijzigd. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Haalt de hoek op of stelt deze in. |
| [setDither(boolean value)](#setDither-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Haalt de modus op voor deze gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Haalt de naam van de gradient op of stelt deze in. |
| [setGradientType(int value)](#setGradientType-int-) | Haalt het type van de gradient op of stelt het in. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Haalt de horizontale offset in percentage op of stelt deze in. |
| [setReverse(boolean value)](#setReverse-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is. |
| [setScale(int value)](#setScale-int-) | Geeft of stelt de schaal in. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Haalt de verticale offset in percentage op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Initialiseert een nieuw exemplaar van de [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) klasse.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer].

Waarde:  true  als [align with layer]; anders,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Haalt de hoek op of stelt deze in.

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


Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is.

Waarde:  true  als dither; anders,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Het vultype.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Haalt de modus op voor deze gradient. Bepaalt 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Haalt de naam van de gradient op of stelt deze in.

Waarde: De naam van de gradient.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Haalt het type van de gradient op of stelt het in.

Waarde: Het type van de gradient.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Haalt de horizontale offset in percentage op of stelt deze in.

Waarde: De horizontale offset.

**Returns:**
double
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Geeft of stelt de schaal in.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Haalt de verticale offset in percentage op of stelt deze in.

Waarde: De verticale offset.

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


Activeert de waarde gewijzigd.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer].

Waarde:  true  als [align with layer]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Haalt de hoek op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is.

Waarde:  true  als dither; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Haalt de modus op voor deze gradient. Bepaalt 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Haalt de naam van de gradient op of stelt deze in.

Waarde: De naam van de gradient.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Haalt het type van de gradient op of stelt het in.

Waarde: Het type van de gradient.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Haalt de horizontale offset in percentage op of stelt deze in.

Waarde: De horizontale offset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Geeft of stelt de schaal in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Haalt de verticale offset in percentage op of stelt deze in.

Waarde: De verticale offset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


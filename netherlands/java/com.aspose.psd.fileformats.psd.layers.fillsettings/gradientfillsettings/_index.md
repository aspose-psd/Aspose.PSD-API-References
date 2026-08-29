---
title: "GradientFillSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Instellingen voor gradientvullingseffect."
type: docs
weight: 14
url: /nl/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Instellingen voor gradientvullingseffect.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Initialiseert een nieuw exemplaar van de [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) klasse. |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Haalt de grenzen van de laagcontainer op of stelt deze in om de positie van de gradient correct te berekenen. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Berekent en retourneert de **denormalized** gradiëntschaal (UI-schaal) die overeenkomt met de huidige Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) waarde. |
| [getDither()](#getDither--) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither is. |
| [getFillType()](#getFillType--) | Het vultype. |
| [getGradient()](#getGradient--) | Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Haalt het type van de gradient op of stelt het in. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Haalt de horizontale offset in percentage op of stelt deze in. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Haalt de interpolatiemethode voor de gradient op of stelt deze in. |
| [getReverse()](#getReverse--) | Haalt een waarde op of stelt deze in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) omgekeerd is. |
| [getScale()](#getScale--) | Haalt op of stelt de **normalized** gradiëntschaal in (in procent). |
| [getVerticalOffset()](#getVerticalOffset--) | Haalt de verticale offset in percentage op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Activeert de waarde gewijzigd. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Haalt de hoek op of stelt deze in. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Haalt de grenzen van de laagcontainer op of stelt deze in om de positie van de gradient correct te berekenen. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Converteert de opgegeven gedenormaliseerde schaal (UI) schaalwaarde naar het **normalized** equivalent en wijst deze toe aan Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither is. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Haalt het type van de gradient op of stelt het in. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Haalt de horizontale offset in percentage op of stelt deze in. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Haalt de interpolatiemethode voor de gradient op of stelt deze in. |
| [setReverse(boolean value)](#setReverse-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) omgekeerd is. |
| [setScale(int value)](#setScale-int-) | Haalt op of stelt de **normalized** gradiëntschaal in (in procent). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Haalt de verticale offset in percentage op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Initialiseert een nieuw exemplaar van de [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) klasse.

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Haalt de grenzen van de laagcontainer op of stelt deze in om de positie van de gradient correct te berekenen.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Berekent en retourneert de **denormalized** gradiëntschaal (UI-schaal) die overeenkomt met de huidige Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | De grenzen van de gradiënt. |

**Returns:**
int - De gedenormaliseerde (UI) schaal in procent zoals weergegeven in Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither is.

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
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Haalt de interpolatiemethode voor de gradient op of stelt deze in.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Haalt een waarde op of stelt deze in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Haalt op of stelt de **normalized** gradiëntschaal in (in procent).

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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Haalt de grenzen van de laagcontainer op of stelt deze in om de positie van de gradient correct te berekenen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Converteert de opgegeven gedenormaliseerde schaal (UI) schaalwaarde naar het **normalized** equivalent en wijst deze toe aan Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). De conversie past de huidige hoek van de gradient\\u2019s ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) en het opgegeven fillArea toe om de normalisatiefactor te berekenen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De gedenormaliseerde schaal, UI-schaal in procent zoals weergegeven door Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | De grenzen van de gradiënt. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) dither is.

Waarde:  true  als dither; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Haalt een specifieke gradientdefinitie‑instantie op of stelt deze in (Solid/Noise).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Haalt de interpolatiemethode voor de gradient op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of deze [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Haalt op of stelt de **normalized** gradiëntschaal in (in procent).

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


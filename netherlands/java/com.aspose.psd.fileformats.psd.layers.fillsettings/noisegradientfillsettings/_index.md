---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Ruisgradientdefinitieklasse."
type: docs
weight: 18
url: /nl/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Ruisgradientdefinitieklasse.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Initialiseert een nieuw exemplaar van de [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) klasse. |
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
| [getColorModel()](#getColorModel--) | Haalt op of stelt het kleurmodel in - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is. |
| [getExpansionCount()](#getExpansionCount--) | Haalt op of stelt het uitbreidingsaantal in ( = 2 voor Photoshop 6.0). |
| [getFillType()](#getFillType--) | Het vultype. |
| [getGradientMode()](#getGradientMode--) | Haalt de modus op voor deze gradient. |
| [getGradientName()](#getGradientName--) | Haalt de naam van de gradient op of stelt deze in. |
| [getGradientType()](#getGradientType--) | Haalt het type van de gradient op of stelt het in. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Haalt de horizontale offset in percentage op of stelt deze in. |
| [getMaximumColor()](#getMaximumColor--) | Haalt op of stelt de maximale kleur van PixelDataFormat in. |
| [getMinimumColor()](#getMinimumColor--) | Haalt op of stelt de minimale kleur van PixelDataFormat in. |
| [getReverse()](#getReverse--) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Haalt op of stelt de willekeurige getalzaad in die wordt gebruikt om kleuren voor Noise gradient te genereren |
| [getRoughness()](#getRoughness--) | Haalt op of stelt de ruwheidsfactor in. |
| [getScale()](#getScale--) | Geeft of stelt de schaal in. |
| [getShowTransparency()](#getShowTransparency--) | Haalt op of stelt de vlag in voor het weergeven van transparantie. |
| [getUseVectorColor()](#getUseVectorColor--) | Haalt op of stelt de vlag in voor het gebruiken van vectorkleur. |
| [getVerticalOffset()](#getVerticalOffset--) | Haalt de verticale offset in percentage op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Activeert de waarde gewijzigd. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Haalt de hoek op of stelt deze in. |
| [setColorModel(short value)](#setColorModel-short-) | Haalt op of stelt het kleurmodel in - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Haalt op of stelt het uitbreidingsaantal in ( = 2 voor Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Haalt de modus op voor deze gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Haalt de naam van de gradient op of stelt deze in. |
| [setGradientType(int value)](#setGradientType-int-) | Haalt het type van de gradient op of stelt het in. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Haalt de horizontale offset in percentage op of stelt deze in. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Haalt op of stelt de maximale kleur van PixelDataFormat in. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Haalt op of stelt de minimale kleur van PixelDataFormat in. |
| [setReverse(boolean value)](#setReverse-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Haalt op of stelt de willekeurige getalzaad in die wordt gebruikt om kleuren voor Noise gradient te genereren |
| [setRoughness(int value)](#setRoughness-int-) | Haalt op of stelt de ruwheidsfactor in. |
| [setScale(int value)](#setScale-int-) | Geeft of stelt de schaal in. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Haalt op of stelt de vlag in voor het weergeven van transparantie. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Haalt op of stelt de vlag in voor het gebruiken van vectorkleur. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Haalt de verticale offset in percentage op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Initialiseert een nieuw exemplaar van de [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) klasse.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Haalt op of stelt het kleurmodel in - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) dither is.

Waarde:  true  als dither; anders,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Haalt op of stelt het uitbreidingsaantal in ( = 2 voor Photoshop 6.0).

**Returns:**
short
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Haalt op of stelt de maximale kleur van PixelDataFormat in.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Haalt op of stelt de minimale kleur van PixelDataFormat in.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) omgekeerd is.

Waarde:  true  als omgekeerd; anders,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Haalt op of stelt de willekeurige getalzaad in die wordt gebruikt om kleuren voor Noise gradient te genereren

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Haalt op of stelt de ruwheidsfactor in.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Geeft of stelt de schaal in.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Haalt op of stelt de vlag in voor het weergeven van transparantie.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Haalt op of stelt de vlag in voor het gebruiken van vectorkleur.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Haalt op of stelt het kleurmodel in - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Haalt op of stelt het uitbreidingsaantal in ( = 2 voor Photoshop 6.0).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Haalt op of stelt de maximale kleur van PixelDataFormat in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Haalt op of stelt de minimale kleur van PixelDataFormat in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Haalt op of stelt de willekeurige getalzaad in die wordt gebruikt om kleuren voor Noise gradient te genereren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Haalt op of stelt de ruwheidsfactor in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Geeft of stelt de schaal in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Haalt op of stelt de vlag in voor het weergeven van transparantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Haalt op of stelt de vlag in voor het gebruiken van vectorkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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


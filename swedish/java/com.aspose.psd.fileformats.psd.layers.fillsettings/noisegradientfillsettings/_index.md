---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Brusgradientdefinitionsklass."
type: docs
weight: 18
url: /sv/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Brusgradientdefinitionsklass.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Initierar en ny instans av klassen [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings). |
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
| [getColorModel()](#getColorModel--) | Hämtar eller anger färgmodellen - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither. |
| [getExpansionCount()](#getExpansionCount--) | Hämtar eller anger expansionsantalet ( = 2 för Photoshop 6.0). |
| [getFillType()](#getFillType--) | Fyllningstypen. |
| [getGradientMode()](#getGradientMode--) | Hämtar läget för denna gradient. |
| [getGradientName()](#getGradientName--) | Hämtar eller anger namnet på gradienten. |
| [getGradientType()](#getGradientType--) | Hämtar eller anger typen av gradienten. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Hämtar eller anger den horisontella förskjutningen i procent. |
| [getMaximumColor()](#getMaximumColor--) | Hämtar eller anger den maximala färgen för PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Hämtar eller anger den minsta färgen för PixelDataFormat. |
| [getReverse()](#getReverse--) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Hämtar eller anger fröet för slumptal som används för att generera färger för brusgradient |
| [getRoughness()](#getRoughness--) | Hämtar eller anger råhetsfaktorn. |
| [getScale()](#getScale--) | Hämtar eller anger skalan. |
| [getShowTransparency()](#getShowTransparency--) | Hämtar eller anger flaggan för att visa transparens. |
| [getUseVectorColor()](#getUseVectorColor--) | Hämtar eller anger flaggan för att använda vektorfärg. |
| [getVerticalOffset()](#getVerticalOffset--) | Hämtar eller anger den vertikala förskjutningen i procent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Utlöser värdeändring. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Hämtar eller anger ett värde som visar om [justera med lager]. |
| [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln. |
| [setColorModel(short value)](#setColorModel-short-) | Hämtar eller anger färgmodellen - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Hämtar eller anger expansionsantalet ( = 2 för Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Hämtar läget för denna gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Hämtar eller anger namnet på gradienten. |
| [setGradientType(int value)](#setGradientType-int-) | Hämtar eller anger typen av gradienten. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Hämtar eller anger den horisontella förskjutningen i procent. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Hämtar eller anger den maximala färgen för PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Hämtar eller anger den minsta färgen för PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Hämtar eller anger fröet för slumptal som används för att generera färger för brusgradient |
| [setRoughness(int value)](#setRoughness-int-) | Hämtar eller anger råhetsfaktorn. |
| [setScale(int value)](#setScale-int-) | Hämtar eller anger skalan. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Hämtar eller anger flaggan för att visa transparens. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Hämtar eller anger flaggan för att använda vektorfärg. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Hämtar eller anger den vertikala förskjutningen i procent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Initierar en ny instans av klassen [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings).

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Hämtar eller anger färgmodellen - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är dither.

Värde:  true  om dither; annars,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Hämtar eller anger expansionsantalet ( = 2 för Photoshop 6.0).

**Returns:**
short
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Hämtar eller anger den maximala färgen för PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Hämtar eller anger den minsta färgen för PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Hämtar eller anger fröet för slumptal som används för att generera färger för brusgradient

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Hämtar eller anger råhetsfaktorn.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Hämtar eller anger skalan.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Hämtar eller anger flaggan för att visa transparens.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Hämtar eller anger flaggan för att använda vektorfärg.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Hämtar eller anger färgmodellen - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Hämtar eller anger expansionsantalet ( = 2 för Photoshop 6.0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Hämtar eller anger den maximala färgen för PixelDataFormat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Hämtar eller anger den minsta färgen för PixelDataFormat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Hämtar eller anger fröet för slumptal som används för att generera färger för brusgradient

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Hämtar eller anger råhetsfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Hämtar eller anger skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Hämtar eller anger flaggan för att visa transparens.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Hämtar eller anger flaggan för att använda vektorfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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


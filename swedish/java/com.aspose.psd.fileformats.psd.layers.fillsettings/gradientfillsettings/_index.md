---
title: "GradientFillSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Inställningar för gradientfyllningseffekt."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Inställningar för gradientfyllningseffekt.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Initierar en ny instans av klassen [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Hämtar eller anger gränserna för lagerbehållaren för att korrekt beräkna gradientens position. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Beräknar och returnerar den  **denormalized**  gradientskalan (UI Scale) som motsvarar det aktuella  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) värdet. |
| [getDither()](#getDither--) | Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är dither. |
| [getFillType()](#getFillType--) | Fyllningstypen. |
| [getGradient()](#getGradient--) | Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Hämtar eller anger typen av gradienten. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Hämtar eller anger den horisontella förskjutningen i procent. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Hämtar eller anger interpolationsmetoden för gradienten. |
| [getReverse()](#getReverse--) | Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är omvänd. |
| [getScale()](#getScale--) | Hämtar eller anger den  **normalized**  gradientskalan (i procent) |
| [getVerticalOffset()](#getVerticalOffset--) | Hämtar eller anger den vertikala förskjutningen i procent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Utlöser värdeändring. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Hämtar eller anger ett värde som visar om [justera med lager]. |
| [setAngle(double value)](#setAngle-double-) | Hämtar eller anger vinkeln. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Hämtar eller anger gränserna för lagerbehållaren för att korrekt beräkna gradientens position. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Konverterar det angivna denormaliserade skalan (UI) till dess  **normalized**  motsvarighet och tilldelar den till  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Hämtar eller anger typen av gradienten. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Hämtar eller anger den horisontella förskjutningen i procent. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Hämtar eller anger interpolationsmetoden för gradienten. |
| [setReverse(boolean value)](#setReverse-boolean-) | Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är omvänd. |
| [setScale(int value)](#setScale-int-) | Hämtar eller anger den  **normalized**  gradientskalan (i procent) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Hämtar eller anger den vertikala förskjutningen i procent. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Initierar en ny instans av klassen [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Hämtar eller anger gränserna för lagerbehållaren för att korrekt beräkna gradientens position.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Beräknar och returnerar den  **denormalized**  gradientskalan (UI Scale) som motsvarar det aktuella  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Gradientens gränser. |

**Returns:**
int - Den denormaliserade (UI) skalan i procent som visas i Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är dither.

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
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Hämtar eller anger interpolationsmetoden för gradienten.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Hämtar eller anger den  **normalized**  gradientskalan (i procent)

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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Hämtar eller anger gränserna för lagerbehållaren för att korrekt beräkna gradientens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Konverterar det angivna denormaliserade skalan (UI) till dess  **normalized**  motsvarighet och tilldelar den till  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). Konverteringen tillämpar gradientens aktuella  Angle ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) och det angivna  fillArea  för att beräkna normaliseringsfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den denormaliserade skalan, UI Scale i procent som visas i Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | Gradientens gränser. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är dither.

Värde:  true  om dither; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Hämtar eller anger specifik gradientdefinitionsinstans (Solid/Noise).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Hämtar eller anger interpolationsmetoden för gradienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) är omvänd.

Värde:  true  om omvänd; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Hämtar eller anger den  **normalized**  gradientskalan (i procent)

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


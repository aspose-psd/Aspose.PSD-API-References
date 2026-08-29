---
title: "StrokeEffect"
second_title: "Aspose.PSD för Java API-referens"
description: "Adobe Photoshop-streckeffekten för PSD‑lagret."
type: docs
weight: 17
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

Adobe® Photoshop® strekeffekt för PSD‑lagret.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Hämtar eller anger blandningsläget. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Hämtar entiteten |
| [getEffectType()](#getEffectType--) | Hämtar en effekttyp |
| [getFillSettings()](#getFillSettings--) | Hämtar eller anger fyllningsinställningarna. |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opaciteten. |
| [getOverprint()](#getOverprint--) | Hämtar eller anger ett värde som indikerar om detta [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) kommer att blanda strecket mot det aktuella lagerinnehållet. |
| [getPosition()](#getPosition--) | Hämtar eller anger positionen för streckeffekten för att kontrollera justeringen av ditt streck mot PSD‑lagrets innehåll. |
| [getSize()](#getSize--) | Hämtar eller anger bredden på strekeffekten. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Hämtar eller anger fyllningsinställningarna. |
| [setOpacity(byte value)](#setOpacity-byte-) | Hämtar eller anger opaciteten. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Hämtar eller anger ett värde som indikerar om detta [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) kommer att blanda strecket mot det aktuella lagerinnehållet. |
| [setPosition(short value)](#setPosition-short-) | Hämtar eller anger positionen för streckeffekten för att kontrollera justeringen av ditt streck mot PSD‑lagrets innehåll. |
| [setSize(int value)](#setSize-int-) | Hämtar eller anger bredden på strekeffekten. |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entitet | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Hämtar eller anger blandningsläget.

Värde: Blandningsläget.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Lagrets pixelgränser. |
| globalAngle | int | Den globala vinkeln för att beräkna global belysningsvinkel. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Hämtar entiteten

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Hämtar en effekttyp

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Hämtar eller anger fyllningsinställningarna.

Värde: Fyllnadsinställningarna.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Hämtar eller anger opaciteten.

Värde: Opaciteten.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Hämtar eller anger ett värde som indikerar om detta [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) kommer att blanda strecket mot det aktuella lagerinnehållet.

Värde:  true  om den måste blanda strecket med det aktuella lagrets innehåll; annars,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Hämtar eller anger positionen för strekeffekten för att kontrollera justeringen av ditt streck mot PSD-lagrets innehåll. Värdet kan vara [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) för att rita strecket inuti PSD-lagrets innehåll, eller [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) för att rita strecket runt PSD-lagrets innehåll, och [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) för att rita strecket både inuti och utanpå.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar eller anger bredden på strekeffekten.

Värde: Bredden på strekeffekten.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Hämtar eller anger ett värde som indikerar om detta objekt är synligt.

Värde:  true  om detta objekt är synligt; annars  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Hämtar eller anger blandningsläget.

Värde: Blandningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Hämtar eller anger fyllningsinställningarna.

Värde: Fyllnadsinställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Hämtar eller anger opaciteten.

Värde: Opaciteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) kommer att blanda strecket mot det aktuella lagerinnehållet.

Värde:  true  om den måste blanda strecket med det aktuella lagrets innehåll; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Hämtar eller anger positionen för strekeffekten för att kontrollera justeringen av ditt streck mot PSD-lagrets innehåll. Värdet kan vara [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) för att rita strecket inuti PSD-lagrets innehåll, eller [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) för att rita strecket runt PSD-lagrets innehåll, och [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) för att rita strecket både inuti och utanpå.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Hämtar eller anger bredden på strekeffekten.

Värde: Bredden på strekeffekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekt är synligt.

Värde:  true  om detta objekt är synligt; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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


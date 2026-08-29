---
title: "ILayerEffect"
second_title: "Aspose.PSD för Java API-referens"
description: "Gränssnitt för lagerffekter"
type: docs
weight: 20
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Gränssnitt för lagerffekter
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Hämtar eller anger blandningsläget. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser. |
| [getEffectType()](#getEffectType--) | Hämtar en effekttyp |
| [getOpacity()](#getOpacity--) | Hämtar eller anger opaciteten där 255 = 100% |
| [isVisible()](#isVisible--) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
| [setBlendMode(long value)](#setBlendMode-long-) | Hämtar eller anger blandningsläget. |
| [setOpacity(byte value)](#setOpacity-byte-) | Hämtar eller anger opaciteten där 255 = 100% |
| [setVisible(boolean value)](#setVisible-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekt är synligt. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Hämtar eller anger blandningsläget.

Värde: Blandningsläget.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Beräknar och hämtar gränserna för effektpixlar baserat på lagrets pixelgränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Lagrets pixelgränser. |
| globalAngle | int | Den globala vinkeln för att beräkna global belysningsvinkel. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Hämtar en effekttyp

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Hämtar eller anger opaciteten där 255 = 100%

Värde: Opaciteten.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Hämtar eller anger ett värde som indikerar om detta objekt är synligt.

Värde:  true  om detta objekt är synligt; annars  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Hämtar eller anger blandningsläget.

Värde: Blandningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Hämtar eller anger opaciteten där 255 = 100%

Värde: Opaciteten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekt är synligt.

Värde:  true  om detta objekt är synligt; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |


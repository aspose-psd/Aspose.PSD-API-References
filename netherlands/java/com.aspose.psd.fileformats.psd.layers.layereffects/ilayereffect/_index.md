---
title: "ILayerEffect"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Interface voor laag-effecten"
type: docs
weight: 20
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Interface voor laag-effecten
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Haalt op of stelt de mengmodus in. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Bereken en haal de grenzen van effectpixels op op basis van de grenzen van invoerlaagpixels. |
| [getEffectType()](#getEffectType--) | Haalt een type effect op |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de dekking in waarbij 255 = 100%. |
| [isVisible()](#isVisible--) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setOpacity(byte value)](#setOpacity-byte-) | Haalt op of stelt de dekking in waarbij 255 = 100%. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Haalt op of stelt de mengmodus in.

Waarde: De mengmodus.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Bereken en haal de grenzen van effectpixels op op basis van de grenzen van invoerlaagpixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | De pixelgrenzen van de laag. |
| globalAngle | int | De globale hoek om de globale lichthoek te berekenen. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Haalt een type effect op

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Haalt op of stelt de dekking in waarbij 255 = 100%.

Waarde: De dekking.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is.

Waarde:  true  als deze instantie zichtbaar is; anders,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Haalt op of stelt de mengmodus in.

Waarde: De mengmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Haalt op of stelt de dekking in waarbij 255 = 100%.

Waarde: De dekking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is.

Waarde:  true  als deze instantie zichtbaar is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |


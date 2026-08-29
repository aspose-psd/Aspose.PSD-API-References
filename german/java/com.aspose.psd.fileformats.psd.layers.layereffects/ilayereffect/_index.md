---
title: "ILayerEffect"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Schnittstelle für Ebeneneffekte"
type: docs
weight: 20
url: /de/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Schnittstelle für Ebeneneffekte
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Liest oder setzt den Mischmodus. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel. |
| [getEffectType()](#getEffectType--) | Liest einen Effekttyp |
| [getOpacity()](#getOpacity--) | Liest oder setzt die Deckkraft, wobei 255 = 100% |
| [isVisible()](#isVisible--) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
| [setBlendMode(long value)](#setBlendMode-long-) | Liest oder setzt den Mischmodus. |
| [setOpacity(byte value)](#setOpacity-byte-) | Liest oder setzt die Deckkraft, wobei 255 = 100% |
| [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Liest oder setzt den Mischmodus.

Wert: Der Mischmodus.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen der Ebenenpixel. |
| globalAngle | int | Der globale Winkel zur Berechnung des globalen Lichtwinkels. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Liest einen Effekttyp

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Liest oder setzt die Deckkraft, wobei 255 = 100%

Wert: Die Opazität.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist.

Wert:  true  wenn diese Instanz sichtbar ist; andernfalls  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Liest oder setzt den Mischmodus.

Wert: Der Mischmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Liest oder setzt die Deckkraft, wobei 255 = 100%

Wert: Die Opazität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist.

Wert:  true  wenn diese Instanz sichtbar ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |


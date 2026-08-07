---
title: "ILayerEffect"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Interfaccia per gli effetti di livello"
type: docs
weight: 20
url: /it/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Interfaccia per gli effetti di livello
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Ottiene o imposta la modalità di fusione. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcola e ottiene i limiti dei pixel dell'effetto basati sui limiti dei pixel del livello di input. |
| [getEffectType()](#getEffectType--) | Ottiene un tipo di effetto |
| [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità dove 255 = 100% |
| [isVisible()](#isVisible--) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setOpacity(byte value)](#setOpacity-byte-) | Ottiene o imposta l'opacità dove 255 = 100% |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Ottiene o imposta la modalità di fusione.

Valore: La modalità di fusione.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Calcola e ottiene i limiti dei pixel dell'effetto basati sui limiti dei pixel del livello di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dei pixel del livello. |
| globalAngle | int | L'angolo globale per calcolare l'angolo della luce globale. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Ottiene un tipo di effetto

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Ottiene o imposta l'opacità dove 255 = 100%

Valore: L'opacità.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Ottiene o imposta un valore che indica se questa istanza è visibile.

Valore:  true  se questa istanza è visibile; altrimenti,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Ottiene o imposta la modalità di fusione.

Valore: La modalità di fusione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Ottiene o imposta l'opacità dove 255 = 100%

Valore: L'opacità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è visibile.

Valore:  true  se questa istanza è visibile; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |


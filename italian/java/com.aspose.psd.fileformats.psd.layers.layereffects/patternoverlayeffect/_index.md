---
title: "PatternOverlayEffect"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Effetto di motivo del livello"
type: docs
weight: 16
url: /it/java/com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class PatternOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Effetto di motivo del livello
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Ottiene o imposta la modalità di fusione. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcola e ottiene i limiti dei pixel dell'effetto basati sui limiti dei pixel del livello di input. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Ottiene l'entità |
| [getEffectType()](#getEffectType--) | Ottiene un tipo di effetto. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità. |
| [getSettings()](#getSettings--) | Ottiene o imposta le impostazioni. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setOpacity(byte value)](#setOpacity-byte-) | Ottiene o imposta l'opacità. |
| [setSettings(PatternFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Ottiene o imposta le impostazioni. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static PatternOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Ottiene o imposta la modalità di fusione.

Valore: La modalità di fusione.

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


Calcola e ottiene i limiti dei pixel dell'effetto basati sui limiti dei pixel del livello di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dei pixel del livello. |
| globalAngle | int | L'angolo globale per calcolare l'angolo della luce globale. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Ottiene l'entità

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Ottiene un tipo di effetto.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Ottiene o imposta l'opacità.

Valore: L'opacità.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final PatternFillSettings getSettings()
```


Ottiene o imposta le impostazioni.

Valore: le impostazioni.

**Returns:**
[PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)
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


Ottiene o imposta un valore che indica se questa istanza è visibile.

Valore:  true  se questa istanza è visibile; altrimenti,  false .

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


Ottiene o imposta la modalità di fusione.

Valore: La modalità di fusione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Ottiene o imposta l'opacità.

Valore: L'opacità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### setSettings(PatternFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setSettings(PatternFillSettings value)
```


Ottiene o imposta le impostazioni.

Valore: le impostazioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è visibile.

Valore:  true  se questa istanza è visibile; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


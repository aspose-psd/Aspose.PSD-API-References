---
title: "OuterGlowEffect"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Effetto di bagliore esterno del livello"
type: docs
weight: 15
url: /it/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Effetto di bagliore esterno del livello
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
| [getFillColor()](#getFillColor--) | Ottiene o imposta il colore. |
| [getIntensity()](#getIntensity--) | Ottiene o imposta l'angolo in gradi. |
| [getJitter()](#getJitter--) | Ottiene o imposta il rumore. |
| [getNoise()](#getNoise--) | Ottiene o imposta il rumore. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità. |
| [getRange()](#getRange--) | Ottiene o imposta il rumore. |
| [getSize()](#getSize--) | Ottiene il valore di sfocatura in pixel. |
| [getSpread()](#getSpread--) | Ottiene o imposta l'intensità in percentuale. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Ottiene o imposta l'effetto AntiAliasing abilitato. |
| [isSoftBlend()](#isSoftBlend--) | Ottiene o imposta un valore che indica se [knocks out]. |
| [isVisible()](#isVisible--) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Ottiene o imposta l'effetto AntiAliasing abilitato. |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Ottiene o imposta il colore. |
| [setIntensity(int value)](#setIntensity-int-) | Ottiene o imposta l'angolo in gradi. |
| [setJitter(int value)](#setJitter-int-) | Ottiene o imposta il rumore. |
| [setNoise(int value)](#setNoise-int-) | Ottiene o imposta il rumore. |
| [setOpacity(byte value)](#setOpacity-byte-) | Ottiene o imposta l'opacità. |
| [setRange(int value)](#setRange-int-) | Ottiene o imposta il rumore. |
| [setSize(int value)](#setSize-int-) | Ottiene il valore di sfocatura in pixel. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Ottiene o imposta un valore che indica se [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Ottiene o imposta l'intensità in percentuale. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Ottiene o imposta il colore.

Valore: Il colore.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Ottiene o imposta l'angolo in gradi.

Valore: L'angolo.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Ottiene o imposta il rumore.

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Ottiene o imposta il rumore.

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
### getRange() {#getRange--}
```
public final int getRange()
```


Ottiene o imposta il rumore.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene il valore di sfocatura in pixel.

Valore: la dimensione.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Ottiene o imposta l'intensità in percentuale.

Valore: La diffusione.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


Ottiene o imposta l'effetto AntiAliasing abilitato.

Valore: La distanza.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Ottiene o imposta un valore che indica se [knocks out].

Valore: vero se [knocks out]; altrimenti, falso.

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Ottiene o imposta l'effetto AntiAliasing abilitato.

Valore: La distanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Ottiene o imposta il colore.

Valore: Il colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Ottiene o imposta l'angolo in gradi.

Valore: L'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Ottiene o imposta il rumore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Ottiene o imposta il rumore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Ottiene o imposta il rumore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Ottiene il valore di sfocatura in pixel.

Valore: la dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Ottiene o imposta un valore che indica se [knocks out].

Valore: vero se [knocks out]; altrimenti, falso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Ottiene o imposta l'intensità in percentuale.

Valore: La diffusione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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


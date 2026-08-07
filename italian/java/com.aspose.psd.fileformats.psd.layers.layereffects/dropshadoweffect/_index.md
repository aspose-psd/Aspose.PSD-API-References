---
title: "DropShadowEffect"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Effetto di ombra proiettata del livello"
type: docs
weight: 12
url: /it/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Effetto di ombra proiettata del livello
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Ottiene o imposta l'angolo in gradi. |
| [getBlendMode()](#getBlendMode--) | Ottiene o imposta la modalità di fusione. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ottiene o imposta il colore. |
| [getDistance()](#getDistance--) | Ottiene o imposta la distanza in pixel. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcola e ottiene i limiti dei pixel dell'effetto basati sui limiti dei pixel del livello di input. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Ottiene l'entità |
| [getEffectType()](#getEffectType--) | Ottiene un tipo di effetto |
| [getKnocksOut()](#getKnocksOut--) | Ottiene o imposta un valore che indica se [knocks out]. |
| [getNoise()](#getNoise--) | Ottiene o imposta il rumore. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità. |
| [getSize()](#getSize--) | Ottiene o imposta il valore di sfocatura in pixel. |
| [getSpread()](#getSpread--) | Ottiene o imposta l'intensità in percentuale. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Ottiene o imposta un valore che indica se [usa questo angolo in tutti gli effetti del livello]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Ottiene o imposta l'angolo in gradi. |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Ottiene o imposta il colore. |
| [setDistance(int value)](#setDistance-int-) | Ottiene o imposta la distanza in pixel. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | Ottiene o imposta un valore che indica se [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | Ottiene o imposta il rumore. |
| [setOpacity(byte value)](#setOpacity-byte-) | Ottiene o imposta l'opacità. |
| [setSize(int value)](#setSize-int-) | Ottiene o imposta il valore di sfocatura in pixel. |
| [setSpread(int value)](#setSpread-int-) | Ottiene o imposta l'intensità in percentuale. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Ottiene o imposta un valore che indica se [usa questo angolo in tutti gli effetti del livello]. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Ottiene o imposta l'angolo in gradi.

Valore: L'angolo.

**Returns:**
int
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
### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene o imposta il colore.

Valore: Il colore.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Ottiene o imposta la distanza in pixel.

Valore: La distanza.

**Returns:**
int
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


Ottiene un tipo di effetto

**Returns:**
int
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


Ottiene o imposta un valore che indica se [knocks out].

Valore: vero se [knocks out]; altrimenti, falso.

**Returns:**
boolean
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
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene o imposta il valore di sfocatura in pixel.

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
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Ottiene o imposta un valore che indica se [usa questo angolo in tutti gli effetti del livello].

Valore:  true  se [use global light]; altrimenti,  false .

**Returns:**
boolean
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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


Ottiene o imposta l'angolo in gradi.

Valore: L'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Ottiene o imposta il colore.

Valore: Il colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Ottiene o imposta la distanza in pixel.

Valore: La distanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


Ottiene o imposta un valore che indica se [knocks out].

Valore: vero se [knocks out]; altrimenti, falso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Ottiene o imposta il valore di sfocatura in pixel.

Valore: la dimensione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Ottiene o imposta un valore che indica se [usa questo angolo in tutti gli effetti del livello].

Valore:  true  se [use global light]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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


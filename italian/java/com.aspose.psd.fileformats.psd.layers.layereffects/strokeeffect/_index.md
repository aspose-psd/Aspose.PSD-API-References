---
title: "StrokeEffect"
second_title: "Riferimento API Aspose.PSD per Java"
description: "L'effetto contorno di Adobe Photoshop per il livello PSD."
type: docs
weight: 17
url: /it/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

L'effetto tratto di Adobe® Photoshop® per il livello PSD.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Ottiene o imposta la modalità di fusione. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcola e ottiene i limiti dei pixel dell'effetto basati sui limiti dei pixel del livello di input. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Ottiene l'entità |
| [getEffectType()](#getEffectType--) | Ottiene un tipo di effetto |
| [getFillSettings()](#getFillSettings--) | Ottiene o imposta le impostazioni di riempimento. |
| [getOpacity()](#getOpacity--) | Ottiene o imposta l'opacità. |
| [getOverprint()](#getOverprint--) | Ottiene o imposta un valore che indica se questo [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mescolerà il contorno con il contenuto del livello corrente. |
| [getPosition()](#getPosition--) | Ottiene o imposta la posizione dell'effetto contorno per controllare l'allineamento del tuo contorno al contenuto del livello PSD. |
| [getSize()](#getSize--) | Ottiene o imposta la larghezza dell'effetto contorno. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Ottiene o imposta la modalità di fusione. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Ottiene o imposta le impostazioni di riempimento. |
| [setOpacity(byte value)](#setOpacity-byte-) | Ottiene o imposta l'opacità. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Ottiene o imposta un valore che indica se questo [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mescolerà il contorno con il contenuto del livello corrente. |
| [setPosition(short value)](#setPosition-short-) | Ottiene o imposta la posizione dell'effetto contorno per controllare l'allineamento del tuo contorno al contenuto del livello PSD. |
| [setSize(int value)](#setSize-int-) | Ottiene o imposta la larghezza dell'effetto contorno. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta un valore che indica se questa istanza è visibile. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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


Ottiene un tipo di effetto

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Ottiene o imposta le impostazioni di riempimento.

Valore: Le impostazioni di riempimento.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Ottiene o imposta l'opacità.

Valore: L'opacità.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Ottiene o imposta un valore che indica se questo [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mescolerà il contorno con il contenuto del livello corrente.

Valore: vero se deve mescolare il contorno con il contenuto del livello corrente; altrimenti, falso.

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Ottiene o imposta la posizione dell'effetto contorno per controllare l'allineamento del tuo contorno al contenuto del livello PSD. Il valore può essere [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) per disegnare il contorno all'interno del contenuto del livello PSD, o [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) per disegnare il contorno attorno al contenuto del livello PSD, e [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) per disegnare il contorno sia all'interno che all'esterno.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene o imposta la larghezza dell'effetto contorno.

Valore: la larghezza dell'effetto contorno.

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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Ottiene o imposta le impostazioni di riempimento.

Valore: Le impostazioni di riempimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Ottiene o imposta un valore che indica se questo [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mescolerà il contorno con il contenuto del livello corrente.

Valore: vero se deve mescolare il contorno con il contenuto del livello corrente; altrimenti, falso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Ottiene o imposta la posizione dell'effetto contorno per controllare l'allineamento del tuo contorno al contenuto del livello PSD. Il valore può essere [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) per disegnare il contorno all'interno del contenuto del livello PSD, o [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) per disegnare il contorno attorno al contenuto del livello PSD, e [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) per disegnare il contorno sia all'interno che all'esterno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Ottiene o imposta la larghezza dell'effetto contorno.

Valore: la larghezza dell'effetto contorno.

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


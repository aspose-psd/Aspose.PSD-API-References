---
title: "SolidGradient"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Impostazioni dell'effetto di riempimento del gradiente."
type: docs
weight: 13
url: /it/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Impostazioni dell'effetto di riempimento del gradiente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Inizializza una nuova istanza della classe [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Aggiunge il punto di colore. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Aggiunge il punto di colore. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Genera i nodi risorsa LFX2. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Ottiene o imposta i punti di colore. |
| [getGradientMode()](#getGradientMode--) | Restituisce la modalità per questo gradiente. |
| [getGradientName()](#getGradientName--) | Ottiene o imposta il nome del gradiente. |
| [getInterpolation()](#getInterpolation--) | Ottiene o imposta Interpolation. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Ottiene o imposta i punti di trasparenza. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Rimuove il punto di colore. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Rimuove il punto di trasparenza. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Ottiene o imposta i punti di colore. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Ottiene o imposta il nome del gradiente. |
| [setInterpolation(short value)](#setInterpolation-short-) | Ottiene o imposta Interpolation. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Ottiene o imposta i punti di trasparenza. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Inizializza una nuova istanza della classe [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient).

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Aggiunge il punto di colore.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Aggiunge il punto di colore.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Genera i nodi risorsa LFX2.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Elenco generato di [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Ottiene o imposta i punti di colore.

Valore: i punti di colore.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


Restituisce la modalità per questo gradiente. Determina 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Ottiene o imposta il nome del gradiente.

Valore: Il nome del gradiente.

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Ottiene o imposta Interpolation. Determina la fluidità, quando 'Gradient Type' = 'Solid'. Intervallo di valori: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Ottiene o imposta i punti di trasparenza.

Valore: i punti di trasparenza.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


Rimuove il punto di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Il punto. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Rimuove il punto di trasparenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Il punto. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Ottiene o imposta i punti di colore.

Valore: i punti di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Ottiene o imposta il nome del gradiente.

Valore: Il nome del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Ottiene o imposta Interpolation. Determina la fluidità, quando 'Gradient Type' = 'Solid'. Intervallo di valori: 0-4096.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Ottiene o imposta i punti di trasparenza.

Valore: i punti di trasparenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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


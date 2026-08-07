---
title: "GradientFillSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Impostazioni dell'effetto di riempimento del gradiente."
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Impostazioni dell'effetto di riempimento del gradiente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Inizializza una nuova istanza della classe [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Ottiene o imposta un valore che indica se [align with layer]. |
| [getAngle()](#getAngle--) | Ottiene o imposta l'angolo. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Ottiene o imposta i limiti del contenitore del livello per calcolare correttamente la posizione del gradiente. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Calcola e restituisce la scala del gradiente **denormalized** (Scala UI) corrispondente al valore corrente di Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è dither. |
| [getFillType()](#getFillType--) | Il tipo di riempimento. |
| [getGradient()](#getGradient--) | Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Ottiene o imposta il tipo di gradiente. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Ottiene o imposta lo spostamento orizzontale in percentuale. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [getReverse()](#getReverse--) | Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è invertito. |
| [getScale()](#getScale--) | Ottiene o imposta la scala del gradiente **normalized** (in percentuale) |
| [getVerticalOffset()](#getVerticalOffset--) | Ottiene o imposta lo spostamento verticale in percentuale. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera la modifica del valore. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Ottiene o imposta un valore che indica se [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Ottiene o imposta l'angolo. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Ottiene o imposta i limiti del contenitore del livello per calcolare correttamente la posizione del gradiente. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Converte il valore della scala denormalized (UI) specificato nella sua equivalente **normalized** e lo assegna a Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Ottiene o imposta il tipo di gradiente. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Ottiene o imposta lo spostamento orizzontale in percentuale. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Ottiene o imposta il metodo di interpolazione per il gradiente. |
| [setReverse(boolean value)](#setReverse-boolean-) | Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è invertito. |
| [setScale(int value)](#setScale-int-) | Ottiene o imposta la scala del gradiente **normalized** (in percentuale) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Ottiene o imposta lo spostamento verticale in percentuale. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Inizializza una nuova istanza della classe [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Ottiene o imposta un valore che indica se [align with layer].

Valore:  true  se [align with layer]; altrimenti,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Ottiene o imposta l'angolo.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Ottiene o imposta i limiti del contenitore del livello per calcolare correttamente la posizione del gradiente.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Calcola e restituisce la scala del gradiente **denormalized** (Scala UI) corrispondente al valore corrente di Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | I limiti del gradiente. |

**Returns:**
int - La scala denormalized (UI) in percentuale come visualizzata in Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è dither.

Valore:  true  se dither; altrimenti,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Il tipo di riempimento.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Ottiene o imposta il tipo di gradiente.

Valore: Il tipo di gradiente.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Ottiene o imposta lo spostamento orizzontale in percentuale.

Valore: Lo spostamento orizzontale.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Ottiene o imposta il metodo di interpolazione per il gradiente.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è invertito.

Valore:  true  se invertito; altrimenti,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Ottiene o imposta la scala del gradiente **normalized** (in percentuale)

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Ottiene o imposta lo spostamento verticale in percentuale.

Valore: Lo spostamento verticale.

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Genera la modifica del valore.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Ottiene o imposta un valore che indica se [align with layer].

Valore:  true  se [align with layer]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Ottiene o imposta l'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Ottiene o imposta i limiti del contenitore del livello per calcolare correttamente la posizione del gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Converte il valore della scala denormalized (UI) specificato nella sua equivalente **normalized** e lo assegna a Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). La conversione applica l'Angle corrente del gradiente ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) e l'area di riempimento fornita (fillArea) per calcolare il fattore di normalizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La scala denormalized, Scala UI in percentuale come visualizzata da Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | I limiti del gradiente. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è dither.

Valore:  true  se dither; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Ottiene o imposta l'istanza della definizione del gradiente specifica (Solid/Noise).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Ottiene o imposta il tipo di gradiente.

Valore: Il tipo di gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Ottiene o imposta lo spostamento orizzontale in percentuale.

Valore: Lo spostamento orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Ottiene o imposta il metodo di interpolazione per il gradiente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Ottiene o imposta un valore che indica se questo [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) è invertito.

Valore:  true  se invertito; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Ottiene o imposta la scala del gradiente **normalized** (in percentuale)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Ottiene o imposta lo spostamento verticale in percentuale.

Valore: Lo spostamento verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

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


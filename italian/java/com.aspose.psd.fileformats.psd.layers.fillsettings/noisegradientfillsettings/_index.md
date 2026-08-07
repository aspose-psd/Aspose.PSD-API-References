---
title: "NoiseGradientFillSettings"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe di definizione del gradiente di rumore."
type: docs
weight: 18
url: /it/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Classe di definizione del gradiente di rumore.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Inizializza una nuova istanza della classe [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings). |
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
| [getColorModel()](#getColorModel--) | Ottiene o imposta il modello di colore - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è dither. |
| [getExpansionCount()](#getExpansionCount--) | Ottiene o imposta il conteggio di espansione ( = 2 per Photoshop 6.0). |
| [getFillType()](#getFillType--) | Il tipo di riempimento. |
| [getGradientMode()](#getGradientMode--) | Restituisce la modalità per questo gradiente. |
| [getGradientName()](#getGradientName--) | Ottiene o imposta il nome del gradiente. |
| [getGradientType()](#getGradientType--) | Ottiene o imposta il tipo di gradiente. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Ottiene o imposta lo spostamento orizzontale in percentuale. |
| [getMaximumColor()](#getMaximumColor--) | Ottiene o imposta il colore massimo di PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Ottiene o imposta il colore minimo di PixelDataFormat. |
| [getReverse()](#getReverse--) | Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è invertito. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Ottiene o imposta il seme del numero casuale usato per generare i colori per il gradiente di rumore |
| [getRoughness()](#getRoughness--) | Ottiene o imposta il fattore di rugosità. |
| [getScale()](#getScale--) | Ottiene o imposta la scala. |
| [getShowTransparency()](#getShowTransparency--) | Ottiene o imposta il flag per mostrare la trasparenza. |
| [getUseVectorColor()](#getUseVectorColor--) | Ottiene o imposta il flag per l'uso del colore vettoriale. |
| [getVerticalOffset()](#getVerticalOffset--) | Ottiene o imposta lo spostamento verticale in percentuale. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Genera la modifica del valore. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Ottiene o imposta un valore che indica se [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Ottiene o imposta l'angolo. |
| [setColorModel(short value)](#setColorModel-short-) | Ottiene o imposta il modello di colore - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Ottiene o imposta il conteggio di espansione ( = 2 per Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Restituisce la modalità per questo gradiente. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Ottiene o imposta il nome del gradiente. |
| [setGradientType(int value)](#setGradientType-int-) | Ottiene o imposta il tipo di gradiente. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Ottiene o imposta lo spostamento orizzontale in percentuale. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Ottiene o imposta il colore massimo di PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Ottiene o imposta il colore minimo di PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è invertito. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Ottiene o imposta il seme del numero casuale usato per generare i colori per il gradiente di rumore |
| [setRoughness(int value)](#setRoughness-int-) | Ottiene o imposta il fattore di rugosità. |
| [setScale(int value)](#setScale-int-) | Ottiene o imposta la scala. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Ottiene o imposta il flag per mostrare la trasparenza. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Ottiene o imposta il flag per l'uso del colore vettoriale. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Ottiene o imposta lo spostamento verticale in percentuale. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Inizializza una nuova istanza della classe [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings).

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Ottiene o imposta il modello di colore - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è dither.

Valore:  true  se dither; altrimenti,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Ottiene o imposta il conteggio di espansione ( = 2 per Photoshop 6.0).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


Il tipo di riempimento.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Ottiene o imposta il colore massimo di PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Ottiene o imposta il colore minimo di PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è invertito.

Valore:  true  se invertito; altrimenti,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Ottiene o imposta il seme del numero casuale usato per generare i colori per il gradiente di rumore

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Ottiene o imposta il fattore di rugosità.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Ottiene o imposta la scala.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Ottiene o imposta il flag per mostrare la trasparenza.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Ottiene o imposta il flag per l'uso del colore vettoriale.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Ottiene o imposta il modello di colore - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è dither.

Valore:  true  se dither; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Ottiene o imposta il conteggio di espansione ( = 2 per Photoshop 6.0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Restituisce la modalità per questo gradiente. Determina 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Ottiene o imposta il colore massimo di PixelDataFormat.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Ottiene o imposta il colore minimo di PixelDataFormat.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) è invertito.

Valore:  true  se invertito; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Ottiene o imposta il seme del numero casuale usato per generare i colori per il gradiente di rumore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Ottiene o imposta il fattore di rugosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Ottiene o imposta la scala.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Ottiene o imposta il flag per mostrare la trasparenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Ottiene o imposta il flag per l'uso del colore vettoriale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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


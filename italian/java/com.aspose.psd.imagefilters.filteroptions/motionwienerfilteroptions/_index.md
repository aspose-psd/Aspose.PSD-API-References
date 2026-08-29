---
title: "MotionWienerFilterOptions"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Opzioni del filtro di deconvoluzione     rimozione del mosso"
type: docs
weight: 18
url: /it/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Opzioni filtro di deconvoluzione deblur motion
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | Inizializza una nuova istanza della  MotionWienerFilterOptions  classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Ottiene o imposta l'angolo in gradus. |
| [getBrightness()](#getBrightness--) | Ottiene o imposta la luminosità. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Ottiene o imposta un valore che indica se questo [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) è in scala di grigi. |
| [getLength()](#getLength--) | Ottiene o imposta la lunghezza. |
| [getSmooth()](#getSmooth--) | Ottiene o imposta smooth. |
| [getSnr()](#getSnr--) | Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Ottiene un valore che indica se questa istanza è parzialmente caricata. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | Ottiene o imposta l'angolo in gradus. |
| [setBrightness(double value)](#setBrightness-double-) | Ottiene o imposta la luminosità. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Ottiene o imposta un valore che indica se questo [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) è in scala di grigi. |
| [setLength(int value)](#setLength-int-) | Ottiene o imposta la lunghezza. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Ottiene un valore che indica se questa istanza è parzialmente caricata. |
| [setSmooth(double value)](#setSmooth-double-) | Ottiene o imposta smooth. |
| [setSnr(double value)](#setSnr-double-) | Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


Inizializza una nuova istanza della  MotionWienerFilterOptions  classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lunghezza | int | La lunghezza. |
| smooth | double | Il smooth. |
| angle | double | L'angolo in gradus. |

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
public double getAngle()
```


Ottiene o imposta l'angolo in gradus.

Valore: L'angolo.

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Ottiene o imposta la luminosità. intervallo consigliato 1 - 1,5 valore predefinito = 1,15

Valore: La luminosità.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Ottiene o imposta un valore che indica se questo [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) è in scala di grigi. Restituisce modalità scala di grigi o modalità RGB.

Valore:  true  se in scala di grigi; altrimenti,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Ottiene o imposta la lunghezza.

Valore: La lunghezza.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Ottiene o imposta smooth.

Valore: Liscio.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007

Valore: Il SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


Ottiene un valore che indica se questa istanza è parzialmente caricata.

Valore:  true  se questa istanza è caricata parzialmente; altrimenti,  false .

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


Ottiene o imposta l'angolo in gradus.

Valore: L'angolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Ottiene o imposta la luminosità. intervallo consigliato 1 - 1,5 valore predefinito = 1,15

Valore: La luminosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Ottiene o imposta un valore che indica se questo [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) è in scala di grigi. Restituisce modalità scala di grigi o modalità RGB.

Valore:  true  se in scala di grigi; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Ottiene o imposta la lunghezza.

Valore: La lunghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Ottiene un valore che indica se questa istanza è parzialmente caricata.

Valore:  true  se questa istanza è caricata parzialmente; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Ottiene o imposta smooth.

Valore: Liscio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Ottiene o imposta il SNR (rapporto segnale-rumore) intervallo consigliato 0.002 - 0.009, valore predefinito = 0.007

Valore: Il SNR.

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


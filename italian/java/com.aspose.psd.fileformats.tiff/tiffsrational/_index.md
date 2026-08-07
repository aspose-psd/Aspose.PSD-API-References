---
title: "TiffSRational"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il tipo razionale TIFF."
type: docs
weight: 13
url: /it/java/com.aspose.psd.fileformats.tiff/tiffsrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

Il tipo razionale TIFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Inizializza una nuova istanza della classe  TiffSRational . |
| [TiffSRational(int value)](#TiffSRational-int-) | Inizializza una nuova istanza della classe TiffRational. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Inizializza una nuova istanza della classe  TiffSRational . |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Epsilon](#Epsilon) | L'epsilon per il calcolo della frazione |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Approssima il valore fornito a una frazione. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approssima il valore fornito a una frazione. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approssima il valore fornito a una frazione. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approssima il valore fornito a una frazione. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'  Object  specificato è uguale a questa istanza. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Restituisce il denominatore. |
| [getNominator()](#getNominator--) | Restituisce il numeratore. |
| [getValue()](#getValue--) | Ottiene il valore float. |
| [getValueD()](#getValueD--) | Restituisce il valore double. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce un  System.String  che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Inizializza una nuova istanza della classe  TiffSRational .

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Inizializza una nuova istanza della classe TiffRational.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il valore del numeratore. |

Il numeratore sarà usato come valore specificato e il denominatore sarà uguale a 1. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Inizializza una nuova istanza della classe  TiffSRational .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numeratore | int | Il numeratore. |
| denominatore | int | Il denominatore. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


L'epsilon per il calcolo della frazione

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'  Object  specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  Object  da confrontare con questa istanza. |

**Returns:**
boolean -  true  se l'  Object  specificato è uguale a questa istanza; altrimenti,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Restituisce il denominatore.

Valore: Il denominatore.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Restituisce il numeratore.

Valore: Il numeratore.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Ottiene il valore float.

Valore: Il valore float.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Restituisce il valore double.

Valore: Il valore double.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Restituisce un  System.String  che rappresenta questa istanza.

**Returns:**
java.lang.String - Un  System.String  che rappresenta questa istanza.
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


---
title: "TiffRational"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il tipo razionale TIFF."
type: docs
weight: 12
url: /it/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Il tipo razionale TIFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffRational()](#TiffRational--) | Inizializza una nuova istanza della classe TiffRational. |
| [TiffRational(long value)](#TiffRational-long-) | Inizializza una nuova istanza della classe TiffRational. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Inizializza una nuova istanza della classe TiffRational. |
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
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
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
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Inizializza una nuova istanza della classe TiffRational.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Inizializza una nuova istanza della classe TiffRational.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | long | Il valore del numeratore. |

Il numeratore sarà usato come valore specificato e il denominatore sarà uguale a 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Inizializza una nuova istanza della classe TiffRational.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numeratore | long | Il numeratore. |
| denominatore | long | Il denominatore. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


L'epsilon per il calcolo della frazione

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Approssima il valore fornito a una frazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con questa istanza. |

**Returns:**
boolean -  true  se l'oggetto specificato è uguale a questa istanza; altrimenti,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Restituisce il denominatore.

Valore: Il denominatore.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Restituisce il numeratore.

Valore: Il numeratore.

**Returns:**
long
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


---
title: "Time"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresentazione di un valore temporale in secondi."
type: docs
weight: 13
url: /it/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Rappresentazione di un valore temporale in secondi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Inizializza una nuova istanza della classe  Time . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Ottiene o imposta la scala per il valore temporale. |
| [getValue()](#getValue--) | Ottiene o imposta il valore temporale nella scala specificata. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Ottiene il valore stringa contenuto in formato XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Ottiene o imposta la scala per il valore temporale. |
| [setValue(int value)](#setValue-int-) | Ottiene o imposta il valore temporale nella scala specificata. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Inizializza una nuova istanza della classe  Time .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | La scala. |
| valore | int | Il valore. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getScale() {#getScale--}
```
public Rational getScale()
```


Ottiene o imposta la scala per il valore temporale.

Per NTSC, usa 1001/30000, o il meno accurato 100/2997. Per PAL, usa 1/25. Valore: La scala per il valore temporale.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Ottiene o imposta il valore temporale nella scala specificata.

Valore: Il valore temporale nella scala specificata.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Ottiene il valore stringa contenuto in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore stringa contenuto in formato XMP.
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Ottiene o imposta la scala per il valore temporale.

Per NTSC, usa 1001/30000, o il meno accurato 100/2997. Per PAL, usa 1/25. Valore: La scala per il valore temporale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Ottiene o imposta il valore temporale nella scala specificata.

Valore: Il valore temporale nella scala specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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


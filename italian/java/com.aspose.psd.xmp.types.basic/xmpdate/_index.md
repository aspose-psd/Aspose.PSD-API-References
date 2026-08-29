---
title: "XmpDate"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta la data nel pacchetto XMP."
type: docs
weight: 11
url: /it/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Rappresenta la data nel pacchetto XMP.

Un valore data-ora è rappresentato usando un sottoinsieme dei formati definiti in Formati di Data e Ora: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Inizializza una nuova istanza della classe  XmpDate  . |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Inizializza una nuova istanza della classe  XmpDate  . |
## Campi

| Campo | Descrizione |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | La stringa di formato ISO 8601 (roundtrip). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Ottiene la stringa di formato per il valore corrente. |
| [getValue()](#getValue--) | Ottiene o imposta il valore della data. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Restituisce il valore contenuto della stringa in formato XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Ottiene o imposta il valore della data. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Inizializza una nuova istanza della classe  XmpDate  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateTime | java.util.Date | Un valore data-ora rappresentato utilizzando un sottoinsieme della formattazione ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Inizializza una nuova istanza della classe  XmpDate  .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateString | java.lang.String | La rappresentazione stringa della data. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


La stringa di formato ISO 8601 (roundtrip).

Vedi di più: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Ottiene la stringa di formato per il valore corrente.

Valore: La stringa di formato per il valore corrente.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Ottiene o imposta il valore della data.

Valore: Il valore della data.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Restituisce il valore contenuto della stringa in formato XMP.

**Returns:**
java.lang.String - Restituisce il valore contenuto della stringa in formato XMP.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Ottiene o imposta il valore della data.

Valore: Il valore della data.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Date |  |

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


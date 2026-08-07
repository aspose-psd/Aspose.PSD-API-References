---
title: "XmpHeaderPi"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta l'istruzione di elaborazione dell'intestazione XMP."
type: docs
weight: 16
url: /it/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Rappresenta l'istruzione di elaborazione dell'intestazione XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Inizializza una nuova istanza della classe  XmpHeaderPi . |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Inizializza una nuova istanza della classe  XmpHeaderPi . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto specificato  System.Object  è uguale a questa istanza. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Rappresenta il GUID dell'intestazione. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Rappresenta il GUID dell'intestazione. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Inizializza una nuova istanza della classe  XmpHeaderPi .

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Inizializza una nuova istanza della classe  XmpHeaderPi .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| guid | java.lang.String | L'identificatore unico. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto specificato  System.Object  è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  System.Object  da confrontare con questa istanza. |

**Returns:**
boolean - true se l'oggetto System.Object specificato è uguale a questa istanza; altrimenti, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGuid() {#getGuid--}
```
public String getGuid()
```


Rappresenta il GUID dell'intestazione.

Il testo dell'intestazione PI contiene un GUID, rendendo improbabile che compaia accidentalmente nel flusso di dati.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Un oggetto da confrontare con questo oggetto. |

**Returns:**
boolean - true se l'oggetto corrente è uguale al parametro other; altrimenti, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Rappresenta il GUID dell'intestazione.

Il testo dell'intestazione PI contiene un GUID, rendendo improbabile che compaia accidentalmente nel flusso di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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


---
title: "XmpMeta"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta xmpmeta."
type: docs
weight: 17
url: /it/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Rappresenta xmpmeta. Opzionale. Lo scopo di questo elemento è identificare i metadati XMP all'interno di testo XML generico che potrebbe contenere altri usi non XMP di RDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Inizializza una nuova istanza della  XmpMeta  classe. |
| [XmpMeta()](#XmpMeta--) | Inizializza una nuova istanza della  XmpMeta  classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Aggiunge l'attributo. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Assegna l'elemento XMP specificato a quello corrente. |
| [clearAttributes()](#clearAttributes--) | Rimuove tutti gli attributi. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [equals(Object other)](#equals-java.lang.Object-) | Determina se l'oggetto specificato  System.Object  è uguale a questa istanza. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Ottiene o imposta la versione del toolkit Adobe Xmp. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Ottiene l'attributo. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Ottiene o imposta la versione del toolkit Adobe Xmp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Inizializza una nuova istanza della  XmpMeta  classe.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Versione del toolkit Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Inizializza una nuova istanza della  XmpMeta  classe.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Aggiunge l'attributo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attribute | java.lang.String | L'attributo. |
| valore | java.lang.String | Il valore. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Assegna l'elemento XMP specificato a quello corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | L'elemento XMP. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Rimuove tutti gli attributi.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determina se l'oggetto specificato  System.Object  è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| altro | java.lang.Object | L'  System.Object  da confrontare con questa istanza. |

**Returns:**
boolean - true se l'oggetto System.Object specificato è uguale a questa istanza; altrimenti, false.
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Ottiene o imposta la versione del toolkit Adobe Xmp.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Ottiene l'attributo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attribute | java.lang.String | L'attributo. |

**Returns:**
java.lang.String - Restituisce l'attributo per il nome attributo specificato.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Un oggetto da confrontare con questo oggetto. |

**Returns:**
boolean - true se l'oggetto corrente è uguale al parametro other; altrimenti, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Un oggetto da confrontare con questo oggetto. |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Ottiene o imposta la versione del toolkit Adobe Xmp.

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


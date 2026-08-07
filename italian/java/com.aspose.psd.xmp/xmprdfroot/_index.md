---
title: "XmpRdfRoot"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta l'elemento rdfRDF."
type: docs
weight: 21
url: /it/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Rappresenta l'elemento rdf:RDF. Un singolo pacchetto XMP deve essere serializzato utilizzando un unico elemento XML rdf:RDF. Il contenuto dell'elemento rdf:RDF deve consistere solo di zero o più elementi rdf:Description.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Inizializza una nuova istanza della classe XmpRdfRoot. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Aggiunge l'attributo. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Assegna l'elemento XMP specificato a quello corrente. |
| [clearAttributes()](#clearAttributes--) | Rimuove tutti gli attributi. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Ottiene l'attributo. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Ottiene l'URI dello spazio dei nomi per un prefisso specifico. |
| [getXmlValue()](#getXmlValue--) | Converte il valore xmp nella rappresentazione xml. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indica se l'oggetto corrente è uguale a un altro oggetto dello stesso tipo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Aggiunge l'URI dello spazio dei nomi per il prefisso. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Inizializza una nuova istanza della classe XmpRdfRoot.

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'  Object  da confrontare con questa istanza. |

**Returns:**
boolean -  true  se l'  Object  specificato è uguale a questa istanza; altrimenti,  false .
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Ottiene l'URI dello spazio dei nomi per un prefisso specifico. Il prefisso può iniziare senza xmlns.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |

**Returns:**
java.lang.String - Restituisce l'URI dello schema del pacchetto.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore xmp nella rappresentazione xml.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito in stringa XML.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Aggiunge l'URI dello spazio dei nomi per il prefisso. Il prefisso può iniziare senza xmlns.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |
| namespaceUri | java.lang.String | URI dello schema del pacchetto. |

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


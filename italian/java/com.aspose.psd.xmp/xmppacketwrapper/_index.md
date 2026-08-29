---
title: "XmpPacketWrapper"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Contiene il pacchetto xmp serializzato, inclusi intestazione e trailer."
type: docs
weight: 20
url: /it/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Contiene il pacchetto xmp serializzato, inclusi intestazione e trailer.

Un wrapper costituito da una coppia di istruzioni di elaborazione XML (PI) può essere posizionato attorno all'elemento rdf:RDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Inizializza una nuova istanza della classe  XmpPacketWrapper . |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Inizializza una nuova istanza della classe  XmpPacketWrapper . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Aggiunge il pacchetto. |
| [clearPackages()](#clearPackages--) | Rimuove tutti i  XmpPackage  all'interno di XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determina se il pacchetto esiste nel wrapper XMP. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Ottiene l'istruzione di elaborazione dell'intestazione. |
| [getMeta()](#getMeta--) | Ottiene i metadati XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Ottiene il pacchetto per URI dello spazio dei nomi. |
| [getPackages()](#getPackages--) | Ottiene l'array di  XmpPackage  all'interno di XMP. |
| [getPackagesCount()](#getPackagesCount--) | Ottiene il numero di pacchetti all'interno della struttura XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Ottiene l'elemento RDF radice. |
| [getTrailerPi()](#getTrailerPi--) | Ottiene l'istruzione di elaborazione del trailer. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Converte il valore XMP nella rappresentazione XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Rimuove il pacchetto XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Imposta l'istruzione di elaborazione dell'intestazione. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Imposta i metadati XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Imposta l'elemento RDF radice. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Imposta l'istruzione di elaborazione del trailer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Inizializza una nuova istanza della classe  XmpPacketWrapper .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | L'intestazione XMP dell'istruzione di elaborazione. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Il trailer XMP dell'istruzione di elaborazione. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | I metadati XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Inizializza una nuova istanza della classe  XmpPacketWrapper .

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Aggiunge il pacchetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Il pacchetto. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Rimuove tutti i  XmpPackage  all'interno di XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Determina se il pacchetto esiste nel wrapper XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI dello schema del pacchetto. |

**Returns:**
boolean - Restituisce true se il pacchetto con lo Uri dello spazio dei nomi specificato esiste nel wrapper XMP.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Ottiene l'istruzione di elaborazione dell'intestazione.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Ottiene i metadati XMP. Facoltativo.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Ottiene il pacchetto per URI dello spazio dei nomi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| namespaceUri | java.lang.String | L'URI dello schema del pacchetto. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Ottiene l'array di  XmpPackage  all'interno di XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - L'array di XmpPackage all'interno di XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Ottiene il numero di pacchetti all'interno della struttura XMP.

**Returns:**
int - La quantità di pacchetti all'interno della struttura XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Ottiene l'elemento RDF radice.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Ottiene l'istruzione di elaborazione del trailer.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito in XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Rimuove il pacchetto XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Il pacchetto. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Imposta l'istruzione di elaborazione dell'intestazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | L'istruzione di elaborazione Header. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Imposta i metadati XMP. Facoltativo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | I metadati XMP. Facoltativo. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Imposta l'elemento RDF radice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | L'elemento radice RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Imposta l'istruzione di elaborazione del trailer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Istruzione di elaborazione Trailer. |

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


---
title: "XmpArray"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta Xmp Array in XmpPackage."
type: docs
weight: 12
url: /it/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Rappresenta Xmp Array in XmpPackage. todo: L'array può contenere dati complessi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Inizializza una nuova istanza della classe XmpArray. |
| [XmpArray(int type)](#XmpArray-int-) | Inizializza una nuova istanza della classe XmpArray. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Aggiunge un nuovo elemento. |
| [addItem(String item)](#addItem-java.lang.String-) | Aggiunge un nuovo elemento. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Ottiene l'array di valori all'interno di [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Ottiene l'array di valori all'interno di XmpArray. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce un  System.String  che rappresenta questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Inizializza una nuova istanza della classe XmpArray.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo dell'array. |
| elementi | java.lang.String[] | L'elenco degli elementi. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Inizializza una nuova istanza della classe XmpArray.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo dell'array. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Aggiunge un nuovo elemento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | L'elemento da aggiungere all'elenco degli elementi. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Aggiunge un nuovo elemento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elemento | java.lang.String | L'elemento da aggiungere all'elenco degli elementi. |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


Ottiene l'array di valori all'interno di [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Ottiene l'array di valori all'interno di XmpArray.

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
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


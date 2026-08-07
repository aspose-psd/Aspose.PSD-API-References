---
title: "DublinCorePackage"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta lo schema Dublin Core."
type: docs
weight: 10
url: /it/java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

Rappresenta lo schema Dublin Core.

Per ulteriori informazioni vedere: http://dublincore.org/documents/usageguide/elements.shtml.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | Inizializza una nuova istanza della classe  DublinCorePackage . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Aggiunge lo spazio dei nomi del tipo complesso. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Aggiunge la proprietà stringa. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Assegna il pacchetto XMP specificato a quello corrente. |
| [clear()](#clear--) | Cancella questa istanza. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Combina il pacchetto. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina se la chiave specificata contiene la chiave. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Ottiene le chiavi nel pacchetto XMP. |
| [getNamespaceUri()](#getNamespaceUri--) | Ottiene l'URI dello spazio dei nomi. |
| [getPrefix()](#getPrefix--) | Ottiene il prefisso. |
| [getXmlNamespace()](#getXmlNamespace--) | Ottiene lo spazio dei nomi XML. |
| [getXmlValue()](#getXmlValue--) | Converte il valore XMP nella rappresentazione XML. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Ottiene o imposta l'Object con la chiave specificata. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Rimuove il valore con la chiave specificata. |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Aggiunge l'autore. |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | Aggiunge l'autore. |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | Aggiunge la descrizione. |
| [setDescription(String desc)](#setDescription-java.lang.String-) | Aggiunge la descrizione. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | Aggiunge l'editore. |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | Aggiunge l'editore. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | Aggiunge l'argomento. |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | Aggiunge l'argomento. |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | Aggiunge il titolo Dublin Core per diverse lingue. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Aggiunge il titolo Dublin Core. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Imposta il valore. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Imposta il valore booleano XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Imposta l'identificatore univoco XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Imposta il valore di tipo XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Imposta l'  Object  con la chiave specificata. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


Inizializza una nuova istanza della classe  DublinCorePackage .

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Aggiunge lo spazio dei nomi del tipo complesso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typePrefix | java.lang.String | Il prefisso del tipo. |
| typeNamespaceUri | java.lang.String | L'URI dello spazio dei nomi del tipo. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Aggiunge la proprietà stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.String | Il valore stringa. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Assegna il pacchetto XMP specificato a quello corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Il pacchetto XMP. |

### clear() {#clear--}
```
public void clear()
```


Cancella questa istanza.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Combina il pacchetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | L'altro pacchetto da combinare. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determina se la chiave specificata contiene la chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La chiave da controllare. |

**Returns:**
boolean - Restituisce true se la chiave specificata contiene la chiave.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Clona questa istanza.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Ottiene le chiavi nel pacchetto XMP.

Valore: Le chiavi nel pacchetto XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ottiene l'URI dello spazio dei nomi.

Valore: L'URI dello spazio dei nomi.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ottiene il prefisso.

Valore: Il prefisso.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Ottiene lo spazio dei nomi XML.

Valore: Lo spazio dei nomi XML.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converte il valore XMP nella rappresentazione XML.

**Returns:**
java.lang.String - Restituisce il valore XMP convertito nella rappresentazione XML.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Ottiene o imposta l'Object con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La chiave che identifica il valore. |

**Returns:**
java.lang.Object - Restituisce l'  Object  con la chiave specificata.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Un  T:System.Collections.Generic.IEnumerator1  che può essere usato per iterare attraverso la collezione.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Rimuove il valore con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore rimosso. |

**Returns:**
boolean - Restituisce true se il valore con la chiave specificata è stato rimosso.
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Aggiunge l'autore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| autore | java.lang.String | L'autore. |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


Aggiunge l'autore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| autore | java.lang.String[] | L'autore. |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


Aggiunge la descrizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | La descrizione. |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


Aggiunge la descrizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| desc | java.lang.String | La descrizione. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


Aggiunge l'editore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| editore | java.lang.String | L'editore. |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


Aggiunge l'editore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| editore | java.lang.String[] | L'editore. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


Aggiunge l'argomento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argomento | java.lang.String | L'argomento. |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


Aggiunge l'argomento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argomento | java.lang.String[] | L'argomento. |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


Aggiunge il titolo Dublin Core per diverse lingue.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | Istanza di  LangAlt . |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Aggiunge il titolo Dublin Core.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| titolo | java.lang.String | Il titolo. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Imposta il valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | Il valore a cui aggiungere. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Imposta il valore booleano XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore impostato. |
| valoreBool | java.lang.String | Il valore booleano. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Imposta l'identificatore univoco XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore GUID impostato. |
| guid | java.lang.String | L'identificatore unico. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Imposta il valore di tipo XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | Il valore da impostare. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Imposta l'  Object  con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La chiave che identifica il valore. |
| valore | java.lang.Object | Il valore  Object  . |

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


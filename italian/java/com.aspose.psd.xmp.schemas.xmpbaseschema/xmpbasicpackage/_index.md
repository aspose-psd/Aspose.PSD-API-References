---
title: "XmpBasicPackage"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta lo spazio dei nomi base XMP."
type: docs
weight: 10
url: /it/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Rappresenta lo spazio dei nomi base XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Inizializza una nuova istanza della classe XmpBasicPackage. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe XmpBasicPackage. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [RatingMax](#RatingMax) | Valore massimo della valutazione. |
| [RatingMin](#RatingMin) | Valore minimo della valutazione. |
| [RatingRejected](#RatingRejected) | Valore rifiutato della valutazione. |
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
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Aggiunge la data di creazione della risorsa. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Aggiunge la data di creazione della risorsa. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Imposta lo strumento creatore. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Imposta l'identificatore. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Imposta l'etichetta. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Aggiunge la data dell'ultima modifica dei metadati. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Aggiunge la data dell'ultima modifica dei metadati. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Aggiunge la data dell'ultima modifica della risorsa. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Aggiunge la data dell'ultima modifica della risorsa. |
| [setRating(int choise)](#setRating-int-) | Imposta la valutazione. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Imposta il valore. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Imposta il valore booleano XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Imposta l'identificatore univoco XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Imposta il valore di tipo XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Ottiene o imposta l'Object con la chiave specificata. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Inizializza una nuova istanza della classe XmpBasicPackage.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Inizializza una nuova istanza della classe XmpBasicPackage.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |
| namespaceUri | java.lang.String | L'URI dello spazio dei nomi. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Valore massimo della valutazione.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Valore minimo della valutazione.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Valore rifiutato della valutazione.

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
| key | java.lang.String | La chiave che identifica il valore. Valore: L'Object. |

**Returns:**
java.lang.Object - Restituisce l'Object con la chiave specificata.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Aggiunge la data di creazione della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createdDate | java.lang.String | Data di creazione. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Aggiunge la data di creazione della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Data di creazione. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Imposta lo strumento creatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorTool | java.lang.String | Nome dello strumento. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Imposta l'identificatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| idenfifier | java.lang.String[] | L'idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Imposta l'etichetta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | java.lang.String | L'etichetta. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadataDate | java.lang.String | Data dei metadati. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Data dei metadati. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modifiedDate | java.lang.String | Data dell'ultima modifica. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Data dell'ultima modifica. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Imposta la valutazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scelta | int | Da -1 a 5 |

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


Ottiene o imposta l'Object con la chiave specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | La chiave che identifica il valore. Valore: L'Object. |
| valore | java.lang.Object |  |

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


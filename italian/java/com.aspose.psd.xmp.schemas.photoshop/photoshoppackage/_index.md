---
title: "PhotoshopPackage"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta lo spazio dei nomi di Adobe Photoshop."
type: docs
weight: 12
url: /it/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Rappresenta lo spazio dei nomi di Adobe Photoshop.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | Inizializza una nuova istanza della classe  PhotoshopPackage . |
## Campi

| Campo | Descrizione |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Valore massimo di urgenza. |
| [UrgencyMin](#UrgencyMin) | Valore minimo di urgenza. |
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
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Imposta la posizione degli autori. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Imposta lo scrittore della didascalia. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Imposta la categoria. |
| [setCity(String city)](#setCity-java.lang.String-) | Imposta la città. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Imposta la modalità colore. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Imposta il paese. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Imposta la data di creazione. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Imposta il credito. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Imposta gli antenati del documento. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Imposta il titolo. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Imposta la cronologia. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | Imposta il profilo ICC. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Imposta le istruzioni. |
| [setSource(String source)](#setSource-java.lang.String-) | Imposta la sorgente. |
| [setState(String state)](#setState-java.lang.String-) | Imposta lo stato. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Imposta le categorie supplementari. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | Imposta il riferimento di trasmissione. |
| [setUrgency(int urgency)](#setUrgency-int-) | Imposta l'urgenza. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Imposta il valore. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Imposta il valore booleano XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Imposta l'identificatore univoco XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Imposta il valore di tipo XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Imposta l'  Object  con la chiave specificata. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


Inizializza una nuova istanza della classe  PhotoshopPackage .

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Valore massimo di urgenza.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Valore minimo di urgenza.

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Imposta la posizione degli autori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| authorsPosition | java.lang.String | La posizione degli autori. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Imposta lo scrittore della didascalia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| captionWriter | java.lang.String | Il redattore della didascalia. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Imposta la categoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| category | java.lang.String | La categoria. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Imposta la città.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| city | java.lang.String | Il nome della città. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Imposta la modalità colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorMode | byte | La modalità colore. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Imposta il paese.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| country | java.lang.String | Il paese. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Imposta la data di creazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createdDate | java.util.Date | La data di creazione. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Imposta il credito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| credit | java.lang.String | Il credito. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Imposta gli antenati del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ancestors | java.lang.String[] | Gli antenati. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Imposta il titolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headline | java.lang.String | Il titolo. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Imposta la cronologia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| history | java.lang.String | La storia. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


Imposta il profilo ICC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iccProfile | java.lang.String | Il profilo icc. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Imposta le istruzioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| istruzioni | java.lang.String | Le istruzioni. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Imposta la sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origine | java.lang.String | L'origine. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Imposta lo stato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stato | java.lang.String | Lo stato. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Imposta le categorie supplementari.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| categorieSupplementari | java.lang.String[] | Le categorie supplementari. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


Imposta il riferimento di trasmissione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| riferimentoTrasmissione | java.lang.String | Il riferimento alla trasmissione. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Imposta l'urgenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | urgenza | int | L'urgenza. |

L'urgenza dovrebbe essere nell'intervallo da 1 a 8. |

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


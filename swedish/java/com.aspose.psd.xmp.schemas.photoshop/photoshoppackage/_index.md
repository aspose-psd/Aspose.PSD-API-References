---
title: "PhotoshopPackage"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar Adobe Photoshop-namnutrymme."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Representerar Adobe Photoshop-namnutrymme.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | Initierar en ny instans av klassen  PhotoshopPackage  . |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Maxvärde för brådska. |
| [UrgencyMin](#UrgencyMin) | Minvärde för brådska. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Lägger till namnrymden för komplex typ. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Lägger till strängegenskap. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Tilldelar det angivna XMP-paketet till det aktuella. |
| [clear()](#clear--) | Rensar denna instans. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Kombinerar paketet. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Avgör om den angivna nyckeln innehåller nyckeln. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Hämtar nycklarna i XMP-paketet. |
| [getNamespaceUri()](#getNamespaceUri--) | Hämtar namnrymdens URI. |
| [getPrefix()](#getPrefix--) | Hämtar prefixet. |
| [getXmlNamespace()](#getXmlNamespace--) | Hämtar XML-namnrymden. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP‑värdet till XML‑representationen. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Hämtar eller anger objektet med den angivna nyckeln. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Ta bort värdet med den angivna nyckeln. |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Ställer in författarens position. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Ställer in bildtextens författare. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Ställer in kategorin. |
| [setCity(String city)](#setCity-java.lang.String-) | Ställer in staden. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Ställer in färgläget. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Ställer in landet. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Ställer in skapelsedatum. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Ställer in krediten. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Ställer in dokumentets förfäder. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Ställer in rubriken. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Ställer in historiken. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | Ställer in ICC‑profilen. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Ställer in instruktionerna. |
| [setSource(String source)](#setSource-java.lang.String-) | Ställer in källan. |
| [setState(String state)](#setState-java.lang.String-) | Ställer in staten. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Ställer in kompletterande kategorier. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | Ställer in överföringsreferensen. |
| [setUrgency(int urgency)](#setUrgency-int-) | Ställer in brådskan. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Ställer in värdet. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Ställer in XMP:s booleska värde. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Ställer in XMP:s unika identifierare. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Ställer in XMP-typvärdet. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Ställer in  Object  med den angivna nyckeln. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


Initierar en ny instans av klassen  PhotoshopPackage  .

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Maxvärde för brådska.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Minvärde för brådska.

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Lägger till namnrymden för komplex typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typePrefix | java.lang.String | Typprefixet. |
| typeNamespaceUri | java.lang.String | Typnamnutrymmets URI. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Lägger till strängegenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.String | Strängvärdet. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Tilldelar det angivna XMP-paketet till det aktuella.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | XMP-paketet. |

### clear() {#clear--}
```
public void clear()
```


Rensar denna instans.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Kombinerar paketet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Det andra paketet att kombinera. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Avgör om den angivna nyckeln innehåller nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som ska kontrolleras. |

**Returns:**
boolean - Returnerar true om den angivna nyckeln innehåller nyckeln.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar nycklarna i XMP-paketet.

Värde: Nycklarna i XMP-paketet.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Hämtar namnrymdens URI.

Värde: Namnutrymmets URI.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Hämtar prefixet.

Värde: Prefixet.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Hämtar XML-namnrymden.

Värde: XML-namnutrymmet.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP‑värdet till XML‑representationen.

**Returns:**
java.lang.String - Returnerar XMP-värdet konverterat till XML-representationen.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Hämtar eller anger objektet med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som identifierar värdet. |

**Returns:**
java.lang.Object - Returnerar  Object  med den angivna nyckeln.
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


Returnerar en enumerator som itererar genom samlingen.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - En  T:System.Collections.Generic.IEnumerator1  som kan användas för att iterera genom samlingen.
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


Ta bort värdet med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med borttaget värde. |

**Returns:**
boolean - Returnerar true om värdet med den angivna nyckeln togs bort.
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Ställer in författarens position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| authorsPosition | java.lang.String | Författarnas position. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Ställer in bildtextens författare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| captionWriter | java.lang.String | Bildtextförfattaren. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Ställer in kategorin.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| category | java.lang.String | Kategorin. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Ställer in staden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| city | java.lang.String | Stadens namn. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Ställer in färgläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorMode | byte | Färgläget. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Ställer in landet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| country | java.lang.String | Landet. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Ställer in skapelsedatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createdDate | java.util.Date | Det skapade datumet. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Ställer in krediten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| credit | java.lang.String | Krediten. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Ställer in dokumentets förfäder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ancestors | java.lang.String[] | Förfäderna. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Ställer in rubriken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headline | java.lang.String | Rubriken. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Ställer in historiken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| history | java.lang.String | Historien. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


Ställer in ICC‑profilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| iccProfile | java.lang.String | ICC-profilen. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Ställer in instruktionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruktioner | java.lang.String | Instruktionerna. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Ställer in källan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| källa | java.lang.String | Källan. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Ställer in staten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tillstånd | java.lang.String | Tillståndet. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Ställer in kompletterande kategorier.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tilläggskategorier | java.lang.String[] | De tilläggskategorierna. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


Ställer in överföringsreferensen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| överföringsreferens | java.lang.String | Överföringsreferensen. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Ställer in brådskan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | brådska | int | Brådskan. |

Brådska bör ligga i intervallet 1 till 8. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Ställer in värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | Värdet att lägga till i. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Ställer in XMP:s booleska värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med angivet värde. |
| boolVärde | java.lang.String | Det booleska värdet. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Ställer in XMP:s unika identifierare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med angivet GUID‑värde. |
| guid | java.lang.String | Den unika identifieraren. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Ställer in XMP-typvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med angivet värde. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | Värdet att sätta till. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Ställer in  Object  med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som identifierar värdet. |
| värde | java.lang.Object | Objektvärdet. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


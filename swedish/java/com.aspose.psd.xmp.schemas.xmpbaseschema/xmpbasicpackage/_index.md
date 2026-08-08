---
title: "XmpBasicPackage"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar XMP basic-namnutrymme."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Representerar XMP basic-namnutrymme.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initierar en ny instans av klassen  XmpBasicPackage  . |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen  XmpBasicPackage  . |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RatingMax](#RatingMax) | Maxvärde för betyg. |
| [RatingMin](#RatingMin) | Minvärde för betyg. |
| [RatingRejected](#RatingRejected) | Avvisat värde för betyg. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Hämtar eller anger Object med den angivna nyckeln. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Ta bort värdet med den angivna nyckeln. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Lägger till resursens skapandedatum. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Lägger till resursens skapandedatum. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Anger skapandeverktyget. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Anger identifieraren. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Anger etiketten. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Lägger till metadata för senaste ändringsdatum. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Lägger till metadata för senaste ändringsdatum. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Lägger till resursens senast ändrade datum. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Lägger till resursens senast ändrade datum. |
| [setRating(int choise)](#setRating-int-) | Anger betyg. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Ställer in värdet. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Ställer in XMP:s booleska värde. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Ställer in XMP:s unika identifierare. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Ställer in XMP-typvärdet. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Hämtar eller anger Object med den angivna nyckeln. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initierar en ny instans av klassen  XmpBasicPackage  .

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initierar en ny instans av klassen  XmpBasicPackage  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |
| namespaceUri | java.lang.String | Namespace‑URI:n. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Maxvärde för betyg.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Minvärde för betyg.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Avvisat värde för betyg.

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


Hämtar eller anger Object med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som identifierar värdet. Värde: Object. |

**Returns:**
java.lang.Object – Returnerar Object med den angivna nyckeln.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Lägger till resursens skapandedatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createdDate | java.lang.String | Skapat datum. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Lägger till resursens skapandedatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Skapat datum. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Anger skapandeverktyget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorTool | java.lang.String | Namn på verktyg. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Anger identifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| idenfifier | java.lang.String[] | Den idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Anger etiketten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | java.lang.String | Etiketten. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Lägger till metadata för senaste ändringsdatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadataDate | java.lang.String | Metadata datum. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Lägger till metadata för senaste ändringsdatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Metadata datum. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Lägger till resursens senast ändrade datum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modifiedDate | java.lang.String | Senast ändrade datum. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Lägger till resursens senast ändrade datum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Senast ändrade datum. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Anger betyg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| choise | int | Från -1 till 5 |

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


Hämtar eller anger Object med den angivna nyckeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln som identifierar värdet. Värde: Object. |
| värde | java.lang.Object |  |

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


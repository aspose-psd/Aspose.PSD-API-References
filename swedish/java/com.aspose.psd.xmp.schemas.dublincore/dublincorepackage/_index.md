---
title: "DublinCorePackage"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar Dublin Core-schema."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

Representerar Dublin Core-schema.

För mer information, se: http://dublincore.org/documents/usageguide/elements.shtml.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | Initierar en ny instans av klassen  DublinCorePackage  . |
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
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Lägger till författaren. |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | Lägger till författaren. |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | Lägger till beskrivningen. |
| [setDescription(String desc)](#setDescription-java.lang.String-) | Lägger till beskrivningen. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | Lägger till utgivaren. |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | Lägger till utgivaren. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | Lägger till ämnet. |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | Lägger till ämnet. |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | Lägger till Dublin Core-titel för olika språk. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Lägger till Dublin Core-titel. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Ställer in värdet. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Ställer in XMP:s booleska värde. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Ställer in XMP:s unika identifierare. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Ställer in XMP-typvärdet. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Ställer in  Object  med den angivna nyckeln. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


Initierar en ny instans av klassen  DublinCorePackage  .

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
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Lägger till författaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| författare | java.lang.String | Författaren. |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


Lägger till författaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| författare | java.lang.String[] | Författaren. |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


Lägger till beskrivningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | Beskrivningen. |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


Lägger till beskrivningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beskrivning | java.lang.String | Beskrivningen. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


Lägger till utgivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utgivare | java.lang.String | Utgivaren. |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


Lägger till utgivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utgivare | java.lang.String[] | Utgivaren. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


Lägger till ämnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ämne | java.lang.String | Ämnet. |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


Lägger till ämnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ämne | java.lang.String[] | Ämnet. |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


Lägger till Dublin Core-titel för olika språk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | Instans av  LangAlt . |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Lägger till Dublin Core-titel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| titel | java.lang.String | Titeln. |

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


---
title: DublinCorePackage
second_title: Aspose.PSD for Java API Reference
description: Represents Dublic Core schema.
type: docs
weight: 10
url: /java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

Represents Dublic Core schema.

For more information see: http://dublincore.org/documents/usageguide/elements.shtml.
## Constructors

| Constructor | Description |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | Initializes a new instance of the  DublinCorePackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Adds the complex type namespace. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Adds string property. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Assigns the specified XMP package to current one. |
| [clear()](#clear--) | Clears this instance. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Combines the package. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether the specified key contains key. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Gets the keys in XMP package. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the namespace URI. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getXmlNamespace()](#getXmlNamespace--) | Gets the XML namespace. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets or sets the  Object  with the specified key. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Remove the value with the specified key. |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Adds the author. |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | Adds the author. |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | Adds the description. |
| [setDescription(String desc)](#setDescription-java.lang.String-) | Adds the description. |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | Adds the publisher. |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | Adds the publisher. |
| [setSubject(String subject)](#setSubject-java.lang.String-) | Adds the subject. |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | Adds the subject. |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | Adds Dublin Core title for different languages. |
| [setTitle(String title)](#setTitle-java.lang.String-) | Adds Dublin Core title. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Sets the value. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Sets the XMP boolean value. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Sets the XMP unique identifier. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Sets the XMP type value. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Sets the  Object  with the specified key. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


Initializes a new instance of the  DublinCorePackage  class.

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Adds the complex type namespace.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typePrefix | java.lang.String | The type prefix. |
| typeNamespaceUri | java.lang.String | The type namespace URI. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Adds string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.String | The string value. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Assigns the specified XMP package to current one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | The XMP package. |

### clear() {#clear--}
```
public void clear()
```


Clears this instance.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Combines the package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | The other package to combine. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determines whether the specified key contains key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key to be checked. |

**Returns:**
boolean - Returns true if the specified key contains key.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Clones this instance.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets the keys in XMP package.

Value: The keys in XMP package.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the namespace URI.

Value: The namespace URI.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

Value: The prefix.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Gets the XML namespace.

Value: The XML namespace.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Gets or sets the  Object  with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key that identifies value. |

**Returns:**
java.lang.Object - Returns the  Object  with the specified key.
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


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - A  T:System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.
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


Remove the value with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with removed value. |

**Returns:**
boolean - Returns true if the value with the specified key was removed.
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Adds the author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | java.lang.String | The author. |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


Adds the author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | java.lang.String[] | The author. |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


Adds the description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | The description. |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


Adds the description.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| desc | java.lang.String | The description. |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


Adds the publisher.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publisher | java.lang.String | The publisher. |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


Adds the publisher.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publisher | java.lang.String[] | The publisher. |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


Adds the subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String | The subject. |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


Adds the subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subject | java.lang.String[] | The subject. |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


Adds Dublin Core title for different languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | Instance of  LangAlt . |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Adds Dublin Core title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Sets the value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | The value to add to. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Sets the XMP boolean value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with set value. |
| boolValue | java.lang.String | The boolean value. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Sets the XMP unique identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with set GUID value. |
| guid | java.lang.String | The unique identifier. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Sets the XMP type value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | The value to set to. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Sets the  Object  with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key that identifies value. |
| value | java.lang.Object | The  Object  value. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


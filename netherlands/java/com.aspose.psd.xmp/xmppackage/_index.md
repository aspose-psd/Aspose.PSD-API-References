---
title: "XmpPackage"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt basisabstractie voor van XMP-pakket."
type: docs
weight: 18
url: /nl/java/com.aspose.psd.xmp/xmppackage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Stelt basisabstractie voor van XMP-pakket.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de  XmpPackage  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Voegt de complex type-namespace toe. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Voegt de waarde toe. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Wijst het opgegeven XMP-pakket toe aan het huidige. |
| [clear()](#clear--) | Wis deze instantie. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Combineert het pakket. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Bepaalt of de opgegeven sleutel de sleutel bevat. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Haalt de sleutels op in het XMP-pakket. |
| [getNamespaceUri()](#getNamespaceUri--) | Haalt de namespace-URI op. |
| [getPrefix()](#getPrefix--) | Haalt het voorvoegsel op. |
| [getXmlNamespace()](#getXmlNamespace--) | Haalt de XML-namespace op. |
| [getXmlValue()](#getXmlValue--) | Converteert XMP-waarde naar de XML-representatie. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Haalt op of stelt het  Object  in met de opgegeven sleutel. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Verwijder de waarde met de opgegeven sleutel. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Stelt de waarde in. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Stelt de XMP-booleanwaarde in. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Stelt de unieke XMP-identificatie in. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Stelt de XMP-typewaarde in. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Stelt het  Object  in met de opgegeven sleutel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Initialiseert een nieuw exemplaar van de  XmpPackage  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | java.lang.String | De prefix. |
| namespaceUri | java.lang.String | De namespace-URI. |

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Voegt de complex type-namespace toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typePrefix | java.lang.String | De type prefix. |
| typeNamespaceUri | java.lang.String | De type namespace URI. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Voegt de waarde toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is gekoppeld aan de toegevoegde waarde. |
| waarde | java.lang.String | De waarde om aan toe te voegen. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Wijst het opgegeven XMP-pakket toe aan het huidige.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Het XMP-pakket. |

### clear() {#clear--}
```
public void clear()
```


Wis deze instantie.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Combineert het pakket.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Het andere pakket om te combineren. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Bepaalt of de opgegeven sleutel de sleutel bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel die gecontroleerd moet worden. |

**Returns:**
boolean - Retourneert true als de opgegeven sleutel de sleutel bevat.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de sleutels op in het XMP-pakket.

Waarde: De sleutels in het XMP-pakket.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Haalt de namespace-URI op.

Waarde: De namespace URI.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Haalt het voorvoegsel op.

Waarde: De prefix.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Haalt de XML-namespace op.

Waarde: De XML namespace.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converteert XMP-waarde naar de XML-representatie.

**Returns:**
java.lang.String - Retourneert de XMP-waarde geconverteerd naar de XML-representatie.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Haalt op of stelt het  Object  in met de opgegeven sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel die de waarde identificeert. |

**Returns:**
java.lang.Object - Retourneert het  Object  met de opgegeven sleutel.
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


Retourneert een enumerator die door de collectie iterereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Een  T:System.Collections.Generic.IEnumerator1  die kan worden gebruikt om door de collectie te itereren.
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


Verwijder de waarde met de opgegeven sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De stringrepresentatie van de sleutel die is geïdentificeerd met de verwijderde waarde. |

**Returns:**
boolean - Retourneert true als de waarde met de opgegeven sleutel is verwijderd.
### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Stelt de waarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is gekoppeld aan de toegevoegde waarde. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | De waarde om aan toe te voegen. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Stelt de XMP-booleanwaarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| boolValue | java.lang.String | De booleaanse waarde. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Stelt de unieke XMP-identificatie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde GUID-waarde. |
| guid | java.lang.String | De unieke identificatie. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Stelt de XMP-typewaarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is geïdentificeerd met de ingestelde waarde. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | De waarde om in te stellen. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Stelt het  Object  in met de opgegeven sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel die de waarde identificeert. |
| waarde | java.lang.Object | De  Object  waarde. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


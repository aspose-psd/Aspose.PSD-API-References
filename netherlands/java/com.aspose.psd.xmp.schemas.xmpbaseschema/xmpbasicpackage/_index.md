---
title: "XmpBasicPackage"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt XMP-basisnaamruimte voor."
type: docs
weight: 10
url: /nl/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Stelt XMP-basisnaamruimte voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initialiseert een nieuw exemplaar van de  XmpBasicPackage  klasse. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de  XmpBasicPackage  klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [RatingMax](#RatingMax) | Maximumwaarde van Rating. |
| [RatingMin](#RatingMin) | Minimumwaarde van Rating. |
| [RatingRejected](#RatingRejected) | Afgewezen waarde van Rating. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Voegt de complex type-namespace toe. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Voegt een string-eigenschap toe. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Haalt op of stelt het Object in met de opgegeven sleutel. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Verwijder de waarde met de opgegeven sleutel. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Voegt de aanmaakdatum van de bron toe. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Voegt de aanmaakdatum van de bron toe. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Stelt de maker-tool in. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Stelt de identifier in. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Stelt het label in. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Voegt de datum van laatste wijziging van metadata toe. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Voegt de datum van laatste wijziging van metadata toe. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Voegt de datum van laatste wijziging van de bron toe. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Voegt de datum van laatste wijziging van de bron toe. |
| [setRating(int choise)](#setRating-int-) | Stelt rating in. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Stelt de waarde in. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Stelt de XMP-booleanwaarde in. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Stelt de unieke XMP-identificatie in. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Stelt de XMP-typewaarde in. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Haalt op of stelt het Object in met de opgegeven sleutel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initialiseert een nieuw exemplaar van de  XmpBasicPackage  klasse.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initialiseert een nieuw exemplaar van de  XmpBasicPackage  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | java.lang.String | De prefix. |
| namespaceUri | java.lang.String | De namespace-URI. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Maximumwaarde van Rating.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Minimumwaarde van Rating.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Afgewezen waarde van Rating.

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


Voegt een string-eigenschap toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De tekenreeksrepresentatie van de sleutel die is gekoppeld aan de toegevoegde waarde. |
| waarde | java.lang.String | De stringwaarde. |

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


Haalt op of stelt het Object in met de opgegeven sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel die de waarde identificeert. Waarde: Het Object. |

**Returns:**
java.lang.Object - Retourneert het Object met de opgegeven sleutel.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Voegt de aanmaakdatum van de bron toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createdDate | java.lang.String | Aanmaakdatum. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Voegt de aanmaakdatum van de bron toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Aanmaakdatum. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Stelt de maker-tool in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| creatorTool | java.lang.String | Naam van hulpmiddel. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Stelt de identifier in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idenfifier | java.lang.String[] | De idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Stelt het label in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | java.lang.String | Het label. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Voegt de datum van laatste wijziging van metadata toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| metadataDate | java.lang.String | Metadata datum. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Voegt de datum van laatste wijziging van metadata toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Metadata datum. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Voegt de datum van laatste wijziging van de bron toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| modifiedDate | java.lang.String | Laatste wijzigingsdatum. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Voegt de datum van laatste wijziging van de bron toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Laatste wijzigingsdatum. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Stelt rating in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keuze | int | Van -1 tot 5 |

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


Haalt op of stelt het Object in met de opgegeven sleutel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel die de waarde identificeert. Waarde: Het Object. |
| waarde | java.lang.Object |  |

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


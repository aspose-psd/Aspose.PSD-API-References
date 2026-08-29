---
title: "PhotoshopPackage"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt de Adobe Photoshop-namespace voor."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Stelt de Adobe Photoshop-namespace voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | Initialiseert een nieuw exemplaar van de PhotoshopPackage-klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Urgentie maximale waarde. |
| [UrgencyMin](#UrgencyMin) | Urgentie minimale waarde. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Haalt op of stelt het  Object  in met de opgegeven sleutel. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Verwijder de waarde met de opgegeven sleutel. |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Stelt de positie van de auteur in. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Stelt de bijschriftschrijver in. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Stelt de categorie in. |
| [setCity(String city)](#setCity-java.lang.String-) | Stelt de stad in. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Stelt de kleurmodus in. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Stelt het land in. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Stelt de aanmaakdatum in. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Stelt de credit in. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Stelt de documentvoorouders in. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Stelt de koptekst in. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Stelt de geschiedenis in. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | Stelt het ICC-profiel in. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Stelt de instructies in. |
| [setSource(String source)](#setSource-java.lang.String-) | Stelt de bron in. |
| [setState(String state)](#setState-java.lang.String-) | Stelt de staat in. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Stelt aanvullende categorieën in. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | Stelt de transmissieverwijzing in. |
| [setUrgency(int urgency)](#setUrgency-int-) | Stelt de urgentie in. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Stelt de waarde in. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Stelt de XMP-booleanwaarde in. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Stelt de unieke XMP-identificatie in. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Stelt de XMP-typewaarde in. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Stelt het  Object  in met de opgegeven sleutel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


Initialiseert een nieuw exemplaar van de PhotoshopPackage-klasse.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Urgentie maximale waarde.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Urgentie minimale waarde.

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Stelt de positie van de auteur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| authorsPosition | java.lang.String | De positie van de auteurs. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Stelt de bijschriftschrijver in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| captionWriter | java.lang.String | De ondertitel schrijver. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Stelt de categorie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| category | java.lang.String | De categorie. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Stelt de stad in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| city | java.lang.String | De naam van de stad. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Stelt de kleurmodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorMode | byte | De kleurmodus. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Stelt het land in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| country | java.lang.String | Het land. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Stelt de aanmaakdatum in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createdDate | java.util.Date | De aanmaakdatum. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Stelt de credit in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| credit | java.lang.String | De credit. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Stelt de documentvoorouders in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ancestors | java.lang.String[] | De voorouders. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Stelt de koptekst in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| headline | java.lang.String | De koptekst. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Stelt de geschiedenis in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| history | java.lang.String | De geschiedenis. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


Stelt het ICC-profiel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| iccProfile | java.lang.String | Het icc-profiel. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Stelt de instructies in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instructies | java.lang.String | De instructies. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Stelt de bron in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bron | java.lang.String | De bron. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Stelt de staat in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| status | java.lang.String | De status. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Stelt aanvullende categorieën in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | De aanvullende categorieën. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


Stelt de transmissieverwijzing in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| transmissionReference | java.lang.String | De transmissieverwijzing. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Stelt de urgentie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | urgency | int | De urgentie. |

Urgentie moet binnen een bereik van 1 tot 8 liggen. |

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


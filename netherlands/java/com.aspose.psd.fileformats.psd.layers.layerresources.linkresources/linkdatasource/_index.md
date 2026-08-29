---
title: "LinkDataSource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de LinkDataSource-klasse die informatie bevat over een gekoppeld bestand of een asset in het PSD-bestand."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource/
---

**Inheritance:**
java.lang.Object
```
public abstract class LinkDataSource
```

Definieert de LinkDataSource-klasse die informatie bevat over een gekoppeld bestand of een asset in het PSD-bestand.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | De descriptorversie. |
| [LatestVersion_internalized](#LatestVersion-internalized) | De laatst beschikbare versie van de linkgegevensbron |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | De onverwachte linkgegevensbron typewaarde |
| [ZeroChar_internalized](#ZeroChar-internalized) | Het nulteken |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Haalt een waarde op of stelt deze in die aangeeft of het PSD‑object vergrendeld is. |
| [getAssetModTime()](#getAssetModTime--) | Haalt de wijzigingstijd van het object op of stelt deze in, voor Adobe® Photoshop® \\u0421\\u0421 Libraries-objecten. |
| [getChildDocId()](#getChildDocId--) | Haalt de kinddocumentidentificatie op of stelt deze in in de liFE- of liFD-gegevensbron van de Lnk2 / LnkE Adobe® Photoshop®-resource. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Haalt de resourceklasse‑id op of stelt deze in. |
| [getClassName_internalized()](#getClassName-internalized--) | Haalt op of stelt de naam van de resourceklasse in. |
| [getCompId()](#getCompId--) | Haalt op of stelt de ID van de momenteel geselecteerde comp voor het onderliggende document in, die -1 zal zijn als er geen is geselecteerd. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Haalt op of stelt de eigenschap ContentID in. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Haalt de lengte van extra gegevens op. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Haalt de lengte van de linkbrongegevens op. |
| [getFileCreator()](#getFileCreator--) | Haalt op of stelt de maker van het bestand in de PSD‑formaat LnkE / Lnk2-resource in. |
| [getFileType()](#getFileType--) | Haalt op of stelt het type van het ingebedde of externe bestand in dat de Adobe® Photoshop® Lnk2 / LnkE-resource bevat of waarnaar gelinkt wordt. |
| [getItems_internalized()](#getItems-internalized--) | Haalt op of stelt een OSTypeStructure‑array in die resource‑eigenschappen definieert. |
| [getLength()](#getLength--) | Haalt de lengte van de linkgegevensbron in bytes op. |
| [getOriginalCompId()](#getOriginalCompId--) | Haalt de oorspronkelijke ID van de momenteel geselecteerde Comp voor het onderliggende document op, die -1 zal zijn als er geen is geselecteerd. |
| [getOriginalFileName()](#getOriginalFileName--) | Haalt de oorspronkelijke bestandsnaam van de gegevensbron in de Adobe® Photoshop® globale linkresource op. |
| [getType()](#getType--) | Haalt het type van de Adobe® Photoshop® globale linkgegevensbron op, dat een van de volgende kan zijn of geen: Het ingebedde gekoppelde bestand liFD dat overeenkomt met de PSD Lnk2Resource; Het externe gekoppelde bestand liFE dat overeenkomt met de PSD LnkeResource; Het alias van het gekoppelde bestand liFA. |
| [getUniqueId()](#getUniqueId--) | Haalt de wereldwijd unieke identifier van de gegevensbron in de PSD‑linkresource op. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Haalt op of stelt de onbekende gegevens in die vóór de Items OSTypeStructures‑eigenschappen komen. |
| [getVersion()](#getVersion--) | Haalt de versie van de gegevensbron in de PSD LnkE / Lnk2-resource op. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Haalt op of stelt een waarde in die aangeeft of deze linkgegevensbron de bestandsopen‑descriptor heeft: CompId en OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Haalt een waarde op die aangeeft of deze PSD‑linkgegevensbron linkt naar het Adobe® Photoshop® \u0421\u0421 Library‑item. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Slaat de blokgegevens van de linkgegevensbron op. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of het PSD‑object vergrendeld is. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Haalt de wijzigingstijd van het object op of stelt deze in, voor Adobe® Photoshop® \\u0421\\u0421 Libraries-objecten. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Haalt de kinddocumentidentificatie op of stelt deze in in de liFE- of liFD-gegevensbron van de Lnk2 / LnkE Adobe® Photoshop®-resource. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt de resourceklasse‑id op of stelt deze in. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Haalt op of stelt de naam van de resourceklasse in. |
| [setCompId(int value)](#setCompId-int-) | Haalt op of stelt de ID van de momenteel geselecteerde comp voor het onderliggende document in, die -1 zal zijn als er geen is geselecteerd. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Haalt op of stelt de eigenschap ContentID in. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Haalt op of stelt de maker van het bestand in de PSD‑formaat LnkE / Lnk2-resource in. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Haalt op of stelt een waarde in die aangeeft of deze linkgegevensbron de bestandsopen‑descriptor heeft: CompId en OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Haalt op of stelt het type van het ingebedde of externe bestand in dat de Adobe® Photoshop® Lnk2 / LnkE-resource bevat of waarnaar gelinkt wordt. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Haalt op of stelt een OSTypeStructure‑array in die resource‑eigenschappen definieert. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Haalt een waarde op die aangeeft of deze PSD‑linkgegevensbron linkt naar het Adobe® Photoshop® \u0421\u0421 Library‑item. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Haalt de oorspronkelijke ID van de momenteel geselecteerde Comp voor het onderliggende document op, die -1 zal zijn als er geen is geselecteerd. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Haalt de oorspronkelijke bestandsnaam van de gegevensbron in de Adobe® Photoshop® globale linkresource op. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Stelt de eigenschapswaarde in op type-structuur. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Haalt de wereldwijd unieke identifier van de gegevensbron in de PSD‑linkresource op. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Haalt op of stelt de onbekende gegevens in die vóór de Items OSTypeStructures‑eigenschappen komen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


De descriptorversie.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


De laatst beschikbare versie van de linkgegevensbron

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


De onverwachte linkgegevensbron typewaarde

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Het nulteken

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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Haalt een waarde op of stelt deze in die aangeeft of het PSD‑object vergrendeld is. De vergrendelde status van het object, voor Adobe® Photoshop® \u0421\u0421 Libraries‑objecten.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Haalt de wijzigingstijd van het object op of stelt deze in, voor Adobe® Photoshop® \\u0421\\u0421 Libraries-objecten.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Haalt de kinddocumentidentificatie op of stelt deze in in de liFE- of liFD-gegevensbron van de Lnk2 / LnkE Adobe® Photoshop®-resource.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Haalt de resourceklasse‑id op of stelt deze in.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Haalt op of stelt de naam van de resourceklasse in.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Haalt de ID op of stelt deze in van de momenteel geselecteerde comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd. Comps zijn composities van een paginalay-out die ontwerpers kunnen maken. Met layer comps kun je meerdere versies van een lay-out maken, beheren en bekijken in één Adobe® Photoshop®‑bestand. Een layer comp is een momentopname van een toestand van het Layers‑paneel. Layer comps slaan drie soorten laagopties op, maar deze eigenschap haalt de Layer Comp‑selectie‑identifier op voor Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Haalt de ContentID‑eigenschap op of stelt deze in. De waarde van deze eigenschap wordt alleen gelezen en opgeslagen wanneer Versie >= 8 is.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Haalt de lengte van extra gegevens op.

Waarde: De lengte van de gegevens.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Haalt de lengte van de linkbrongegevens op.

**Returns:**
long - De lengte van de brongegevens.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Haalt op of stelt de maker van het bestand in de PSD‑formaat LnkE / Lnk2-resource in.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Haalt op of stelt het type van het ingebedde of externe bestand in dat de Adobe® Photoshop® Lnk2 / LnkE-resource bevat of waarnaar gelinkt wordt.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Haalt op of stelt een OSTypeStructure‑array in die resource‑eigenschappen definieert.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Haalt de lengte van de linkgegevensbron in bytes op.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Haalt de originele ID op van de momenteel geselecteerde Comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd. Deze eigenschap haalt de originele layer Comp‑selectie‑identifier op voor Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Haalt de oorspronkelijke bestandsnaam van de gegevensbron in de Adobe® Photoshop® globale linkresource op.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Haalt het type van de Adobe® Photoshop® globale linkgegevensbron op, dat een van de volgende kan zijn of geen: Het ingebedde gekoppelde bestand liFD dat overeenkomt met de PSD Lnk2Resource; Het externe gekoppelde bestand liFE dat overeenkomt met de PSD LnkeResource; Het alias van het gekoppelde bestand liFA.

Waarde: Het type van de PSD‑koppelings‑datasource.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Haalt de wereldwijd unieke identifier van de gegevensbron in de PSD‑linkresource op.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Haalt op of stelt de onbekende gegevens in die vóór de Items OSTypeStructures‑eigenschappen komen.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt de versie van de gegevensbron in de PSD LnkE / Lnk2-resource op.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Haalt op of stelt een waarde in die aangeeft of deze linkgegevensbron de bestandsopen‑descriptor heeft: CompId en OriginalCompId.

Waarde:  true  als deze instantie een open bestandsdescriptor heeft; anders,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Haalt een waarde op die aangeeft of deze PSD‑linkgegevensbron linkt naar het Adobe® Photoshop® \u0421\u0421 Library‑item.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Slaat de blokgegevens van de linkgegevensbron op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om naar op te slaan. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of het PSD‑object vergrendeld is. De vergrendelde status van het object, voor Adobe® Photoshop® \u0421\u0421 Libraries‑objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Haalt de wijzigingstijd van het object op of stelt deze in, voor Adobe® Photoshop® \\u0421\\u0421 Libraries-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Haalt de kinddocumentidentificatie op of stelt deze in in de liFE- of liFD-gegevensbron van de Lnk2 / LnkE Adobe® Photoshop®-resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Haalt de resourceklasse‑id op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Haalt op of stelt de naam van de resourceklasse in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Haalt de ID op of stelt deze in van de momenteel geselecteerde comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd. Comps zijn composities van een paginalay-out die ontwerpers kunnen maken. Met layer comps kun je meerdere versies van een lay-out maken, beheren en bekijken in één Adobe® Photoshop®‑bestand. Een layer comp is een momentopname van een toestand van het Layers‑paneel. Layer comps slaan drie soorten laagopties op, maar deze eigenschap haalt de Layer Comp‑selectie‑identifier op voor Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Haalt de ContentID‑eigenschap op of stelt deze in. De waarde van deze eigenschap wordt alleen gelezen en opgeslagen wanneer Versie >= 8 is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Haalt op of stelt de maker van het bestand in de PSD‑formaat LnkE / Lnk2-resource in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of deze linkgegevensbron de bestandsopen‑descriptor heeft: CompId en OriginalCompId.

Waarde:  true  als deze instantie een open bestandsdescriptor heeft; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Haalt op of stelt het type van het ingebedde of externe bestand in dat de Adobe® Photoshop® Lnk2 / LnkE-resource bevat of waarnaar gelinkt wordt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Haalt op of stelt een OSTypeStructure‑array in die resource‑eigenschappen definieert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Haalt een waarde op die aangeeft of deze PSD‑linkgegevensbron linkt naar het Adobe® Photoshop® \u0421\u0421 Library‑item.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Haalt de originele ID op van de momenteel geselecteerde Comp voor het onderliggende document, die -1 zal zijn als er geen is geselecteerd. Deze eigenschap haalt de originele layer Comp‑selectie‑identifier op voor Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Haalt de oorspronkelijke bestandsnaam van de gegevensbron in de Adobe® Photoshop® globale linkresource op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Stelt de eigenschapswaarde in op type-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De structuur. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Haalt de wereldwijd unieke identifier van de gegevensbron in de PSD‑linkresource op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Haalt op of stelt de onbekende gegevens in die vóór de Items OSTypeStructures‑eigenschappen komen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

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


---
title: "CustResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Klasse CustResource."
type: docs
weight: 27
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class CustResource extends LayerResource
```

Klasse CustResource. Deze resource bevat informatie over het mengen van een bijgesneden element.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CustResource()](#CustResource--) | Initialiseert een nieuw exemplaar van de [CustResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/custresource) klasse. |
| [CustResource(byte[] data)](#CustResource-byte---) | Initialiseert een nieuw exemplaar van de [CustResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/custresource) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | De PSB-headerversie |
| [PsbResourceSignature](#PsbResourceSignature) | De PSB-specifieke resourcehandtekening. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | De PSD-headerversie |
| [ResourceSignature](#ResourceSignature) | De algemene resourcehandtekening. |
| [TypeToolKey](#TypeToolKey) | De typegereedschap-informatiesleutel. |
| [ventureLicense_internalized](#ventureLicense-internalized) | De venture-licentie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Controleert en stelt in of de resource PSB-specifiek is. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLayerCreatedDateTime()](#getLayerCreatedDateTime--) | Haalt op of stelt de aanmaakdatum van de laag in. |
| [getLayerCreatedDateTime_internalized()](#getLayerCreatedDateTime-internalized--) |  |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Haalt de eigenschapswaarde op volgens type-structuur. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD-versie op die vereist is voor de laagresource. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat de resource op in de opgegeven streamcontainer. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setClassNameAndId_internalized(String className, ClassID classID)](#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Stelt de klassenaam en identifier in. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setLayerCreatedDateTime(Date value)](#setLayerCreatedDateTime-java.util.Date-) | Haalt op of stelt de aanmaakdatum van de laag in. |
| [setLayerCreatedDateTime_internalized(System.DateTime value)](#setLayerCreatedDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Stelt de eigenschapswaarde in op type-structuur. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustResource() {#CustResource--}
```
public CustResource()
```


Initialiseert een nieuw exemplaar van de [CustResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/custresource) klasse.

### CustResource(byte[] data) {#CustResource-byte---}
```
public CustResource(byte[] data)
```


Initialiseert een nieuw exemplaar van de [CustResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/custresource) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De gegevens van de bron. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


De PSB-headerversie

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


De PSB-specifieke resourcehandtekening.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


De PSD-headerversie

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


De algemene resourcehandtekening.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


De typegereedschap-informatiesleutel.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


De venture-licentie.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Controleert en stelt in of de resource PSB‑specifiek is. Sommige resources worden momenteel niet herkend, maar we hebben een volledige lijst van PSB‑specifieke resources die hun gedrag bij het opslaan wijzigen. Dus moeten we dit ten minste in UnknownResource controleren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | int | De sleutel. |

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
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Haalt op of stelt de header in.

Waarde: de header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Haalt de laagresource‑sleutel op.

**Returns:**
int
### getLayerCreatedDateTime() {#getLayerCreatedDateTime--}
```
public final Date getLayerCreatedDateTime()
```


Haalt op of stelt de aanmaakdatum van de laag in.

Waarde: De aanmaakdatum van de laag.

**Returns:**
java.util.Date
### getLayerCreatedDateTime_internalized() {#getLayerCreatedDateTime-internalized--}
```
public final System.DateTime getLayerCreatedDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Haalt de prefixlengte op. Standaardwaarde is 12 voor 8BIM‑resources en 16 voor 8B64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| psdVersion | int | De PSD-versie. |

**Returns:**
int - De prefixlengte.
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Haalt de eigenschapswaarde op via type-structuur. Alleen gebruikt voor UnitTests.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| structureName | java.lang.String | Naam van de structuur. |

**Returns:**
java.lang.Object - OSType-structuur voor eenvoudige unit-testing
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Haalt de minimale PSD‑versie op die vereist is voor layer‑resource. 0 geeft geen beperkingen aan.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bepaalt of de resource PSB-specifiek is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | int | De resource‑sleutel. |

**Returns:**
boolean -  true  als de resource PSB‑specifiek is; anders,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is.

Waarde:  true  als deze instantie PSB‑specifieke resource is; anders,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Slaat de resource op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De streamcontainer om naar op te slaan. |
| psdVersion | int | De PSD-versie. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Slaat de aangepaste resource‑header op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| handtekening | int | De handtekening. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Slaat de headerhandtekening, identifier en lengte op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
| handtekening | int | De handtekening. |
| isLengthLong | boolean | als ingesteld op  true  is de lengte lang. |

### setClassNameAndId_internalized(String className, ClassID classID) {#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassNameAndId_internalized(String className, ClassID classID)
```


Stelt de klassenaam en identifier in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| className | java.lang.String | Naam van de klasse. |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | De klasse-identificatie. |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Haalt op of stelt de header in.

Waarde: de header.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setLayerCreatedDateTime(Date value) {#setLayerCreatedDateTime-java.util.Date-}
```
public final void setLayerCreatedDateTime(Date value)
```


Haalt op of stelt de aanmaakdatum van de laag in.

Waarde: De aanmaakdatum van de laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### setLayerCreatedDateTime_internalized(System.DateTime value) {#setLayerCreatedDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreatedDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.DateTime |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Stelt de eigenschapswaarde in op type-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De structuur. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een String die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een String die deze instantie vertegenwoordigt.
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


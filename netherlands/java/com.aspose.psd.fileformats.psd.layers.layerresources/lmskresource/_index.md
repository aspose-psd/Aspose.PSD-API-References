---
title: "LmskResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De LMsk resource."
type: docs
weight: 50
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

De LMsk resource.

--------------------

Deze bron bevat een kleurruimte‑ID, die verwijst naar een specifiek kleurruimtetype, en 4 kleurcomponenten. Afhankelijk van de ID hebben de kleurcomponenten verschillende betekenissen. Als het kleurruimtetype geen vier waarden vereist, zijn de extra componenten ongedefinieerd en worden altijd als nullen weggeschreven. Kleurcomponenten per kleurruimtetype: RGB - de eerste drie componenten zijn rood, groen en blauw. HSB - de eerste drie componenten zijn tint, verzadiging en helderheid. CMYK - de vier componenten zijn cyaan, magenta, geel en zwart. Lab - de eerste drie componenten zijn lichtheid, a‑chrominantie en b‑chrominantie. Grijswaarden - de eerste component is de grijswaarde, van 0...10000.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LmskResource()](#LmskResource--) | Initialiseert een nieuw exemplaar van de [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) klasse. |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | Haalt de kleurcomponent 1 op. |
| [getColorComponent2()](#getColorComponent2--) | Haalt de kleurcomponent 2 op. |
| [getColorComponent3()](#getColorComponent3--) | Haalt de kleurcomponent 3 op. |
| [getColorComponent4()](#getColorComponent4--) | Haalt de kleurcomponent 4 op. |
| [getColorSpace()](#getColorSpace--) | Haalt de kleurruimte op. |
| [getFlag()](#getFlag--) | Haalt de vlag op. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getOpacity()](#getOpacity--) | Haalt de dekking op. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
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
| [setColorComponent1(int value)](#setColorComponent1-int-) | Haalt de kleurcomponent 1 op. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | Haalt de kleurcomponent 2 op. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | Haalt de kleurcomponent 3 op. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | Haalt de kleurcomponent 4 op. |
| [setColorSpace(int value)](#setColorSpace-int-) | Haalt de kleurruimte op. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setOpacity(short value)](#setOpacity-short-) | Haalt de dekking op. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


Initialiseert een nieuw exemplaar van de [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) klasse.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


Haalt de kleurcomponent 1 op.

Waarde: De kleurcomponent 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


Haalt de kleurcomponent 2 op.

Waarde: De kleurcomponent 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


Haalt de kleurcomponent 3 op.

Waarde: De kleurcomponent 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


Haalt de kleurcomponent 4 op.

Waarde: De kleurcomponent 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


Haalt de kleurruimte op.

Waarde: de kleurenruimte.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


Haalt de vlag op.

Waarde: De vlag.

**Returns:**
byte
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
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


Haalt de dekking op.

Waarde: De dekking.

**Returns:**
short
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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


Haalt de kleurcomponent 1 op.

Waarde: De kleurcomponent 1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


Haalt de kleurcomponent 2 op.

Waarde: De kleurcomponent 2.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


Haalt de kleurcomponent 3 op.

Waarde: De kleurcomponent 3.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


Haalt de kleurcomponent 4 op.

Waarde: De kleurcomponent 4.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


Haalt de kleurruimte op.

Waarde: de kleurenruimte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


Haalt de dekking op.

Waarde: De dekking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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


---
title: "BritResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Klasse BritResource."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BritResource extends AdjustmentLayerResource
```

Klasse BritResource. Resource van de helderheid/contrast‑aanpassingslaag.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BritResource()](#BritResource--) | Initialiseert een nieuw exemplaar van de [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource)‑klasse. |
| [BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor)](#BritResource-short-short-short-boolean-) | Initialiseert een nieuw exemplaar van de [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource)‑klasse. |
| [BritResource(byte[] bytes)](#BritResource-byte---) | Initialiseert een nieuw exemplaar van de [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource)‑klasse. |
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
| [getBrightness()](#getBrightness--) | Geeft of stelt de helderheid in. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Haalt het contrast op of stelt dit in. |
| [getData()](#getData--) | Haalt op of stelt de gegevens in. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLabColor()](#getLabColor--) | Haalt een waarde op of stelt deze in die aangeeft of [lab color]. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Haalt op of stelt de gemiddelde waarde voor helderheid en contrast in. |
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
| [setBrightness(short value)](#setBrightness-short-) | Geeft of stelt de helderheid in. |
| [setContrast(short value)](#setContrast-short-) | Haalt het contrast op of stelt dit in. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [lab color]. |
| [setMeanValueForBrightnessAndContrast(short value)](#setMeanValueForBrightnessAndContrast-short-) | Haalt op of stelt de gemiddelde waarde voor helderheid en contrast in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BritResource() {#BritResource--}
```
public BritResource()
```


Initialiseert een nieuw exemplaar van de [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource)‑klasse.

### BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor) {#BritResource-short-short-short-boolean-}
```
public BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor)
```


Initialiseert een nieuw exemplaar van de [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource)‑klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| helderheid | short | De helderheid. |
| contrast | short | Het contrast. |
| meanValueForBrightnessAndContrast | short | De gemiddelde waarde voor helderheid en contrast. |
| labColor | boolean | indien ingesteld op  true  [lab color]. |

### BritResource(byte[] bytes) {#BritResource-byte---}
```
public BritResource(byte[] bytes)
```


Initialiseert een nieuw exemplaar van de [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource)‑klasse. De PSD‑formaatspecificatie bevat de volgende beschrijving: 2 Helderheid 2 Contrast 2 Gemiddelde waarde voor helderheid en contrast 1 Alleen Lab‑kleur. Het wordt niet gebruikt in moderne PSD (CS5 en hoger) waar CgEd wordt gebruikt. CgEd slaat informatieve eigenschappen op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | byte[] | De bytes. |

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
### getBrightness() {#getBrightness--}
```
public final short getBrightness()
```


Geeft of stelt de helderheid in.

Waarde: De helderheid.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final short getContrast()
```


Haalt het contrast op of stelt dit in.

Waarde: het contrast.

**Returns:**
short
### getData() {#getData--}
```
public final byte[] getData()
```


Haalt op of stelt de gegevens in.

Waarde: De gegevens.

**Returns:**
byte[]
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
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Haalt een waarde op of stelt deze in die aangeeft of [lab color].

Waarde:  true  als [lab color]; anders,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final short getMeanValueForBrightnessAndContrast()
```


Haalt op of stelt de gemiddelde waarde voor helderheid en contrast in.

Waarde: De gemiddelde waarde voor helderheid en contrast.

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

### setBrightness(short value) {#setBrightness-short-}
```
public final void setBrightness(short value)
```


Geeft of stelt de helderheid in.

Waarde: De helderheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setContrast(short value) {#setContrast-short-}
```
public final void setContrast(short value)
```


Haalt het contrast op of stelt dit in.

Waarde: het contrast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [lab color].

Waarde:  true  als [lab color]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMeanValueForBrightnessAndContrast(short value) {#setMeanValueForBrightnessAndContrast-short-}
```
public final void setMeanValueForBrightnessAndContrast(short value)
```


Haalt op of stelt de gemiddelde waarde voor helderheid en contrast in.

Waarde: De gemiddelde waarde voor helderheid en contrast.

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


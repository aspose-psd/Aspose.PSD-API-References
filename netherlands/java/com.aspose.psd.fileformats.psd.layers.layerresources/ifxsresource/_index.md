---
title: "IfxsResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Ifxs resourcegroep laag-effecten resource"
type: docs
weight: 37
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/basefxresource)
```
public final class IfxsResource extends BaseFxResource
```

Ifxs resource (groepslaag-effecten resource)
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [IfxsResource()](#IfxsResource--) | Initialiseert een nieuw exemplaar van de [IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource) klasse. |
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
| [fillDefaultStructs_internalized(BaseFxResource fxResource, boolean isMultiStructure)](#fillDefaultStructs-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource-boolean-) | Vult structuur met standaardstructuren |
| [findResourceForTest_internalized(int type)](#findResourceForTest-internalized-int-) | Vindt de effectentiteit. |
| [generateDefaultResource_internalized()](#generateDefaultResource-internalized--) | Genereert de standaardresource. |
| [getClass()](#getClass--) |  |
| [getDefaultListStructure_internalized(int multiType, int type, boolean isMultiStructure)](#getDefaultListStructure-internalized-int-int-boolean-) | Maakt een nieuw exemplaar van [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) gebaseerd op LayerMultiEffectsTypes met standaard effectstructuren. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Haalt de descriptorversie op. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLayerStyle_internalized()](#getLayerStyle-internalized--) | Haalt de laagstijl op of stelt deze in. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
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
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setLayerStyle_internalized(LayerStyleFX value)](#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-) | Haalt de laagstijl op of stelt deze in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [update_internalized()](#update-internalized--) | Werkt dit exemplaar bij. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IfxsResource() {#IfxsResource--}
```
public IfxsResource()
```


Initialiseert een nieuw exemplaar van de [IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource) klasse.

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
### fillDefaultStructs_internalized(BaseFxResource fxResource, boolean isMultiStructure) {#fillDefaultStructs-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.BaseFxResource-boolean-}
```
public static void fillDefaultStructs_internalized(BaseFxResource fxResource, boolean isMultiStructure)
```


Vult structuur met standaardstructuren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fxResource | [BaseFxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/basefxresource) | Elke effectresource |
| isMultiStructure | boolean | Vlag voor gebruik van multi-structuurklasse |

### findResourceForTest_internalized(int type) {#findResourceForTest-internalized-int-}
```
public final IEffectEntity findResourceForTest_internalized(int type)
```


Vindt de effectentiteit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity - Retourneert de effectentiteit.
### generateDefaultResource_internalized() {#generateDefaultResource-internalized--}
```
public static IfxsResource generateDefaultResource_internalized()
```


Genereert de standaardresource.

**Returns:**
[IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource) - Generated default [IfxsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ifxsresource)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultListStructure_internalized(int multiType, int type, boolean isMultiStructure) {#getDefaultListStructure-internalized-int-int-boolean-}
```
public static ListStructure getDefaultListStructure_internalized(int multiType, int type, boolean isMultiStructure)
```


Maakt een nieuw exemplaar van [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) gebaseerd op LayerMultiEffectsTypes met standaard effectstructuren. Als isMultiStructure true is, zal de structuur Multi zijn, anders Simple.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| multiType | int | Het multi-type van effect. |
| type | int | Het type effect. |
| isMultiStructure | boolean | Vlag voor gebruik van multi-structuurklasse |

**Returns:**
[ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) - The new instance of [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) based on LayerMultiEffectsTypes with default effect structures.
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Haalt de descriptorversie op.

Waarde: De descriptorversie.

**Returns:**
int
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
### getLayerStyle_internalized() {#getLayerStyle-internalized--}
```
public final LayerStyleFX getLayerStyle_internalized()
```


Haalt de laagstijl op of stelt deze in.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX
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

### setLayerStyle_internalized(LayerStyleFX value) {#setLayerStyle-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX-}
```
public final void setLayerStyle_internalized(LayerStyleFX value)
```


Haalt de laagstijl op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.internal.fileformats.psd.layers.layereffects.LayerStyleFX |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een String die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een String die deze instantie vertegenwoordigt.
### update_internalized() {#update-internalized--}
```
public final void update_internalized()
```


Werk deze instantie bij. TODO: Verwijder deze methode. Bijwerken moet automatisch gebeuren.

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


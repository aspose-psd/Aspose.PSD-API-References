---
title: "BlwhResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De BlwhResource-klasse is een resource van de Zwart-wit-aanpassingslaag."
type: docs
weight: 15
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

De BlwhResource-klasse is een resource van de Zwart-wit-aanpassingslaag.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Initialiseert een nieuw exemplaar van de [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) klasse. |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Haalt of stelt de bestandsnaam van de zwart-wit preset in. |
| [getBlues()](#getBlues--) | Haalt of stelt de blauwe waarde in. |
| [getBwPresetKind()](#getBwPresetKind--) | Haalt of stelt de waarde van het type zwart-wit preset in. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Haalt of stelt de cyaanwaarde in. |
| [getData()](#getData--) | Haalt op of stelt de gegevens in. |
| [getGreens()](#getGreens--) | Haalt of stelt de groene waarde in. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getMagentas()](#getMagentas--) | Haalt of stelt de magentawaarde in. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD-versie op die vereist is voor de laagresource. |
| [getReds()](#getReds--) | Haalt of stelt de rode waarde in. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [getTintColor()](#getTintColor--) | Haalt de ARGB‑tintkleur op. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Haalt of stelt de dubbele waarde van de blauwe tintkleur in. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Haalt of stelt de dubbele waarde van de groene tintkleur in. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Haalt of stelt de dubbele waarde van de rode tintkleur in. |
| [getUseTint()](#getUseTint--) | Haalt of stelt een waarde in die aangeeft of [tint color] wordt gebruikt. |
| [getYellows()](#getYellows--) | Haalt of stelt de gele waarde in. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat de resource op in de opgegeven streamcontainer. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Haalt of stelt de bestandsnaam van de zwart-wit preset in. |
| [setBlues(int value)](#setBlues-int-) | Haalt of stelt de blauwe waarde in. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Haalt of stelt de waarde van het type zwart-wit preset in. |
| [setCyans(int value)](#setCyans-int-) | Haalt of stelt de cyaanwaarde in. |
| [setGreens(int value)](#setGreens-int-) | Haalt of stelt de groene waarde in. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setMagentas(int value)](#setMagentas-int-) | Haalt of stelt de magentawaarde in. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Stelt de eigenschapswaarde in op type-structuur. |
| [setReds(int value)](#setReds-int-) | Haalt of stelt de rode waarde in. |
| [setTintColor(int value)](#setTintColor-int-) | Stelt de tintkleur in. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Haalt of stelt de dubbele waarde van de blauwe tintkleur in. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Haalt of stelt de dubbele waarde van de groene tintkleur in. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Haalt of stelt de dubbele waarde van de rode tintkleur in. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Haalt of stelt een waarde in die aangeeft of [tint color] wordt gebruikt. |
| [setYellows(int value)](#setYellows-int-) | Haalt of stelt de gele waarde in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Initialiseert een nieuw exemplaar van de [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) klasse.

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Haalt of stelt de bestandsnaam van de zwart-wit preset in.

Waarde: De bestandsnaam van de zwart-wit preset.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Haalt of stelt de blauwe waarde in.

Waarde: De blauwe waarde.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Haalt of stelt de waarde van het type zwart-wit preset in.

Waarde: De waarde van het type zwart-wit preset.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Haalt of stelt de cyaanwaarde in.

Waarde: De cyaanwaarde.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Haalt op of stelt de gegevens in.

Waarde: De gegevens.

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Haalt of stelt de groene waarde in.

Waarde: De groene waarde.

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
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Haalt of stelt de magentawaarde in.

Waarde: De magentawaarde.

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
### getReds() {#getReds--}
```
public final int getReds()
```


Haalt of stelt de rode waarde in.

Waarde: De rode waarde.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Haalt de ARGB‑tintkleur op.

**Returns:**
int - De ARGB‑tintkleur.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Haalt of stelt de dubbele waarde van de blauwe tintkleur in.

Waarde: De dubbele waarde van de blauwe tintkleur.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Haalt of stelt de dubbele waarde van de groene tintkleur in.

Waarde: De groene tintkleur double-waarde.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Haalt of stelt de dubbele waarde van de rode tintkleur in.

Waarde: De rode tintkleur double-waarde.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Haalt of stelt een waarde in die aangeeft of [tint color] wordt gebruikt.

Waarde:  true  als [tint color] wordt gebruikt; anders,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Haalt of stelt de gele waarde in.

Waarde: De gele waarde.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Haalt of stelt de bestandsnaam van de zwart-wit preset in.

Waarde: De bestandsnaam van de zwart-wit preset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Haalt of stelt de blauwe waarde in.

Waarde: De blauwe waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Haalt of stelt de waarde van het type zwart-wit preset in.

Waarde: De waarde van het type zwart-wit preset.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Haalt of stelt de cyaanwaarde in.

Waarde: De cyaanwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Haalt of stelt de groene waarde in.

Waarde: De groene waarde.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Haalt of stelt de magentawaarde in.

Waarde: De magentawaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Stelt de eigenschapswaarde in op type-structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De structuur. |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Haalt of stelt de rode waarde in.

Waarde: De rode waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Stelt de tintkleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De waarde. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Haalt of stelt de dubbele waarde van de blauwe tintkleur in.

Waarde: De dubbele waarde van de blauwe tintkleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Haalt of stelt de dubbele waarde van de groene tintkleur in.

Waarde: De groene tintkleur double-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Haalt of stelt de dubbele waarde van de rode tintkleur in.

Waarde: De rode tintkleur double-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Haalt of stelt een waarde in die aangeeft of [tint color] wordt gebruikt.

Waarde:  true  als [tint color] wordt gebruikt; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Haalt of stelt de gele waarde in.

Waarde: De gele waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


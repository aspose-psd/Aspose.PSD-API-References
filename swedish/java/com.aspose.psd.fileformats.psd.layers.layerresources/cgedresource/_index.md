---
title: "CgEdResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Klassen CgEdResource."
type: docs
weight: 18
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CgEdResource extends AdjustmentLayerResource
```

Klass CgEdResource. Content Generator Extra Data (Photoshop CS5)
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CgEdResource()](#CgEdResource--) | Initierar en ny instans av klassen [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [TypeToolKey](#TypeToolKey) | Nyckeln för typverktygsinformation. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuto()](#getAuto--) | Hämtar eller anger ett värde som indikerar om denna [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) är automatisk. |
| [getBrightness()](#getBrightness--) | Hämtar eller anger ljusstyrkan. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Hämtar eller anger kontrasten. |
| [getData()](#getData--) | Hämtar eller anger data. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLabColor()](#getLabColor--) | Hämtar eller anger ett värde som indikerar om [lab color] används. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Hämtar egenskapsvärdet enligt typstruktur. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getUseLegacy()](#getUseLegacy--) | Hämtar eller anger ett värde som indikerar om [use legacy]. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setAuto(boolean value)](#setAuto-boolean-) | Hämtar eller anger ett värde som indikerar om denna [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) är automatisk. |
| [setBrightness(int value)](#setBrightness-int-) | Hämtar eller anger ljusstyrkan. |
| [setContrast(int value)](#setContrast-int-) | Hämtar eller anger kontrasten. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Hämtar eller anger ett värde som indikerar om [lab color] används. |
| [setMeanValueForBrightnessAndContrast(int value)](#setMeanValueForBrightnessAndContrast-int-) | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ställer in egenskapsvärdet enligt typstruktur. |
| [setUseLegacy(boolean value)](#setUseLegacy-boolean-) | Hämtar eller anger ett värde som indikerar om [use legacy]. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger versionen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgEdResource() {#CgEdResource--}
```
public CgEdResource()
```


Initierar en ny instans av klassen [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). PSD-formatsspecifikationen innehåller följande beskrivning: 4 Descriptor Version( = 16) Variable Length Descriptor of extra data Suggestion: it may not be used in old versions of PS(Before CS5).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB‑huvudversionen

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Den PSB‑specifika resurs‑signaturen.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD‑huvudversionen.

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Den gemensamma resurs‑signaturen.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Nyckeln för typverktygsinformation.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Venture‑licensen.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kontrollerar och anger om resursen är PSB-specifik. Vissa resurser känns inte igen för närvarande, men vi har en fullständig lista över PSB-specifika resurser som ändrar deras beteende vid sparning. Så vi måste åtminstone kontrollera detta i UnknownResource.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Nyckeln. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAuto() {#getAuto--}
```
public final boolean getAuto()
```


Hämtar eller anger ett värde som indikerar om denna [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) är automatisk.

Värde:  true  om automatisk; annars  false .

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Hämtar eller anger ljusstyrkan.

Värde: ljusstyrkan.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Hämtar eller anger kontrasten.

Värde: kontrasten.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Hämtar eller anger data.

Värde: Data.

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Hämtar lagrets resursnyckel.

**Returns:**
int
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Hämtar eller anger ett värde som indikerar om [lab color] används.

Värde:  true  om [lab color] används; annars  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar lagrets resurslängd i byte.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final int getMeanValueForBrightnessAndContrast()
```


Hämtar eller anger medelvärdet för ljusstyrka och kontrast.

Värde: Medelvärdet för ljusstyrka och kontrast.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Hämtar prefixlängden. Standardvärdet är 12 för 8BIM-resurser och 16 för 8B64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdVersion | int | PSD-versionen. |

**Returns:**
int - Prefixlängden.
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Hämtar egenskapsvärdet enligt typstruktur. Används endast för UnitTests.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| structureName | java.lang.String | Namnet på strukturen. |

**Returns:**
java.lang.Object - OSType-struktur för enkel enhetstestning
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta psd-version som krävs för lagerresursen. 0 indikerar inga begränsningar.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getUseLegacy() {#getUseLegacy--}
```
public final boolean getUseLegacy()
```


Hämtar eller anger ett värde som indikerar om [use legacy].

Värde:  true  om [use legacy]; annars,  false .

**Returns:**
boolean
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar eller anger versionen.

Värde: Versionen.

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


Bestämmer om resursen är PSB‑specifik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | int | Resursnyckeln. |

**Returns:**
boolean - true om resursen är PSB-specifik; annars false.
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs.

Värde: true om detta objekt är PSB-specifik resurs; annars false.

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


Sparar resursen till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psdVersion | int | PSD-versionen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Sparar den anpassade resursrubriken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Sparar rubrikens signatur, identifierare och längd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
| signatur | int | Signaturen. |
| isLengthLong | boolean | Om satt till true är längden lång. |

### setAuto(boolean value) {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) är automatisk.

Värde:  true  om automatisk; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Hämtar eller anger ljusstyrkan.

Värde: ljusstyrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Hämtar eller anger kontrasten.

Värde: kontrasten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Hämtar eller anger rubriken.

Värde: Headern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Hämtar eller anger ett värde som indikerar om [lab color] används.

Värde:  true  om [lab color] används; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMeanValueForBrightnessAndContrast(int value) {#setMeanValueForBrightnessAndContrast-int-}
```
public final void setMeanValueForBrightnessAndContrast(int value)
```


Hämtar eller anger medelvärdet för ljusstyrka och kontrast.

Värde: Medelvärdet för ljusstyrka och kontrast.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Ställer in egenskapsvärdet enligt typstruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Strukturen. |

### setUseLegacy(boolean value) {#setUseLegacy-boolean-}
```
public final void setUseLegacy(boolean value)
```


Hämtar eller anger ett värde som indikerar om [use legacy].

Värde:  true  om [use legacy]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Hämtar eller anger versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En String som representerar detta objekt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


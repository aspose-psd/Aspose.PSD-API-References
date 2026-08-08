---
title: "BlwhResource"
second_title: "Aspose.PSD för Java API-referens"
description: "BlwhResource-klassen är en resurs för svartvittjusteringslager."
type: docs
weight: 15
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

BlwhResource-klassen är en resurs för svartvittjusteringslager.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Initierar en ny instans av klassen [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource). |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Hämtar eller anger filnamnet för den svartvita förinställningen. |
| [getBlues()](#getBlues--) | Hämtar eller anger blåttvärdet. |
| [getBwPresetKind()](#getBwPresetKind--) | Hämtar eller anger värdet för typ av svartvit förinställning. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Hämtar eller anger cyanvärdet. |
| [getData()](#getData--) | Hämtar eller anger data. |
| [getGreens()](#getGreens--) | Hämtar eller anger gröntvärdet. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getMagentas()](#getMagentas--) | Hämtar eller anger magentavärdet. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getReds()](#getReds--) | Hämtar eller anger rödvärdet. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getTintColor()](#getTintColor--) | Hämtar ARGB‑toningsfärgen. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Hämtar eller anger dubbelvärdet för blå nyansfärg. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Hämtar eller anger dubbelvärdet för grön nyansfärg. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Hämtar eller anger dubbelvärdet för röd nyansfärg. |
| [getUseTint()](#getUseTint--) | Hämtar eller anger ett värde som indikerar om [tint color] används. |
| [getYellows()](#getYellows--) | Hämtar eller anger gultvärdet. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Hämtar eller anger filnamnet för den svartvita förinställningen. |
| [setBlues(int value)](#setBlues-int-) | Hämtar eller anger blåttvärdet. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Hämtar eller anger värdet för typ av svartvit förinställning. |
| [setCyans(int value)](#setCyans-int-) | Hämtar eller anger cyanvärdet. |
| [setGreens(int value)](#setGreens-int-) | Hämtar eller anger gröntvärdet. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setMagentas(int value)](#setMagentas-int-) | Hämtar eller anger magentavärdet. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ställer in egenskapsvärdet enligt typstruktur. |
| [setReds(int value)](#setReds-int-) | Hämtar eller anger rödvärdet. |
| [setTintColor(int value)](#setTintColor-int-) | Anger toningsfärgen. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Hämtar eller anger dubbelvärdet för blå nyansfärg. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Hämtar eller anger dubbelvärdet för grön nyansfärg. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Hämtar eller anger dubbelvärdet för röd nyansfärg. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Hämtar eller anger ett värde som indikerar om [tint color] används. |
| [setYellows(int value)](#setYellows-int-) | Hämtar eller anger gultvärdet. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Initierar en ny instans av klassen [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource).

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Hämtar eller anger filnamnet för den svartvita förinställningen.

Värde: Den svartvita förinställningens filnamn.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Hämtar eller anger blåttvärdet.

Värde: Blåttvärdet.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Hämtar eller anger värdet för typ av svartvit förinställning.

Värde: Värdet för typ av svartvit förinställning.

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


Hämtar eller anger cyanvärdet.

Värde: Cyanvärdet.

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
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Hämtar eller anger gröntvärdet.

Värde: Gröntvärdet.

**Returns:**
int
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
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar lagrets resurslängd i byte.

**Returns:**
int
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Hämtar eller anger magentavärdet.

Värde: Magentavärdet.

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
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta psd-version som krävs för lagerresursen. 0 indikerar inga begränsningar.

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


Hämtar eller anger rödvärdet.

Värde: Rödvärdet.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Hämtar ARGB‑toningsfärgen.

**Returns:**
int - ARGB‑toningsfärgen.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Hämtar eller anger dubbelvärdet för blå nyansfärg.

Värde: Dubbelvärdet för blå nyansfärg.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Hämtar eller anger dubbelvärdet för grön nyansfärg.

Värde: Dubbelvärdet för grön nyansfärg.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Hämtar eller anger dubbelvärdet för röd nyansfärg.

Värde: Dubbelvärdet för röd nyansfärg.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Hämtar eller anger ett värde som indikerar om [tint color] används.

Värde:  true  om [tint color] används; annars,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Hämtar eller anger gultvärdet.

Värde: Gularnas värde.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Hämtar eller anger filnamnet för den svartvita förinställningen.

Värde: Den svartvita förinställningens filnamn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Hämtar eller anger blåttvärdet.

Värde: Blåttvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Hämtar eller anger värdet för typ av svartvit förinställning.

Värde: Värdet för typ av svartvit förinställning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Hämtar eller anger cyanvärdet.

Värde: Cyanvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Hämtar eller anger gröntvärdet.

Värde: Gröntvärdet.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Hämtar eller anger magentavärdet.

Värde: Magentavärdet.

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

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Hämtar eller anger rödvärdet.

Värde: Rödvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Anger toningsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Värdet. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Hämtar eller anger dubbelvärdet för blå nyansfärg.

Värde: Dubbelvärdet för blå nyansfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Hämtar eller anger dubbelvärdet för grön nyansfärg.

Värde: Dubbelvärdet för grön nyansfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Hämtar eller anger dubbelvärdet för röd nyansfärg.

Värde: Dubbelvärdet för röd nyansfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Hämtar eller anger ett värde som indikerar om [tint color] används.

Värde:  true  om [tint color] används; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Hämtar eller anger gultvärdet.

Värde: Gularnas värde.

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


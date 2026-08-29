---
title: "BlncResource"
second_title: "Aspose.PSD för Java API-referens"
description: "BlncResource-klassen är en resurs för färgjusteringslager."
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlncResource extends AdjustmentLayerResource
```

BlncResource-klassen är en resurs för färgjusteringslager.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BlncResource()](#BlncResource--) | Initierar en ny instans av klassen [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DataLength_internalized](#DataLength-internalized) | Den förväntade datalängden. |
| [HighlightsCyanRedBalanceExceptionMessage_internalized](#HighlightsCyanRedBalanceExceptionMessage-internalized) | Meddelandet för undantaget när högdagrar cyan-red-balans är utanför intervallet. |
| [HighlightsMagentaGreenBalanceExceptionMessage_internalized](#HighlightsMagentaGreenBalanceExceptionMessage-internalized) | Meddelandet för undantaget när högdagrar magenta-grön-balans är utanför intervallet. |
| [HighlightsYellowBlueBalanceExceptionMessage_internalized](#HighlightsYellowBlueBalanceExceptionMessage-internalized) | Meddelandet för undantaget när högdagrar gul-blå-balans är utanför intervallet. |
| [MidtonesCyanRedBalanceExceptionMessage_internalized](#MidtonesCyanRedBalanceExceptionMessage-internalized) | Mellantonens cyan röda balans utanför intervallet undantagsmeddelande. |
| [MidtonesMagentaGreenBalanceExceptionMessage_internalized](#MidtonesMagentaGreenBalanceExceptionMessage-internalized) | Mellantonens magenta gröna balans utanför intervallet undantagsmeddelande. |
| [MidtonesYellowBlueBalanceExceptionMessage_internalized](#MidtonesYellowBlueBalanceExceptionMessage-internalized) | Mellantonens gul blå balans utanför intervallet undantagsmeddelande. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [ShadowsCyanRedBalanceExceptionMessage_internalized](#ShadowsCyanRedBalanceExceptionMessage-internalized) | Skuggornas cyan röda balans utanför intervallet undantagsmeddelande. |
| [ShadowsMagentaGreenBalanceExceptionMessage_internalized](#ShadowsMagentaGreenBalanceExceptionMessage-internalized) | Skuggornas magenta gröna balans utanför intervallet undantagsmeddelande. |
| [ShadowsYellowBlueBalanceExceptionMessage_internalized](#ShadowsYellowBlueBalanceExceptionMessage-internalized) | Skuggornas gul blå balans utanför intervallet undantagsmeddelande. |
| [TypeToolKey](#TypeToolKey) | Nyckeln för typverktygsinformation. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Hämtar eller anger data. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getHighlightsCyanRedBalance()](#getHighlightsCyanRedBalance--) | Hämtar eller anger balansen för Highlight Cyan Red. |
| [getHighlightsMagentaGreenBalance()](#getHighlightsMagentaGreenBalance--) | Hämtar eller anger balansen för Highlight Magenta Green. |
| [getHighlightsYellowBlueBalance()](#getHighlightsYellowBlueBalance--) | Hämtar eller anger balansen för Highlight Yellow Blue. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getMidtonesCyanRedBalance()](#getMidtonesCyanRedBalance--) | Hämtar eller anger balansen för Midtone Cyan Red. |
| [getMidtonesMagentaGreenBalance()](#getMidtonesMagentaGreenBalance--) | Hämtar eller anger balansen för Midtone Magenta Green. |
| [getMidtonesYellowBlueBalance()](#getMidtonesYellowBlueBalance--) | Hämtar eller anger balansen för Midtone Yellow Blue. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Hämtar eller anger ett värde som indikerar om denna [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) bevarar luminans. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getShadowsCyanRedBalance()](#getShadowsCyanRedBalance--) | Hämtar eller anger balansen för Shadow Cyan Red. |
| [getShadowsMagentaGreenBalance()](#getShadowsMagentaGreenBalance--) | Hämtar eller anger balansen för Shadow Magenta Green. |
| [getShadowsYellowBlueBalance()](#getShadowsYellowBlueBalance--) | Hämtar eller anger skuggornas gula blå balans. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setHighlightsCyanRedBalance(short value)](#setHighlightsCyanRedBalance-short-) | Hämtar eller anger balansen för Highlight Cyan Red. |
| [setHighlightsMagentaGreenBalance(short value)](#setHighlightsMagentaGreenBalance-short-) | Hämtar eller anger balansen för Highlight Magenta Green. |
| [setHighlightsYellowBlueBalance(short value)](#setHighlightsYellowBlueBalance-short-) | Hämtar eller anger balansen för Highlight Yellow Blue. |
| [setMidtonesCyanRedBalance(short value)](#setMidtonesCyanRedBalance-short-) | Hämtar eller anger balansen för Midtone Cyan Red. |
| [setMidtonesMagentaGreenBalance(short value)](#setMidtonesMagentaGreenBalance-short-) | Hämtar eller anger balansen för Midtone Magenta Green. |
| [setMidtonesYellowBlueBalance(short value)](#setMidtonesYellowBlueBalance-short-) | Hämtar eller anger balansen för Midtone Yellow Blue. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Hämtar eller anger ett värde som indikerar om denna [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) bevarar luminans. |
| [setShadowsCyanRedBalance(short value)](#setShadowsCyanRedBalance-short-) | Hämtar eller anger balansen för Shadow Cyan Red. |
| [setShadowsMagentaGreenBalance(short value)](#setShadowsMagentaGreenBalance-short-) | Hämtar eller anger balansen för Shadow Magenta Green. |
| [setShadowsYellowBlueBalance(short value)](#setShadowsYellowBlueBalance-short-) | Hämtar eller anger skuggornas gula blå balans. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlncResource() {#BlncResource--}
```
public BlncResource()
```


Initierar en ny instans av klassen [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource).

### DataLength_internalized {#DataLength-internalized}
```
public static final int DataLength_internalized
```


Den förväntade datalängden.

### HighlightsCyanRedBalanceExceptionMessage_internalized {#HighlightsCyanRedBalanceExceptionMessage-internalized}
```
public static final String HighlightsCyanRedBalanceExceptionMessage_internalized
```


Meddelandet för undantaget när högdagrar cyan-red-balans är utanför intervallet.

### HighlightsMagentaGreenBalanceExceptionMessage_internalized {#HighlightsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String HighlightsMagentaGreenBalanceExceptionMessage_internalized
```


Meddelandet för undantaget när högdagrar magenta-grön-balans är utanför intervallet.

### HighlightsYellowBlueBalanceExceptionMessage_internalized {#HighlightsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String HighlightsYellowBlueBalanceExceptionMessage_internalized
```


Meddelandet för undantaget när högdagrar gul-blå-balans är utanför intervallet.

### MidtonesCyanRedBalanceExceptionMessage_internalized {#MidtonesCyanRedBalanceExceptionMessage-internalized}
```
public static final String MidtonesCyanRedBalanceExceptionMessage_internalized
```


Mellantonens cyan röda balans utanför intervallet undantagsmeddelande.

### MidtonesMagentaGreenBalanceExceptionMessage_internalized {#MidtonesMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String MidtonesMagentaGreenBalanceExceptionMessage_internalized
```


Mellantonens magenta gröna balans utanför intervallet undantagsmeddelande.

### MidtonesYellowBlueBalanceExceptionMessage_internalized {#MidtonesYellowBlueBalanceExceptionMessage-internalized}
```
public static final String MidtonesYellowBlueBalanceExceptionMessage_internalized
```


Mellantonens gul blå balans utanför intervallet undantagsmeddelande.

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

### ShadowsCyanRedBalanceExceptionMessage_internalized {#ShadowsCyanRedBalanceExceptionMessage-internalized}
```
public static final String ShadowsCyanRedBalanceExceptionMessage_internalized
```


Skuggornas cyan röda balans utanför intervallet undantagsmeddelande.

### ShadowsMagentaGreenBalanceExceptionMessage_internalized {#ShadowsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String ShadowsMagentaGreenBalanceExceptionMessage_internalized
```


Skuggornas magenta gröna balans utanför intervallet undantagsmeddelande.

### ShadowsYellowBlueBalanceExceptionMessage_internalized {#ShadowsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String ShadowsYellowBlueBalanceExceptionMessage_internalized
```


Skuggornas gul blå balans utanför intervallet undantagsmeddelande.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static BlncResource create_internalized(byte[] data)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] |  |

**Returns:**
[BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getHighlightsCyanRedBalance() {#getHighlightsCyanRedBalance--}
```
public final short getHighlightsCyanRedBalance()
```


Hämtar eller anger balansen för Highlight Cyan Red.

Värde: Höjdpunkternas cyan röda balans.

**Returns:**
short
### getHighlightsMagentaGreenBalance() {#getHighlightsMagentaGreenBalance--}
```
public final short getHighlightsMagentaGreenBalance()
```


Hämtar eller anger balansen för Highlight Magenta Green.

Värde: Höjdpunkternas magenta gröna balans.

**Returns:**
short
### getHighlightsYellowBlueBalance() {#getHighlightsYellowBlueBalance--}
```
public final short getHighlightsYellowBlueBalance()
```


Hämtar eller anger balansen för Highlight Yellow Blue.

Värde: Höjdpunkternas gula blå balans.

**Returns:**
short
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
### getMidtonesCyanRedBalance() {#getMidtonesCyanRedBalance--}
```
public final short getMidtonesCyanRedBalance()
```


Hämtar eller anger balansen för Midtone Cyan Red.

Värde: Mellantonernas cyan röda balans.

**Returns:**
short
### getMidtonesMagentaGreenBalance() {#getMidtonesMagentaGreenBalance--}
```
public final short getMidtonesMagentaGreenBalance()
```


Hämtar eller anger balansen för Midtone Magenta Green.

Värde: Mellantonernas magenta gröna balans.

**Returns:**
short
### getMidtonesYellowBlueBalance() {#getMidtonesYellowBlueBalance--}
```
public final short getMidtonesYellowBlueBalance()
```


Hämtar eller anger balansen för Midtone Yellow Blue.

Värde: Mellantonernas gula blå balans.

**Returns:**
short
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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Hämtar eller anger ett värde som indikerar om denna [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) bevarar luminans.

Värde:  true  om den bevarar luminans; annars,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta psd-version som krävs för lagerresursen. 0 indikerar inga begränsningar.

**Returns:**
int
### getShadowsCyanRedBalance() {#getShadowsCyanRedBalance--}
```
public final short getShadowsCyanRedBalance()
```


Hämtar eller anger balansen för Shadow Cyan Red.

Värde: Skuggornas cyan röda balans.

**Returns:**
short
### getShadowsMagentaGreenBalance() {#getShadowsMagentaGreenBalance--}
```
public final short getShadowsMagentaGreenBalance()
```


Hämtar eller anger balansen för Shadow Magenta Green.

Värde: Skuggornas magenta gröna balans.

**Returns:**
short
### getShadowsYellowBlueBalance() {#getShadowsYellowBlueBalance--}
```
public final short getShadowsYellowBlueBalance()
```


Hämtar eller anger skuggornas gula blå balans.

Värde: Skuggornas gula blå balans.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

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

### setHighlightsCyanRedBalance(short value) {#setHighlightsCyanRedBalance-short-}
```
public final void setHighlightsCyanRedBalance(short value)
```


Hämtar eller anger balansen för Highlight Cyan Red.

Värde: Höjdpunkternas cyan röda balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setHighlightsMagentaGreenBalance(short value) {#setHighlightsMagentaGreenBalance-short-}
```
public final void setHighlightsMagentaGreenBalance(short value)
```


Hämtar eller anger balansen för Highlight Magenta Green.

Värde: Höjdpunkternas magenta gröna balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setHighlightsYellowBlueBalance(short value) {#setHighlightsYellowBlueBalance-short-}
```
public final void setHighlightsYellowBlueBalance(short value)
```


Hämtar eller anger balansen för Highlight Yellow Blue.

Värde: Höjdpunkternas gula blå balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setMidtonesCyanRedBalance(short value) {#setMidtonesCyanRedBalance-short-}
```
public final void setMidtonesCyanRedBalance(short value)
```


Hämtar eller anger balansen för Midtone Cyan Red.

Värde: Mellantonernas cyan röda balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setMidtonesMagentaGreenBalance(short value) {#setMidtonesMagentaGreenBalance-short-}
```
public final void setMidtonesMagentaGreenBalance(short value)
```


Hämtar eller anger balansen för Midtone Magenta Green.

Värde: Mellantonernas magenta gröna balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setMidtonesYellowBlueBalance(short value) {#setMidtonesYellowBlueBalance-short-}
```
public final void setMidtonesYellowBlueBalance(short value)
```


Hämtar eller anger balansen för Midtone Yellow Blue.

Värde: Mellantonernas gula blå balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) bevarar luminans.

Värde:  true  om den bevarar luminans; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setShadowsCyanRedBalance(short value) {#setShadowsCyanRedBalance-short-}
```
public final void setShadowsCyanRedBalance(short value)
```


Hämtar eller anger balansen för Shadow Cyan Red.

Värde: Skuggornas cyan röda balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setShadowsMagentaGreenBalance(short value) {#setShadowsMagentaGreenBalance-short-}
```
public final void setShadowsMagentaGreenBalance(short value)
```


Hämtar eller anger balansen för Shadow Magenta Green.

Värde: Skuggornas magenta gröna balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setShadowsYellowBlueBalance(short value) {#setShadowsYellowBlueBalance-short-}
```
public final void setShadowsYellowBlueBalance(short value)
```


Hämtar eller anger skuggornas gula blå balans.

Värde: Skuggornas gula blå balans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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


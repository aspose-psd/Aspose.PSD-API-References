---
title: "Hue2Resource"
second_title: "Aspose.PSD för Java API-referens"
description: "Klass Hue2Resource."
type: docs
weight: 36
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class Hue2Resource extends AdjustmentLayerResource
```

Klass Hue2Resource. Resurs för exponeringjusteringslager
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Hue2Resource()](#Hue2Resource--) | Initierar en ny instans av klassen [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource). |
| [Hue2Resource(byte[] data)](#Hue2Resource-byte---) | Initierar en ny instans av klassen [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource). |
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
| [getClass()](#getClass--) |  |
| [getColorize()](#getColorize--) | Hämtar eller anger ett värde som indikerar om denna [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) är färglagd. |
| [getData()](#getData--) | Hämtar eller anger data. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getHue()](#getHue--) | Hämtar eller anger huvudnyansen. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getLightness()](#getLightness--) | Hämtar eller anger huvudljushet. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getRanges()](#getRanges--) | Hämtar intervallen för Hue/Saturation-justeringslager. |
| [getSaturation()](#getSaturation--) | Hämtar eller anger huvudmättnad. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getVersion()](#getVersion--) | Hämtar versionen. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setColorize(boolean value)](#setColorize-boolean-) | Hämtar eller anger ett värde som indikerar om denna [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) är färglagd. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setHue(short value)](#setHue-short-) | Hämtar eller anger huvudnyansen. |
| [setLightness(short value)](#setLightness-short-) | Hämtar eller anger huvudljushet. |
| [setRanges(ColorRangeHsl[] value)](#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---) | Hämtar intervallen för Hue/Saturation-justeringslager. |
| [setSaturation(short value)](#setSaturation-short-) | Hämtar eller anger huvudmättnad. |
| [setVersion(short value)](#setVersion-short-) | Hämtar versionen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hue2Resource() {#Hue2Resource--}
```
public Hue2Resource()
```


Initierar en ny instans av klassen [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource).

### Hue2Resource(byte[] data) {#Hue2Resource-byte---}
```
public Hue2Resource(byte[] data)
```


Initierar en ny instans av klassen [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Data för resursen. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorize() {#getColorize--}
```
public final boolean getColorize()
```


Hämtar eller anger ett värde som indikerar om denna [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) är färglagd.

Värde:  true  om färgläggning; annars,  false .

**Returns:**
boolean
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
### getHue() {#getHue--}
```
public final short getHue()
```


Hämtar eller anger huvudnyansen.

Värde: huvudnyansen.

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
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Hämtar eller anger huvudljushet.

Värde: huvudljushet.

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
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Hämtar den minsta psd-version som krävs för lagerresursen. 0 indikerar inga begränsningar.

**Returns:**
int
### getRanges() {#getRanges--}
```
public final ColorRangeHsl[] getRanges()
```


Hämtar intervallen för Hue/Saturation-justeringslager. Intervall i PS kan byta namn om intervallet ändras, så vi bör arbeta efter index.

Värde: intervallen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl[]
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Hämtar eller anger huvudmättnad.

Värde: huvudmättnad.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Hämtar versionen. Standard är 2

Värde: Versionen.

**Returns:**
short
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

### setColorize(boolean value) {#setColorize-boolean-}
```
public final void setColorize(boolean value)
```


Hämtar eller anger ett värde som indikerar om denna [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) är färglagd.

Värde:  true  om färgläggning; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Hämtar eller anger huvudnyansen.

Värde: huvudnyansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Hämtar eller anger huvudljushet.

Värde: huvudljushet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setRanges(ColorRangeHsl[] value) {#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---}
```
public void setRanges(ColorRangeHsl[] value)
```


Hämtar intervallen för Hue/Saturation-justeringslager. Intervall i PS kan byta namn om intervallet ändras, så vi bör arbeta efter index.

Värde: intervallen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorRangeHsl\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Hämtar eller anger huvudmättnad.

Värde: huvudmättnad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Hämtar versionen. Standard är 2

Värde: Versionen.

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


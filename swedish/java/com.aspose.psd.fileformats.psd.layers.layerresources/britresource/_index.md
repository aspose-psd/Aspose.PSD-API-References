---
title: "BritResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Klassen BritResource."
type: docs
weight: 17
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BritResource extends AdjustmentLayerResource
```

Klassen BritResource. Resurs för justering av ljusstyrka/kontrastlager.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BritResource()](#BritResource--) | Initierar en ny instans av klassen [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource) class. |
| [BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor)](#BritResource-short-short-short-boolean-) | Initierar en ny instans av klassen [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource) class. |
| [BritResource(byte[] bytes)](#BritResource-byte---) | Initierar en ny instans av klassen [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource) class. |
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
| [getBrightness()](#getBrightness--) | Hämtar eller anger ljusstyrkan. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Hämtar eller anger kontrasten. |
| [getData()](#getData--) | Hämtar eller anger data. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLabColor()](#getLabColor--) | Hämtar eller anger ett värde som indikerar om [lab color]. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setBrightness(short value)](#setBrightness-short-) | Hämtar eller anger ljusstyrkan. |
| [setContrast(short value)](#setContrast-short-) | Hämtar eller anger kontrasten. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Hämtar eller anger ett värde som indikerar om [lab color]. |
| [setMeanValueForBrightnessAndContrast(short value)](#setMeanValueForBrightnessAndContrast-short-) | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BritResource() {#BritResource--}
```
public BritResource()
```


Initierar en ny instans av klassen [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource) class.

### BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor) {#BritResource-short-short-short-boolean-}
```
public BritResource(short brightness, short contrast, short meanValueForBrightnessAndContrast, boolean labColor)
```


Initierar en ny instans av klassen [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource) class.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ljusstyrka | short | Ljusstyrkan. |
| kontrast | short | Kontrasten. |
| meanValueForBrightnessAndContrast | short | Det genomsnittliga värdet för ljusstyrka och kontrast. |
| labColor | boolean | om inställt på  true  [lab color]. |

### BritResource(byte[] bytes) {#BritResource-byte---}
```
public BritResource(byte[] bytes)
```


Initierar en ny instans av klassen [BritResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/britresource) class. PSD-formatsspecifikationen innehåller följande beskrivning: 2 Brightness 2 Contrast 2 Mean value for brightness and contrast 1 Lab color only Det används inte i moderna PSD(CS5 och upp) där Cg Ed är. Cg Ed lagrar infoegenskaper.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | byte[] | Byte. |

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
### getBrightness() {#getBrightness--}
```
public final short getBrightness()
```


Hämtar eller anger ljusstyrkan.

Värde: ljusstyrkan.

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


Hämtar eller anger kontrasten.

Värde: kontrasten.

**Returns:**
short
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


Hämtar eller anger ett värde som indikerar om [lab color].

Värde:  true  om [lab color]; annars,  false .

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
public final short getMeanValueForBrightnessAndContrast()
```


Hämtar eller anger medelvärdet för ljusstyrka och kontrast.

Värde: Medelvärdet för ljusstyrka och kontrast.

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

### setBrightness(short value) {#setBrightness-short-}
```
public final void setBrightness(short value)
```


Hämtar eller anger ljusstyrkan.

Värde: ljusstyrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setContrast(short value) {#setContrast-short-}
```
public final void setContrast(short value)
```


Hämtar eller anger kontrasten.

Värde: kontrasten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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


Hämtar eller anger ett värde som indikerar om [lab color].

Värde:  true  om [lab color]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMeanValueForBrightnessAndContrast(short value) {#setMeanValueForBrightnessAndContrast-short-}
```
public final void setMeanValueForBrightnessAndContrast(short value)
```


Hämtar eller anger medelvärdet för ljusstyrka och kontrast.

Värde: Medelvärdet för ljusstyrka och kontrast.

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


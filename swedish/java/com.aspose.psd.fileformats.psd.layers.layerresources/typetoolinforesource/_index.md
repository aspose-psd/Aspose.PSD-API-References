---
title: "TypeToolInfoResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Typverktygsinformationen."
type: docs
weight: 79
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

Typverktygsinformationen. För PSD-versioner lägre än 6.0.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Initierar en ny instans av klassen [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
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
| [getAComponent()](#getAComponent--) | Hämtar eller anger en komponent. |
| [getBComponent()](#getBComponent--) | Hämtar eller anger b-komponenten. |
| [getCharacterCount()](#getCharacterCount--) | Hämtar eller anger teckenantalet. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Hämtar eller anger färgrymdsvärdet. |
| [getFontVersion()](#getFontVersion--) | Hämtar eller anger typsnittsversionen. |
| [getFonts()](#getFonts--) | Hämtar eller anger teckensnitten. |
| [getFontsCount()](#getFontsCount--) | Hämtar teckensnittsantalet. |
| [getGComponent()](#getGComponent--) | Hämtar eller anger g-komponenten. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Hämtar eller anger horisontell placering. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getLineCount()](#getLineCount--) | Hämtar radantalet. |
| [getLines()](#getLines--) | Hämtar eller anger raderna. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getRComponent()](#getRComponent--) | Hämtar eller anger r-komponenten. |
| [getScaleFactor()](#getScaleFactor--) | Hämtar eller anger skalningsfaktorn. |
| [getSelectionEnd()](#getSelectionEnd--) | Hämtar eller anger markeringsslutet. |
| [getSelectionStart()](#getSelectionStart--) | Hämtar eller anger markeringsstarten. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getStyles()](#getStyles--) | Hämtar eller anger teckensnittsstilarna. |
| [getStylesCount()](#getStylesCount--) | Hämtar stilantalet. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger transformmatrisen. |
| [getTypeValue()](#getTypeValue--) | Hämtar eller anger typvärdet. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Hämtar eller anger vertikal placering. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setAComponent(short value)](#setAComponent-short-) | Hämtar eller anger en komponent. |
| [setBComponent(short value)](#setBComponent-short-) | Hämtar eller anger b-komponenten. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Hämtar eller anger teckenantalet. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Hämtar eller anger de råa färgdata. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Hämtar eller anger färgrymdsvärdet. |
| [setFontVersion(short value)](#setFontVersion-short-) | Hämtar eller anger typsnittsversionen. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Hämtar eller anger teckensnitten. |
| [setGComponent(short value)](#setGComponent-short-) | Hämtar eller anger g-komponenten. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Hämtar eller anger horisontell placering. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Hämtar eller anger raderna. |
| [setRComponent(short value)](#setRComponent-short-) | Hämtar eller anger r-komponenten. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Hämtar eller anger skalningsfaktorn. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Hämtar eller anger markeringsslutet. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Hämtar eller anger markeringsstarten. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Hämtar eller anger teckensnittsstilarna. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Hämtar eller anger transformmatrisen. |
| [setTypeValue(short value)](#setTypeValue-short-) | Hämtar eller anger typvärdet. |
| [setVersion(short value)](#setVersion-short-) | Hämtar eller anger versionen. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Hämtar eller anger vertikal placering. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Initierar en ny instans av klassen [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Hämtar eller anger en komponent.

Värde: en komponent.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Hämtar eller anger b-komponenten.

Värde: B-komponenten.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Hämtar eller anger teckenantalet.

Värde: teckenantalet.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


Hämtar eller anger färgrymdsvärdet.

Värde: färgrymdsvärdet.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Hämtar eller anger typsnittsversionen.

Värde: teckensnittsversionen.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Hämtar eller anger teckensnitten.

Värde: teckensnitten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Hämtar teckensnittsantalet.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Hämtar eller anger g-komponenten.

Värde: G-komponenten.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Hämtar eller anger rubriken.

Värde: Headern.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Hämtar eller anger horisontell placering.

Värde: horisontell placering.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Hämtar radantalet.

Värde: radantalet.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Hämtar eller anger raderna.

Värde: raderna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Hämtar eller anger r-komponenten.

Värde: R-komponenten.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Hämtar eller anger skalningsfaktorn.

Värde: skalfaktorn.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Hämtar eller anger markeringsslutet.

Värde: markeringsslutet.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Hämtar eller anger markeringsstarten.

Värde: markeringsstarten.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Hämtar eller anger teckensnittsstilarna.

Värde: teckensnittsstilarna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Hämtar stilantalet.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Hämtar eller anger transformmatrisen.

Värde: transformationsmatrisen.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Hämtar eller anger typvärdet.

Värde: typvärdet.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Hämtar eller anger versionen.

Värde: Versionen.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Hämtar eller anger vertikal placering.

Värde: vertikal placering.

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


Sparar den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |
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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Hämtar eller anger en komponent.

Värde: en komponent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Hämtar eller anger b-komponenten.

Värde: B-komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Hämtar eller anger teckenantalet.

Värde: teckenantalet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Hämtar eller anger de råa färgdata.

Värde: de råa färgdata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Hämtar eller anger färgrymdsvärdet.

Värde: färgrymdsvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Hämtar eller anger typsnittsversionen.

Värde: teckensnittsversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Hämtar eller anger teckensnitten.

Värde: teckensnitten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Hämtar eller anger g-komponenten.

Värde: G-komponenten.

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Hämtar eller anger horisontell placering.

Värde: horisontell placering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Hämtar eller anger raderna.

Värde: raderna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Hämtar eller anger r-komponenten.

Värde: R-komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Hämtar eller anger skalningsfaktorn.

Värde: skalfaktorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Hämtar eller anger markeringsslutet.

Värde: markeringsslutet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Hämtar eller anger markeringsstarten.

Värde: markeringsstarten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Hämtar eller anger teckensnittsstilarna.

Värde: teckensnittsstilarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Hämtar eller anger transformmatrisen.

Värde: transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Hämtar eller anger typvärdet.

Värde: typvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Hämtar eller anger versionen.

Värde: Versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Hämtar eller anger vertikal placering.

Värde: vertikal placering.

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


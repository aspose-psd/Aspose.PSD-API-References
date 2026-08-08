---
title: "TypeToolInfoResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De informatie over het typegereedschap."
type: docs
weight: 79
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

De typegereedschapsinformatie. Voor PSD-versie lager dan 6.0.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Initialiseert een nieuw exemplaar van de klasse [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
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
| [getAComponent()](#getAComponent--) | Haalt een component op of stelt deze in. |
| [getBComponent()](#getBComponent--) | Haalt de b-component op of stelt deze in. |
| [getCharacterCount()](#getCharacterCount--) | Haalt het aantal tekens op of stelt dit in. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Haalt de kleurruimtewaarde op of stelt deze in. |
| [getFontVersion()](#getFontVersion--) | Haalt op of stelt de lettertype‑versie in. |
| [getFonts()](#getFonts--) | Haalt de lettertypen op of stelt deze in. |
| [getFontsCount()](#getFontsCount--) | Haalt het aantal lettertypen op. |
| [getGComponent()](#getGComponent--) | Haalt de g-component op of stelt deze in. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Haalt de horizontale plaatsing op of stelt deze in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getLineCount()](#getLineCount--) | Haalt het aantal regels op. |
| [getLines()](#getLines--) | Haalt de regels op of stelt deze in. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD-versie op die vereist is voor de laagresource. |
| [getRComponent()](#getRComponent--) | Haalt de r-component op of stelt deze in. |
| [getScaleFactor()](#getScaleFactor--) | Haalt de schaalfactor op of stelt deze in. |
| [getSelectionEnd()](#getSelectionEnd--) | Haalt het einde van de selectie op of stelt dit in. |
| [getSelectionStart()](#getSelectionStart--) | Haalt op of stelt de selectie-start in. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [getStyles()](#getStyles--) | Haalt op of stelt de lettertype-stijlen in. |
| [getStylesCount()](#getStylesCount--) | Haalt het aantal stijlen op. |
| [getTransformMatrix()](#getTransformMatrix--) | Haalt op of stelt de transformatie-matrix in. |
| [getTypeValue()](#getTypeValue--) | Haalt op of stelt de typewaarde in. |
| [getVersion()](#getVersion--) | Haalt of stelt de versie in. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Haalt op of stelt de verticale plaatsing in. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat de opgegeven streamcontainer op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setAComponent(short value)](#setAComponent-short-) | Haalt een component op of stelt deze in. |
| [setBComponent(short value)](#setBComponent-short-) | Haalt de b-component op of stelt deze in. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Haalt het aantal tekens op of stelt dit in. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Haalt op of stelt de ruwe kleurgegevens in. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Haalt de kleurruimtewaarde op of stelt deze in. |
| [setFontVersion(short value)](#setFontVersion-short-) | Haalt op of stelt de lettertype‑versie in. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Haalt de lettertypen op of stelt deze in. |
| [setGComponent(short value)](#setGComponent-short-) | Haalt de g-component op of stelt deze in. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Haalt de horizontale plaatsing op of stelt deze in. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Haalt de regels op of stelt deze in. |
| [setRComponent(short value)](#setRComponent-short-) | Haalt de r-component op of stelt deze in. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Haalt de schaalfactor op of stelt deze in. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Haalt het einde van de selectie op of stelt dit in. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Haalt op of stelt de selectie-start in. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Haalt op of stelt de lettertype-stijlen in. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Haalt op of stelt de transformatie-matrix in. |
| [setTypeValue(short value)](#setTypeValue-short-) | Haalt op of stelt de typewaarde in. |
| [setVersion(short value)](#setVersion-short-) | Haalt of stelt de versie in. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Haalt op of stelt de verticale plaatsing in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Initialiseert een nieuw exemplaar van de klasse [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Haalt een component op of stelt deze in.

Waarde: een component.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Haalt de b-component op of stelt deze in.

Waarde: de b-component.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Haalt het aantal tekens op of stelt dit in.

Waarde: het aantal tekens.

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


Haalt de kleurruimtewaarde op of stelt deze in.

Waarde: de kleurruimtewaarde.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Haalt op of stelt de lettertype‑versie in.

Waarde: de lettertypeversie.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Haalt de lettertypen op of stelt deze in.

Waarde: de lettertypen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Haalt het aantal lettertypen op.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Haalt de g-component op of stelt deze in.

Waarde: de g-component.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Haalt op of stelt de header in.

Waarde: de header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Haalt de horizontale plaatsing op of stelt deze in.

Waarde: de horizontale plaatsing.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Haalt het aantal regels op.

Waarde: het aantal regels.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Haalt de regels op of stelt deze in.

Waarde: de regels.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Haalt de r-component op of stelt deze in.

Waarde: de r-component.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Haalt de schaalfactor op of stelt deze in.

Waarde: de schaalfactor.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Haalt het einde van de selectie op of stelt dit in.

Waarde: het einde van de selectie.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Haalt op of stelt de selectie-start in.

Waarde: het begin van de selectie.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Haalt op of stelt de lettertype-stijlen in.

Waarde: de lettertype-stijlen.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Haalt het aantal stijlen op.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Haalt op of stelt de transformatie-matrix in.

Waarde: De transformatiematrix.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Haalt op of stelt de typewaarde in.

Waarde: De typewaarde.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Haalt of stelt de versie in.

Waarde: De versie.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Haalt op of stelt de verticale plaatsing in.

Waarde: De verticale plaatsing.

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


Slaat de opgegeven streamcontainer op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |
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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Haalt een component op of stelt deze in.

Waarde: een component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Haalt de b-component op of stelt deze in.

Waarde: de b-component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Haalt het aantal tekens op of stelt dit in.

Waarde: het aantal tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Haalt op of stelt de ruwe kleurgegevens in.

Waarde: De ruwe kleurgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Haalt de kleurruimtewaarde op of stelt deze in.

Waarde: de kleurruimtewaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Haalt op of stelt de lettertype‑versie in.

Waarde: de lettertypeversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Haalt de lettertypen op of stelt deze in.

Waarde: de lettertypen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Haalt de g-component op of stelt deze in.

Waarde: de g-component.

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Haalt de horizontale plaatsing op of stelt deze in.

Waarde: de horizontale plaatsing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Haalt de regels op of stelt deze in.

Waarde: de regels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Haalt de r-component op of stelt deze in.

Waarde: de r-component.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Haalt de schaalfactor op of stelt deze in.

Waarde: de schaalfactor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Haalt het einde van de selectie op of stelt dit in.

Waarde: het einde van de selectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Haalt op of stelt de selectie-start in.

Waarde: het begin van de selectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Haalt op of stelt de lettertype-stijlen in.

Waarde: de lettertype-stijlen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Haalt op of stelt de transformatie-matrix in.

Waarde: De transformatiematrix.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Haalt op of stelt de typewaarde in.

Waarde: De typewaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Haalt of stelt de versie in.

Waarde: De versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Haalt op of stelt de verticale plaatsing in.

Waarde: De verticale plaatsing.

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


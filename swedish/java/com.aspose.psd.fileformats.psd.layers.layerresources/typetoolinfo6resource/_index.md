---
title: "TypeToolInfo6Resource"
second_title: "Aspose.PSD för Java API-referens"
description: "Typverktygsinformationen."
type: docs
weight: 78
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

Typverktygsinformationen. För PSD‑version högre än eller lika med 6.0.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Initierar en ny instans av klassen [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource). |
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
| [getBottom()](#getBottom--) | Hämtar eller anger den nedre positionen. |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | Hämtar eller anger textgränserna i textrutan. |
| [getBounds_internalized()](#getBounds-internalized--) | Hämtar eller anger textrutans gränser. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Hämtar eller anger klass‑ID. |
| [getClassName()](#getClassName--) | Hämtar eller anger klassnamnet. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Hämtar eller anger beskrivarversionen. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getItems()](#getItems--) | Hämtar eller anger objekten. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLeft()](#getLeft--) | Hämtar eller anger den vänstra positionen. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | Tolkar rådata till en instans av klassen TyShRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | Hämtar [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure)-elementet om det finns. |
| [getRight()](#getRight--) | Hämtar eller anger den högra positionen. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | Hämtar indexet för text i denna resurs. |
| [getTextVersion()](#getTextVersion--) | Hämtar eller anger textversionen. |
| [getTop()](#getTop--) | Hämtar eller anger den övre positionen. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger transformmatrisen. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen av typverktyget. |
| [getWarpClassID()](#getWarpClassID--) | Hämtar eller anger klass‑ID. |
| [getWarpClassName()](#getWarpClassName--) | Hämtar eller anger warp‑klassnamnet. |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | Hämtar eller anger warp‑beskrivarversionen. |
| [getWarpItems()](#getWarpItems--) | Hämtar eller anger warp‑objekten. |
| [getWarpVersion()](#getWarpVersion--) | Hämtar eller anger warp‑versionen. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger den nedre positionen. |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | Hämtar eller anger textgränserna i textrutan. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger klass‑ID. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Hämtar eller anger klassnamnet. |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | Hämtar eller anger beskrivarversionen. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger objekten. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger den vänstra positionen. |
| [setRight(int value)](#setRight-int-) | Hämtar eller anger den högra positionen. |
| [setTextVersion(short value)](#setTextVersion-short-) | Hämtar eller anger textversionen. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger den övre positionen. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Hämtar eller anger transformmatrisen. |
| [setVersion(short value)](#setVersion-short-) | Hämtar eller anger versionen av typverktyget. |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger klass‑ID. |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | Hämtar eller anger warp‑klassnamnet. |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | Hämtar eller anger warp‑beskrivarversionen. |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger warp‑objekten. |
| [setWarpVersion(short value)](#setWarpVersion-short-) | Hämtar eller anger warp‑versionen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | Serialisera TyShRoot‑data till råformat. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


Initierar en ny instans av klassen [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Klassens ID. |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Warp-klassens ID. |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Hämtar eller anger den nedre positionen.

Värde: Den nedre platsen.

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


Hämtar eller anger textgränserna i textrutan.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


Hämtar eller anger textrutans gränser.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassID() {#getClassID--}
```
public final ClassID getClassID()
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Hämtar eller anger klassnamnet.

Värde: Klassnamnet.

**Returns:**
java.lang.String
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Hämtar eller anger beskrivarversionen.

Värde: Deskriptörsversionen.

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Hämtar eller anger objekten.

Värde: Objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Hämtar lagrets resursnyckel.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Hämtar eller anger den vänstra positionen.

Värde: Den vänstra platsen.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Hämtar lagrets resurslängd i byte.

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


Tolkar rådata till en instans av klassen TyShRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - Den råa datan som TyShRoot-klassinstans.
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
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


Hämtar [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure)-elementet om det finns.

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


Hämtar eller anger den högra positionen.

Värde: Den högra platsen.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


Hämtar indexet för text i denna resurs.

**Returns:**
int - Returnerar indexet för text i denna resurs.
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


Hämtar eller anger textversionen.

Värde: Textversionen.

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


Hämtar eller anger den övre positionen.

Värde: Den övre platsen.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Hämtar eller anger transformmatrisen.

Värde: transformationsmatrisen.

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Hämtar eller anger versionen av typverktyget.

Värde: Versionen av typverktyget.

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


Hämtar eller anger warp‑klassnamnet.

Värde: Förvrängningsklassens namn.

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


Hämtar eller anger warp‑beskrivarversionen.

Värde: Versionen för förvrängningsbeskrivaren.

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


Hämtar eller anger warp‑versionen.

Värde: Förvrängningsversionen.

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

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Hämtar eller anger den nedre positionen.

Värde: Den nedre platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


Hämtar eller anger textgränserna i textrutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Hämtar eller anger klassnamnet.

Värde: Klassnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


Hämtar eller anger beskrivarversionen.

Värde: Deskriptörsversionen.

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Hämtar eller anger objekten.

Värde: Objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Hämtar eller anger den vänstra positionen.

Värde: Den vänstra platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Hämtar eller anger den högra positionen.

Värde: Den högra platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


Hämtar eller anger textversionen.

Värde: Textversionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Hämtar eller anger den övre positionen.

Värde: Den övre platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Hämtar eller anger versionen av typverktyget.

Värde: Versionen av typverktyget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


Hämtar eller anger warp‑klassnamnet.

Värde: Förvrängningsklassens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


Hämtar eller anger warp‑beskrivarversionen.

Värde: Versionen för förvrängningsbeskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


Hämtar eller anger warp‑versionen.

Värde: Förvrängningsversionen.

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
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


Serialisera TyShRoot‑data till råformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataModel | com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot |  |

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


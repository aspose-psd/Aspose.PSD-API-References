---
title: "TypeToolInfo6Resource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De informatie over het typegereedschap."
type: docs
weight: 78
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

De typegereedschapinformatie. Voor PSD-versie hoger of gelijk aan 6.0.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Initialiseert een nieuw exemplaar van de [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource) klasse. |
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
| [getBottom()](#getBottom--) | Krijgt of stelt de onderste locatie in. |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | Krijgt of stelt de tekstgrenzen in het tekstvak in. |
| [getBounds_internalized()](#getBounds-internalized--) | Krijgt of stelt de grenzen van het tekstvak in. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Haalt op of stelt de klasse‑ID in. |
| [getClassName()](#getClassName--) | Haalt de klassenaam op of stelt deze in. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Haalt of stelt de descriptorversie in. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getItems()](#getItems--) | Haalt op of stelt de items in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLeft()](#getLeft--) | Krijgt of stelt de linker locatie in. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | Parse de ruwe gegevens naar een TyShRoot-klasse‑instantie. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD-versie op die vereist is voor de laagresource. |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | Haalt het [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) item op als het bestaat. |
| [getRight()](#getRight--) | Haalt of stelt de rechter locatie in. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | Haalt de index van tekst in deze bron op. |
| [getTextVersion()](#getTextVersion--) | Haalt of stelt de tekstversie in. |
| [getTop()](#getTop--) | Haalt of stelt de bovenste locatie in. |
| [getTransformMatrix()](#getTransformMatrix--) | Haalt op of stelt de transformatie-matrix in. |
| [getVersion()](#getVersion--) | Haalt of stelt de versie van het typegereedschap in. |
| [getWarpClassID()](#getWarpClassID--) | Haalt op of stelt de klasse‑ID in. |
| [getWarpClassName()](#getWarpClassName--) | Haalt op of stelt de warp‑klassennaam in. |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | Haalt op of stelt de warp‑descriptorversie in. |
| [getWarpItems()](#getWarpItems--) | Haalt of stelt de warp-items in. |
| [getWarpVersion()](#getWarpVersion--) | Haalt op of stelt de warp‑versie in. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat de resource op in de opgegeven streamcontainer. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setBottom(int value)](#setBottom-int-) | Krijgt of stelt de onderste locatie in. |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | Krijgt of stelt de tekstgrenzen in het tekstvak in. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt op of stelt de klasse‑ID in. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Haalt de klassenaam op of stelt deze in. |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | Haalt of stelt de descriptorversie in. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Haalt op of stelt de items in. |
| [setLeft(int value)](#setLeft-int-) | Krijgt of stelt de linker locatie in. |
| [setRight(int value)](#setRight-int-) | Haalt of stelt de rechter locatie in. |
| [setTextVersion(short value)](#setTextVersion-short-) | Haalt of stelt de tekstversie in. |
| [setTop(int value)](#setTop-int-) | Haalt of stelt de bovenste locatie in. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Haalt op of stelt de transformatie-matrix in. |
| [setVersion(short value)](#setVersion-short-) | Haalt of stelt de versie van het typegereedschap in. |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt op of stelt de klasse‑ID in. |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | Haalt op of stelt de warp‑klassennaam in. |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | Haalt op of stelt de warp‑descriptorversie in. |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Haalt of stelt de warp-items in. |
| [setWarpVersion(short value)](#setWarpVersion-short-) | Haalt op of stelt de warp‑versie in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | Serialiseer TyShRoot-gegevens naar raw. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


Initialiseert een nieuw exemplaar van de [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | De klasse-ID. |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | De warp-klasse-ID. |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Krijgt of stelt de onderste locatie in.

Waarde: De onderste locatie.

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


Krijgt of stelt de tekstgrenzen in het tekstvak in.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


Krijgt of stelt de grenzen van het tekstvak in.

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


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Haalt de klassenaam op of stelt deze in.

Waarde: De klassenaam.

**Returns:**
java.lang.String
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Haalt of stelt de descriptorversie in.

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Haalt op of stelt de items in.

Waarde: De items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Haalt de laagresource‑sleutel op.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Krijgt of stelt de linker locatie in.

Waarde: De linker locatie.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


Parse de ruwe gegevens naar een TyShRoot-klasse‑instantie.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - De ruwe gegevens als TyShRoot-klasse‑instantie.
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
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


Haalt het [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) item op als het bestaat.

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


Haalt of stelt de rechter locatie in.

Waarde: De rechter locatie.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


Haalt de index van tekst in deze bron op.

**Returns:**
int - Retourneert de index van tekst in deze bron.
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


Haalt of stelt de tekstversie in.

Waarde: De tekstversie.

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


Haalt of stelt de bovenste locatie in.

Waarde: De bovenste locatie.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Haalt op of stelt de transformatie-matrix in.

Waarde: De transformatiematrix.

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Haalt of stelt de versie van het typegereedschap in.

Waarde: De versie van het typegereedschap.

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


Haalt op of stelt de warp‑klassennaam in.

Waarde: De warp-klassenaam.

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


Haalt op of stelt de warp‑descriptorversie in.

Waarde: De warp-descriptorversie.

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


Haalt op of stelt de warp‑versie in.

Waarde: De warp-versie.

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

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Krijgt of stelt de onderste locatie in.

Waarde: De onderste locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


Krijgt of stelt de tekstgrenzen in het tekstvak in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Haalt de klassenaam op of stelt deze in.

Waarde: De klassenaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


Haalt of stelt de descriptorversie in.

Waarde: De descriptorversie.

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Haalt op of stelt de items in.

Waarde: De items.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Krijgt of stelt de linker locatie in.

Waarde: De linker locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Haalt of stelt de rechter locatie in.

Waarde: De rechter locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


Haalt of stelt de tekstversie in.

Waarde: De tekstversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Haalt of stelt de bovenste locatie in.

Waarde: De bovenste locatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Haalt of stelt de versie van het typegereedschap in.

Waarde: De versie van het typegereedschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


Haalt op of stelt de warp‑klassennaam in.

Waarde: De warp-klassenaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


Haalt op of stelt de warp‑descriptorversie in.

Waarde: De warp-descriptorversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


Haalt op of stelt de warp‑versie in.

Waarde: De warp-versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een String die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een String die deze instantie vertegenwoordigt.
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


Serialiseer TyShRoot-gegevens naar raw.

**Parameters:**
| Parameter | Type | Beschrijving |
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


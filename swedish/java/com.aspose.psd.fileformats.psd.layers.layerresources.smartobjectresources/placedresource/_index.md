---
title: "PlacedResource"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar klassen PlacedResource som innehåller gemensam information om ett placerat lager eller ett smart objekt‑lager i PSD-filen."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

Definierar PlacedResource-klassen som innehåller gemensam information om ett placerat lager eller ett smart objektlager i PSD-filen. Den används för att stödja smarta objektlager i Adobe\\ufffd Photoshop\\ufffd-bilder.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Det anpassade kuvertförvrängningsnamnet |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Det förvalda förvrängningsklassnamnet |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Det förvalda förvrängningsklassnamnet |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Den förväntade versionen av förvrängningsbeskrivaren |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Den förväntade warp-versionen |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Det horisontella identifierarnamnet |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Namnet på nyckeln för mesh-punkter |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Namnet på orienteringsidentifieraren |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Det förväntade versionsvärdet |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB‑huvudversionen |
| [PsbResourceSignature](#PsbResourceSignature) | Den PSB‑specifika resurs‑signaturen. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD‑huvudversionen. |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Namnet på identifieraren för klassen rational point |
| [ResourceSignature](#ResourceSignature) | Den gemensamma resurs‑signaturen. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Storleken på double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Storleken på int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Antalet transformvärden |
| [UOrderKey_internalized](#UOrderKey-internalized) | U-ordningsnyckeln |
| [VOrderKey_internalized](#VOrderKey-internalized) | V-ordningsnyckeln |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Namnet på vertikal identifierare |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Det anpassade warp-namnet |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Warp-headerns längd. |
| [WarpKey_internalized](#WarpKey-internalized) | Warp-nyckeln. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Namnet på warp none |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Warp-perspektivnyckeln |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Warp-perspektiv annat |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Warp-rotationsnyckeln |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Warp-stilsnyckeln |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Warp-värdesnyckeln |
| [ZeroChar_internalized](#ZeroChar-internalized) | Nolltecknet. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Venture‑licensen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Påstår att det specificerade faktiska värdet är lika med det förväntade värdet. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kontrollerar och sätter om resursen är PSB‑specifik. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden. |
| [getBottom()](#getBottom--) | Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden. |
| [getBounds()](#getBounds--) | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Hämtar eller anger rubriken. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [getItems()](#getItems--) | Hämtar eller anger warp‑objekten. |
| [getKey()](#getKey--) | Hämtar lagrets resursnyckel. |
| [getLeft()](#getLeft--) | Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen. |
| [getLength()](#getLength--) | Hämtar lagrets resurslängd i byte. |
| [getPageNumber()](#getPageNumber--) | Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen. |
| [getPerspective()](#getPerspective--) | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Hämtar eller anger typen av det placerade lagret i PSD‑filen. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Hämtar prefixlängden. |
| [getPsdVersion()](#getPsdVersion--) | Hämtar den minsta PSD‑versionen som krävs för lagrets resurs. |
| [getRight()](#getRight--) | Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen. |
| [getSignature()](#getSignature--) | Hämtar lagrets resurs‑signatur. |
| [getTop()](#getTop--) | Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden. |
| [getTotalPages()](#getTotalPages--) | Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen. |
| [getTransformMatrix()](#getTransformMatrix--) | Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen. |
| [getUOrder()](#getUOrder--) | Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [getUniqueId()](#getUniqueId--) | Hämtar eller anger det globala unika identifieraren för det placerade lagret i PSD‑bilden. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [getValue()](#getValue--) | Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden. |
| [getVersion()](#getVersion--) | Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Hämtar eller anger måttenheten för de vertikala nätpunkterna. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Hämtar eller anger klass‑ID. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Hämtar eller anger warp‑klassnamnet. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Hämtar eller anger warp‑beskrivarversionen. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Hämtar eller anger warp‑objekten. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Hämtar eller anger warp‑versionen. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Hämtar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) på det angivna indexet. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Hämtar ett värde som indikerar om detta objekt har gränsenheter. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | Hämtar eller anger ett värde som indikerar om detta objekts warp‑stil är anpassad. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestämmer om resursen är PSB‑specifik. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Hämtar ett värde som indikerar om denna instans är PSB‑specifik resurs. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Sparar resursen till den angivna strömbehållaren. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Sparar den anpassade resursrubriken. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Sparar rubrikens signatur, identifierare och längd. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden. |
| [setBottom(double value)](#setBottom-double-) | Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Hämtar eller anger gränserna för det placerade lagret i PSD‑filen. |
| [setCustom(boolean value)](#setCustom-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekts warp‑stil är anpassad. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Hämtar eller anger rubriken. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Hämtar eller anger måttenheten för de horisontella nätpunkterna. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Hämtar eller anger warp‑objekten. |
| [setLeft(double value)](#setLeft-double-) | Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen. |
| [setPageNumber(int value)](#setPageNumber-int-) | Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen. |
| [setPerspective(double value)](#setPerspective-double-) | Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Hämtar eller anger typen av det placerade lagret i PSD‑filen. |
| [setRight(double value)](#setRight-double-) | Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell. |
| [setTop(double value)](#setTop-double-) | Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden. |
| [setTotalPages(int value)](#setTotalPages-int-) | Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen. |
| [setUOrder(int value)](#setUOrder-int-) | Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Hämtar eller anger det globala unika identifieraren för det placerade lagret i PSD‑bilden. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen. |
| [setValue(double value)](#setValue-double-) | Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden. |
| [setVersion(int value)](#setVersion-int-) | Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Hämtar eller anger måttenheten för de vertikala nätpunkterna. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Hämtar eller anger klass‑ID. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Hämtar eller anger warp‑klassnamnet. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Hämtar eller anger warp‑beskrivarversionen. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Hämtar eller anger warp‑versionen. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Det anpassade kuvertförvrängningsnamnet

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Det förvalda förvrängningsklassnamnet

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Det förvalda förvrängningsklassnamnet

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Den förväntade versionen av förvrängningsbeskrivaren

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Den förväntade warp-versionen

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Det horisontella identifierarnamnet

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Namnet på nyckeln för mesh-punkter

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Namnet på orienteringsidentifieraren

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Det förväntade versionsvärdet

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

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Namnet på identifieraren för klassen rational point

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Den gemensamma resurs‑signaturen.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


Storleken på double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


Storleken på int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Antalet transformvärden

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


U-ordningsnyckeln

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


V-ordningsnyckeln

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Namnet på vertikal identifierare

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Det anpassade warp-namnet

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Warp-headerns längd.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Warp‑nyckeln. Även standard‑warp‑klassnamnet.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Namnet på warp none

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Warp-perspektivnyckeln

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Warp-perspektiv annat

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Warp-rotationsnyckeln

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Warp-stilsnyckeln

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Warp-värdesnyckeln

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Nolltecknet.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Venture‑licensen.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Påstår att det specificerade faktiska värdet är lika med det förväntade värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| actualValue | java.lang.Object | Det faktiska värdet. |
| expectedValue | java.lang.Object | Det förväntade värdet. |
| meddelande | java.lang.String | Meddelandet. |

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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden.

Värde: Anti‑alias‑policyn för det placerade lagret.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden.

Värde: Den nedre platsen för det placerade lagret.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar eller anger gränserna för det placerade lagret i PSD‑filen.

Värde: Gränserna för det placerade lagret.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix.

Värde: Standardmåttenhetstypen.

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
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Hämtar eller anger måttenheten för de horisontella nätpunkterna.

Värde: Måttenheten för de horisontella nätpunkterna.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

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
public final double getLeft()
```


Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen.

Värde: Den vänstra platsen för det placerade lagret.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


Hämtar lagrets resurslängd i byte.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen.

Värde: Sidnumret för det placerade lagret.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Perspektivvärdet för det placerade lagret.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Det andra perspektivvärdet för det placerade lagret.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Hämtar eller anger typen av det placerade lagret i PSD‑filen.

Värde: Typen av det placerade lagret.

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
### getRight() {#getRight--}
```
public final double getRight()
```


Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen.

Värde: Den högra platsen för det placerade lagret.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Hämtar lagrets resurs‑signatur.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden.

Värde: Den övre platsen för det placerade lagret.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen.

Värde: Totalt antal sidor i det placerade lagret.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen.

Värde: Transformationsmatrisen för det placerade lagret.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: U‑ordningsvärdet för det placerade lagret.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Hämtar eller anger det globala unika identifieraren för det placerade lagret i PSD‑bilden.

Värde: Det unika identifieraren för det placerade lagret.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: V-ordningsvärdet för det placerade lagret.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden.

Värde: Förvrängningsvärdet för det placerade lagret.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3.

Värde: Versionen för det placerade lagret.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Hämtar eller anger måttenheten för de vertikala nätpunkterna.

Värde: Måttenheten för de vertikala nätpunkterna.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Hämtar eller anger warp‑klassnamnet.

Värde: Förvrängningsklassens namn.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Hämtar eller anger warp‑beskrivarversionen.

Värde: Versionen för förvrängningsbeskrivaren.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Hämtar eller anger warp‑versionen.

Värde: Förvrängningsversionen.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Hämtar [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | java.lang.String | Nyckelnamnet. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Hämtar ett värde som indikerar om detta objekt har gränsenheter.

Värde:  true  om detta objekt har gränsenheter; annars  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Hämtar eller anger ett värde som indikerar om detta objekts förvrängningsstil är anpassad. Om true innehåller den nätpunkter. Om den sätts till false raderas nätpunkterna.

Värde:  true  om det placerade lagret har anpassad stil; annars  false .

**Returns:**
boolean
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
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell.

Värde:  true  om rotationsorienteringen är horisontell; annars  false .

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
public abstract void save(StreamContainer streamContainer, int psdVersion)
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

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Hämtar eller anger anti-alias-policyn för det placerade lagret i PSD-bilden.

Värde: Anti‑alias‑policyn för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Hämtar eller anger den nedre placeringen för det placerade lagret i PSD-bilden.

Värde: Den nedre platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Hämtar eller anger gränserna för det placerade lagret i PSD‑filen.

Värde: Gränserna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekts förvrängningsstil är anpassad. Om true innehåller den nätpunkter. Om den sätts till false raderas nätpunkterna.

Värde:  true  om det placerade lagret har anpassad stil; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Hämtar eller anger standardenhetstypen för tilldelade värden såsom Left, Top, Right, Bottom, TransformMatrix.

Värde: Standardmåttenhetstypen.

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

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Hämtar eller anger måttenheten för de horisontella nätpunkterna.

Värde: Måttenheten för de horisontella nätpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Hämtar eller anger warp‑objekten.

Värde: Warp‑objekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Hämtar eller anger vänsterpositionen för det placerade lagret i PSD‑filen.

Värde: Den vänstra platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Hämtar eller anger sidnumret för det placerade lagret i PSD‑filen.

Värde: Sidnumret för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Hämtar eller anger perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Perspektivvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Hämtar eller anger det andra perspektivvärdet för det placerade lagret i PSD‑filen.

Värde: Det andra perspektivvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Hämtar eller anger typen av det placerade lagret i PSD‑filen.

Värde: Typen av det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Hämtar eller anger högerpositionen för det placerade lagret i PSD‑filen.

Värde: Den högra platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta objekts roteringsorientering är horisontell.

Värde:  true  om rotationsorienteringen är horisontell; annars  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Hämtar eller anger toppositionen för det placerade lagret i PSD‑bilden.

Värde: Den övre platsen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Hämtar eller anger det totala antalet sidor för det placerade lagret i PSD‑filen.

Värde: Totalt antal sidor i det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Hämtar eller anger transformmatrisen för det placerade lagret i PSD‑filen.

Värde: Transformationsmatrisen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Hämtar eller anger U‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: U‑ordningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Hämtar eller anger det globala unika identifieraren för det placerade lagret i PSD‑bilden.

Värde: Det unika identifieraren för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Hämtar eller anger V‑ordningsvärdet för det placerade lagret i PSD‑filen.

Värde: V-ordningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Hämtar eller anger warp‑värdet för det placerade lagret i PSD‑bilden.

Värde: Förvrängningsvärdet för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Hämtar versionen av det placerade lagret i PSD‑filen, vanligtvis 3.

Värde: Versionen för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Hämtar eller anger måttenheten för de vertikala nätpunkterna.

Värde: Måttenheten för de vertikala nätpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Hämtar eller anger de horisontella nätpunkterna för det placerade lagret i PSD‑filen.

Värde: De horisontella nätpunkterna för det placerade lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Hämtar eller anger klass‑ID.

Värde: Klass-ID:t.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Hämtar eller anger warp‑klassnamnet.

Värde: Förvrängningsklassens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Hämtar eller anger warp‑beskrivarversionen.

Värde: Versionen för förvrängningsbeskrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Hämtar eller anger warp‑versionen.

Värde: Förvrängningsversionen.

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


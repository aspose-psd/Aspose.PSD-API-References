---
title: "PlacedResource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert de PlacedResource-klasse die algemene informatie bevat over een geplaatste laag of een smart‑object‑laag in het PSD‑bestand."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

Definieert de PlacedResource-klasse die gemeenschappelijke informatie bevat over een geplaatste laag of een smart object-laag in het PSD-bestand. Wordt gebruikt om smart object-lagen te ondersteunen in de Adobe\ufffd Photoshop\ufffd-afbeeldingen.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | De aangepaste envelope warp-naam |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | De standaard warp-klassenaam |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | De standaard warp-klassenaam |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | De verwachte warp-descriptorversie |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | De verwachte warp-versie |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | De horizontale identifier-naam |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | De mesh-punten-sleutelnaam |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | De oriëntatie-identifier-naam |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | De verwachte versie-waarde |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | De PSB-headerversie |
| [PsbResourceSignature](#PsbResourceSignature) | De PSB-specifieke resourcehandtekening. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | De PSD-headerversie |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | De rationele punt-klasse-identifier-naam |
| [ResourceSignature](#ResourceSignature) | De algemene resourcehandtekening. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | De grootte van double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | De grootte van int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Het aantal transformatie-waarden |
| [UOrderKey_internalized](#UOrderKey-internalized) | De u-ordeksleutel |
| [VOrderKey_internalized](#VOrderKey-internalized) | De v-ordeksleutel |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | De verticale identifier-naam |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | De warp aangepaste naam |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | De warp headerlengte. |
| [WarpKey_internalized](#WarpKey-internalized) | De warp-sleutel. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | De warp geen naam |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | De warp perspectief-sleutel |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | De warp perspectief andere |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | De warp rotatie-sleutel |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | De warp stijl-sleutel |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | De warp waarde-sleutel |
| [ZeroChar_internalized](#ZeroChar-internalized) | Het nulteken. |
| [ventureLicense_internalized](#ventureLicense-internalized) | De venture-licentie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Bevestigt dat de opgegeven werkelijke waarde gelijk is aan de verwachte waarde. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Controleert en stelt in of de resource PSB-specifiek is. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in. |
| [getBottom()](#getBottom--) | Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in. |
| [getBounds()](#getBounds--) | Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Haalt of stelt het standaard eenheidstype in voor toegewezen waarden zoals Links, Boven, Rechts, Onder, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Haalt op of stelt de header in. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Haalt of stelt de meeteenheid van de horizontale rasterpunten in. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [getItems()](#getItems--) | Haalt of stelt de warp-items in. |
| [getKey()](#getKey--) | Haalt de laagresource‑sleutel op. |
| [getLeft()](#getLeft--) | Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in. |
| [getLength()](#getLength--) | Haalt de lengte van de laagresource in bytes op. |
| [getPageNumber()](#getPageNumber--) | Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in. |
| [getPerspective()](#getPerspective--) | Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Haalt of stelt het type van de geplaatste laag in het PSD-bestand in. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Haalt de prefixlengte op. |
| [getPsdVersion()](#getPsdVersion--) | Haalt de minimale PSD-versie op die vereist is voor de laagresource. |
| [getRight()](#getRight--) | Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in. |
| [getSignature()](#getSignature--) | Haalt de laagresourcehandtekening op. |
| [getTop()](#getTop--) | Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in. |
| [getTotalPages()](#getTotalPages--) | Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in. |
| [getTransformMatrix()](#getTransformMatrix--) | Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in. |
| [getUOrder()](#getUOrder--) | Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [getUniqueId()](#getUniqueId--) | Haalt op of stelt de globale unieke identifier van de geplaatste laag in de PSD‑afbeelding in. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [getValue()](#getValue--) | Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in. |
| [getVersion()](#getVersion--) | Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Haalt op of stelt de meeteenheid van de verticale mesh‑punten in. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Haalt op of stelt de klasse‑ID in. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Haalt op of stelt de warp‑klassennaam in. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Haalt op of stelt de warp‑descriptorversie in. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Haalt of stelt de warp-items in. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Haalt op of stelt de warp‑versie in. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Haalt de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) op op de opgegeven index. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Haalt een waarde op die aangeeft of deze instantie bound‑eenheden heeft. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | Haalt op of stelt een waarde in die aangeeft of de warp‑stijl van deze instantie aangepast is. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bepaalt of de resource PSB-specifiek is. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Haalt een waarde op die aangeeft of deze instantie resource PSB-specifiek is. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Haalt op of stelt een waarde in die aangeeft of de rotatie‑oriëntatie van deze instantie horizontaal is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Slaat de resource op in de opgegeven streamcontainer. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Slaat de aangepaste resource‑header op. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Slaat de headerhandtekening, identifier en lengte op. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in. |
| [setBottom(double value)](#setBottom-double-) | Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in. |
| [setCustom(boolean value)](#setCustom-boolean-) | Haalt op of stelt een waarde in die aangeeft of de warp‑stijl van deze instantie aangepast is. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Haalt of stelt het standaard eenheidstype in voor toegewezen waarden zoals Links, Boven, Rechts, Onder, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Haalt op of stelt de header in. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Haalt of stelt de meeteenheid van de horizontale rasterpunten in. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Haalt of stelt de warp-items in. |
| [setLeft(double value)](#setLeft-double-) | Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in. |
| [setPageNumber(int value)](#setPageNumber-int-) | Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in. |
| [setPerspective(double value)](#setPerspective-double-) | Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Haalt of stelt het type van de geplaatste laag in het PSD-bestand in. |
| [setRight(double value)](#setRight-double-) | Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Haalt op of stelt een waarde in die aangeeft of de rotatie‑oriëntatie van deze instantie horizontaal is. |
| [setTop(double value)](#setTop-double-) | Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in. |
| [setTotalPages(int value)](#setTotalPages-int-) | Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in. |
| [setUOrder(int value)](#setUOrder-int-) | Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Haalt op of stelt de globale unieke identifier van de geplaatste laag in de PSD‑afbeelding in. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in. |
| [setValue(double value)](#setValue-double-) | Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in. |
| [setVersion(int value)](#setVersion-int-) | Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Haalt op of stelt de meeteenheid van de verticale mesh‑punten in. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Haalt op of stelt de klasse‑ID in. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Haalt op of stelt de warp‑klassennaam in. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Haalt op of stelt de warp‑descriptorversie in. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Haalt op of stelt de warp‑versie in. |
| [toString()](#toString--) | Retourneert een String die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


De aangepaste envelope warp-naam

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


De standaard warp-klassenaam

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


De standaard warp-klassenaam

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


De verwachte warp-descriptorversie

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


De verwachte warp-versie

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


De horizontale identifier-naam

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


De mesh-punten-sleutelnaam

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


De oriëntatie-identifier-naam

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


De verwachte versie-waarde

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

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


De rationele punt-klasse-identifier-naam

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


De algemene resourcehandtekening.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


De grootte van double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


De grootte van int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Het aantal transformatie-waarden

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


De u-ordeksleutel

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


De v-ordeksleutel

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


De verticale identifier-naam

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


De warp aangepaste naam

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


De warp headerlengte.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


De warp‑sleutel. Ook de standaard warp‑klassennaam.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


De warp geen naam

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


De warp perspectief-sleutel

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


De warp perspectief andere

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


De warp rotatie-sleutel

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


De warp stijl-sleutel

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


De warp waarde-sleutel

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Het nulteken.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


De venture-licentie.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Bevestigt dat de opgegeven werkelijke waarde gelijk is aan de verwachte waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| actualValue | java.lang.Object | De werkelijke waarde. |
| expectedValue | java.lang.Object | De verwachte waarde. |
| bericht | java.lang.String | Het bericht. |

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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in.

Waarde: Het anti‑aliasbeleid van de geplaatste laag.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De onderste locatie van de geplaatste laag.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in.

Waarde: De grenzen van de geplaatste laag.

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


Haalt of stelt het standaard eenheidstype in voor toegewezen waarden zoals Links, Boven, Rechts, Onder, TransformMatrix.

Waarde: Het standaard meeteenheidstype.

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
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Haalt of stelt de meeteenheid van de horizontale rasterpunten in.

Waarde: De maateenheid van de horizontale rasterpunten.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

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
public final double getLeft()
```


Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De linkse locatie van de geplaatste laag.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


Haalt de lengte van de laagresource in bytes op.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in.

Waarde: Het paginanummer van de geplaatste laag.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De perspectiefwaarde van de geplaatste laag.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De andere perspectiefwaarde van de geplaatste laag.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Haalt of stelt het type van de geplaatste laag in het PSD-bestand in.

Waarde: Het type van de geplaatste laag.

**Returns:**
int
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
### getRight() {#getRight--}
```
public final double getRight()
```


Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De rechtse locatie van de geplaatste laag.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Haalt de laagresourcehandtekening op.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De bovenste locatie van de geplaatste laag.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in.

Waarde: Het totale aantal pagina's van de geplaatste laag.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in.

Waarde: De transformatiematrix van de geplaatste laag.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De U-ordewaarde van de geplaatste laag.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Haalt op of stelt de globale unieke identifier van de geplaatste laag in de PSD‑afbeelding in.

Waarde: De unieke identifier van de geplaatste laag.

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


Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De V-ordewaarde van de geplaatste laag.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in.

Waarde: De warp-waarde van de geplaatste laag.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3.

Waarde: De versie van de geplaatste laag.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Haalt op of stelt de meeteenheid van de verticale mesh‑punten in.

Waarde: De maateenheid van de verticale rasterpunten.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Haalt op of stelt de warp‑klassennaam in.

Waarde: De warp-klassenaam.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Haalt op of stelt de warp‑descriptorversie in.

Waarde: De warp-descriptorversie.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Haalt op of stelt de warp‑versie in.

Waarde: De warp-versie.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Haalt de [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | java.lang.String | De sleutelnaam. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Haalt een waarde op die aangeeft of deze instantie bound‑eenheden heeft.

Waarde:  true  als deze instantie grens-eenheden heeft; anders,  false .

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Haalt een waarde op of stelt deze in die aangeeft of de warp-stijl van deze instantie aangepast is. Als true bevat het mesh-punten. Als false worden de mesh-punten gewist.

Waarde:  true  als de geplaatste laag een aangepaste stijl heeft; anders,  false .

**Returns:**
boolean
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
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Haalt op of stelt een waarde in die aangeeft of de rotatie‑oriëntatie van deze instantie horizontaal is.

Waarde:  true  als de rotatie-oriëntatie horizontaal is; anders,  false .

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

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Haalt of stelt het anti-alias-beleid van de geplaatste laag in de PSD-afbeelding in.

Waarde: Het anti‑aliasbeleid van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Haalt of stelt de onderkantlocatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De onderste locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Haalt of stelt de grenzen van de geplaatste laag in het PSD-bestand in.

Waarde: De grenzen van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of de warp-stijl van deze instantie aangepast is. Als true bevat het mesh-punten. Als false worden de mesh-punten gewist.

Waarde:  true  als de geplaatste laag een aangepaste stijl heeft; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Haalt of stelt het standaard eenheidstype in voor toegewezen waarden zoals Links, Boven, Rechts, Onder, TransformMatrix.

Waarde: Het standaard meeteenheidstype.

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

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Haalt of stelt de meeteenheid van de horizontale rasterpunten in.

Waarde: De maateenheid van de horizontale rasterpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Haalt of stelt de warp-items in.

Waarde: De warp items.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Haalt of stelt de linkse locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De linkse locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Haalt of stelt het paginanummer van de geplaatste laag in het PSD-bestand in.

Waarde: Het paginanummer van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Haalt of stelt de perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De perspectiefwaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Haalt of stelt de andere perspectiefwaarde van de geplaatste laag in het PSD-bestand in.

Waarde: De andere perspectiefwaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Haalt of stelt het type van de geplaatste laag in het PSD-bestand in.

Waarde: Het type van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Haalt of stelt de rechter locatie van de geplaatste laag in het PSD-bestand in.

Waarde: De rechtse locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of de rotatie‑oriëntatie van deze instantie horizontaal is.

Waarde:  true  als de rotatie-oriëntatie horizontaal is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Haalt of stelt de bovenste locatie van de geplaatste laag in de PSD-afbeelding in.

Waarde: De bovenste locatie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Haalt op of stelt het totale aantal pagina's van de geplaatste laag in het PSD‑bestand in.

Waarde: Het totale aantal pagina's van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Haalt op of stelt de transformatiematrix van de geplaatste laag in het PSD‑bestand in.

Waarde: De transformatiematrix van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Haalt op of stelt de U‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De U-ordewaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Haalt op of stelt de globale unieke identifier van de geplaatste laag in de PSD‑afbeelding in.

Waarde: De unieke identifier van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Haalt op of stelt de V‑ordewaarde van de geplaatste laag in het PSD‑bestand in.

Waarde: De V-ordewaarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Haalt op of stelt de warp‑waarde van de geplaatste laag in de PSD‑afbeelding in.

Waarde: De warp-waarde van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Haalt de versie van de geplaatste laag in het PSD‑bestand op, meestal 3.

Waarde: De versie van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Haalt op of stelt de meeteenheid van de verticale mesh‑punten in.

Waarde: De maateenheid van de verticale rasterpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Haalt of stelt de horizontale rasterpunten van de geplaatste laag in het PSD-bestand in.

Waarde: De horizontale rasterpunten van de geplaatste laag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Haalt op of stelt de klasse‑ID in.

Waarde: Het class-ID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Haalt op of stelt de warp‑klassennaam in.

Waarde: De warp-klassenaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Haalt op of stelt de warp‑descriptorversie in.

Waarde: De warp-descriptorversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Haalt op of stelt de warp‑versie in.

Waarde: De warp-versie.

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


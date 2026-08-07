---
title: "PlacedResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die PlacedResource-Klasse, die allgemeine Informationen über eine platzierte Ebene oder eine Smart-Object-Ebene in der PSD-Datei enthält."
type: docs
weight: 12
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

Definiert die PlacedResource‑Klasse, die allgemeine Informationen über eine platzierte Ebene oder eine Smart‑Object‑Ebene in der PSD‑Datei enthält. Sie wird verwendet, um Smart‑Object‑Ebenen in den Adobe\\ufffd Photoshop\\ufffd‑Bildern zu unterstützen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Der benutzerdefinierte Umschlag-Warp-Name |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Der Standard-Warp-Klassenname |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Der Standard-Warp-Klassenname |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Die erwartete Warp-Deskriptor-Version |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Die erwartete Warp-Version |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Der horizontale Bezeichner-Name |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Der Mesh-Punkte-Schlüsselname |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Der Orientierungsbezeichner-Name |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Der erwartete Versionswert |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Die PSB‑Header‑Version |
| [PsbResourceSignature](#PsbResourceSignature) | Die PSB‑spezifische Ressourcen‑Signatur. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Die PSD‑Header‑Version |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Der rationale Punktklassenbezeichner-Name |
| [ResourceSignature](#ResourceSignature) | Die allgemeine Ressourcen‑Signatur. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Die Größe von double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Die Größe von int |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Die Transformationswert-Anzahl |
| [UOrderKey_internalized](#UOrderKey-internalized) | Der u-Ordnungsschlüssel |
| [VOrderKey_internalized](#VOrderKey-internalized) | Der v-Ordnungsschlüssel |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Der vertikale Bezeichner-Name |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Der benutzerdefinierte Warp-Name |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Die Warp-Header-Länge. |
| [WarpKey_internalized](#WarpKey-internalized) | Der Warp-Schlüssel. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Der Warp-None-Name |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Der Warp-Perspektivschlüssel |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Der Warp-Perspektive-Other |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Der Warp-Drehschlüssel |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Der Warp-Stil-Schlüssel |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Der Warp-Wertschlüssel |
| [ZeroChar_internalized](#ZeroChar-internalized) | Das Nullzeichen. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Die Venture-Lizenz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Behauptet, dass der angegebene tatsächliche Wert dem erwarteten Wert entspricht. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild. |
| [getBottom()](#getBottom--) | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| [getBounds()](#getBounds--) | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [getItems()](#getItems--) | Liest oder setzt die Verzerrungsobjekte. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| [getLength()](#getLength--) | Ermittelt die Länge der Schichtressource in Bytes. |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei. |
| [getPerspective()](#getPerspective--) | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getRight()](#getRight--) | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getTop()](#getTop--) | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| [getTotalPages()](#getTotalPages--) | Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei. |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei. |
| [getUOrder()](#getUOrder--) | Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [getUniqueId()](#getUniqueId--) | Liest oder setzt die global eindeutige Kennung der platzierten Ebene im PSD-Bild. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [getValue()](#getValue--) | Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild. |
| [getVersion()](#getVersion--) | Liest die Version der platzierten Ebene in der PSD-Datei, normalerweise 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Liest oder setzt die Klassen-ID. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Liest oder setzt den Verzerrungsklassennamen. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Liest oder setzt die Warp-Deskriptor-Version. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Liest oder setzt die Verzerrungsobjekte. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Liest oder setzt die Warp-Version. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Liest die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) am angegebenen Index. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Liest einen Wert, der angibt, ob diese Instanz Begrenzungseinheiten hat. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | Liest oder setzt einen Wert, der angibt, ob der Warp-Stil dieser Instanz benutzerdefiniert ist. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Liest oder setzt einen Wert, der angibt, ob die Rotationsausrichtung dieser Instanz horizontal ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert die Ressource im angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild. |
| [setBottom(double value)](#setBottom-double-) | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| [setCustom(boolean value)](#setCustom-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Warp-Stil dieser Instanz benutzerdefiniert ist. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Liest oder setzt die Verzerrungsobjekte. |
| [setLeft(double value)](#setLeft-double-) | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| [setPageNumber(int value)](#setPageNumber-int-) | Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei. |
| [setPerspective(double value)](#setPerspective-double-) | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei. |
| [setRight(double value)](#setRight-double-) | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Rotationsausrichtung dieser Instanz horizontal ist. |
| [setTop(double value)](#setTop-double-) | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| [setTotalPages(int value)](#setTotalPages-int-) | Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei. |
| [setUOrder(int value)](#setUOrder-int-) | Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Liest oder setzt die global eindeutige Kennung der platzierten Ebene im PSD-Bild. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [setValue(double value)](#setValue-double-) | Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild. |
| [setVersion(int value)](#setVersion-int-) | Liest die Version der platzierten Ebene in der PSD-Datei, normalerweise 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Liest oder setzt die Klassen-ID. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Liest oder setzt den Verzerrungsklassennamen. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Liest oder setzt die Warp-Deskriptor-Version. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Liest oder setzt die Warp-Version. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Der benutzerdefinierte Umschlag-Warp-Name

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Der Standard-Warp-Klassenname

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Der Standard-Warp-Klassenname

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


Die erwartete Warp-Deskriptor-Version

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


Die erwartete Warp-Version

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Der horizontale Bezeichner-Name

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Der Mesh-Punkte-Schlüsselname

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Der Orientierungsbezeichner-Name

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


Der erwartete Versionswert

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Die PSB‑Header‑Version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Die PSB‑spezifische Ressourcen‑Signatur.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Die PSD‑Header‑Version

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Der rationale Punktklassenbezeichner-Name

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Die allgemeine Ressourcen‑Signatur.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


Die Größe von double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


Die Größe von int

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Die Transformationswert-Anzahl

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


Der u-Ordnungsschlüssel

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


Der v-Ordnungsschlüssel

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Der vertikale Bezeichner-Name

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Der benutzerdefinierte Warp-Name

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


Die Warp-Header-Länge.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


Der Warp-Schlüssel. Außerdem der Standard-Warp-Klassenname.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Der Warp-None-Name

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


Der Warp-Perspektivschlüssel

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


Der Warp-Perspektive-Other

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


Der Warp-Drehschlüssel

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


Der Warp-Stil-Schlüssel

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


Der Warp-Wertschlüssel

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Das Nullzeichen.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Die Venture-Lizenz.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Behauptet, dass der angegebene tatsächliche Wert dem erwarteten Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| actualValue | java.lang.Object | Der tatsächliche Wert. |
| expectedValue | java.lang.Object | Der erwartete Wert. |
| message | java.lang.String | Die Nachricht. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. Einige Ressourcen werden derzeit nicht erkannt, aber wir haben eine vollständige Liste von PSB-spezifischen Ressourcen, die ihr Verhalten beim Speichern ändern. Daher müssen wir dies zumindest in UnknownResource überprüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Schlüssel. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild.

Wert: Die Antialias-Richtlinie der platzierten Ebene.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild.

Wert: Die untere Position der platzierten Ebene.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei.

Wert: Die Begrenzungen der platzierten Ebene.

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


Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix.

Wert: Der Standard-Maßeinheitstyp.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Liest oder setzt die Maßeinheit der horizontalen Netzpunkte.

Wert: Die Maßeinheit der horizontalen Netzpunkte.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Liest oder setzt die Verzerrungsobjekte.

Wert: Die Warp-Elemente.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Ermittelt den Schichtressourcen-Schlüssel.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei.

Wert: Die linke Position der platzierten Ebene.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


Ermittelt die Länge der Schichtressource in Bytes.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei.

Wert: Die Seitenzahl der platzierten Ebene.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der Perspektivwert der platzierten Ebene.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der weitere Perspektivwert der platzierten Ebene.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei.

Wert: Der Typ der platzierten Ebene.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Ermittelt die Präfixlänge. Standardwert ist 12 für 8BIM-Ressourcen und 16 für 8B64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdVersion | int | Die PSD‑Version. |

**Returns:**
int - Die Präfixlänge.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei.

Wert: Die rechte Position der platzierten Ebene.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Ermittelt die Signatur der Schichtressource.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild.

Wert: Die obere Position der platzierten Ebene.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei.

Wert: Die Gesamtseiten der platzierten Ebene.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei.

Wert: Die Transformationsmatrix der platzierten Ebene.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der U-Ordnungswert der platzierten Ebene.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Liest oder setzt die global eindeutige Kennung der platzierten Ebene im PSD-Bild.

Wert: Der eindeutige Bezeichner der platzierten Ebene.

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


Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der V-Ordnungswert der platzierten Ebene.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild.

Wert: Der Verzerrungswert der platzierten Ebene.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liest die Version der platzierten Ebene in der PSD-Datei, normalerweise 3.

Wert: Die Version der platzierten Ebene.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Liest oder setzt die Maßeinheit der vertikalen Netzpunkte.

Wert: Die Maßeinheit der vertikalen Netzpunkte.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Liest oder setzt die Klassen-ID.

Wert: Die Klassen-ID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Liest oder setzt den Verzerrungsklassennamen.

Wert: Der Name der Verzerrungsklasse.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Liest oder setzt die Warp-Deskriptor-Version.

Wert: Die Version des Verzerrungsdeskriptors.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Liest oder setzt die Verzerrungsobjekte.

Wert: Die Warp-Elemente.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Liest oder setzt die Warp-Version.

Wert: Die Verzerrungs-Version.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Liest die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) am angegebenen Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | java.lang.String | Der Schlüsselname. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Liest einen Wert, der angibt, ob diese Instanz Begrenzungseinheiten hat.

Wert:  true  wenn diese Instanz Begrenzungseinheiten hat; andernfalls  false .

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Liest oder setzt einen Wert, der angibt, ob der Verzerrungsstil dieser Instanz benutzerdefiniert ist. Wenn true, enthält er Netzpunkte. Wenn auf false gesetzt, löscht er Netzpunkte.

Wert:  true  wenn die platzierte Ebene einen benutzerdefinierten Stil hat; andernfalls  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Bestimmt, ob die Ressource PSB-spezifisch ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | int | Der Ressourcen-Schlüssel. |

**Returns:**
boolean -  true  wenn die Ressource PSB-spezifisch ist; andernfalls  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist.

Wert:  true  wenn diese Instanz ressourcen-PSB-spezifisch ist; andernfalls  false .

**Returns:**
boolean
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Liest oder setzt einen Wert, der angibt, ob die Rotationsausrichtung dieser Instanz horizontal ist.

Wert:  true  wenn die Rotationsorientierung horizontal ist; andernfalls  false .

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


Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert wird. |
| psdVersion | int | Die PSD‑Version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Speichert den benutzerdefinierten Ressourcen-Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Speichert die Header-Signatur, den Bezeichner und die Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |
| Signatur | int | Die Signatur. |
| isLengthLong | boolean | wenn auf  true  gesetzt, ist die Länge lang. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Liest oder setzt die Antialiasing-Richtlinie der platzierten Ebene im PSD-Bild.

Wert: Die Antialias-Richtlinie der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild.

Wert: Die untere Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei.

Wert: Die Begrenzungen der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob der Verzerrungsstil dieser Instanz benutzerdefiniert ist. Wenn true, enthält er Netzpunkte. Wenn auf false gesetzt, löscht er Netzpunkte.

Wert:  true  wenn die platzierte Ebene einen benutzerdefinierten Stil hat; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix.

Wert: Der Standard-Maßeinheitstyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Ermittelt oder legt den Header fest.

Wert: Der Header.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Liest oder setzt die Maßeinheit der horizontalen Netzpunkte.

Wert: Die Maßeinheit der horizontalen Netzpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Liest oder setzt die Verzerrungsobjekte.

Wert: Die Warp-Elemente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei.

Wert: Die linke Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei.

Wert: Die Seitenzahl der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der Perspektivwert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei.

Wert: Der weitere Perspektivwert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei.

Wert: Der Typ der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei.

Wert: Die rechte Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Rotationsausrichtung dieser Instanz horizontal ist.

Wert:  true  wenn die Rotationsorientierung horizontal ist; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild.

Wert: Die obere Position der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei.

Wert: Die Gesamtseiten der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei.

Wert: Die Transformationsmatrix der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der U-Ordnungswert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Liest oder setzt die global eindeutige Kennung der platzierten Ebene im PSD-Bild.

Wert: Der eindeutige Bezeichner der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei.

Wert: Der V-Ordnungswert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild.

Wert: Der Verzerrungswert der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Liest die Version der platzierten Ebene in der PSD-Datei, normalerweise 3.

Wert: Die Version der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Liest oder setzt die Maßeinheit der vertikalen Netzpunkte.

Wert: Die Maßeinheit der vertikalen Netzpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei.

Wert: Die horizontalen Netzpunkte der platzierten Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Liest oder setzt die Klassen-ID.

Wert: Die Klassen-ID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Liest oder setzt den Verzerrungsklassennamen.

Wert: Der Name der Verzerrungsklasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Liest oder setzt die Warp-Deskriptor-Version.

Wert: Die Version des Verzerrungsdeskriptors.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Liest oder setzt die Warp-Version.

Wert: Die Verzerrungs-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


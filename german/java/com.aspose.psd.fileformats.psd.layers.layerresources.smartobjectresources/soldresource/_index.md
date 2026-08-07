---
title: "SoLdResource"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert die SoLdResource-Klasse, die Informationen über eine Smart-Object-Ebene in einer PSD-Datei enthält."
type: docs
weight: 15
url: /de/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource), [com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource)
```
public class SoLdResource extends SmartObjectResource
```

Definiert die Klasse SoLdResource, die Informationen über eine Smart‑Object‑Ebene in einer PSD‑Datei enthält. Sie wird verwendet, um Smart‑Object‑Ebenen in Adobe® Photoshop®‑Bildern zu unterstützen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SoLdResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)](#SoLdResource-java.util.UUID-boolean-boolean-) | Initialisiert eine neue Instanz der Klasse [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource). |
| [SoLdResource()](#SoLdResource--) | Initialisiert eine neue Instanz der Klasse [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [AntiAliasPolicyKey_internalized](#AntiAliasPolicyKey-internalized) | Der Anti‑Aliasing‑Richtlinien‑Schlüssel |
| [BottomKey_internalized](#BottomKey-internalized) | Der untere Schlüssel |
| [BoundsKey_internalized](#BoundsKey-internalized) | Der Begrenzungs‑Schlüssel |
| [CompIdKey_internalized](#CompIdKey-internalized) | Der Schlüsselname der CompID |
| [CompInfoKey_internalized](#CompInfoKey-internalized) | Der Name des Comp-Informationsschlüssels |
| [CompKey_internalized](#CompKey-internalized) | Der Comp-Schlüssel |
| [CompNoneValue_internalized](#CompNoneValue-internalized) | Der Comp-Wert, der 'none' bedeutet |
| [CropKey_internalized](#CropKey-internalized) | Der Zuschneide-Schlüssel |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Der benutzerdefinierte Umschlag-Warp-Name |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Der Standard-Warp-Klassenname |
| [DenominatorKey_internalized](#DenominatorKey-internalized) | Der Nenner-Schlüssel |
| [DurationKey_internalized](#DurationKey-internalized) | Der Dauer-Schlüssel |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Der Standard-Warp-Klassenname |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | Die erwartete Warp-Deskriptor-Version |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | Die erwartete Warp-Version |
| [FrameCountKey_internalized](#FrameCountKey-internalized) | Der Bildanzahl-Schlüssel |
| [FrameStepKey_internalized](#FrameStepKey-internalized) | Der Bildschritt-Schlüssel |
| [HeightKey_internalized](#HeightKey-internalized) | Der Höhen-Schlüssel |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Der horizontale Bezeichner-Name |
| [IdentKey_internalized](#IdentKey-internalized) | Der eindeutige Bezeichner-Schlüssel |
| [ItemsPropertyCannotBeNull_internalized](#ItemsPropertyCannotBeNull-internalized) | Die Items-Eigenschaft darf nicht null sein |
| [LeftKey_internalized](#LeftKey-internalized) | Der linke Schlüssel |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Der Mesh-Punkte-Schlüsselname |
| [NonAffineTransformKey_internalized](#NonAffineTransformKey-internalized) | Der nicht-affine Transformationsschlüssel |
| [NullClassId_internalized](#NullClassId-internalized) | Der Null-Klassenbezeichner |
| [NumeratorKey_internalized](#NumeratorKey-internalized) | Der Zähler-Schlüssel |
| [OptionalKeys_internalized](#OptionalKeys-internalized) | Die Sammlung optionaler Schlüssel |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Der Orientierungsbezeichner-Name |
| [OriginalCompIdKey_internalized](#OriginalCompIdKey-internalized) | Der Schlüsselname der ursprünglichen CompID |
| [PageNumberKey_internalized](#PageNumberKey-internalized) | Der Seitenzahl-Schlüssel |
| [PlacedIdKey_internalized](#PlacedIdKey-internalized) | Der platzierte Bezeichner-Schlüssel |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | Der erwartete Versionswert |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Die PSB‑Header‑Version |
| [PsbResourceSignature](#PsbResourceSignature) | Die PSB‑spezifische Ressourcen‑Signatur. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Die PSD‑Header‑Version |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Der rationale Punktklassenbezeichner-Name |
| [ResolutionKey_internalized](#ResolutionKey-internalized) | Der Auflösungs-Schlüssel |
| [ResourceSignature](#ResourceSignature) | Die allgemeine Ressourcen‑Signatur. |
| [RightKey_internalized](#RightKey-internalized) | Der rechte Schlüssel |
| [SizeKey_internalized](#SizeKey-internalized) | Der Größen-Schlüssel |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | Die Größe von double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | Die Größe von int |
| [SmartVersionValue_internalized](#SmartVersionValue-internalized) | Der erwartete Smart-Object-Ressourcenversionswert. |
| [TopKey_internalized](#TopKey-internalized) | Der obere Schlüssel |
| [TotalPagesKey_internalized](#TotalPagesKey-internalized) | Der Gesamtseiten-Schlüssel |
| [TransformKey_internalized](#TransformKey-internalized) | Der Transformations-Schlüssel |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Die Transformationswert-Anzahl |
| [TypeKey_internalized](#TypeKey-internalized) | Der Typ-Schlüssel |
| [TypeToolKey](#TypeToolKey) | Der Typwerkzeug‑Info‑Schlüssel: 'SoLd'. |
| [TypeValue_internalized](#TypeValue-internalized) | Der erwartete Typwert. |
| [UOrderKey_internalized](#UOrderKey-internalized) | Der u-Ordnungsschlüssel |
| [VOrderKey_internalized](#VOrderKey-internalized) | Der v-Ordnungsschlüssel |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Der vertikale Bezeichner-Name |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Der benutzerdefinierte Warp-Name |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Die Warp-Header-Länge. |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | Die Warp-Header-Länge. |
| [WarpKey_internalized](#WarpKey-internalized) | Der Warp-Schlüssel. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Der Warp-None-Name |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | Der Warp-Perspektivschlüssel |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | Der Warp-Perspektive-Other |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | Der Warp-Drehschlüssel |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | Der Warp-Stil-Schlüssel |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | Der Warp-Wertschlüssel |
| [WidthKey_internalized](#WidthKey-internalized) | Der Breiten‑Schlüssel |
| [YouCannotAccessCropPropertyMessage_internalized](#YouCannotAccessCropPropertyMessage-internalized) | Sie können nicht auf die Crop‑Eigenschaft zugreifen Nachricht |
| [YouCannotSetCompIdPropertyMessage_internalized](#YouCannotSetCompIdPropertyMessage-internalized) | Sie können die CompId‑Eigenschaft nicht setzen Nachricht |
| [YouCannotSetCompPropertyMessage_internalized](#YouCannotSetCompPropertyMessage-internalized) | Sie können die Comp‑Eigenschaft nicht setzen Nachricht |
| [YouCannotSetOriginalCompIdPropertyMessage_internalized](#YouCannotSetOriginalCompIdPropertyMessage-internalized) | Sie können die OriginalCompId‑Eigenschaft nicht setzen Nachricht |
| [ZeroChar_internalized](#ZeroChar-internalized) | Das Nullzeichen. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Die Venture-Lizenz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Behauptet, dass der angegebene tatsächliche Wert dem erwarteten Wert entspricht. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Überprüft das und setzt, ob die Ressource PSB-spezifisch ist. |
| [convertListStructureToDoubleArray_internalized(ListStructure list)](#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-) | Konvertiert die Listenstruktur in ein Double‑Array. |
| [create_internalized(System.Guid uniqueId, boolean isCustom, boolean hasCompInfo)](#create-internalized-com.aspose.ms.System.Guid-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Liest oder setzt die Anti‑Alias‑Richtlinie der Smart‑Object‑Layer‑Daten im PSD‑Bild. |
| [getBottom()](#getBottom--) | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| [getBounds()](#getBounds--) | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| [getClass()](#getClass--) |  |
| [getComp()](#getComp--) | Liest oder setzt den Comp‑Wert der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getCompId()](#getCompId--) | Liest oder setzt die ID der aktuell ausgewählten Komponente für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. |
| [getCrop()](#getCrop--) | Liest oder setzt den Zuschnitt der Smart‑Object‑Layer‑Daten im PSD‑Bild. |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix. |
| [getDurationDenominator()](#getDurationDenominator--) | Liest oder setzt den Dauer‑Nenner. |
| [getDurationNumerator()](#getDurationNumerator--) | Liest oder setzt den Dauer‑Zähler. |
| [getFrameCount()](#getFrameCount--) | Liest oder setzt die Bildanzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getFrameStepDenominator()](#getFrameStepDenominator--) | Liest oder setzt den Bildschritt‑Nenner. |
| [getFrameStepNumerator()](#getFrameStepNumerator--) | Liest oder setzt den Bildschritt‑Zähler. |
| [getHeader_internalized()](#getHeader-internalized--) | Ermittelt oder legt den Header fest. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [getItems()](#getItems--) | Liest oder setzt die Deskriptor‑Elemente der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getKey()](#getKey--) | Ermittelt den Schichtressourcen-Schlüssel. |
| [getLeft()](#getLeft--) | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| [getLength()](#getLength--) | Liest die Länge der Smart‑Object‑Ressource in Bytes. |
| [getNonAffineTransformMatrix()](#getNonAffineTransformMatrix--) | Liest oder setzt die nicht‑affine Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getOriginalCompId()](#getOriginalCompId--) | Liest die ursprüngliche ID der aktuell ausgewählten Comp für das Unterdokument, die -1 ist, wenn keine ausgewählt ist. |
| [getPageNumber()](#getPageNumber--) | Liest oder setzt die Seitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getPerspective()](#getPerspective--) | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [getPlacedId()](#getPlacedId--) | Liest oder setzt die eindeutige Kennung dieser Smart‑Object‑Layer‑Daten im PSD‑Bild. |
| [getPlacedId_internalized()](#getPlacedId-internalized--) |  |
| [getPlacedLayerType()](#getPlacedLayerType--) | Liest oder setzt den Typ der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Ermittelt die Präfixlänge. |
| [getPsdVersion()](#getPsdVersion--) | Ermittelt die minimale PSD-Version, die für die Schichtressource erforderlich ist. |
| [getResolution()](#getResolution--) | Liest oder setzt die Auflösung der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getResolutionUnit()](#getResolutionUnit--) | Liest oder setzt die Auflösungseinheit der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getRight()](#getRight--) | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| [getSignature()](#getSignature--) | Ermittelt die Signatur der Schichtressource. |
| [getTop()](#getTop--) | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| [getTotalPages()](#getTotalPages--) | Liest oder setzt die Gesamtseitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt die Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei |
| [getUOrder()](#getUOrder--) | Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [getUniqueId()](#getUniqueId--) | Liest oder setzt die globale eindeutige Kennung der Smart‑Object‑Layer‑Daten [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) im PSD‑Bild. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Liest oder setzt den V-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [getValue()](#getValue--) | Liest oder setzt den Verzerrungswert der platzierten Ebene im PSD-Bild. |
| [getVersion()](#getVersion--) | Liest die Version der platzierten Ebene in der PSD-Datei, normalerweise 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Liest oder setzt die Klassen-ID. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Liest oder setzt den Verzerrungsklassennamen. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Liest oder setzt die Warp-Deskriptor-Version. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Die Warp-Elemente. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Liest oder setzt die Warp-Version. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Liest die [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) am angegebenen Index. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Liest einen Wert, der angibt, ob diese Instanz Begrenzungseinheiten hat. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [initializeBounds_internalized(Rectangle bounds)](#initializeBounds-internalized-com.aspose.psd.Rectangle-) | Initialisiert die Grenzen und Matrizen. |
| [initializeItems_internalized()](#initializeItems-internalized--) |  |
| [isCustom()](#isCustom--) | Liest oder setzt einen Wert, der angibt, ob der Warp-Stil dieser Instanz benutzerdefiniert ist. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Bestimmt, ob die Ressource PSB-spezifisch ist. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Ermittelt einen Wert, der angibt, ob diese Instanz ressourcen-PSB-spezifisch ist. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Liest oder setzt einen Wert, der angibt, ob die Rotationsausrichtung dieser Instanz horizontal ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Speichert die Smart-Object-Ressource im angegebenen Stream-Container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Speichert den benutzerdefinierten Ressourcen-Header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Speichert die Header-Signatur, den Bezeichner und die Länge. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Liest oder setzt die Anti‑Alias‑Richtlinie der Smart‑Object‑Layer‑Daten im PSD‑Bild. |
| [setBottom(double value)](#setBottom-double-) | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| [setComp(int value)](#setComp-int-) | Liest oder setzt den Comp‑Wert der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setCompId(int value)](#setCompId-int-) | Liest oder setzt die ID der aktuell ausgewählten Komponente für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. |
| [setCrop(int value)](#setCrop-int-) | Liest oder setzt den Zuschnitt der Smart‑Object‑Layer‑Daten im PSD‑Bild. |
| [setCustom(boolean value)](#setCustom-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Warp-Stil dieser Instanz benutzerdefiniert ist. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix. |
| [setDurationDenominator(int value)](#setDurationDenominator-int-) | Liest oder setzt den Dauer‑Nenner. |
| [setDurationNumerator(int value)](#setDurationNumerator-int-) | Liest oder setzt den Dauer‑Zähler. |
| [setFrameCount(int value)](#setFrameCount-int-) | Liest oder setzt die Bildanzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setFrameStepDenominator(int value)](#setFrameStepDenominator-int-) | Liest oder setzt den Bildschritt‑Nenner. |
| [setFrameStepNumerator(int value)](#setFrameStepNumerator-int-) | Liest oder setzt den Bildschritt‑Zähler. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Ermittelt oder legt den Header fest. |
| [setHeight(double value)](#setHeight-double-) | Liest oder setzt die Höhe. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Liest oder setzt die Deskriptor‑Elemente der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setLeft(double value)](#setLeft-double-) | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| [setNonAffineTransformMatrix(double[] value)](#setNonAffineTransformMatrix-double---) | Liest oder setzt die nicht‑affine Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setOriginalCompId_internalized(int value)](#setOriginalCompId-internalized-int-) | Liest die ursprüngliche ID der aktuell ausgewählten Comp für das Unterdokument, die -1 ist, wenn keine ausgewählt ist. |
| [setPageNumber(int value)](#setPageNumber-int-) | Liest oder setzt die Seitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setPerspective(double value)](#setPerspective-double-) | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | Liest oder setzt die eindeutige Kennung dieser Smart‑Object‑Layer‑Daten im PSD‑Bild. |
| [setPlacedId_internalized(System.Guid value)](#setPlacedId-internalized-com.aspose.ms.System.Guid-) |  |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Liest oder setzt den Typ der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setResolution(double value)](#setResolution-double-) | Liest oder setzt die Auflösung der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Liest oder setzt die Auflösungseinheit der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setRight(double value)](#setRight-double-) | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Rotationsausrichtung dieser Instanz horizontal ist. |
| [setTop(double value)](#setTop-double-) | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| [setTotalPages(int value)](#setTotalPages-int-) | Liest oder setzt die Gesamtseitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Liest oder setzt die Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei |
| [setUOrder(int value)](#setUOrder-int-) | Liest oder setzt den U-Order-Wert der platzierten Ebene in der PSD-Datei. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Liest oder setzt die globale eindeutige Kennung der Smart‑Object‑Layer‑Daten [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) im PSD‑Bild. |
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
| [setWidth(double value)](#setWidth-double-) | Liest oder setzt die Breite. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SoLdResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo) {#SoLdResource-java.util.UUID-boolean-boolean-}
```
public SoLdResource(UUID uniqueId, boolean isCustom, boolean hasCompInfo)
```


Initialisiert eine neue Instanz der Klasse [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource). Es ist notwendig, die Items‑Eigenschaft zu setzen oder InitializeItems() aufzurufen, um eine fertige Instanz zu erhalten. Dieser Konstruktor ist für die Verwendung durch [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator) und in Unit‑Tests vorgesehen. Verwenden Sie [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator), um SoLdResource‑Klassen zu erstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | java.util.UUID | Der eindeutige Bezeichner der Smart‑Object‑Ebene‑Daten [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource). |
| isCustom | boolean | wenn auf  true  gesetzt, [ist benutzerdefiniert]. |
| hasCompInfo | boolean | wenn auf  true  gesetzt, [hat Komp‑Informationen]. |

### SoLdResource() {#SoLdResource--}
```
public SoLdResource()
```


Initialisiert eine neue Instanz der Klasse [SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource). Dieser Standardkonstruktor ist für die Verwendung durch SoLdResourceLoader vorgesehen. Verwenden Sie [SmartResourceCreator](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartresourcecreator), um SoLdResource‑Klassen zu erstellen.

### AntiAliasPolicyKey_internalized {#AntiAliasPolicyKey-internalized}
```
public static final String AntiAliasPolicyKey_internalized
```


Der Anti‑Aliasing‑Richtlinien‑Schlüssel

### BottomKey_internalized {#BottomKey-internalized}
```
public static final String BottomKey_internalized
```


Der untere Schlüssel

### BoundsKey_internalized {#BoundsKey-internalized}
```
public static final String BoundsKey_internalized
```


Der Begrenzungs‑Schlüssel

### CompIdKey_internalized {#CompIdKey-internalized}
```
public static final String CompIdKey_internalized
```


Der Schlüsselname der CompID

### CompInfoKey_internalized {#CompInfoKey-internalized}
```
public static final String CompInfoKey_internalized
```


Der Name des Comp-Informationsschlüssels

### CompKey_internalized {#CompKey-internalized}
```
public static final String CompKey_internalized
```


Der Comp-Schlüssel

### CompNoneValue_internalized {#CompNoneValue-internalized}
```
public static final int CompNoneValue_internalized
```


Der Comp-Wert, der 'none' bedeutet

### CropKey_internalized {#CropKey-internalized}
```
public static final String CropKey_internalized
```


Der Zuschneide-Schlüssel

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

### DenominatorKey_internalized {#DenominatorKey-internalized}
```
public static final String DenominatorKey_internalized
```


Der Nenner-Schlüssel

### DurationKey_internalized {#DurationKey-internalized}
```
public static final String DurationKey_internalized
```


Der Dauer-Schlüssel

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

### FrameCountKey_internalized {#FrameCountKey-internalized}
```
public static final String FrameCountKey_internalized
```


Der Bildanzahl-Schlüssel

### FrameStepKey_internalized {#FrameStepKey-internalized}
```
public static final String FrameStepKey_internalized
```


Der Bildschritt-Schlüssel

### HeightKey_internalized {#HeightKey-internalized}
```
public static final String HeightKey_internalized
```


Der Höhen-Schlüssel

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Der horizontale Bezeichner-Name

### IdentKey_internalized {#IdentKey-internalized}
```
public static final String IdentKey_internalized
```


Der eindeutige Bezeichner-Schlüssel

### ItemsPropertyCannotBeNull_internalized {#ItemsPropertyCannotBeNull-internalized}
```
public static final String ItemsPropertyCannotBeNull_internalized
```


Die Items-Eigenschaft darf nicht null sein

### LeftKey_internalized {#LeftKey-internalized}
```
public static final String LeftKey_internalized
```


Der linke Schlüssel

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Der Mesh-Punkte-Schlüsselname

### NonAffineTransformKey_internalized {#NonAffineTransformKey-internalized}
```
public static final String NonAffineTransformKey_internalized
```


Der nicht-affine Transformationsschlüssel

### NullClassId_internalized {#NullClassId-internalized}
```
public static final String NullClassId_internalized
```


Der Null-Klassenbezeichner

### NumeratorKey_internalized {#NumeratorKey-internalized}
```
public static final String NumeratorKey_internalized
```


Der Zähler-Schlüssel

### OptionalKeys_internalized {#OptionalKeys-internalized}
```
public static final String[] OptionalKeys_internalized
```


Die Sammlung optionaler Schlüssel

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Der Orientierungsbezeichner-Name

### OriginalCompIdKey_internalized {#OriginalCompIdKey-internalized}
```
public static final String OriginalCompIdKey_internalized
```


Der Schlüsselname der ursprünglichen CompID

### PageNumberKey_internalized {#PageNumberKey-internalized}
```
public static final String PageNumberKey_internalized
```


Der Seitenzahl-Schlüssel

### PlacedIdKey_internalized {#PlacedIdKey-internalized}
```
public static final String PlacedIdKey_internalized
```


Der platzierte Bezeichner-Schlüssel

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

### ResolutionKey_internalized {#ResolutionKey-internalized}
```
public static final String ResolutionKey_internalized
```


Der Auflösungs-Schlüssel

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Die allgemeine Ressourcen‑Signatur.

### RightKey_internalized {#RightKey-internalized}
```
public static final String RightKey_internalized
```


Der rechte Schlüssel

### SizeKey_internalized {#SizeKey-internalized}
```
public static final String SizeKey_internalized
```


Der Größen-Schlüssel

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

### SmartVersionValue_internalized {#SmartVersionValue-internalized}
```
public static final int SmartVersionValue_internalized
```


Der erwartete Smart-Object-Ressourcenversionswert.

### TopKey_internalized {#TopKey-internalized}
```
public static final String TopKey_internalized
```


Der obere Schlüssel

### TotalPagesKey_internalized {#TotalPagesKey-internalized}
```
public static final String TotalPagesKey_internalized
```


Der Gesamtseiten-Schlüssel

### TransformKey_internalized {#TransformKey-internalized}
```
public static final String TransformKey_internalized
```


Der Transformations-Schlüssel

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Die Transformationswert-Anzahl

### TypeKey_internalized {#TypeKey-internalized}
```
public static final String TypeKey_internalized
```


Der Typ-Schlüssel

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Der Typwerkzeug‑Info‑Schlüssel: 'SoLd'.

### TypeValue_internalized {#TypeValue-internalized}
```
public static final String TypeValue_internalized
```


Der erwartete Typwert.

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

### WidthKey_internalized {#WidthKey-internalized}
```
public static final String WidthKey_internalized
```


Der Breiten‑Schlüssel

### YouCannotAccessCropPropertyMessage_internalized {#YouCannotAccessCropPropertyMessage-internalized}
```
public static final String YouCannotAccessCropPropertyMessage_internalized
```


Sie können nicht auf die Crop‑Eigenschaft zugreifen Nachricht

### YouCannotSetCompIdPropertyMessage_internalized {#YouCannotSetCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetCompIdPropertyMessage_internalized
```


Sie können die CompId‑Eigenschaft nicht setzen Nachricht

### YouCannotSetCompPropertyMessage_internalized {#YouCannotSetCompPropertyMessage-internalized}
```
public static final String YouCannotSetCompPropertyMessage_internalized
```


Sie können die Comp‑Eigenschaft nicht setzen Nachricht

### YouCannotSetOriginalCompIdPropertyMessage_internalized {#YouCannotSetOriginalCompIdPropertyMessage-internalized}
```
public static final String YouCannotSetOriginalCompIdPropertyMessage_internalized
```


Sie können die OriginalCompId‑Eigenschaft nicht setzen Nachricht

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

### convertListStructureToDoubleArray_internalized(ListStructure list) {#convertListStructureToDoubleArray-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ListStructure-}
```
public static double[] convertListStructureToDoubleArray_internalized(ListStructure list)
```


Konvertiert die Listenstruktur in ein Double‑Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| list | [ListStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/liststructure) | Die ListStructure-Instanz. |

**Returns:**
double[] – Das erstellte double[]-Array.
### create_internalized(System.Guid uniqueId, boolean isCustom, boolean hasCompInfo) {#create-internalized-com.aspose.ms.System.Guid-boolean-boolean-}
```
public static SoLdResource create_internalized(System.Guid uniqueId, boolean isCustom, boolean hasCompInfo)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid |  |
| isCustom | boolean |  |
| hasCompInfo | boolean |  |

**Returns:**
[SoLdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/soldresource)
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


Liest oder setzt die Anti‑Alias‑Richtlinie der Smart‑Object‑Layer‑Daten im PSD‑Bild.

Wert: Die Antialiasing-Richtlinie der Smart-Object-Ebenendaten.

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
### getComp() {#getComp--}
```
public final int getComp()
```


Liest oder setzt den Comp-Wert der Smart-Object-Ebenendaten in der PSD-Datei.  Layer-Comps in Smart Objects

Wert: Der Comp-Wert, ist -1, wenn keiner vorhanden ist.

**Returns:**
int
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Liest oder setzt die ID des aktuell ausgewählten Comps für das Unterdokument, die -1 ist, wenn keiner ausgewählt ist. Comps sind Zusammensetzungen eines Seitenlayouts, die Designer erstellen können. Mit Layer-Comps können Sie mehrere Versionen eines Layouts in einer einzigen Adobe Photoshop‑Datei erstellen, verwalten und anzeigen. Ein Layer-Comp ist ein Schnappschuss eines Zustands des Ebenen‑Panels. Layer-Comps speichern drei Arten von Ebenenoptionen, aber diese Eigenschaft gibt die Auswahl‑ID des Layer‑Comps für die Smart‑Object‑Ebene in der PSD‑Datei zurück.  Layer-Comps in Smart Objects

Wert: Die ID des aktuell ausgewählten Comps für das Unterdokument im PSD‑Bild, die -1 ist, wenn keiner ausgewählt ist.

**Returns:**
int
### getCrop() {#getCrop--}
```
public final int getCrop()
```


Liest oder setzt den Zuschnitt der Smart‑Object‑Layer‑Daten im PSD‑Bild.

Wert: Der Beschnittwert der platzierten Ebeneninformationen.

**Returns:**
int
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Liest oder setzt den Standard-Einheitstyp für zugewiesene Werte wie Left, Top, Right, Bottom, TransformMatrix.

Wert: Der Standard-Maßeinheitstyp.

**Returns:**
int
### getDurationDenominator() {#getDurationDenominator--}
```
public final int getDurationDenominator()
```


Liest oder setzt den Dauer‑Nenner.

Wert: Der Dauer‑Nenner.

**Returns:**
int
### getDurationNumerator() {#getDurationNumerator--}
```
public final int getDurationNumerator()
```


Liest oder setzt den Dauer‑Zähler.

Wert: Der Dauer‑Zähler.

**Returns:**
int
### getFrameCount() {#getFrameCount--}
```
public final int getFrameCount()
```


Liest oder setzt die Bildanzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Bildanzahl der platzierten Ebeneninformationen.

**Returns:**
int
### getFrameStepDenominator() {#getFrameStepDenominator--}
```
public final int getFrameStepDenominator()
```


Liest oder setzt den Bildschritt‑Nenner.

Wert: Der Bildschritt‑Nenner.

**Returns:**
int
### getFrameStepNumerator() {#getFrameStepNumerator--}
```
public final int getFrameStepNumerator()
```


Liest oder setzt den Bildschritt‑Zähler.

Wert: Der Bildschritt‑Zähler.

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
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Liest oder setzt die Höhe.

Wert: Die Höhe.

**Returns:**
double
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


Liest oder setzt die Deskriptor‑Elemente der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Deskriptor‑Elemente der platzierten Ebeneninformationen.

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
public int getLength()
```


Liest die Länge der Smart‑Object‑Ressource in Bytes.

**Returns:**
int
### getNonAffineTransformMatrix() {#getNonAffineTransformMatrix--}
```
public final double[] getNonAffineTransformMatrix()
```


Liest oder setzt die nicht‑affine Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die nicht‑affine Transformationsmatrix der Smart‑Object‑Ebene.

**Returns:**
double[]
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Liest die ursprüngliche ID des aktuell ausgewählten Comps für das Unterdokument, die -1 ist, wenn keiner ausgewählt ist. Diese Eigenschaft gibt die ursprüngliche Layer‑Comp‑Auswahl‑ID für die Smart‑Object‑Ebene in der PSD‑Datei zurück.  Layer-Comps in Smart Objects

Wert: Die ursprüngliche ID des aktuell ausgewählten Comps für das Unterdokument im PSD‑Bild, die -1 ist, wenn keiner ausgewählt ist.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Liest oder setzt die Seitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Seitennummer der Smart‑Object‑Ebenendaten.

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
### getPlacedId() {#getPlacedId--}
```
public final UUID getPlacedId()
```


Liest oder setzt die eindeutige Kennung dieser Smart‑Object‑Layer‑Daten im PSD‑Bild.

Wert: Der eindeutige Bezeichner dieser Smart‑Object‑Ebenenressource.

**Returns:**
java.util.UUID
### getPlacedId_internalized() {#getPlacedId-internalized--}
```
public final System.Guid getPlacedId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Liest oder setzt den Typ der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Der Typ der Smart‑Object‑Ebenendaten.

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
### getResolution() {#getResolution--}
```
public final double getResolution()
```


Liest oder setzt die Auflösung der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Auflösung der Smart‑Object‑Ebene.

**Returns:**
double
### getResolutionUnit() {#getResolutionUnit--}
```
public final int getResolutionUnit()
```


Liest oder setzt die Auflösungseinheit der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Einheit der Auflösung der Smart‑Object‑Ebene.

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


Liest oder setzt die Gesamtseitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Gesamtseitenzahl der Smart‑Object‑Ebene‑Daten.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Liest oder setzt die Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei

Wert: Die Transformationsmatrix der Smart‑Object‑Ebene‑Daten.

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


Liest oder setzt die globale eindeutige Kennung der Smart‑Object‑Layer‑Daten [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) im PSD‑Bild.

Wert: Der global eindeutige Bezeichner der Smart‑Object‑Ebene‑Daten [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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


Die Warp-Elemente.

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
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Liest oder setzt die Breite.

Wert: Die Breite.

**Returns:**
double
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

### initializeBounds_internalized(Rectangle bounds) {#initializeBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void initializeBounds_internalized(Rectangle bounds)
```


Initialisiert die Grenzen und Matrizen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Begrenzungen. |

### initializeItems_internalized() {#initializeItems-internalized--}
```
public void initializeItems_internalized()
```




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
public void save(StreamContainer streamContainer, int psdVersion)
```


Speichert die Smart-Object-Ressource im angegebenen Stream-Container.

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


Liest oder setzt die Anti‑Alias‑Richtlinie der Smart‑Object‑Layer‑Daten im PSD‑Bild.

Wert: Die Antialiasing-Richtlinie der Smart-Object-Ebenendaten.

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

### setComp(int value) {#setComp-int-}
```
public final void setComp(int value)
```


Liest oder setzt den Comp-Wert der Smart-Object-Ebenendaten in der PSD-Datei.  Layer-Comps in Smart Objects

Wert: Der Comp-Wert, ist -1, wenn keiner vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Liest oder setzt die ID des aktuell ausgewählten Comps für das Unterdokument, die -1 ist, wenn keiner ausgewählt ist. Comps sind Zusammensetzungen eines Seitenlayouts, die Designer erstellen können. Mit Layer-Comps können Sie mehrere Versionen eines Layouts in einer einzigen Adobe Photoshop‑Datei erstellen, verwalten und anzeigen. Ein Layer-Comp ist ein Schnappschuss eines Zustands des Ebenen‑Panels. Layer-Comps speichern drei Arten von Ebenenoptionen, aber diese Eigenschaft gibt die Auswahl‑ID des Layer‑Comps für die Smart‑Object‑Ebene in der PSD‑Datei zurück.  Layer-Comps in Smart Objects

Wert: Die ID des aktuell ausgewählten Comps für das Unterdokument im PSD‑Bild, die -1 ist, wenn keiner ausgewählt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setCrop(int value) {#setCrop-int-}
```
public final void setCrop(int value)
```


Liest oder setzt den Zuschnitt der Smart‑Object‑Layer‑Daten im PSD‑Bild.

Wert: Der Beschnittwert der platzierten Ebeneninformationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setDurationDenominator(int value) {#setDurationDenominator-int-}
```
public final void setDurationDenominator(int value)
```


Liest oder setzt den Dauer‑Nenner.

Wert: Der Dauer‑Nenner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDurationNumerator(int value) {#setDurationNumerator-int-}
```
public final void setDurationNumerator(int value)
```


Liest oder setzt den Dauer‑Zähler.

Wert: Der Dauer‑Zähler.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFrameCount(int value) {#setFrameCount-int-}
```
public final void setFrameCount(int value)
```


Liest oder setzt die Bildanzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Bildanzahl der platzierten Ebeneninformationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFrameStepDenominator(int value) {#setFrameStepDenominator-int-}
```
public final void setFrameStepDenominator(int value)
```


Liest oder setzt den Bildschritt‑Nenner.

Wert: Der Bildschritt‑Nenner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFrameStepNumerator(int value) {#setFrameStepNumerator-int-}
```
public final void setFrameStepNumerator(int value)
```


Liest oder setzt den Bildschritt‑Zähler.

Wert: Der Bildschritt‑Zähler.

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

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Liest oder setzt die Höhe.

Wert: Die Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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


Liest oder setzt die Deskriptor‑Elemente der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Deskriptor‑Elemente der platzierten Ebeneninformationen.

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

### setNonAffineTransformMatrix(double[] value) {#setNonAffineTransformMatrix-double---}
```
public final void setNonAffineTransformMatrix(double[] value)
```


Liest oder setzt die nicht‑affine Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die nicht‑affine Transformationsmatrix der Smart‑Object‑Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setOriginalCompId_internalized(int value) {#setOriginalCompId-internalized-int-}
```
public final void setOriginalCompId_internalized(int value)
```


Liest die ursprüngliche ID des aktuell ausgewählten Comps für das Unterdokument, die -1 ist, wenn keiner ausgewählt ist. Diese Eigenschaft gibt die ursprüngliche Layer‑Comp‑Auswahl‑ID für die Smart‑Object‑Ebene in der PSD‑Datei zurück.  Layer-Comps in Smart Objects

Wert: Die ursprüngliche ID des aktuell ausgewählten Comps für das Unterdokument im PSD‑Bild, die -1 ist, wenn keiner ausgewählt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Liest oder setzt die Seitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Seitennummer der Smart‑Object‑Ebenendaten.

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

### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public final void setPlacedId(UUID value)
```


Liest oder setzt die eindeutige Kennung dieser Smart‑Object‑Layer‑Daten im PSD‑Bild.

Wert: Der eindeutige Bezeichner dieser Smart‑Object‑Ebenenressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### setPlacedId_internalized(System.Guid value) {#setPlacedId-internalized-com.aspose.ms.System.Guid-}
```
public final void setPlacedId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Guid |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Liest oder setzt den Typ der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Der Typ der Smart‑Object‑Ebenendaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setResolution(double value) {#setResolution-double-}
```
public final void setResolution(double value)
```


Liest oder setzt die Auflösung der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Auflösung der Smart‑Object‑Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public final void setResolutionUnit(int value)
```


Liest oder setzt die Auflösungseinheit der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Einheit der Auflösung der Smart‑Object‑Ebene.

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


Liest oder setzt die Gesamtseitenzahl der Smart‑Object‑Layer‑Daten in der PSD‑Datei.

Wert: Die Gesamtseitenzahl der Smart‑Object‑Ebene‑Daten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Liest oder setzt die Transformationsmatrix der Smart‑Object‑Layer‑Daten in der PSD‑Datei

Wert: Die Transformationsmatrix der Smart‑Object‑Ebene‑Daten.

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


Liest oder setzt die globale eindeutige Kennung der Smart‑Object‑Layer‑Daten [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource) im PSD‑Bild.

Wert: Der global eindeutige Bezeichner der Smart‑Object‑Ebene‑Daten [SmartObjectResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/smartobjectresource).

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

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Liest oder setzt die Breite.

Wert: Die Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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


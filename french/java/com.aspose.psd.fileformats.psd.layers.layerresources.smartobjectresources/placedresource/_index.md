---
title: "PlacedResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe PlacedResource qui contient des informations communes sur un calque placé ou un calque d'objet dynamique dans le fichier PSD."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

Définit la classe PlacedResource qui contient des informations communes sur un calque placé ou un calque d'objet intelligent dans le fichier PSD. Elle est utilisée pour prendre en charge les calques d'objet intelligent dans les images Adobe\ufffd Photoshop\ufffd.
## Champs

| Champ | Description |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | Le nom de la déformation d'enveloppe personnalisée |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | Le nom de la classe de déformation par défaut |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | Le nom de la classe de déformation par défaut |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | La version du descripteur de déformation attendue |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | La version de la déformation attendue |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | Le nom de l'identifiant horizontal |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | Le nom de la clé des points de maillage |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | Le nom de l'identifiant d'orientation |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | La valeur de version attendue |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | La version d'en-tête PSB |
| [PsbResourceSignature](#PsbResourceSignature) | La signature de ressource spécifique à PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | La version d'en-tête PSD |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | Le nom de l'identifiant de la classe de point rationnel |
| [ResourceSignature](#ResourceSignature) | La signature de ressource commune. |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | La taille du double |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | La taille de l'entier |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | Le nombre de valeurs de transformation |
| [UOrderKey_internalized](#UOrderKey-internalized) | La clé d'ordre u |
| [VOrderKey_internalized](#VOrderKey-internalized) | La clé d'ordre v |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | Le nom de l'identifiant vertical |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | Le nom personnalisé de la déformation |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | La longueur de l'en-tête de la déformation. |
| [WarpKey_internalized](#WarpKey-internalized) | La clé de la déformation. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | Le nom de l'absence de déformation |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | La clé de perspective de déformation |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | L'autre perspective de déformation |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | La clé de rotation de déformation |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | La clé de style de déformation |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | La clé de valeur de déformation |
| [ZeroChar_internalized](#ZeroChar-internalized) | Le caractère zéro. |
| [ventureLicense_internalized](#ventureLicense-internalized) | La licence de l'entreprise. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | Vérifie que la valeur réelle spécifiée est égale à la valeur attendue. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Vérifie et définit si la ressource est spécifique PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD. |
| [getBottom()](#getBottom--) | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| [getBounds()](#getBounds--) | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Obtient ou définit le type d'unité par défaut pour les valeurs assignées telles que Left, Top, Right, Bottom, TransformMatrix. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [getItems()](#getItems--) | Obtient ou définit les éléments de déformation. |
| [getKey()](#getKey--) | Obtient la clé de la ressource de calque. |
| [getLeft()](#getLeft--) | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| [getLength()](#getLength--) | Obtient la longueur de la ressource de calque en octets. |
| [getPageNumber()](#getPageNumber--) | Obtient ou définit le numéro de page du calque placé dans le fichier PSD. |
| [getPerspective()](#getPerspective--) | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Obtient ou définit le type du calque placé dans le fichier PSD. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Obtient la longueur du préfixe. |
| [getPsdVersion()](#getPsdVersion--) | Obtient la version minimale de PSD requise pour la ressource de calque. |
| [getRight()](#getRight--) | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| [getSignature()](#getSignature--) | Obtient la signature de la ressource de calque. |
| [getTop()](#getTop--) | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| [getTotalPages()](#getTotalPages--) | Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD. |
| [getUOrder()](#getUOrder--) | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| [getUniqueId()](#getUniqueId--) | Obtient ou définit l'identifiant unique global du calque placé dans l'image PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Obtient ou définit la valeur V order du calque placé dans le fichier PSD. |
| [getValue()](#getValue--) | Obtient ou définit la valeur warp du calque placé dans l'image PSD. |
| [getVersion()](#getVersion--) | Obtient la version du calque placé dans le fichier PSD, généralement 3. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Obtient ou définit l'unité de mesure des points de maillage verticaux. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | Obtient ou définit l'ID de classe. |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | Obtient ou définit le nom de classe warp. |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | Obtient ou définit la version du descripteur warp. |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | Obtient ou définit les éléments de déformation. |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | Obtient ou définit la version warp. |
| [get_Item(String index)](#get-Item-java.lang.String-) | Obtient le [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) à l'index spécifié. |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | Obtient une valeur indiquant si cette instance possède des unités de limites. |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | Obtient ou définit une valeur indiquant si le style warp de cette instance est personnalisé. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Détermine si la ressource est spécifique PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Obtient une valeur indiquant si cette instance est une ressource spécifique PSB. |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | Obtient ou définit une valeur indiquant si l'orientation de rotation de cette instance est horizontale. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Enregistre l'en-tête de ressource personnalisé. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Enregistre la signature, l'identifiant et la longueur de l'en-tête. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD. |
| [setBottom(double value)](#setBottom-double-) | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Obtient ou définit une valeur indiquant si le style warp de cette instance est personnalisé. |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Obtient ou définit le type d'unité par défaut pour les valeurs assignées telles que Left, Top, Right, Bottom, TransformMatrix. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtient ou définit les éléments de déformation. |
| [setLeft(double value)](#setLeft-double-) | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Obtient ou définit le numéro de page du calque placé dans le fichier PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Obtient ou définit le type du calque placé dans le fichier PSD. |
| [setRight(double value)](#setRight-double-) | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | Obtient ou définit une valeur indiquant si l'orientation de rotation de cette instance est horizontale. |
| [setTop(double value)](#setTop-double-) | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Obtient ou définit l'identifiant unique global du calque placé dans l'image PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Obtient ou définit la valeur V order du calque placé dans le fichier PSD. |
| [setValue(double value)](#setValue-double-) | Obtient ou définit la valeur warp du calque placé dans l'image PSD. |
| [setVersion(int value)](#setVersion-int-) | Obtient la version du calque placé dans le fichier PSD, généralement 3. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Obtient ou définit l'unité de mesure des points de maillage verticaux. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Obtient ou définit l'ID de classe. |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | Obtient ou définit le nom de classe warp. |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | Obtient ou définit la version du descripteur warp. |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | Obtient ou définit la version warp. |
| [toString()](#toString--) | Renvoie une chaîne qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


Le nom de la déformation d'enveloppe personnalisée

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


Le nom de la classe de déformation par défaut

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


Le nom de la classe de déformation par défaut

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


La version du descripteur de déformation attendue

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


La version de la déformation attendue

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


Le nom de l'identifiant horizontal

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


Le nom de la clé des points de maillage

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


Le nom de l'identifiant d'orientation

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


La valeur de version attendue

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


La version d'en-tête PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


La signature de ressource spécifique à PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


La version d'en-tête PSD

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


Le nom de l'identifiant de la classe de point rationnel

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


La signature de ressource commune.

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


La taille du double

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


La taille de l'entier

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


Le nombre de valeurs de transformation

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


La clé d'ordre u

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


La clé d'ordre v

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


Le nom de l'identifiant vertical

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


Le nom personnalisé de la déformation

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


La longueur de l'en-tête de la déformation.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


La clé warp. Aussi le nom de classe warp par défaut.

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


Le nom de l'absence de déformation

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


La clé de perspective de déformation

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


L'autre perspective de déformation

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


La clé de rotation de déformation

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


La clé de style de déformation

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


La clé de valeur de déformation

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Le caractère zéro.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


La licence de l'entreprise.

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


Vérifie que la valeur réelle spécifiée est égale à la valeur attendue.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| actualValue | java.lang.Object | La valeur réelle. |
| expectedValue | java.lang.Object | La valeur attendue. |
| message | java.lang.String | Le message. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Vérifie et définit si la ressource est spécifique PSB. Certaines ressources ne sont pas reconnues pour le moment, mais nous disposons d'une liste complète des ressources spécifiques PSB qui modifient leur comportement lors de l'enregistrement. Nous devons donc vérifier cela dans UnknownResource au moins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | int | La clé. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD.

Valeur : la politique d'anticrénelage du calque placé.

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


Obtient ou définit la position inférieure du calque placé dans l'image PSD.

Valeur : la position inférieure du calque placé.

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtient ou définit les limites du calque placé dans le fichier PSD.

Valeur : les limites du calque placé.

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


Obtient ou définit le type d'unité par défaut pour les valeurs assignées telles que Left, Top, Right, Bottom, TransformMatrix.

Valeur : le type d'unité de mesure par défaut.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


Obtient ou définit l'unité de mesure des points de maillage horizontaux.

Valeur : l'unité de mesure des points de maillage horizontaux.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


Obtient ou définit les éléments de déformation.

Valeur : les éléments warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Obtient la clé de la ressource de calque.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


Obtient ou définit la position gauche du calque placé dans le fichier PSD.

Valeur : la position gauche du calque placé.

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


Obtient la longueur de la ressource de calque en octets.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Obtient ou définit le numéro de page du calque placé dans le fichier PSD.

Valeur: Le numéro de page de la couche placée.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD.

Valeur: La valeur de perspective de la couche placée.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD.

Valeur: L'autre valeur de perspective de la couche placée.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


Obtient ou définit le type du calque placé dans le fichier PSD.

Valeur: Le type de la couche placée.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Obtient la longueur du préfixe. La valeur par défaut est 12 pour les ressources 8BIM et 16 pour les 8B64.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| psdVersion | int | La version PSD. |

**Returns:**
int - La longueur du préfixe.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Obtient la version minimale de PSD requise pour la ressource de calque. 0 indique aucune restriction.

**Returns:**
int
### getRight() {#getRight--}
```
public final double getRight()
```


Obtient ou définit la position droite du calque placé dans le fichier PSD.

Valeur: La position droite de la couche placée.

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient la signature de la ressource de calque.

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


Obtient ou définit la position supérieure du calque placé dans l'image PSD.

Valeur: La position supérieure de la couche placée.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD.

Valeur: Le nombre total de pages de la couche placée.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD.

Valeur: La matrice de transformation de la couche placée.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre U de la couche placée.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


Obtient ou définit l'identifiant unique global du calque placé dans l'image PSD.

Valeur: L'identifiant unique de la couche placée.

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


Obtient ou définit la valeur V order du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre V de la couche placée.

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Obtient ou définit la valeur warp du calque placé dans l'image PSD.

Valeur: La valeur de déformation de la couche placée.

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient la version du calque placé dans le fichier PSD, généralement 3.

Valeur: La version de la couche placée.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


Obtient ou définit l'unité de mesure des points de maillage verticaux.

Valeur: L'unité de mesure des points de maillage verticaux.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


Obtient ou définit l'ID de classe.

Valeur: L'ID de classe.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


Obtient ou définit le nom de classe warp.

Valeur: Le nom de classe de déformation.

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


Obtient ou définit la version du descripteur warp.

Valeur: La version du descripteur de déformation.

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


Obtient ou définit les éléments de déformation.

Valeur : les éléments warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


Obtient ou définit la version warp.

Valeur: La version de la déformation.

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


Obtient le [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | java.lang.String | Le nom de la clé. |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


Obtient une valeur indiquant si cette instance possède des unités de limites.

Valeur:  true  si cette instance possède des unités de limites ; sinon,  false .

**Returns:**
booléen
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
| Paramètre | Type | Description |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé. Si true, il contient des points de maillage. Si réglé sur false, il efface les points de maillage.

Valeur:  true  si la couche placée a un style personnalisé ; sinon,  false .

**Returns:**
booléen
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Détermine si la ressource est spécifique PSB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | int | La clé de la ressource. |

**Returns:**
boolean -  true  si la ressource est spécifique PSB ; sinon,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Obtient une valeur indiquant si cette instance est une ressource spécifique PSB.

Valeur :  true  si cette instance est une ressource spécifique PSB ; sinon,  false .

**Returns:**
booléen
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


Obtient ou définit une valeur indiquant si l'orientation de rotation de cette instance est horizontale.

Valeur:  true  si l'orientation de rotation est horizontale ; sinon,  false .

**Returns:**
booléen
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


Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux où enregistrer. |
| psdVersion | int | La version PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Enregistre l'en-tête de ressource personnalisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |
| signature | int | La signature. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Enregistre la signature, l'identifiant et la longueur de l'en-tête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |
| signature | int | La signature. |
| isLengthLong | booléen | si réglé sur  true  la longueur est longue. |

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD.

Valeur : la politique d'anticrénelage du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Obtient ou définit la position inférieure du calque placé dans l'image PSD.

Valeur : la position inférieure du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Obtient ou définit les limites du calque placé dans le fichier PSD.

Valeur : les limites du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé. Si true, il contient des points de maillage. Si réglé sur false, il efface les points de maillage.

Valeur:  true  si la couche placée a un style personnalisé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Obtient ou définit le type d'unité par défaut pour les valeurs assignées telles que Left, Top, Right, Bottom, TransformMatrix.

Valeur : le type d'unité de mesure par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


Obtient ou définit l'unité de mesure des points de maillage horizontaux.

Valeur : l'unité de mesure des points de maillage horizontaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


Obtient ou définit les éléments de déformation.

Valeur : les éléments warp.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Obtient ou définit la position gauche du calque placé dans le fichier PSD.

Valeur : la position gauche du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Obtient ou définit le numéro de page du calque placé dans le fichier PSD.

Valeur: Le numéro de page de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD.

Valeur: La valeur de perspective de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD.

Valeur: L'autre valeur de perspective de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


Obtient ou définit le type du calque placé dans le fichier PSD.

Valeur: Le type de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Obtient ou définit la position droite du calque placé dans le fichier PSD.

Valeur: La position droite de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


Obtient ou définit une valeur indiquant si l'orientation de rotation de cette instance est horizontale.

Valeur:  true  si l'orientation de rotation est horizontale ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Obtient ou définit la position supérieure du calque placé dans l'image PSD.

Valeur: La position supérieure de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD.

Valeur: Le nombre total de pages de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD.

Valeur: La matrice de transformation de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre U de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


Obtient ou définit l'identifiant unique global du calque placé dans l'image PSD.

Valeur: L'identifiant unique de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


Obtient ou définit la valeur V order du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre V de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Obtient ou définit la valeur warp du calque placé dans l'image PSD.

Valeur: La valeur de déformation de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtient la version du calque placé dans le fichier PSD, généralement 3.

Valeur: La version de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


Obtient ou définit l'unité de mesure des points de maillage verticaux.

Valeur: L'unité de mesure des points de maillage verticaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


Obtient ou définit l'ID de classe.

Valeur: L'ID de classe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


Obtient ou définit le nom de classe warp.

Valeur: Le nom de classe de déformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


Obtient ou définit la version du descripteur warp.

Valeur: La version du descripteur de déformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


Obtient ou définit la version warp.

Valeur: La version de la déformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente cette instance.

**Returns:**
java.lang.String - Une chaîne qui représente cette instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


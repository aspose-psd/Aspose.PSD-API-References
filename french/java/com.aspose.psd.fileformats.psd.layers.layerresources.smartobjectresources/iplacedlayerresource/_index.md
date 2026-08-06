---
title: "IPlacedLayerResource"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit l'interface IPlacedLayerResource qui contient des informations sur un calque placé dans le fichier PSD."
type: docs
weight: 17
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Définit l'interface IPlacedLayerResource qui contient des informations sur un calque placé dans le fichier PSD. C'est une interface de balisage utilisée pour désigner les ressources PlLd, Sold et Sole dans les images Adobe\ufffd Photoshop\ufffd. Elle est utilisée pour prendre en charge les calques d'objet intelligent dans les images Adobe\ufffd Photoshop\ufffd.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD. |
| [getBottom()](#getBottom--) | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| [getBounds()](#getBounds--) | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [getItems()](#getItems--) | Obtient ou définit les éléments de déformation. |
| [getLeft()](#getLeft--) | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| [getPageNumber()](#getPageNumber--) | Obtient ou définit le numéro de page du calque placé dans le fichier PSD. |
| [getPerspective()](#getPerspective--) | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Obtient ou définit le type du calque placé dans le fichier PSD. |
| [getRight()](#getRight--) | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| [getTop()](#getTop--) | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| [getTotalPages()](#getTotalPages--) | Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD. |
| [getUOrder()](#getUOrder--) | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| [getUniqueId()](#getUniqueId--) | Obtient ou définit l'identifiant unique global du calque placé ou d'objet intelligent dans l'image PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Obtient ou définit la valeur V order du calque placé dans le fichier PSD. |
| [getValue()](#getValue--) | Obtient ou définit la valeur warp du calque placé dans l'image PSD. |
| [getVersion()](#getVersion--) | Obtient la version du calque placé dans le fichier PSD, généralement 3-5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Obtient ou définit l'unité de mesure des points de maillage verticaux. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [isCustom()](#isCustom--) | Obtient ou définit une valeur indiquant si le style warp de cette instance est personnalisé. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD. |
| [setBottom(double value)](#setBottom-double-) | Obtient ou définit la position inférieure du calque placé dans l'image PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtient ou définit les limites du calque placé dans le fichier PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Obtient ou définit une valeur indiquant si le style warp de cette instance est personnalisé. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Obtient ou définit l'unité de mesure des points de maillage horizontaux. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Obtient ou définit les éléments de déformation. |
| [setLeft(double value)](#setLeft-double-) | Obtient ou définit la position gauche du calque placé dans le fichier PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Obtient ou définit le numéro de page du calque placé dans le fichier PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Obtient ou définit le type du calque placé dans le fichier PSD. |
| [setRight(double value)](#setRight-double-) | Obtient ou définit la position droite du calque placé dans le fichier PSD. |
| [setTop(double value)](#setTop-double-) | Obtient ou définit la position supérieure du calque placé dans l'image PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Obtient ou définit l'identifiant unique global du calque placé ou d'objet intelligent dans l'image PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Obtient ou définit la valeur V order du calque placé dans le fichier PSD. |
| [setValue(double value)](#setValue-double-) | Obtient ou définit la valeur warp du calque placé dans l'image PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Obtient ou définit l'unité de mesure des points de maillage verticaux. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD.

Valeur : la politique d'anticrénelage du calque placé.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Obtient ou définit la position inférieure du calque placé dans l'image PSD.

Valeur : la position inférieure du calque placé.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Obtient ou définit les limites du calque placé dans le fichier PSD.

Valeur : les limites du calque placé.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Obtient ou définit l'unité de mesure des points de maillage horizontaux.

Valeur : l'unité de mesure des points de maillage horizontaux.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Obtient ou définit les éléments de déformation.

Valeur : les éléments warp.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Obtient ou définit la position gauche du calque placé dans le fichier PSD.

Valeur : la position gauche du calque placé.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Obtient ou définit le numéro de page du calque placé dans le fichier PSD.

Valeur: Le numéro de page de la couche placée.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD.

Valeur: La valeur de perspective de la couche placée.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD.

Valeur: L'autre valeur de perspective de la couche placée.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Obtient ou définit le type du calque placé dans le fichier PSD.

Valeur: Le type de la couche placée.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Obtient ou définit la position droite du calque placé dans le fichier PSD.

Valeur: La position droite de la couche placée.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Obtient ou définit la position supérieure du calque placé dans l'image PSD.

Valeur: La position supérieure de la couche placée.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD.

Valeur: Le nombre total de pages de la couche placée.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD.

Valeur: La matrice de transformation de la couche placée.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre U de la couche placée.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Obtient ou définit l'identifiant unique global du calque placé ou d'objet intelligent dans l'image PSD.

Valeur: L'identifiant unique de la couche placée.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Obtient ou définit la valeur V order du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre V de la couche placée.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Obtient ou définit la valeur warp du calque placé dans l'image PSD.

Valeur: La valeur de déformation de la couche placée.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Obtient la version du calque placé dans le fichier PSD, généralement 3-5.

Valeur : la version du calque placé ou d'objet intelligent.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Obtient ou définit l'unité de mesure des points de maillage verticaux.

Valeur: L'unité de mesure des points de maillage verticaux.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé. Si true, il contient des points de maillage. Si réglé sur false, il efface les points de maillage.

Valeur :  true  si la ressource du calque placé ou d'objet intelligent possède un style personnalisé ; sinon,  false .

**Returns:**
booléen
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Obtient ou définit la politique d'anticrénelage du calque placé dans l'image PSD.

Valeur : la politique d'anticrénelage du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Obtient ou définit la position inférieure du calque placé dans l'image PSD.

Valeur : la position inférieure du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Obtient ou définit les limites du calque placé dans le fichier PSD.

Valeur : les limites du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Obtient ou définit une valeur indiquant si le style de déformation de cette instance est personnalisé. Si true, il contient des points de maillage. Si réglé sur false, il efface les points de maillage.

Valeur :  true  si la ressource du calque placé ou d'objet intelligent possède un style personnalisé ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Obtient ou définit l'unité de mesure des points de maillage horizontaux.

Valeur : l'unité de mesure des points de maillage horizontaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Obtient ou définit les éléments de déformation.

Valeur : les éléments warp.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Obtient ou définit la position gauche du calque placé dans le fichier PSD.

Valeur : la position gauche du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Obtient ou définit le numéro de page du calque placé dans le fichier PSD.

Valeur: Le numéro de page de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Obtient ou définit la valeur de perspective du calque placé dans le fichier PSD.

Valeur: La valeur de perspective de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Obtient ou définit l'autre valeur de perspective du calque placé dans le fichier PSD.

Valeur: L'autre valeur de perspective de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Obtient ou définit le type du calque placé dans le fichier PSD.

Valeur: Le type de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Obtient ou définit la position droite du calque placé dans le fichier PSD.

Valeur: La position droite de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Obtient ou définit la position supérieure du calque placé dans l'image PSD.

Valeur: La position supérieure de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Obtient ou définit le nombre total de pages du calque placé dans le fichier PSD.

Valeur: Le nombre total de pages de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Obtient ou définit la matrice de transformation du calque placé dans le fichier PSD.

Valeur: La matrice de transformation de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Obtient ou définit la valeur d'ordre U du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre U de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Obtient ou définit l'identifiant unique global du calque placé ou d'objet intelligent dans l'image PSD.

Valeur: L'identifiant unique de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Obtient ou définit la valeur V order du calque placé dans le fichier PSD.

Valeur: La valeur d'ordre V de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Obtient ou définit la valeur warp du calque placé dans l'image PSD.

Valeur: La valeur de déformation de la couche placée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Obtient ou définit l'unité de mesure des points de maillage verticaux.

Valeur: L'unité de mesure des points de maillage verticaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Obtient ou définit les points de maillage horizontaux du calque placé dans le fichier PSD.

Valeur : les points de maillage horizontaux du calque placé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |


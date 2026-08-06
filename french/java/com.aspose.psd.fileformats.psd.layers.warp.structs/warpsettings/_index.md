---
title: "WarpSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres du calque avec warp"
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Paramètres du calque avec warp
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## Champs

| Champ | Description |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | La valeur par défaut de ProcessingArea |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtient ou définit les limites de l'image warp |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Obtient ou définit la taille de la grille de déformation. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Obtient ou définit la taille des lignes du maillage. |
| [getMeshPoints()](#getMeshPoints--) | Points de maillage Photoshop |
| [getRenderQuality()](#getRenderQuality--) | Obtient ou définit la valeur de la qualité de rendu de la déformation - entre vitesse et qualité |
| [getRotate()](#getRotate--) | Obtient ou définit la valeur de rotation |
| [getStyle()](#getStyle--) | Obtient ou définit le style du warp |
| [getValue()](#getValue--) | Obtient ou définit la valeur du warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Obtient ou définit la modification de l'utilisateur dans MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtient ou définit les limites de l'image warp |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Obtient ou définit la taille de la grille de déformation. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Obtient ou définit la taille des lignes du maillage. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Points de maillage Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Renvoie le point de maillage à partir des vecteurs de ressource |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Obtient ou définit la valeur de la qualité de rendu de la déformation - entre vitesse et qualité |
| [setRotate(int value)](#setRotate-int-) | Obtient ou définit la valeur de rotation |
| [setStyle(int value)](#setStyle-int-) | Obtient ou définit le style du warp |
| [setValue(double value)](#setValue-double-) | Obtient ou définit la valeur du warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Enregistre ces paramètres de warp dans PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Enregistre ces paramètres de warp dans PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Les points du maillage de la déformation |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image warp |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Les points du maillage de la déformation |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image warp |
| style | int | Le style de la déformation |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Éléments PS avec paramètres de warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image warp |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La ressource avec les paramètres de warp |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


La valeur par défaut de ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtient ou définit les limites de l'image warp

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


Obtient ou définit la taille de la grille de déformation. La valeur par défaut est 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Obtient ou définit la taille des lignes du maillage. GridSize est une définition de PS que le client peut sélectionner. Chaque GridSize possède 4 lignes de maillage. Si le nombre de GridSize est supérieur à 1, alors la dernière Mesh Line du premier Grid et la première du deuxième Grid forment une seule Mesh Line.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Points de maillage Photoshop

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Obtient ou définit la valeur de la qualité de rendu de la déformation - entre vitesse et qualité

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Obtient ou définit la valeur de rotation

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Obtient ou définit le style du warp

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Obtient ou définit la valeur du warp

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


Obtient ou définit la modification de l'utilisateur dans MeshPoints

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Obtient ou définit les limites de l'image warp

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Obtient ou définit la taille de la grille de déformation. La valeur par défaut est 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Obtient ou définit la taille des lignes du maillage. GridSize est une définition de PS que le client peut sélectionner. Chaque GridSize possède 4 lignes de maillage. Si le nombre de GridSize est supérieur à 1, alors la dernière Mesh Line du premier Grid et la première du deuxième Grid forment une seule Mesh Line.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Points de maillage Photoshop

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Renvoie le point de maillage à partir des vecteurs de ressource

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La ressource avec les paramètres de warp |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Obtient ou définit la valeur de la qualité de rendu de la déformation - entre vitesse et qualité

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Obtient ou définit la valeur de rotation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Obtient ou définit le style du warp

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Obtient ou définit la valeur du warp

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Enregistre ces paramètres de warp dans PlacedResource

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La ressource avec les paramètres de warp |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Ressource avec les paramètres de warp de ce WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Enregistre ces paramètres de warp dans PlacedResource

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La ressource avec les paramètres de warp |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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


---
title: "WarpSettings"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Paramètres du calque avec warp"
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
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
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
## Champs

| Champ | Description |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | La valeur par défaut de ProcessingArea |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Obtient ou définit les limites de l'image warp |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Points de maillage Photoshop |
| [getProcessingArea()](#getProcessingArea--) | Obtient ou définit la valeur de la taille de la zone de traitement. |
| [getRotate()](#getRotate--) | Obtient ou définit la valeur de rotation |
| [getStyle()](#getStyle--) | Obtient ou définit le style du warp |
| [getValue()](#getValue--) | Obtient ou définit la valeur du warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Obtient ou définit la modification de l'utilisateur dans MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Obtient ou définit les limites de l'image warp |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Points de maillage Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Renvoie le point de maillage à partir des vecteurs de ressource |
| [setProcessingArea(int value)](#setProcessingArea-int-) | Obtient ou définit la valeur de la taille de la zone de traitement. |
| [setRotate(int value)](#setRotate-int-) | Obtient ou définit la valeur de rotation |
| [setStyle(int value)](#setStyle-int-) | Obtient ou définit le style du warp |
| [setValue(double value)](#setValue-double-) | Obtient ou définit la valeur du warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Enregistre ces paramètres de warp dans PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Enregistre ces paramètres de warp dans PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Éléments PS avec paramètres de warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image warp |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initialise une nouvelle instance de la classe [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | La ressource avec les paramètres de warp |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
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
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Points de maillage Photoshop

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


Obtient ou définit la valeur de la taille de la zone de traitement. La valeur par défaut est 10. La plage est [2;40]

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

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Points de maillage Photoshop

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

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
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


Obtient ou définit la valeur de la taille de la zone de traitement. La valeur par défaut est 10. La plage est [2;40]

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


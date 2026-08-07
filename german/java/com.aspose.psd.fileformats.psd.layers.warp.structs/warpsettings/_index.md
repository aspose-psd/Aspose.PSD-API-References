---
title: "WarpSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Parameter einer Ebene mit Warp"
type: docs
weight: 12
url: /de/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parameter einer Ebene mit Warp
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse. |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse. |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse. |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | Der Standardwert von ProcessingArea |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Liest oder setzt die Grenzen des Verzerrungsbildes |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Liest oder setzt die Größe des Warp-Gitters. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Liest oder setzt die Größe der Maschenlinien. |
| [getMeshPoints()](#getMeshPoints--) | Photoshop-Mesh-Punkte |
| [getRenderQuality()](#getRenderQuality--) | Liest oder setzt den Wert der Warp-Render-Qualität – zwischen Geschwindigkeit und Qualität |
| [getRotate()](#getRotate--) | Liest oder setzt den Rotationswert |
| [getStyle()](#getStyle--) | Liest oder setzt den Stil der Verzerrung |
| [getValue()](#getValue--) | Liest oder setzt den Wert der Verzerrung |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Liest oder setzt die Benutzeränderung in MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Liest oder setzt die Grenzen des Verzerrungsbildes |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Liest oder setzt die Größe des Warp-Gitters. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Liest oder setzt die Größe der Maschenlinien. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Photoshop-Mesh-Punkte |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Gibt den Mesh-Punkt aus Ressourcenvektoren zurück |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Liest oder setzt den Wert der Warp-Render-Qualität – zwischen Geschwindigkeit und Qualität |
| [setRotate(int value)](#setRotate-int-) | Liest oder setzt den Rotationswert |
| [setStyle(int value)](#setStyle-int-) | Liest oder setzt den Stil der Verzerrung |
| [setValue(double value)](#setValue-double-) | Liest oder setzt den Wert der Verzerrung |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Speichert diese Verzerrungsparameter in PlacedResource. |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Speichert diese Verzerrungsparameter in PlacedResource. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Die Maschenpunkte des Warps |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen des Verzerrungsbildes |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Die Maschenpunkte des Warps |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen des Verzerrungsbildes |
| style | int | Der Stil des Warps |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | PS-Elemente mit Verzerrungseinstellungen |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen des Verzerrungsbildes |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initialisiert eine neue Instanz der [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Die Ressource mit Verzerrungseinstellungen |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


Der Standardwert von ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Liest oder setzt die Grenzen des Verzerrungsbildes

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


Liest oder setzt die Größe des Warp-Gitters. Standard ist 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Liest oder setzt die Größe der Maschenlinien. GridSize ist eine Definition aus PS, die der Kunde auswählen kann. Jede GridSize hat 4 Maschenlinien. Wenn die Anzahl der GridSize größer als 1 ist, dann sind die letzte Maschenlinie des ersten Gitters und die erste des zweiten Gitters eine gemeinsame Maschenlinie.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Photoshop-Mesh-Punkte

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Liest oder setzt den Wert der Warp-Render-Qualität – zwischen Geschwindigkeit und Qualität

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Liest oder setzt den Rotationswert

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Liest oder setzt den Stil der Verzerrung

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Liest oder setzt den Wert der Verzerrung

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


Liest oder setzt die Benutzeränderung in MeshPoints

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Liest oder setzt die Grenzen des Verzerrungsbildes

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Liest oder setzt die Größe des Warp-Gitters. Standard ist 1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Liest oder setzt die Größe der Maschenlinien. GridSize ist eine Definition aus PS, die der Kunde auswählen kann. Jede GridSize hat 4 Maschenlinien. Wenn die Anzahl der GridSize größer als 1 ist, dann sind die letzte Maschenlinie des ersten Gitters und die erste des zweiten Gitters eine gemeinsame Maschenlinie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Photoshop-Mesh-Punkte

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Gibt den Mesh-Punkt aus Ressourcenvektoren zurück

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Die Ressource mit Verzerrungseinstellungen |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Liest oder setzt den Wert der Warp-Render-Qualität – zwischen Geschwindigkeit und Qualität

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Liest oder setzt den Rotationswert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Liest oder setzt den Stil der Verzerrung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Liest oder setzt den Wert der Verzerrung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Speichert diese Verzerrungsparameter in PlacedResource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Die Ressource mit Verzerrungseinstellungen |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Ressource mit Verzerrungsparametern aus diesem WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Speichert diese Verzerrungsparameter in PlacedResource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Die Ressource mit Verzerrungseinstellungen |

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


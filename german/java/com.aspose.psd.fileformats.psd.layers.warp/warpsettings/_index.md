---
title: "WarpSettings"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Parameter einer Ebene mit Warp"
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
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
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initialisiert eine neue Instanz der Klasse [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initialisiert eine neue Instanz der Klasse [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings). |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | Der Standardwert von ProcessingArea |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Liest oder setzt die Grenzen des Verzerrungsbildes |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Photoshop-Mesh-Punkte |
| [getProcessingArea()](#getProcessingArea--) | Liest oder setzt den Wert der Größe des Verarbeitungsbereichs. |
| [getRotate()](#getRotate--) | Liest oder setzt den Rotationswert |
| [getStyle()](#getStyle--) | Liest oder setzt den Stil der Verzerrung |
| [getValue()](#getValue--) | Liest oder setzt den Wert der Verzerrung |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Liest oder setzt die Benutzeränderung in MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Liest oder setzt die Grenzen des Verzerrungsbildes |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Photoshop-Mesh-Punkte |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Gibt den Mesh-Punkt aus Ressourcenvektoren zurück |
| [setProcessingArea(int value)](#setProcessingArea-int-) | Liest oder setzt den Wert der Größe des Verarbeitungsbereichs. |
| [setRotate(int value)](#setRotate-int-) | Liest oder setzt den Rotationswert |
| [setStyle(int value)](#setStyle-int-) | Liest oder setzt den Stil der Verzerrung |
| [setValue(double value)](#setValue-double-) | Liest oder setzt den Wert der Verzerrung |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Speichert diese Verzerrungsparameter in PlacedResource. |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Speichert diese Verzerrungsparameter in PlacedResource. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initialisiert eine neue Instanz der Klasse [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | PS-Elemente mit Verzerrungseinstellungen |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen des Verzerrungsbildes |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initialisiert eine neue Instanz der Klasse [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Die Ressource mit Verzerrungseinstellungen |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
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
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Photoshop-Mesh-Punkte

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


Liest oder setzt den Wert der Größe des Verarbeitungsbereichs. Standardwert ist 10. Bereich ist [2;40]

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

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Photoshop-Mesh-Punkte

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

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
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


Liest oder setzt den Wert der Größe des Verarbeitungsbereichs. Standardwert ist 10. Bereich ist [2;40]

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


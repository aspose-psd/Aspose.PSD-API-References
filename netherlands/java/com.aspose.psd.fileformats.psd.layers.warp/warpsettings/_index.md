---
title: "WarpSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Parameters van laag met warp"
type: docs
weight: 11
url: /nl/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parameters van laag met warp
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initialiseert een nieuw exemplaar van de [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) klasse. |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initialiseert een nieuw exemplaar van de [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | De standaardwaarde van ProcessingArea |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Haalt op of stelt de grenzen van de warp‑afbeelding in |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Photoshop‑meshpunten |
| [getProcessingArea()](#getProcessingArea--) | Haalt op of stelt de waarde van de grootte van het verwerkingsgebied in. |
| [getRotate()](#getRotate--) | Haalt op of stelt de rotatiewaarde in |
| [getStyle()](#getStyle--) | Haalt op of stelt de stijl van warp in |
| [getValue()](#getValue--) | Haalt op of stelt de waarde van warp in |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Haalt op of stelt de gebruikerswijziging in MeshPoints in |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Haalt op of stelt de grenzen van de warp‑afbeelding in |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Photoshop‑meshpunten |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Retourneert een mesh‑punt uit resource‑vectoren |
| [setProcessingArea(int value)](#setProcessingArea-int-) | Haalt op of stelt de waarde van de grootte van het verwerkingsgebied in. |
| [setRotate(int value)](#setRotate-int-) | Haalt op of stelt de rotatiewaarde in |
| [setStyle(int value)](#setStyle-int-) | Haalt op of stelt de stijl van warp in |
| [setValue(double value)](#setValue-double-) | Haalt op of stelt de waarde van warp in |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Slaat deze warp‑parameters op in PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Slaat deze warp‑parameters op in PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initialiseert een nieuw exemplaar van de [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | PS‑items met warp‑instellingen |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | De grenzen van de warp‑afbeelding |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initialiseert een nieuw exemplaar van de [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | De resource met warp‑instellingen |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
```


De standaardwaarde van ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Haalt op of stelt de grenzen van de warp‑afbeelding in

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


Photoshop‑meshpunten

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


Haalt op of stelt de waarde van de grootte van het verwerkingsgebied in. Standaardwaarde is 10. Bereik is [2;40]

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Haalt op of stelt de rotatiewaarde in

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Haalt op of stelt de stijl van warp in

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Haalt op of stelt de waarde van warp in

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


Haalt op of stelt de gebruikerswijziging in MeshPoints in

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


Haalt op of stelt de grenzen van de warp‑afbeelding in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Photoshop‑meshpunten

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Retourneert een mesh‑punt uit resource‑vectoren

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | De resource met warp‑instellingen |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


Haalt op of stelt de waarde van de grootte van het verwerkingsgebied in. Standaardwaarde is 10. Bereik is [2;40]

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Haalt op of stelt de rotatiewaarde in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Haalt op of stelt de stijl van warp in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Haalt op of stelt de waarde van warp in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Slaat deze warp‑parameters op in PlacedResource

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De resource met warp‑instellingen |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Resource met warp‑parameters van deze WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Slaat deze warp‑parameters op in PlacedResource

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | De resource met warp‑instellingen |

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


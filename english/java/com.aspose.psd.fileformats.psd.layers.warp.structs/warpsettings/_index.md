---
title: WarpSettings
second_title: Aspose.PSD for Java API Reference
description: Parameters of layer with warp
type: docs
weight: 12
url: /java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Parameters of layer with warp
## Constructors

| Constructor | Description |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class. |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class. |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class. |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | The default value of ProcessingArea |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets or sets bounds of warp image |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Gets or sets the size of the warp grid. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Gets or sets the size of the mesh lines. |
| [getMeshPoints()](#getMeshPoints--) | Photoshop mesh points |
| [getRenderQuality()](#getRenderQuality--) | Gets or sets value of warp render quality - between speed and quality |
| [getRotate()](#getRotate--) | Gets or sets rotate value |
| [getStyle()](#getStyle--) | Gets or sets style of warp |
| [getValue()](#getValue--) | Gets or sets value of warp |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Gets or sets user change in MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Gets or sets bounds of warp image |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Gets or sets the size of the warp grid. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Gets or sets the size of the mesh lines. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Photoshop mesh points |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | It returns mesh point from resource vectors |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Gets or sets value of warp render quality - between speed and quality |
| [setRotate(int value)](#setRotate-int-) | Gets or sets rotate value |
| [setStyle(int value)](#setStyle-int-) | Gets or sets style of warp |
| [setValue(double value)](#setValue-double-) | Gets or sets value of warp |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | It save this warp params to PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | It save this warp params to PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | The mesh points of warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds of warp image |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | The mesh points of warp |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds of warp image |
| style | int | The style of warp |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | PS items with warp settings |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds of warp image |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Initializes a new instance of the [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | The resource with warp settings |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


The default value of ProcessingArea

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Gets or sets bounds of warp image

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


Gets or sets the size of the warp grid. Default is 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Gets or sets the size of the mesh lines. GridSize it is definition from PS that client can selected. Every GridSize has 4 mesh lines. If the number of GridSize is greater than 1, then the last mesh Line of first Grid and first of the second Grid are one Mesh Line.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Photoshop mesh points

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Gets or sets value of warp render quality - between speed and quality

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Gets or sets rotate value

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Gets or sets style of warp

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Gets or sets value of warp

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


Gets or sets user change in MeshPoints

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


Gets or sets bounds of warp image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Gets or sets the size of the warp grid. Default is 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Gets or sets the size of the mesh lines. GridSize it is definition from PS that client can selected. Every GridSize has 4 mesh lines. If the number of GridSize is greater than 1, then the last mesh Line of first Grid and first of the second Grid are one Mesh Line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Photoshop mesh points

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


It returns mesh point from resource vectors

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | The resource with warp settings |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Gets or sets value of warp render quality - between speed and quality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Gets or sets rotate value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Gets or sets style of warp

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Gets or sets value of warp

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


It save this warp params to PlacedResource

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The resource with warp settings |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Resource with warp params from this WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


It save this warp params to PlacedResource

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | The resource with warp settings |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: "WarpSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "带扭曲的图层参数"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

带扭曲的图层参数
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | 初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。 |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | 初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。 |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | 初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。 |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | ProcessingArea 的默认值 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 获取或设置扭曲图像的边界 |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | 获取或设置 warp 网格的大小。 |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | 获取或设置网格线的大小。 |
| [getMeshPoints()](#getMeshPoints--) | Photoshop 网格点 |
| [getRenderQuality()](#getRenderQuality--) | 获取或设置 warp 渲染质量的值 - 在速度和质量之间。 |
| [getRotate()](#getRotate--) | 获取或设置旋转值 |
| [getStyle()](#getStyle--) | 获取或设置扭曲的样式 |
| [getValue()](#getValue--) | 获取或设置扭曲的值 |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | 获取或设置 MeshPoints 中的用户更改 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 获取或设置扭曲图像的边界 |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | 获取或设置 warp 网格的大小。 |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | 获取或设置网格线的大小。 |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Photoshop 网格点 |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 它返回来自资源向量的网格点 |
| [setRenderQuality(int value)](#setRenderQuality-int-) | 获取或设置 warp 渲染质量的值 - 在速度和质量之间。 |
| [setRotate(int value)](#setRotate-int-) | 获取或设置旋转值 |
| [setStyle(int value)](#setStyle-int-) | 获取或设置扭曲的样式 |
| [setValue(double value)](#setValue-double-) | 获取或设置扭曲的值 |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | 它将此扭曲参数保存到 PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 它将此扭曲参数保存到 PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | warp 的网格点 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 扭曲图像的边界 |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | warp 的网格点 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 扭曲图像的边界 |
| style | int | warp 的样式 |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 带有扭曲设置的 PS 项目 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 扭曲图像的边界 |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


初始化 [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 带有扭曲设置的资源 |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


ProcessingArea 的默认值

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


获取或设置扭曲图像的边界

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


获取或设置扭曲网格的大小。默认值为 1。

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


获取或设置网格线的大小。GridSize 是来自 PS 的定义，客户端可以选择。每个 GridSize 有 4 条网格线。如果 GridSize 的数量大于 1，则第一个网格的最后一条网格线和第二个网格的第一条网格线是同一条网格线。

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Photoshop 网格点

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


获取或设置 warp 渲染质量的值 - 在速度和质量之间。

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


获取或设置旋转值

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


获取或设置扭曲的样式

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


获取或设置扭曲的值

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


获取或设置 MeshPoints 中的用户更改

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


获取或设置扭曲图像的边界

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


获取或设置扭曲网格的大小。默认值为 1。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


获取或设置网格线的大小。GridSize 是来自 PS 的定义，客户端可以选择。每个 GridSize 有 4 条网格线。如果 GridSize 的数量大于 1，则第一个网格的最后一条网格线和第二个网格的第一条网格线是同一条网格线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Photoshop 网格点

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


它返回来自资源向量的网格点

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 带有扭曲设置的资源 |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


获取或设置 warp 渲染质量的值 - 在速度和质量之间。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


获取或设置旋转值

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


获取或设置扭曲的样式

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


获取或设置扭曲的值

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


它将此扭曲参数保存到 PlacedResource

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 带有扭曲设置的资源 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - 来自此 WarpParams 的扭曲参数资源
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


它将此扭曲参数保存到 PlacedResource

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 带有扭曲设置的资源 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


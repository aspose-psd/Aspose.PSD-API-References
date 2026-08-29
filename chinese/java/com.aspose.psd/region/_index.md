---
title: "Region"
second_title: "Aspose.PSD 的 Java API 参考"
description: "描述由矩形和路径组成的图形形状的内部。"
type: docs
weight: 90
url: /zh/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

描述由矩形和路径组成的图形形状的内部。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Region()](#Region--) | 初始化一个新的  T:Aspose.Imaging.Region 。 |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | 从指定的  T:Aspose.Imaging.RectangleF  结构初始化一个新的  T:Aspose.Imaging.Region 。 |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | 从指定的  T:Aspose.Imaging.Rectangle  结构初始化一个新的  T:Aspose.Imaging.Region 。 |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | 使用指定的  T:Aspose.Imaging.GraphicsPath  初始化一个新的  T:Aspose.Imaging.Region 。 |
## Methods

| Method | 描述 |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | 更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.GraphicsPath 中未与此  com.aspose.psd.region 相交的部分。 |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | 更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.Rectangle  结构中未与此  com.aspose.psd.region 相交的部分。 |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | 更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.RectangleF  结构中未与此  com.aspose.psd.region 相交的部分。 |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | 更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.Region 中未与此  com.aspose.psd.region 相交的部分。 |
| [deepClone()](#deepClone--) | 创建此  com.aspose.psd.region 的精确深拷贝。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | 更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.graphicsPath 相交的部分。 |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | 更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.Rectangle  结构相交的部分。 |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | 更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.RectangleF  结构相交的部分。 |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | 更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.region 相交的部分。 |
| [getActions_internalized()](#getActions-internalized--) | 获取区域操作。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | 将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.graphicsPath 的交集。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | 将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.Rectangle  结构的交集。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | 将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.RectangleF  结构的交集。 |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | 将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.region 的交集。 |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | 测试此  com.aspose.psd.Region  在指定的绘图表面上是否具有空内部。 |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | 测试指定的  com.aspose.psd.Region  是否在指定的绘图表面上与此  com.aspose.psd.Region 完全相同。 |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | 测试此  com.aspose.psd.Region  在指定的绘图表面上是否具有无限内部。 |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | 测试指定的  com.aspose.psd.Point  结构是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | 测试指定的  com.aspose.psd.Point  结构在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | 测试指定的  com.aspose.psd.PointF  结构是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | 测试指定的  com.aspose.psd.PointF  结构在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | 测试指定的  com.aspose.psd.Rectangle  结构的任何部分是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | 测试指定的  com.aspose.psd.Rectangle  结构的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | 测试指定的  com.aspose.psd.RectangleF  结构的任何部分是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | 测试指定的  com.aspose.psd.RectangleF  结构的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 测试指定的点是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | 测试指定的点在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | 测试指定的矩形的任何部分是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | 测试指定的矩形的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | 测试指定的点在使用指定的  com.aspose.psd.Graphics 对象绘制时是否包含在此  com.aspose.psd.Region 对象中。 |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | 测试指定的矩形的任何部分是否包含在此  com.aspose.psd.region 中。 |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | 测试指定的矩形的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。 |
| [makeEmpty()](#makeEmpty--) | 将此  com.aspose.psd.Region  初始化为空内部。 |
| [makeInfinite()](#makeInfinite--) | 将此  com.aspose.psd.Region 对象初始化为无限内部。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | 获取或设置更改时的区域。 |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | 使用指定的  com.aspose.psd.matrix 对此  com.aspose.psd.Region 进行变换。 |
| [translate(float dx, float dy)](#translate-float-float-) | 按指定的量偏移此  com.aspose.psd.Region 的坐标。 |
| [translate(int dx, int dy)](#translate-int-int-) | 按指定的量偏移此  com.aspose.psd.Region 的坐标。 |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.graphicsPath 的并集。 |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.Rectangle 结构的并集。 |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.RectangleF 结构的并集。 |
| [union(Region region)](#union-com.aspose.psd.Region-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.region 的并集。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.graphicsPath 的并集减去交集。 |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.Rectangle 结构的并集减去交集。 |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.RectangleF 结构的并集减去交集。 |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | 将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.region 的并集减去交集。 |
### Region() {#Region--}
```
public Region()
```


初始化一个新的  T:Aspose.Imaging.Region 。

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


从指定的  T:Aspose.Imaging.RectangleF  结构初始化一个新的  T:Aspose.Imaging.Region 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 定义新 T:Aspose.Imaging.Region 内部的 T:Aspose.Imaging.RectangleF 结构。 |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


从指定的  T:Aspose.Imaging.Rectangle  结构初始化一个新的  T:Aspose.Imaging.Region 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 定义新 T:Aspose.Imaging.Region 内部的 T:Aspose.Imaging.Rectangle 结构。 |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


使用指定的  T:Aspose.Imaging.GraphicsPath  初始化一个新的  T:Aspose.Imaging.Region 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 定义新 T:Aspose.Imaging.Region 的 T:Aspose.Imaging.GraphicsPath。 |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.GraphicsPath 中未与此  com.aspose.psd.region 相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 用于补充此 com.aspose.psd.region 的 com.aspose.psd.GraphicsPath。 |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.Rectangle  结构中未与此  com.aspose.psd.region 相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 用于补充此 com.aspose.psd.region 的 com.aspose.psd.Rectangle 结构。 |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.RectangleF  结构中未与此  com.aspose.psd.region 相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 用于补充此 com.aspose.psd.region 的 com.aspose.psd.RectangleF 结构。 |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


更新此  com.aspose.psd.Region ，使其包含指定的  com.aspose.psd.Region 中未与此  com.aspose.psd.region 相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 用于补充此 com.aspose.psd.Region 对象的 com.aspose.psd.Region 对象。 |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


创建此  com.aspose.psd.region 的精确深拷贝。

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.graphicsPath 相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 从此 com.aspose.psd.region 中排除的 com.aspose.psd.GraphicsPath。 |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.Rectangle  结构相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 从此 com.aspose.psd.region 中排除的 com.aspose.psd.Rectangle 结构。 |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.RectangleF  结构相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 从此 com.aspose.psd.region 中排除的 com.aspose.psd.RectangleF 结构。 |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


更新此  com.aspose.psd.Region ，使其仅包含其内部未与指定的  com.aspose.psd.region 相交的部分。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 从此 com.aspose.psd.region 中排除的 com.aspose.psd.Region。 |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


获取区域操作。

**Returns:**
com.aspose.internal.RegionAction[] - 区域操作。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.graphicsPath 的交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 与此 com.aspose.psd.region 相交的 com.aspose.psd.GraphicsPath。 |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.Rectangle  结构的交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 与此 com.aspose.psd.region 相交的 com.aspose.psd.Rectangle 结构。 |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.RectangleF  结构的交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 与此 com.aspose.psd.region 相交的 com.aspose.psd.RectangleF 结构。 |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


将此  com.aspose.psd.Region  更新为它与指定的  com.aspose.psd.region 的交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 与此 com.aspose.psd.region 相交的 com.aspose.psd.Region。 |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


测试此  com.aspose.psd.Region  在指定的绘图表面上是否具有空内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | 表示绘图表面的 com.aspose.psd.Graphics。 |

**Returns:**
布尔值 - 如果在应用与  g  关联的变换时，此  com.aspose.psd.Region  的内部为空，则为 true；否则为 false。
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


测试指定的  com.aspose.psd.Region  是否在指定的绘图表面上与此  com.aspose.psd.Region 完全相同。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 要测试的  com.aspose.psd.Region  。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 表示绘图表面的 com.aspose.psd.Graphics。 |

**Returns:**
布尔值 - 如果在应用与  g  参数关联的变换时，region 的内部与此 region 的内部相同，则为 True；否则为 false。
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


测试此  com.aspose.psd.Region  在指定的绘图表面上是否具有无限内部。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | 表示绘图表面的 com.aspose.psd.Graphics。 |

**Returns:**
布尔值 - 如果在应用与  g  关联的变换时，此  com.aspose.psd.Region  的内部是无限的，则为 true；否则为 false。
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


测试指定的  com.aspose.psd.Point  结构是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要测试的  com.aspose.psd.Point  结构。 |

**Returns:**
布尔值 - 当  point  包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


测试指定的  com.aspose.psd.Point  结构在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 要测试的  com.aspose.psd.Point  结构。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当  point  包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


测试指定的  com.aspose.psd.PointF  结构是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要测试的  com.aspose.psd.PointF  结构。 |

**Returns:**
布尔值 - 当  point  包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


测试指定的  com.aspose.psd.PointF  结构在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 要测试的  com.aspose.psd.PointF  结构。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当  point  包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


测试指定的  com.aspose.psd.Rectangle  结构的任何部分是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 要测试的  com.aspose.psd.Rectangle  结构。 |

**Returns:**
布尔值 - 当  rect  的任何部分包含在此  com.aspose.psd.Region  中时，此方法返回 true；否则为 false。
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


测试指定的  com.aspose.psd.Rectangle  结构的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 要测试的  com.aspose.psd.Rectangle  结构。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当  rect  的任何部分包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


测试指定的  com.aspose.psd.RectangleF  结构的任何部分是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 要测试的  com.aspose.psd.RectangleF  结构。 |

**Returns:**
布尔值 - 当  rect  的任何部分包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


测试指定的  com.aspose.psd.RectangleF  结构的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 要测试的  com.aspose.psd.RectangleF  结构。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当  rect  包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


测试指定的点是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |

**Returns:**
布尔值 - 当指定的点包含在此  com.aspose.psd.Region  中时为 True；否则为 false。
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


测试指定的点在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当指定的点包含在此  com.aspose.psd.Region  中时为 True；否则为 false。
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


测试指定的矩形的任何部分是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | float | 要测试的矩形的宽度。 |
| 高度 | float | 要测试的矩形的高度。 |

**Returns:**
布尔值 - 当指定矩形的任何部分包含在此  com.aspose.psd.Region  对象中时为 true；否则为 false。
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


测试指定的矩形的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | float | 要测试的矩形的宽度。 |
| 高度 | float | 要测试的矩形的高度。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当指定矩形的任何部分包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


测试指定的点在使用指定的  com.aspose.psd.Graphics 对象绘制时是否包含在此  com.aspose.psd.Region 对象中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当指定的点包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


测试指定的矩形的任何部分是否包含在此  com.aspose.psd.region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | int | 要测试的矩形的宽度。 |
| 高度 | int | 要测试的矩形的高度。 |

**Returns:**
布尔值 - 当指定矩形的任何部分包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


测试指定的矩形的任何部分在使用指定的  com.aspose.psd.graphics 绘制时是否包含在此  com.aspose.psd.Region 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| 宽度 | int | 要测试的矩形的宽度。 |
| 高度 | int | 要测试的矩形的高度。 |
| g | [Graphics](../../com.aspose.psd/graphics) | 一个表示图形上下文的  com.aspose.psd.Graphics 。 |

**Returns:**
布尔值 - 当指定矩形的任何部分包含在此  com.aspose.psd.Region  中时为 true；否则为 false。
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


将此  com.aspose.psd.Region  初始化为空内部。

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


将此  com.aspose.psd.Region 对象初始化为无限内部。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


获取或设置更改时的区域。

值：更改时的区域。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


使用指定的  com.aspose.psd.matrix 对此  com.aspose.psd.Region 进行变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于转换此  com.aspose.psd.region 的  com.aspose.psd.Matrix 。 |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


按指定的量偏移此  com.aspose.psd.Region 的坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | 水平偏移此  com.aspose.psd.Region  的量。 |
| dy | float | 垂直偏移此  com.aspose.psd.Region  的量。 |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


按指定的量偏移此  com.aspose.psd.Region 的坐标。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | int | 水平偏移此  com.aspose.psd.Region  的量。 |
| dy | int | 垂直偏移此  com.aspose.psd.Region  的量。 |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.graphicsPath 的并集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 与此  com.aspose.psd.region  合并的  com.aspose.psd.GraphicsPath  。 |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.Rectangle 结构的并集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 与此  com.aspose.psd.region  合并的  com.aspose.psd.Rectangle  结构。 |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.RectangleF 结构的并集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 与此  com.aspose.psd.region  合并的  com.aspose.psd.RectangleF  结构。 |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.region 的并集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 与此  com.aspose.psd.region  合并的  com.aspose.psd.Region  。 |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.graphicsPath 的并集减去交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | 与此  com.aspose.psd.region  进行异或的  com.aspose.psd.GraphicsPath  。 |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.Rectangle 结构的并集减去交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 与此  com.aspose.psd.region  进行异或的  com.aspose.psd.Rectangle  结构。 |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.RectangleF 结构的并集减去交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 与此  com.aspose.psd.region  进行异或的  com.aspose.psd.RectangleF  结构。 |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


将此 com.aspose.psd.Region 更新为它本身与指定的 com.aspose.psd.region 的并集减去交集。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | 与此  com.aspose.psd.region  进行异或的  com.aspose.psd.Region  。 |


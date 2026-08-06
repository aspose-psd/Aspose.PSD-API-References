---
title: "GraphicsPath"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示一系列相连的直线和曲线。"
type: docs
weight: 50
url: /zh/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

表示一系列相连的直线和曲线。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | 初始化 GraphicsPath 类的新实例。 |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | 初始化 GraphicsPath 类的新实例。 |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | 初始化 GraphicsPath 类的新实例。 |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | 初始化 GraphicsPath 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | 添加一个新图形。 |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | 添加新图形。 |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | 将指定的 com.aspose.psd.GraphicsPath 追加到此路径。 |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | 将指定的 com.aspose.psd.GraphicsPath 追加到此路径。 |
| [deepClone()](#deepClone--) | 对该图形路径执行深度克隆。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | 应用指定的变换，然后将此 com.aspose.psd.GraphicsPath 中的每条曲线转换为一系列相连的线段。 |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | 将此 com.aspose.psd.GraphicsPath 中的每条曲线转换为一系列相连的线段。 |
| [getBounds()](#getBounds--) | 获取或设置对象的边界。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 获取对象的边界。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 获取对象的边界。 |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | 获取路径图形。 |
| [getFillMode()](#getFillMode--) | 获取 com.aspose.psd.FillMode 枚举，该枚举决定此 com.aspose.psd.GraphicsPath 中形状内部的填充方式。 |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | 指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | 指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | 指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | 指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | 指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。 |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | 指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。 |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | 指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。 |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | 指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。 |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | 指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。 |
| [isVisible(float x, float y)](#isVisible-float-float-) | 指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。 |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | 指示指定的点是否位于指定的 com.aspose.psd.graphics 的可见剪裁区域内的此 com.aspose.psd.GraphicsPath 中。 |
| [isVisible(int x, int y)](#isVisible-int-int-) | 指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。 |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | 指示使用指定的 com.aspose.psd.graphics 时，指定的点是否位于此 com.aspose.psd.GraphicsPath 内。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | 移除一个图形。 |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | 移除图形。 |
| [reset()](#reset--) | 清空图形路径并将 com.aspose.psd.FillMode 设置为 F:com.aspose.psd.fillMode.alternate。 |
| [reverse()](#reverse--) | 反转此 com.aspose.psd.graphicsPath 中每个形状的图形、形状和点的顺序。 |
| [setFillMode(int value)](#setFillMode-int-) | 设置 com.aspose.psd.FillMode 枚举，该枚举决定此 com.aspose.psd.GraphicsPath 中形状内部的填充方式。 |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 将指定的变换应用于形状。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | 对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | 对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | 对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | 对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。 |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | 向路径添加额外的轮廓。 |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | 向  com.aspose.psd.graphicsPath  添加额外的轮廓。 |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | 用在使用指定笔绘制此路径时填充区域的曲线替换此  com.aspose.psd.GraphicsPath 。 |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


初始化 GraphicsPath 类的新实例。

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


初始化 GraphicsPath 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 用于初始化的图形。 |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


初始化 GraphicsPath 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 用于初始化的图形。 |
| fillMode | int | 填充模式。 |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


初始化 GraphicsPath 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fillMode | int | 填充模式。 |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


添加一个新图形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | 要添加的图形。 |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


添加新图形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 要添加的图形集合。 |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


将指定的 com.aspose.psd.GraphicsPath 追加到此路径。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 要添加的  com.aspose.psd.GraphicsPath 。 |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


将指定的 com.aspose.psd.GraphicsPath 追加到此路径。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | 要添加的  com.aspose.psd.GraphicsPath 。 |
| connect | boolean | 布尔值，指定添加的路径中的第一个图形是否是此路径中最后一个图形的一部分。值为 true 表示添加的路径中的第一个图形是此路径中最后一个图形的一部分。值为 false 表示添加的路径中的第一个图形与此路径中最后一个图形分离。 |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


对该图形路径执行深度克隆。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


将此路径中的每条曲线转换为一系列相连的线段。

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


应用指定的变换，然后将此 com.aspose.psd.GraphicsPath 中的每条曲线转换为一系列相连的线段。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于在展平之前转换此  com.aspose.psd.GraphicsPath  的  com.aspose.psd.Matrix 。 |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


将此 com.aspose.psd.GraphicsPath 中的每条曲线转换为一系列相连的线段。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于在展平之前转换此  com.aspose.psd.GraphicsPath  的  com.aspose.psd.Matrix 。 |
| flatness | float | 指定曲线与其展平近似之间允许的最大误差。默认值为 0.25。降低 flatness 值会增加近似中的线段数量。 |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


获取或设置对象的边界。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


获取对象的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 在计算边界之前要应用的矩阵。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


获取对象的边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于对象的笔。这可能会影响对象的边界大小。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


获取路径图形。

**Returns:**
com.aspose.psd.Figure[] - 路径图形。
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


获取 com.aspose.psd.FillMode 枚举，该枚举决定此 com.aspose.psd.GraphicsPath 中形状内部的填充方式。

**Returns:**
int - 填充模式。一个  com.aspose.psd.FillMode  枚举，指定此  com.aspose.psd.GraphicsPath  中形状内部的填充方式。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 指定要测试位置的  com.aspose.psd.Point 。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | 指定要测试位置的  com.aspose.psd.Point 。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 指定要测试位置的  com.aspose.psd.PointF 。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | 指定要测试位置的  com.aspose.psd.PointF 。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部（下方），则此方法返回 true；否则返回 false。
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部（下方），则此方法返回 true；否则返回 false。
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


指示在使用指定的 com.aspose.psd.pen 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部，则此方法返回 true；否则返回 false。
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


指示在使用指定的 com.aspose.psd.Pen 并使用指定的 com.aspose.psd.graphics 绘制时，指定的点是否位于此 com.aspose.psd.GraphicsPath 的轮廓内（下方）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| pen | [Pen](../../com.aspose.psd/pen) | 用于测试的  com.aspose.psd.Pen 。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点在使用指定的  com.aspose.psd.Pen 绘制时位于此  com.aspose.psd.GraphicsPath  的轮廓内部，则此方法返回 true；否则返回 false。
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 表示要测试点的  com.aspose.psd.Point 。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | 表示要测试点的  com.aspose.psd.Point 。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 一个表示要测试的点的 com.aspose.psd.PointF。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | 一个表示要测试的点的 com.aspose.psd.PointF。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点位于此对象中，则此方法返回 true；否则返回 false。
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


指示指定的点是否位于指定的 com.aspose.psd.graphics 的可见剪裁区域内的此 com.aspose.psd.GraphicsPath 中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


指示指定的点是否位于此 com.aspose.psd.graphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


指示使用指定的 com.aspose.psd.graphics 时，指定的点是否位于此 com.aspose.psd.GraphicsPath 内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| graphics | [Graphics](../../com.aspose.psd/graphics) | 用于测试可见性的  com.aspose.psd.Graphics 。 |

**Returns:**
boolean - 如果指定的点位于此 com.aspose.psd.GraphicsPath 中，则此方法返回 true；否则返回 false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


移除一个图形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | 要删除的图形。 |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


移除图形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | 要删除的图形集合。 |

### reset() {#reset--}
```
public void reset()
```


清空图形路径并将 com.aspose.psd.FillMode 设置为 F:com.aspose.psd.fillMode.alternate。

### reverse() {#reverse--}
```
public void reverse()
```


反转此 com.aspose.psd.graphicsPath 中每个形状的图形、形状和点的顺序。

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


设置 com.aspose.psd.FillMode 枚举，该枚举决定此 com.aspose.psd.GraphicsPath 中形状内部的填充方式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 填充模式。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


将指定的变换应用于形状。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 要应用的变换。 |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 一个 com.aspose.psd.PointF 结构数组，用于定义一个平行四边形，矩形由 srcRect 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 一个表示被转换为由 destPoints 定义的平行四边形的矩形的 com.aspose.psd.RectangleF。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 一个 com.aspose.psd.PointF 结构数组，用于定义一个平行四边形，矩形由 srcRect 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 一个表示被转换为由 destPoints 定义的平行四边形的矩形的 com.aspose.psd.RectangleF。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 一个指定要应用于路径的几何变换的 com.aspose.psd.Matrix。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 一个 com.aspose.psd.PointF 结构数组，用于定义一个平行四边形，矩形由 srcRect 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 一个表示被转换为由 destPoints 定义的平行四边形的矩形的 com.aspose.psd.RectangleF。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 一个指定要应用于路径的几何变换的 com.aspose.psd.Matrix。 |
| warpMode | int | 一个指定此扭曲操作使用透视模式还是双线性模式的 com.aspose.psd.WarpMode 枚举。 |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


对该  com.aspose.psd.graphicsPath  应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | 一个 com.aspose.psd.PointF 结构数组，用于定义一个平行四边形，矩形由 srcRect 定义并被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点隐含。 |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | 一个表示被转换为由 destPoints 定义的平行四边形的矩形的 com.aspose.psd.RectangleF。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 一个指定要应用于路径的几何变换的 com.aspose.psd.Matrix。 |
| warpMode | int | 一个指定此扭曲操作使用透视模式还是双线性模式的 com.aspose.psd.WarpMode 枚举。 |
| flatness | float | 一个介于 0 到 1 之间的值，用于指定生成路径的平整度。更多信息，请参阅 com.aspose.psd.GraphicsPath.flatten 方法。 |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


向路径添加额外的轮廓。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 一个指定路径原始轮廓与此方法创建的新轮廓之间宽度的 com.aspose.psd.Pen。 |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


向  com.aspose.psd.graphicsPath  添加额外的轮廓。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 一个指定路径原始轮廓与此方法创建的新轮廓之间宽度的 com.aspose.psd.Pen。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 一个指定在加宽路径之前要应用的变换的 com.aspose.psd.Matrix。 |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


用在使用指定笔绘制此路径时填充区域的曲线替换此  com.aspose.psd.GraphicsPath 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | 一个指定路径原始轮廓与此方法创建的新轮廓之间宽度的 com.aspose.psd.Pen。 |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 一个指定在加宽路径之前要应用的变换的 com.aspose.psd.Matrix。 |
| flatness | float | 一个指定曲线平整度的值。 |


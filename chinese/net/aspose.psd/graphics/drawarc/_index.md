---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制一个弧线，表示由一对坐标、宽度和高度指定的椭圆的一部分。"
type: docs
weight: 170
url: /zh/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定弧线的颜色、宽度和样式。 |
| x | 单精度 | 定义椭圆的矩形左上角的 x 坐标。 |
| y | 单精度 | 定义椭圆的矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 定义椭圆的矩形的宽度。 |
| 高度 | 单精度 | 定义椭圆的矩形的高度。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到弧线起始点的角度（以度为单位）。 |
| sweepAngle | 单精度 | 从 *startAngle* 参数顺时针测量到弧线结束点的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

绘制一个弧线，表示由 [`RectangleF`](../../rectanglef/) 结构指定的椭圆的一部分。

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定弧线的颜色、宽度和样式。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 结构，定义椭圆的边界。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到弧线起始点的角度（以度为单位）。 |
| sweepAngle | 单精度 | 从 *startAngle* 参数顺时针测量到弧线结束点的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null |

### 另请参阅

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

绘制由一对坐标、宽度和高度指定的椭圆的一段弧线。

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定弧线的颜色、宽度和样式。 |
| x | Int32 | 定义椭圆的矩形左上角的 x 坐标。 |
| y | Int32 | 定义椭圆的矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 定义椭圆的矩形的宽度。 |
| 高度 | Int32 | 定义椭圆的矩形的高度。 |
| startAngle | Int32 | 从 x 轴顺时针测量到弧线起始点的角度（以度为单位）。 |
| sweepAngle | Int32 | 从 *startAngle* 参数顺时针测量到弧线结束点的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

绘制一个弧线，表示由 [`Rectangle`](../../rectangle/) 结构指定的椭圆的一部分。

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定弧线的颜色、宽度和样式。 |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) 结构，定义椭圆的边界。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到弧线起始点的角度（以度为单位）。 |
| sweepAngle | 单精度 | 从 *startAngle* 参数顺时针测量到弧线结束点的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



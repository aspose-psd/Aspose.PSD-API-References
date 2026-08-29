---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制由 RectangleF 结构指定的椭圆和两条径向线定义的饼形。"
type: docs
weight: 290
url: /zh/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

绘制由 [`RectangleF`](../../rectanglef/) 结构指定的椭圆和两条径向线定义的饼形。

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | 决定饼形颜色、宽度和样式的 [`Pen`](../../pen/)。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 结构，表示定义饼形来源椭圆的边界矩形。 |
| startAngle | 单精度 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | 单精度 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | 决定饼形颜色、宽度和样式的 [`Pen`](../../pen/)。 |
| x | 单精度 | 定义饼形来源椭圆的边界矩形左上角的 x 坐标。 |
| y | 单精度 | 定义饼形来源椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 定义饼形来源椭圆的边界矩形的宽度。 |
| 高度 | 单精度 | 定义饼形来源椭圆的边界矩形的高度。 |
| startAngle | 单精度 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | 单精度 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

绘制由使用 [`Rectangle`](../../rectangle/) 结构指定的椭圆和两条径向线定义的饼形。

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | 决定饼形颜色、宽度和样式的 [`Pen`](../../pen/)。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 结构，表示定义饼形来源椭圆的边界矩形。 |
| startAngle | 单精度 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | 单精度 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

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

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

绘制由坐标对、宽度、高度以及两条径向线指定的椭圆定义的饼形。

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | 决定饼形颜色、宽度和样式的 [`Pen`](../../pen/)。 |
| x | Int32 | 定义饼形来源椭圆的边界矩形左上角的 x 坐标。 |
| y | Int32 | 定义饼形来源椭圆的边界矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 定义饼形来源椭圆的边界矩形的宽度。 |
| 高度 | Int32 | 定义饼形来源椭圆的边界矩形的高度。 |
| startAngle | Int32 | 角度，以度为单位，顺时针从 x 轴测量到饼形的第一条边。 |
| sweepAngle | Int32 | 角度，以度为单位，顺时针从 *startAngle* 参数测量到饼形的第二条边。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



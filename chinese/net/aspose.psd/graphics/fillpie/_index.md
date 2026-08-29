---
title: "Graphics.FillPie"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。填充由 RectangleF 结构和两条径向线指定的椭圆所定义的饼形区域内部。"
type: docs
weight: 380
url: /zh/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

填充由[`RectangleF`](../../rectanglef/)结构指定的椭圆和两条径向线定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) 决定填充的特性。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 结构，表示定义饼形区域所在椭圆的外接矩形。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到饼形区域第一边的角度（以度为单位）。 |
| sweepAngle | 单精度 | 从 *startAngle* 参数顺时针测量到饼形区域第二边的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参阅

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

填充由[`RectangleF`](../../rectanglef/)结构指定的椭圆和两条径向线定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) 决定填充的特性。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 结构，表示定义饼形区域所在椭圆的外接矩形。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到饼形区域第一边的角度（以度为单位）。 |
| sweepAngle | 单精度 | 从 *startAngle* 参数顺时针测量到饼形区域第二边的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参阅

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) 决定填充的特性。 |
| x | 单精度 | 定义饼形区域所在椭圆的外接矩形左上角的 x 坐标。 |
| y | 单精度 | 定义饼形区域所在椭圆的外接矩形左上角的 y 坐标。 |
| 宽度 | 单精度 | 定义饼形区域所在椭圆的外接矩形的宽度。 |
| 高度 | 单精度 | 定义饼形区域所在椭圆的外接矩形的高度。 |
| startAngle | 单精度 | 从 x 轴顺时针测量到饼形区域第一边的角度（以度为单位）。 |
| sweepAngle | 单精度 | 从 *startAngle* 参数顺时针测量到饼形区域第二边的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参阅

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

填充由一对坐标、宽度、高度以及两条径向线指定的椭圆定义的饼形区域的内部。

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) 决定填充的特性。 |
| x | Int32 | 定义饼形区域所在椭圆的外接矩形左上角的 x 坐标。 |
| y | Int32 | 定义饼形区域所在椭圆的外接矩形左上角的 y 坐标。 |
| 宽度 | Int32 | 定义饼形区域所在椭圆的外接矩形的宽度。 |
| 高度 | Int32 | 定义饼形区域所在椭圆的外接矩形的高度。 |
| startAngle | Int32 | 从 x 轴顺时针测量到饼形区域第一边的角度（以度为单位）。 |
| sweepAngle | Int32 | 从 *startAngle* 参数顺时针测量到饼形区域第二边的角度（以度为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *brush* 为 null。 |

### 另请参阅

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



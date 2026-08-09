---
title: "Graphics.DrawClosedCurve"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制由 PointF 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 Alternate 填充模式。"
type: docs
weight: 200
url: /zh/net/aspose.psd/graphics/drawclosedcurve/
---
{{< psd/tize >}}
## DrawClosedCurve(Pen, PointF[]) {#drawclosedcurve}

绘制由 [`PointF`](../../pointf/) 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 Alternate 填充模式。

```csharp
public void DrawClosedCurve(Pen pen, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawClosedCurve(Pen, PointF[], float) {#drawclosedcurve_1}

绘制由 [`PointF`](../../pointf/) 结构数组定义的闭合基数样条曲线，使用指定的张力。此方法使用默认的 Alternate 填充模式。

```csharp
public void DrawClosedCurve(Pen pen, PointF[] points, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawClosedCurve(Pen, Point[]) {#drawclosedcurve_2}

绘制由 [`Point`](../../point/) 结构数组定义的闭合基数样条曲线。此方法使用默认张力 0.5 和 Alternate 填充模式。

```csharp
public void DrawClosedCurve(Pen pen, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条的 [`Point`](../../point/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawClosedCurve(Pen, Point[], float) {#drawclosedcurve_3}

绘制由 [`Point`](../../point/) 结构数组定义的闭合基数样条曲线，使用指定的张力。此方法使用默认的 Alternate 填充模式。

```csharp
public void DrawClosedCurve(Pen pen, Point[] points, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条的 [`Point`](../../point/) 结构数组。 |
| 张力 | 单精度 | 大于或等于 0.0F 的值，指定曲线的张力。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。通过指定的 PointF 结构数组绘制基数样条曲线。此方法使用默认张力 0.5。"
type: docs
weight: 210
url: /zh/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。此方法使用默认张力 0.5。

```csharp
public void DrawCurve(Pen pen, PointF[] points)
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

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

使用指定的张力，通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 表示定义曲线的点的 [`PointF`](../../pointf/) 结构数组。 |
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

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。绘制从数组起始位置偏移开始。此方法使用默认张力 0.5。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| offset | Int32 | 从 *points* 参数数组的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | Int32 | 起始点之后包含在曲线中的段数。 |

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

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

使用指定的张力，通过指定的 [`PointF`](../../pointf/) 结构数组绘制基数样条曲线。绘制从数组起始位置偏移开始。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条的 [`PointF`](../../pointf/) 结构数组。 |
| offset | Int32 | 从 *points* 参数数组的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | Int32 | 起始点之后包含在曲线中的段数。 |
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

## DrawCurve(Pen, Point[]) {#drawcurve_4}

通过指定的 [`Point`](../../point/) 结构数组绘制基数样条曲线。

```csharp
public void DrawCurve(Pen pen, Point[] points)
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

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

使用指定的张力，在指定的 [`Point`](../../point/) 结构数组上绘制基数样条。

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
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

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

使用指定的张力，在指定的 [`Point`](../../point/) 结构数组上绘制基数样条。

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条的 [`Point`](../../point/) 结构数组。 |
| offset | Int32 | 从 *points* 参数数组的第一个元素到曲线起始点的偏移量。 |
| numberOfSegments | Int32 | 起始点之后包含在曲线中的段数。 |
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



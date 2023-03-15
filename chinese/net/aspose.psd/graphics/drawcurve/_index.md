---
title: Graphics.DrawCurve
second_title: Aspose.PSD for .NET API 参考
description: Graphics 方法. 通过指定数组绘制基数样条PointF结构此方法使用默认张力 0.5.
type: docs
weight: 200
url: /zh/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

通过指定数组绘制基数样条[`PointF`](../../pointf/)结构。此方法使用默认张力 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 阵列的[`PointF`](../../pointf/)定义样条的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

通过指定数组绘制基数样条[`PointF`](../../pointf/)使用指定张力的结构.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 阵列的[`PointF`](../../pointf/)表示定义曲线的点的结构。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

通过指定数组绘制基数样条[`PointF`](../../pointf/)结构。绘图从数组的开头开始偏移。 此方法使用默认张力 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 阵列的[`PointF`](../../pointf/)定义样条的结构。 |
| offset | Int32 | 距数组中第一个元素的偏移量*points*参数到曲线的起点。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

通过指定数组绘制基数样条[`PointF`](../../pointf/)使用特定张力的结构。绘图从数组的开头开始偏移。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 阵列的[`PointF`](../../pointf/)定义样条的结构。 |
| offset | Int32 | 距数组中第一个元素的偏移量*points*参数到曲线的起点。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

通过指定数组绘制基数样条[`Point`](../../point/)结构.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | Point[] | 阵列的[`Point`](../../point/)定义样条的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

通过指定数组绘制基数样条[`Point`](../../point/)使用指定张力的结构.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | Point[] | 阵列的[`Point`](../../point/)定义样条的结构。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

通过指定数组绘制基数样条[`Point`](../../point/)使用指定张力的结构.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和高度。 |
| points | Point[] | 阵列的[`Point`](../../point/)定义样条的结构。 |
| offset | Int32 | 距数组中第一个元素的偏移量*points*参数到曲线的起点。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |
| tension | Single | 大于或等于 0.0F 的值指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)



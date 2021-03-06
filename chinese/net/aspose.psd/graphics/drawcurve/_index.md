---
title: DrawCurve
second_title: Aspose.PSD for .NET API 参考
description: 通过PointFaspose.psd/pointf结构的指定数组绘制基数样条此方法使用默认张力 0.5
type: docs
weight: 200
url: /zh/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

通过[`PointF`](../../pointf)结构的指定数组绘制基数样条。此方法使用默认张力 0.5。

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条线的[`PointF`](../../pointf)结构数组。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

使用指定的张力通过指定的[`PointF`](../../pointf)结构数组绘制基数样条。

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | [`PointF`](../../pointf)结构的数组，表示定义曲线的点。 |
| tension | Single | 值大于或等于 0.0F，指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

通过[`PointF`](../../pointf)结构的指定数组绘制基数样条。绘图从数组的开头偏移开始。 此方法使用默认张力 0.5。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条线的[`PointF`](../../pointf)结构数组。 |
| offset | Int32 | 从*points*参数数组中的第一个元素到曲线起点的偏移量。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

使用指定的张力通过指定的[`PointF`](../../pointf)结构数组绘制基数样条。绘图从数组的开头偏移开始。

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | PointF[] | 定义样条线的[`PointF`](../../pointf)结构数组。 |
| offset | Int32 | 从*points*参数数组中的第一个元素到曲线起点的偏移量。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |
| tension | Single | 值大于或等于 0.0F，指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

通过[`Point`](../../point)结构的指定数组绘制基数样条。

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条的[`Point`](../../point)结构数组。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

使用指定的张力通过指定的[`Point`](../../point)结构数组绘制基本样条。

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条的[`Point`](../../point)结构数组。 |
| tension | Single | 值大于或等于 0.0F，指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

使用指定的张力通过指定的[`Point`](../../point)结构数组绘制基本样条。

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定曲线的颜色、宽度和高度。 |
| points | Point[] | 定义样条的[`Point`](../../point)结构数组。 |
| offset | Int32 | 从*points*参数数组中的第一个元素到曲线起点的偏移量。 |
| numberOfSegments | Int32 | 要包含在曲线中的起点之后的段数。 |
| tension | Single | 值大于或等于 0.0F，指定曲线的张力。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 - 或 - *points*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

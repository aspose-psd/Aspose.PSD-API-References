---
title: DrawArc
second_title: Aspose.PSD for .NET API 参考
description: 绘制一条弧表示由一对坐标宽度和高度指定的椭圆的一部分
type: docs
weight: 160
url: /zh/net/aspose.psd/graphics/drawarc/
---
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

绘制一条弧，表示由一对坐标、宽度和高度指定的椭圆的一部分。

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定圆弧的颜色、宽度和样式。 |
| x | Single | 定义椭圆的矩形左上角的 x 坐标。 |
| y | Single | 定义椭圆的矩形左上角的 y 坐标。 |
| width | Single | 定义椭圆的矩形的宽度。 |
| height | Single | 定义椭圆的矩形的高度。 |
| startAngle | Single | 从 x 轴到圆弧起点顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到圆弧终点的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

绘制一条弧，表示由[`RectangleF`](../../rectanglef)结构指定的椭圆的一部分。

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定圆弧的颜色、宽度和样式。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef)定义椭圆边界的结构。 |
| startAngle | Single | 从 x 轴到圆弧起点顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到圆弧终点的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空 |

### 也可以看看

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

绘制一条弧，表示由一对坐标、宽度和高度指定的椭圆的一部分。

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定圆弧的颜色、宽度和样式。 |
| x | Int32 | 定义椭圆的矩形左上角的 x 坐标。 |
| y | Int32 | 定义椭圆的矩形左上角的 y 坐标。 |
| width | Int32 | 定义椭圆的矩形的宽度。 |
| height | Int32 | 定义椭圆的矩形的高度。 |
| startAngle | Int32 | 从 x 轴到圆弧起点顺时针测量的角度。 |
| sweepAngle | Int32 | 从*startAngle*参数顺时针测量到圆弧终点的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

绘制一条弧，表示由[`Rectangle`](../../rectangle)结构指定的椭圆的一部分。

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)确定圆弧的颜色、宽度和样式。 |
| rect | Rectangle | [`RectangleF`](../../rectanglef)定义椭圆边界的结构。 |
| startAngle | Single | 从 x 轴到圆弧起点顺时针测量的角度。 |
| sweepAngle | Single | 从*startAngle*参数顺时针测量到圆弧终点的角度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

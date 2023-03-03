---
title: Graphics.DrawBezier
second_title: Aspose.PSD for .NET API 参考
description: Graphics 方法. 绘制由表示点的四对有序坐标定义的贝塞尔样条
type: docs
weight: 170
url: /zh/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

绘制由表示点的四对有序坐标定义的贝塞尔样条。

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和样式。 |
| x1 | Single | 曲线起点的 x 坐标。 |
| y1 | Single | 曲线起点的 y 坐标。 |
| x2 | Single | 曲线第一个控制点的 x 坐标。 |
| y2 | Single | 曲线第一个控制点的 y 坐标。 |
| x3 | Single | 曲线第二个控制点的 x 坐标。 |
| y3 | Single | 曲线第二个控制点的 y 坐标。 |
| x4 | Single | 曲线终点的 x 坐标。 |
| y4 | Single | 曲线终点的 y 坐标。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

绘制由四个定义的贝塞尔样条[`PointF`](../../pointf/)结构.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和样式。 |
| pt1 | PointF | [`PointF`](../../pointf/)表示曲线起点的结构。 |
| pt2 | PointF | [`PointF`](../../pointf/)表示曲线的第一个控制点的结构。 |
| pt3 | PointF | [`PointF`](../../pointf/)表示曲线的第二个控制点的结构。 |
| pt4 | PointF | [`PointF`](../../pointf/)表示曲线终点的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

绘制由四个定义的贝塞尔样条[`Point`](../../point/)结构.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)确定曲线的颜色、宽度和样式的结构。 |
| pt1 | Point | [`Point`](../../point/)表示曲线起点的结构。 |
| pt2 | Point | [`Point`](../../point/)表示曲线的第一个控制点的结构。 |
| pt3 | Point | [`Point`](../../point/)表示曲线的第二个控制点的结构。 |
| pt4 | Point | [`Point`](../../point/)表示曲线终点的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*一片空白。 |

### 也可以看看

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 命名空间 [Aspose.PSD](../../graphics/)
* 部件 [Aspose.PSD](../../../)



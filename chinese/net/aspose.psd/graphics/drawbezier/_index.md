---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制由四对有序坐标点定义的 Bézier 样条曲线，这些坐标点表示点。"
type: docs
weight: 180
url: /zh/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

绘制由四对有序坐标（表示点）定义的贝塞尔样条。

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | 确定曲线的颜色、宽度和样式的 [`Pen`](../../pen/)。 |
| x1 | 单精度 | 曲线起点的 x 坐标。 |
| y1 | 单精度 | 曲线起点的 y 坐标。 |
| x2 | 单精度 | 曲线第一个控制点的 x 坐标。 |
| y2 | 单精度 | 曲线第一个控制点的 y 坐标。 |
| x3 | 单精度 | 曲线第二个控制点的 x 坐标。 |
| y3 | 单精度 | 曲线第二个控制点的 y 坐标。 |
| x4 | 单精度 | 曲线终点的 x 坐标。 |
| y4 | 单精度 | 曲线结束点的 y 坐标。 |

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

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

绘制由四个 [`PointF`](../../pointf/) 结构定义的 Bézier 样条。

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | 确定曲线的颜色、宽度和样式的 [`Pen`](../../pen/)。 |
| pt1 | PointF | [`PointF`](../../pointf/) 结构表示曲线的起始点。 |
| pt2 | PointF | [`PointF`](../../pointf/) 结构表示曲线的第一个控制点。 |
| pt3 | PointF | [`PointF`](../../pointf/) 结构表示曲线的第二个控制点。 |
| pt4 | PointF | [`PointF`](../../pointf/) 结构表示曲线的结束点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

绘制由四个 [`Point`](../../point/) 结构定义的 Bézier 样条。

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 结构决定曲线的颜色、宽度和样式。 |
| pt1 | Point | [`Point`](../../point/) 结构表示曲线的起始点。 |
| pt2 | Point | [`Point`](../../point/) 结构表示曲线的第一个控制点。 |
| pt3 | Point | [`Point`](../../point/) 结构表示曲线的第二个控制点。 |
| pt4 | Point | [`Point`](../../point/) 结构表示曲线的结束点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



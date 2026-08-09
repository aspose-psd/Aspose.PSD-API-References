---
title: "Graphics.DrawPolygon"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制由 PointF 结构数组定义的多边形。"
type: docs
weight: 300
url: /zh/net/aspose.psd/graphics/drawpolygon/
---
{{< psd/tize >}}
## DrawPolygon(Pen, PointF[]) {#drawpolygon}

绘制由 [`PointF`](../../pointf/) 结构数组定义的多边形。

```csharp
public void DrawPolygon(Pen pen, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定多边形的颜色、宽度和样式。 |
| points | PointF[] | 由 [`PointF`](../../pointf/) 结构组成的数组，表示多边形的顶点。 |

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

## DrawPolygon(Pen, Point[]) {#drawpolygon_1}

绘制由 [`Point`](../../point/) 结构数组定义的多边形。

```csharp
public void DrawPolygon(Pen pen, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 决定多边形的颜色、宽度和样式。 |
| points | Point[] | 由 [`Point`](../../point/) 结构组成的数组，表示多边形的顶点。 |

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



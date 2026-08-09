---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD for .NET API 参考"
description: "Graphics 方法。绘制一系列将 Point 结构数组连接起来的线段"
type: docs
weight: 270
url: /zh/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

绘制一系列将 [`Point`](../../point/) 结构数组连接起来的线段。

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定线段的颜色、宽度和样式。 |
| points | Point[] | 表示要连接的点的 [`Point`](../../point/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |
| ArgumentException | The *points* 数组包含少于 2 个点。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

绘制一系列将 [`PointF`](../../pointf/) 结构数组连接起来的线段。

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 用于确定线段的颜色、宽度和样式。 |
| points | PointF[] | 表示要连接的点的 [`PointF`](../../pointf/) 结构数组。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* 为 null。-or- *points* 为 null。 |
| ArgumentException | The *points* 数组包含少于 2 个点。 |

### 另请参阅

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



---
title: DrawLines
second_title: Aspose.PSD for .NET API 参考
description: 绘制一系列连接数组的线段Pointaspose.psd/point结构.
type: docs
weight: 260
url: /zh/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

绘制一系列连接数组的线段[`Point`](../../point)结构.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了线段的颜色、宽度和样式。 |
| points | Point[] | 数组[`Point`](../../point)表示要连接的点的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |
| ArgumentException | 这*points*数组包含少于 2 个点。 |

### 也可以看看

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

绘制一系列连接数组的线段[`PointF`](../../pointf)结构.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)它决定了线段的颜色、宽度和样式。 |
| points | PointF[] | 数组[`PointF`](../../pointf)表示要连接的点的结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | *pen*为空。 -或- *points*一片空白。 |
| ArgumentException | 这*points*数组包含少于 2 个点。 |

### 也可以看看

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.PSD](../../graphics)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
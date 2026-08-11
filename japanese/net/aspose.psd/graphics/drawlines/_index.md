---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。配列の Point 構造体を接続する一連の線分を描画します。"
type: docs
weight: 270
url: /ja/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

配列の [`Point`](../../point/) 構造体を接続する一連の線分を描画します。

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は線分の色、幅、スタイルを決定します。 |
| points | Point[] | 接続する点を表す [`Point`](../../point/) 構造体の配列。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |
| ArgumentException | *points* 配列の要素が 2 未満です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

配列の [`PointF`](../../pointf/) 構造体を接続する一連の線分を描画します。

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は線分の色、幅、スタイルを決定します。 |
| points | PointF[] | 接続する点を表す [`PointF`](../../pointf/) 構造体の配列。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。-or- *points* は null です。 |
| ArgumentException | *points* 配列の要素が 2 未満です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



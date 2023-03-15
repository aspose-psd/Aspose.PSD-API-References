---
title: Graphics.DrawLines
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. の配列を接続する一連の線分を描画しますPoint構造物.
type: docs
weight: 260
url: /ja/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

の配列を接続する一連の線分を描画します[`Point`](../../point/)構造物.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)線分の色、幅、スタイルを決定します。 |
| points | Point[] | の配列[`Point`](../../point/)接続するポイントを表す構造。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |
| ArgumentException | の*points*配列に含まれる点が 2 つ未満です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

の配列を接続する一連の線分を描画します[`PointF`](../../pointf/)構造物.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)線分の色、幅、スタイルを決定します。 |
| points | PointF[] | の配列[`PointF`](../../pointf/)接続するポイントを表す構造。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen* null です。 -または- *points*無効である。 |
| ArgumentException | の*points*配列に含まれる点が 2 つ未満です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)



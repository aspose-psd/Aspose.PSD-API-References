---
title: Graphics.DrawBezier
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. 点を表す 4 つの順序付けられた座標のペアによって定義されるベジエ スプラインを描画します
type: docs
weight: 170
url: /ja/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

点を表す 4 つの順序付けられた座標のペアによって定義されるベジエ スプラインを描画します。

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、およびスタイルを決定します。 |
| x1 | Single | 曲線の始点の x 座標。 |
| y1 | Single | 曲線の始点の y 座標。 |
| x2 | Single | 曲線の最初の制御点の x 座標。 |
| y2 | Single | 曲線の最初の制御点の y 座標。 |
| x3 | Single | 曲線の 2 番目の制御点の x 座標。 |
| y3 | Single | 曲線の 2 番目の制御点の y 座標。 |
| x4 | Single | 曲線の終点の x 座標。 |
| y4 | Single | 曲線の終点の y 座標。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

4 で定義されるベジェ スプラインを描画します。[`PointF`](../../pointf/)構造物.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、およびスタイルを決定します。 |
| pt1 | PointF | [`PointF`](../../pointf/)曲線の始点を表す構造。 |
| pt2 | PointF | [`PointF`](../../pointf/)曲線の最初の制御点を表す構造体。 |
| pt3 | PointF | [`PointF`](../../pointf/)曲線の 2 番目の制御点を表す構造体。 |
| pt4 | PointF | [`PointF`](../../pointf/)曲線の終点を表す構造。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

4 で定義されるベジェ スプラインを描画します。[`Point`](../../point/)構造物.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)曲線の色、幅、およびスタイルを決定する構造。 |
| pt1 | Point | [`Point`](../../point/)曲線の始点を表す構造。 |
| pt2 | Point | [`Point`](../../point/)曲線の最初の制御点を表す構造体。 |
| pt3 | Point | [`Point`](../../point/)曲線の 2 番目の制御点を表す構造体。 |
| pt4 | Point | [`Point`](../../point/)曲線の終点を表す構造。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)



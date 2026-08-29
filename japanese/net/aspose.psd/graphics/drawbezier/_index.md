---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。4 つの座標の順序付きペアで定義されたベジエスプラインを描画します"
type: docs
weight: 180
url: /ja/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

点を表す4つの順序付き座標ペアで定義されたベジェスプラインを描画します。

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、スタイルを決定します |
| x1 | シングル | 曲線の開始点の x 座標です。 |
| y1 | シングル | 曲線の開始点の y 座標です。 |
| x2 | シングル | 曲線の最初の制御点の x 座標です。 |
| y2 | シングル | 曲線の最初の制御点の y 座標です。 |
| x3 | シングル | 曲線の2番目の制御点の x 座標です。 |
| y3 | シングル | 曲線の2番目の制御点の y 座標です。 |
| x4 | シングル | 曲線の終了点の x 座標です。 |
| y4 | シングル | 曲線の終点の y 座標です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

4つの [`PointF`](../../pointf/) 構造体で定義されたベジエスプラインを描画します。

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) は曲線の色、幅、スタイルを決定します |
| pt1 | PointF | [`PointF`](../../pointf/) 構造体は曲線の開始点を表します。 |
| pt2 | PointF | [`PointF`](../../pointf/) 構造体は曲線の最初の制御点を表します。 |
| pt3 | PointF | [`PointF`](../../pointf/) 構造体は曲線の第二の制御点を表します。 |
| pt4 | PointF | [`PointF`](../../pointf/) 構造体は曲線の終点を表します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

4つの [`Point`](../../point/) 構造体で定義されたベジエスプラインを描画します。

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) 構造体は曲線の色、幅、スタイルを決定します。 |
| pt1 | Point | [`Point`](../../point/) 構造体は曲線の開始点を表します。 |
| pt2 | Point | [`Point`](../../point/) 構造体は曲線の最初の制御点を表します。 |
| pt3 | Point | [`Point`](../../point/) 構造体は曲線の第二の制御点を表します。 |
| pt4 | Point | [`Point`](../../point/) 構造体は曲線の終点を表します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



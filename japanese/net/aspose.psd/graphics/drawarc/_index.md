---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。座標のペアと幅と高さで指定された楕円の一部を表す弧を描画します。"
type: docs
weight: 170
url: /ja/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

座標のペア、幅、および高さで指定された楕円の一部を表す弧を描画します。

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | 弧の色、幅、スタイルを決定する[`Pen`](../../pen/)です。 |
| x | シングル | 楕円を定義する矩形の左上隅の x 座標です。 |
| y | シングル | 楕円を定義する矩形の左上隅の y 座標です。 |
| width | シングル | 楕円を定義する矩形の幅です。 |
| height | シングル | 楕円を定義する矩形の高さです。 |
| startAngle | シングル | 弧の開始点まで、x 軸から時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータから弧の終了点まで、時計回りに測定した角度（度）です。 |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

[`RectangleF`](../../rectanglef/) 構造体で指定された楕円の一部を表す弧を描画します。

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | 弧の色、幅、スタイルを決定する[`Pen`](../../pen/)です。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 構造体は楕円の境界を定義します。 |
| startAngle | シングル | 弧の開始点まで、x 軸から時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータから弧の終了点まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* が null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

座標のペア、幅、および高さで指定された楕円の一部を表す弧を描画します。

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | 弧の色、幅、スタイルを決定する[`Pen`](../../pen/)です。 |
| x | Int32 | 楕円を定義する矩形の左上隅の x 座標です。 |
| y | Int32 | 楕円を定義する矩形の左上隅の y 座標です。 |
| width | Int32 | 楕円を定義する矩形の幅です。 |
| height | Int32 | 楕円を定義する矩形の高さです。 |
| startAngle | Int32 | 弧の開始点まで、x 軸から時計回りに測定した角度（度）です。 |
| sweepAngle | Int32 | *startAngle* パラメータから弧の終了点まで、時計回りに測定した角度（度）です。 |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

[`Rectangle`](../../rectangle/) 構造体で指定された楕円の一部を表す弧を描画します。

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | 弧の色、幅、スタイルを決定する[`Pen`](../../pen/)です。 |
| rect | Rectangle | [`RectangleF`](../../rectanglef/) 構造体は楕円の境界を定義します。 |
| startAngle | シングル | 弧の開始点まで、x 軸から時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータから弧の終了点まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



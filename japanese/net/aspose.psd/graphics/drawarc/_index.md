---
title: Graphics.DrawArc
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. 座標幅および高さのペアで指定された楕円の一部を表す円弧を描画します
type: docs
weight: 160
url: /ja/net/aspose.psd/graphics/drawarc/
---
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

座標、幅、および高さのペアで指定された楕円の一部を表す円弧を描画します。

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)円弧の色、幅、およびスタイルを決定します。 |
| x | Single | 楕円を定義する四角形の左上隅の x 座標。 |
| y | Single | 楕円を定義する四角形の左上隅の y 座標。 |
| width | Single | 楕円を定義する長方形の幅。 |
| height | Single | 楕円を定義する長方形の高さ。 |
| startAngle | Single | X 軸から円弧の始点まで時計回りに測定した角度 (度単位)。 |
| sweepAngle | Single | から時計回りに測定した度単位の角度*startAngle*パラメータを円弧の終点に移動します。 |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

で指定された楕円の一部を表す円弧を描画します[`RectangleF`](../../rectanglef/)構造体.

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)円弧の色、幅、およびスタイルを決定します。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/)楕円の境界を定義する構造。 |
| startAngle | Single | X 軸から円弧の始点まで時計回りに測定した角度 (度単位)。 |
| sweepAngle | Single | から時計回りに測定した度単位の角度*startAngle*パラメータを円弧の終点に移動します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である |

### 関連項目

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

座標、幅、および高さのペアで指定された楕円の一部を表す円弧を描画します。

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)円弧の色、幅、およびスタイルを決定します。 |
| x | Int32 | 楕円を定義する四角形の左上隅の x 座標。 |
| y | Int32 | 楕円を定義する四角形の左上隅の y 座標。 |
| width | Int32 | 楕円を定義する長方形の幅。 |
| height | Int32 | 楕円を定義する長方形の高さ。 |
| startAngle | Int32 | X 軸から円弧の始点まで時計回りに測定した角度 (度単位)。 |
| sweepAngle | Int32 | から時計回りに測定した度単位の角度*startAngle*パラメータを円弧の終点に移動します。 |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

で指定された楕円の一部を表す円弧を描画します[`Rectangle`](../../rectangle/)構造体.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)円弧の色、幅、およびスタイルを決定します。 |
| rect | Rectangle | [`RectangleF`](../../rectanglef/)楕円の境界を定義する構造。 |
| startAngle | Single | X 軸から円弧の始点まで時計回りに測定した角度 (度単位)。 |
| sweepAngle | Single | から時計回りに測定した度単位の角度*startAngle*パラメータを円弧の終点に移動します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)



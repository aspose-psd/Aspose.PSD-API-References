---
title: Graphics.DrawPie
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. で指定された楕円で定義されるパイの形状を描画しますRectangleF構造と 2 つの放射状の線.
type: docs
weight: 280
url: /ja/net/aspose.psd/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

で指定された楕円で定義されるパイの形状を描画します[`RectangleF`](../../rectanglef/)構造と 2 つの放射状の線.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)パイの形の色、幅、スタイルを決定します。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/)パイ形状の元になる楕円を定義する外接する四角形を表す構造体。 |
| startAngle | Single | X 軸から円グラフの最初の辺まで時計回りに測定された角度 (度単位)。 |
| sweepAngle | Single | から時計回りに度単位で測定された角度*startAngle*パラメータをパイ形状の 2 番目の辺に設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

座標ペア、幅、高さ、および 2 本の放射状線で指定された楕円によって定義されるパイ形状を描画します。

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)パイの形の色、幅、スタイルを決定します。 |
| x | Single | パイ形状の元になる楕円を定義する外接する四角形の左上隅の x 座標。 |
| y | Single | パイ形状の元となる楕円を定義する外接する四角形の左上隅の y 座標。 |
| width | Single | パイ形状の元になる楕円を定義する外接する四角形の幅。 |
| height | Single | パイ形状の元になる楕円を定義する外接する四角形の高さ。 |
| startAngle | Single | X 軸から円グラフの最初の辺まで時計回りに測定された角度 (度単位)。 |
| sweepAngle | Single | から時計回りに度単位で測定された角度*startAngle*パラメータをパイ形状の 2 番目の辺に設定します。 |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

で指定された楕円で定義されるパイの形状を描画します[`Rectangle`](../../rectangle/)構造と 2 つの放射状の線.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)パイの形の色、幅、スタイルを決定します。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/)パイ形状の元になる楕円を定義する外接する四角形を表す構造体。 |
| startAngle | Single | X 軸から円グラフの最初の辺まで時計回りに測定された角度 (度単位)。 |
| sweepAngle | Single | から時計回りに度単位で測定された角度*startAngle*パラメータをパイ形状の 2 番目の辺に設定します。 |

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

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

座標ペア、幅、高さ、および 2 本の放射状線で指定された楕円によって定義されるパイ形状を描画します。

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/)パイの形の色、幅、スタイルを決定します。 |
| x | Int32 | パイ形状の元になる楕円を定義する外接する四角形の左上隅の x 座標。 |
| y | Int32 | パイ形状の元となる楕円を定義する外接する四角形の左上隅の y 座標。 |
| width | Int32 | パイ形状の元になる楕円を定義する外接する四角形の幅。 |
| height | Int32 | パイ形状の元になる楕円を定義する外接する四角形の高さ。 |
| startAngle | Int32 | X 軸から円グラフの最初の辺まで時計回りに測定された角度 (度単位)。 |
| sweepAngle | Int32 | から時計回りに度単位で測定された角度*startAngle*パラメータをパイ形状の 2 番目の辺に設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *pen*無効である。 |

### 関連項目

* class [Pen](../../pen/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)



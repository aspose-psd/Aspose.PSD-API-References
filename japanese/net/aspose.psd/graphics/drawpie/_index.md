---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。RectangleF 構造体で指定された楕円と二本の放射線で定義されたパイ形状を描画します。"
type: docs
weight: 290
url: /ja/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

[`RectangleF`](../../rectanglef/) 構造体で指定された楕円と二本の放射線で定義されたパイ形状を描画します。

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) はパイ形状の色、幅、スタイルを決定します。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 構造体は、パイ形状の元になる楕円を定義するバウンディング矩形を表します。 |
| startAngle | シングル | x 軸からパイ形状の第一辺まで、時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータからパイ形状の第二辺まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

座標ペア、幅、高さ、および2本の放射線で指定された楕円によって定義されるパイ形状を描画します。

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) はパイ形状の色、幅、スタイルを決定します。 |
| x | シングル | パイ形状の元になる楕円を定義するバウンディング矩形の左上隅の x 座標です。 |
| y | シングル | パイ形状の元になる楕円を定義するバウンディング矩形の左上隅の y 座標です。 |
| width | シングル | パイ形状の元になる楕円を定義するバウンディング矩形の幅です。 |
| height | シングル | パイ形状の元になる楕円を定義するバウンディング矩形の高さです。 |
| startAngle | シングル | x 軸からパイ形状の第一辺まで、時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータからパイ形状の第二辺まで、時計回りに測定した角度（度）です。 |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

[`Rectangle`](../../rectangle/) 構造体で指定された楕円と2本の放射線で定義されたパイ形状を描画します。

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) はパイ形状の色、幅、スタイルを決定します。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 構造体は、パイ形状の元になる楕円を定義するバウンディング矩形を表します。 |
| startAngle | シングル | x 軸からパイ形状の第一辺まで、時計回りに測定した角度（度）です。 |
| sweepAngle | シングル | *startAngle* パラメータからパイ形状の第二辺まで、時計回りに測定した角度（度）です。 |

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

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

座標ペア、幅、高さ、および2本の放射線で指定された楕円によって定義されるパイ形状を描画します。

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) はパイ形状の色、幅、スタイルを決定します。 |
| x | Int32 | パイ形状の元になる楕円を定義するバウンディング矩形の左上隅の x 座標です。 |
| y | Int32 | パイ形状の元になる楕円を定義するバウンディング矩形の左上隅の y 座標です。 |
| width | Int32 | パイ形状の元になる楕円を定義するバウンディング矩形の幅です。 |
| height | Int32 | パイ形状の元になる楕円を定義するバウンディング矩形の高さです。 |
| startAngle | Int32 | x 軸からパイ形状の第一辺まで、時計回りに測定した角度（度）です。 |
| sweepAngle | Int32 | *startAngle* パラメータからパイ形状の第二辺まで、時計回りに測定した角度（度）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pen* は null です。 |

### 関連項目

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



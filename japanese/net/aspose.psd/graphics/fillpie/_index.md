---
title: Graphics.FillPie
second_title: Aspose.PSD for .NET API リファレンス
description: Graphics 方法. で指定された楕円で定義されたパイ セクションの内部を塗りつぶしますRectangleF構造と 2 つの放射状の線.
type: docs
weight: 370
url: /ja/net/aspose.psd/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

で指定された楕円で定義されたパイ セクションの内部を塗りつぶします。[`RectangleF`](../../rectanglef/)構造と 2 つの放射状の線.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)塗りつぶしの特性を決定します。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/)パイ セクションの元になる楕円を定義する外接する四角形を表す構造体。 |
| startAngle | Single | X 軸から円グラフの最初の辺まで時計回りに測定された度単位の角度。 |
| sweepAngle | Single | から時計回りに測定した度単位の角度*startAngle*パラメータをパイ セクションの 2 番目の側に設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush*無効である。 |

### 関連項目

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

で指定された楕円で定義されたパイ セクションの内部を塗りつぶします。[`RectangleF`](../../rectanglef/)構造と 2 つの放射状の線.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)塗りつぶしの特性を決定します。 |
| rect | RectangleF | [`RectangleF`](../../rectanglef/)パイ セクションの元になる楕円を定義する外接する四角形を表す構造体。 |
| startAngle | Single | X 軸から円グラフの最初の辺まで時計回りに測定された度単位の角度。 |
| sweepAngle | Single | から時計回りに測定した度単位の角度*startAngle*パラメータをパイ セクションの 2 番目の側に設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush*無効である。 |

### 関連項目

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

1 組の座標、幅、高さ、および 2 本の放射状の線で指定された楕円で定義されるパイ セクションの内部を塗りつぶします。

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)塗りつぶしの特性を決定します。 |
| x | Single | パイ セクションの元になる楕円を定義する外接する四角形の左上隅の x 座標。 |
| y | Single | パイ セクションの元になる楕円を定義する外接する四角形の左上隅の y 座標。 |
| width | Single | パイ セクションの元になる楕円を定義する外接する四角形の幅。 |
| height | Single | パイ セクションの元になる楕円を定義する外接する四角形の高さ。 |
| startAngle | Single | X 軸から円グラフの最初の辺まで時計回りに測定された度単位の角度。 |
| sweepAngle | Single | から時計回りに測定した度単位の角度*startAngle*パラメータをパイ セクションの 2 番目の側に設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush*無効である。 |

### 関連項目

* class [Brush](../../brush/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

1 組の座標、幅、高さ、および 2 本の放射状の線で指定された楕円で定義されるパイ セクションの内部を塗りつぶします。

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/)塗りつぶしの特性を決定します。 |
| x | Int32 | パイ セクションの元になる楕円を定義する外接する四角形の左上隅の x 座標。 |
| y | Int32 | パイ セクションの元になる楕円を定義する外接する四角形の左上隅の y 座標。 |
| width | Int32 | パイ セクションの元になる楕円を定義する外接する四角形の幅。 |
| height | Int32 | パイ セクションの元になる楕円を定義する外接する四角形の高さ。 |
| startAngle | Int32 | X 軸から円グラフの最初の辺まで時計回りに測定された度単位の角度。 |
| sweepAngle | Int32 | から時計回りに測定した度単位の角度*startAngle*パラメータをパイ セクションの 2 番目の側に設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *brush*無効である。 |

### 関連項目

* class [Brush](../../brush/)
* class [Graphics](../)
* 名前空間 [Aspose.PSD](../../graphics/)
* 組み立て [Aspose.PSD](../../../)



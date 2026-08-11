---
title: "構造体 RectangleF"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.RectangleF 構造体。矩形の位置とサイズを表す4つの浮動小数点数を格納します。"
type: docs
weight: 5850
url: /ja/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

矩形の位置とサイズを表す4つの浮動小数点数のセットを格納します。

```csharp
public struct RectangleF
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | `RectangleF` 構造体の新しいインスタンスを、指定された位置とサイズで初期化します。 |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | `RectangleF` 構造体の新しいインスタンスを、指定された位置とサイズで初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | `RectangleF` 構造体の新しいインスタンスを取得します。このインスタンスは [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/) および [`Height`](./height/) の値がゼロに設定されています。 |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | この `RectangleF` 構造体の [`Y`](./y/) と [`Height`](./height/) の合計である y 座標を取得または設定します。 |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | この `RectangleF` 構造体の高さを取得または設定します。 |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | この `RectangleF` の [`Width`](./width/) または [`Height`](./height/) プロパティがゼロであるかどうかを示す値を取得します。 |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | この `RectangleF` 構造体の左端の x 座標を取得または設定します。 |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | この `RectangleF` 構造体の左上隅の座標を取得または設定します。 |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | この `RectangleF` 構造体の [`X`](./x/) と [`Width`](./width/) の合計である x 座標を取得または設定します。 |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | この `RectangleF` のサイズを取得または設定します。 |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | この `RectangleF` 構造体の上端の y 座標を取得または設定します。 |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | この `RectangleF` 構造体の幅を取得または設定します。 |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | この `RectangleF` 構造体の左上隅の x 座標を取得または設定します。 |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | この `RectangleF` 構造体の左上隅の y 座標を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | 指定された位置に左上隅と右下隅を持つ `RectangleF` 構造体を作成します。 |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | 指定された2つの点から新しい [`Rectangle`](../rectangle/) を作成します。作成された [`Rectangle`](../rectangle/) の2つの頂点は渡された *point1* と *point2* に等しくなります。これらは通常、対角の頂点です。 |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | 指定された `RectangleF` 構造体の膨張したコピーを作成して返します。コピーは指定された量だけ膨張します。元の矩形は変更されません。 |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | 2つの矩形の交差部分を表す `RectangleF` 構造体を返します。交差がない場合は空の `RectangleF` が返されます。 |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | 2つの矩形の合併を含むことができる、可能な限り最小の第3の矩形を作成します。 |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | 指定された点がこの `RectangleF` 構造体に含まれているかどうかを判断します。 |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | *rect* が表す矩形領域がこの `RectangleF` 構造体に完全に含まれているかどうかを判断します。 |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | 指定された点がこの `RectangleF` 構造体に含まれているかどうかを判断します。 |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | *obj* がこの `RectangleF` と同じ位置とサイズを持つ `RectangleF` かどうかをテストします。 |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | この `RectangleF` 構造体のハッシュコードを取得します。 |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | この `RectangleF` を指定された量だけ膨張させます。 |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | この `RectangleF` 構造体を指定された量だけ膨張させます。 |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | この `RectangleF` 構造体を自身と指定された `RectangleF` 構造体との交差部分に置き換えます。 |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | この矩形が *rect* と交差するかどうかを判断します。 |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | この矩形の位置を指定された量だけ調整します。 |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | この矩形の位置を指定された量だけ調整します。 |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | この `RectangleF` の属性を人間が読みやすい文字列に変換します。 |
| [operator /](../../aspose.psd/rectanglef/op_division/) | 演算子 / を実装します。 |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | 二つの `RectangleF` 構造体の位置とサイズが等しいかテストします。 |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | 指定された [`Rectangle`](../rectangle/) 構造体を `RectangleF` 構造体に変換します。 |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | 二つの `RectangleF` 構造体の位置またはサイズが異なるかテストします。 |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | 演算子 * を実装します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



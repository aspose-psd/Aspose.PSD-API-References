---
title: "構造体 Rectangle"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Rectangle 構造体。矩形の位置とサイズを表す 4 つの整数のセットを格納します。"
type: docs
weight: 5840
url: /ja/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

矩形の位置とサイズを表す 4 つの整数のセットを格納します。

```csharp
public struct Rectangle
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | 指定された位置とサイズで `Rectangle` 構造体の新しいインスタンスを初期化します。 |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | 指定された位置とサイズで `Rectangle` 構造体の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | `Rectangle` 構造体の新しいインスタンスを取得します。このインスタンスは [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/)、[`Height`](./height/) の値が 0 に設定されています。 |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | この `Rectangle` 構造体の [`Y`](./y/) と [`Height`](./height/) プロパティ値の合計である y 座標を取得または設定します。 |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | この `Rectangle` 構造体の高さを取得または設定します。 |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | この `Rectangle` のすべての数値プロパティが 0 の値であるかどうかを示す値を取得します。 |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | この `Rectangle` 構造体の左端の x 座標を取得または設定します。 |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | この `Rectangle` 構造体の左上隅の座標を取得または設定します。 |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | この `Rectangle` 構造体の [`X`](./x/) と [`Width`](./width/) プロパティ値の合計である x 座標を取得または設定します。 |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | この `Rectangle` のサイズを取得または設定します。 |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | この `Rectangle` 構造体の上端の y 座標を取得または設定します。 |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | この `Rectangle` 構造体の幅を取得または設定します。 |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | この `Rectangle` 構造体の左上隅の x 座標を取得または設定します。 |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | この `Rectangle` 構造体の左上隅の y 座標を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | 指定された [`RectangleF`](../rectanglef/) 構造体を、[`RectangleF`](../rectanglef/) の値を次の整数に切り上げて `Rectangle` 構造体に変換します。 |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | 指定されたエッジ位置で `Rectangle` 構造体を作成します。 |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | 指定された2つの点から新しい `Rectangle` を作成します。作成された `Rectangle` の2つの縦方向は渡された *point1* と *point2* に等しくなります。これらは通常、対角の頂点です。 |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | 指定された `Rectangle` 構造体の拡張コピーを作成して返します。コピーは指定された量だけ拡張されます。元の `Rectangle` 構造体は変更されません。 |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | 2つの `Rectangle` 構造体の交差を表す3番目の `Rectangle` 構造体を返します。交差がない場合は空の `Rectangle` が返されます。 |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | 指定された [`RectangleF`](../rectanglef/) を、[`RectangleF`](../rectanglef/) の値を最も近い整数に丸めて `Rectangle` に変換します。 |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | 指定された [`RectangleF`](../rectanglef/) を、[`RectangleF`](../rectanglef/) の値を切り捨てて `Rectangle` に変換します。 |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | 2つの `Rectangle` 構造体の合集合を含む `Rectangle` 構造体を取得します。 |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | 指定された点がこの `Rectangle` 構造体に含まれているかどうかを判定します。 |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | *rect* が表す矩形領域がこの `Rectangle` 構造体に完全に含まれているかどうかを判定します。 |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | 指定された点がこの `Rectangle` 構造体に含まれているかどうかを判定します。 |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | *obj* がこの `Rectangle` 構造体と同じ位置とサイズを持つ `Rectangle` 構造体かどうかをテストします。 |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | この `Rectangle` 構造体のハッシュコードを返します。 |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | この `Rectangle` を指定された量だけ拡張します。 |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | この `Rectangle` を指定された量だけ拡張します。 |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | この `Rectangle` を自身と指定された `Rectangle` の交差部分に置き換えます。 |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | この矩形が *rect* と交差するかどうかを判断します。 |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | この矩形の位置を指定された量だけ調整します。 |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | この矩形の位置を指定された量だけ調整します。 |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | この `Rectangle` の属性を人間が読みやすい文字列に変換します。 |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | 2つの `Rectangle` 構造体が同じ位置とサイズを持つかどうかをテストします。 |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | 2つの `Rectangle` 構造体が位置またはサイズが異なるかどうかをテストします。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



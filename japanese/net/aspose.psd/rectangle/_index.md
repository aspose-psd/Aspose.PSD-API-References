---
title: Struct Rectangle
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Rectangle 構造体. 四角形の位置とサイズを表す 4 つの整数のセットを格納します
type: docs
weight: 5340
url: /ja/net/aspose.psd/rectangle/
---
## Rectangle structure

四角形の位置とサイズを表す 4 つの整数のセットを格納します。

```csharp
public struct Rectangle
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | の新しいインスタンスを初期化します`Rectangle`指定された場所とサイズの構造体. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | の新しいインスタンスを初期化します`Rectangle`指定された場所とサイズの構造体. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | の新しいインスタンスを取得します`Rectangle`持つ構造[`X`](./x/) 、[`Y`](./y/) 、[`Width`](./width/)と[`Height`](./height/)ゼロに設定された値. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | の合計である y 座標を取得または設定します[`Y`](./y/)と[`Height`](./height/)これのプロパティ値`Rectangle`構造体. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | この高さを取得または設定します`Rectangle`構造体. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | このすべての数値プロパティが`Rectangle`ゼロの値を持つ. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | この左端の x 座標を取得または設定します`Rectangle`構造体. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | この左上隅の座標を取得または設定します`Rectangle`構造体. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | の合計である x 座標を取得または設定します。[`X`](./x/)と[`Width`](./width/)これのプロパティ値`Rectangle`構造体. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | このサイズを取得または設定します`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | この上端の y 座標を取得または設定します`Rectangle`構造体. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | この幅を取得または設定します`Rectangle`構造体. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | この左上隅の x 座標を取得または設定します`Rectangle`構造体. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | この左上隅の y 座標を取得または設定します`Rectangle`構造体. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | 指定された[`RectangleF`](../rectanglef/)への構造`Rectangle`を丸めた構造[`RectangleF`](../rectanglef/)値から次に高い整数値へ. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | を作成します`Rectangle`指定されたエッジ位置を持つ構造. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | 新しい`Rectangle`指定された 2 点から。作成された 2 つの垂直`Rectangle`渡されたものと等しくなります*point1*と*point2*.これらは通常、反対側の頂点になります。 |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | 指定された`Rectangle`構造。コピーは、指定された量だけ膨張します。オリジナル`Rectangle`構造は変更されません. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | 3 番目を返します`Rectangle`他の 2 つの交差点を表す構造`Rectangle`構造。交点がない場合は空`Rectangle`返されます. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | 指定された[`RectangleF`](../rectanglef/)に`Rectangle`丸めることで[`RectangleF`](../rectanglef/)最も近い整数値への値. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | 指定された[`RectangleF`](../rectanglef/)に`Rectangle`を切り捨てることによって[`RectangleF`](../rectanglef/)値. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | を取得します`Rectangle` つの結合を含む構造`Rectangle`構造物. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | 指定したポイントがこの範囲内に含まれているかどうかを判断します`Rectangle`構造体. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | で表される長方形の領域が*rect*この中に完全に含まれています`Rectangle`構造体. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | 指定したポイントがこの範囲内に含まれているかどうかを判断します`Rectangle`構造体. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | かどうかをテストします*obj*です`Rectangle`これと同じ位置とサイズの構造`Rectangle`構造体. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | このハッシュコードを返します`Rectangle`構造体. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | これを膨らませます`Rectangle`指定された量によって. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | これを膨らませます`Rectangle`指定された量によって. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | これを置き換えます`Rectangle`それ自体と指定された`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | この長方形が交差するかどうかを決定します*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | 幅と高さを正にし、左を右より小さく、上を下より小さくして、長方形を正規化します。 |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | 指定した量だけこの長方形の位置を調整します。 |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | 指定した量だけこの長方形の位置を調整します。 |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | この属性を変換します`Rectangle`人間が読める文字列. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | 2 つの`Rectangle`構造体の位置とサイズは同じです. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | 2 つの`Rectangle`構造は場所またはサイズが異なります. |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



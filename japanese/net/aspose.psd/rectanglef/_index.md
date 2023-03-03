---
title: Struct RectangleF
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.RectangleF 構造体. 四角形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します
type: docs
weight: 5350
url: /ja/net/aspose.psd/rectanglef/
---
## RectangleF structure

四角形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。

```csharp
public struct RectangleF
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | の新しいインスタンスを初期化します`RectangleF`指定された場所とサイズの構造体. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | の新しいインスタンスを初期化します`RectangleF`指定された場所とサイズの構造体. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | の新しいインスタンスを取得します`RectangleF`持つ構造[`X`](./x/) 、[`Y`](./y/) 、[`Width`](./width/)と[`Height`](./height/)ゼロに設定された値. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | の合計である y 座標を取得または設定します[`Y`](./y/)と[`Height`](./height/)これの`RectangleF`構造体. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | この高さを取得または設定します`RectangleF`構造体. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | かどうかを示す値を取得します。[`Width`](./width/)また[`Height`](./height/)これのプロパティ`RectangleF`ゼロの値を持っています. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | この左端の x 座標を取得または設定します`RectangleF`構造体. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | この左上隅の座標を取得または設定します`RectangleF`構造体. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | の合計である x 座標を取得または設定します。[`X`](./x/)と[`Width`](./width/)これの`RectangleF`構造体. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | このサイズを取得または設定します`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | この上端の y 座標を取得または設定します`RectangleF`構造体. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | この幅を取得または設定します`RectangleF`構造体. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | この左上隅の x 座標を取得または設定します`RectangleF`構造体. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | この左上隅の y 座標を取得または設定します`RectangleF`構造体. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | を作成します`RectangleF`指定された位置に左上隅と右下隅がある構造. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | 新しい[`Rectangle`](../rectangle/)指定された 2 点から。作成された 2 つの頂点[`Rectangle`](../rectangle/)渡されたものと等しくなります*point1*と*point2*.これらは通常、反対側の頂点になります。 |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | 指定された`RectangleF`構造。コピーは、指定された量だけ膨張します。元の長方形は変更されません. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | を返します`RectangleF` 2 つの長方形の交点を表す構造。交差点がなく、空いている場合`RectangleF`返されます. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | 結合を形成する 2 つの四角形の両方を含むことができる最小の 3 番目の四角形を作成します. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | 指定したポイントがこの範囲内に含まれているかどうかを判断します`RectangleF`構造体. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | で表される長方形の領域が*rect*この中に完全に含まれています`RectangleF`構造体. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | 指定したポイントがこの範囲内に含まれているかどうかを判断します`RectangleF`構造体. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | かどうかをテストします*obj*です`RectangleF`これと同じ位置とサイズで`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | このハッシュコードを取得します`RectangleF`構造体. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | これを膨らませます`RectangleF`指定された量によって. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | これを膨らませます`RectangleF`指定された量で構造化. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | これを置き換えます`RectangleF`それ自体と指定されたものとの交点を持つ構造`RectangleF`構造体. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | この長方形が交差するかどうかを決定します*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | 幅と高さを正にし、左を右より小さく、上を下より小さくして、長方形を正規化します。 |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | 指定した量だけこの長方形の位置を調整します。 |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | 指定した量だけこの長方形の位置を調整します。 |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | この属性を変換します`RectangleF`人間が読める文字列. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | 演算子 /. を実装します |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | 2 つの`RectangleF`構造体の位置とサイズは同じです. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | 指定された[`Rectangle`](../rectangle/)への構造`RectangleF`構造体. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | 2 つの`RectangleF`構造は場所またはサイズが異なります. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | 演算子 *. を実装します |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



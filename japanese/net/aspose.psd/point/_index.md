---
title: "構造体 Point"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Point 構造体。二次元平面上の点を定義する整数の x と y 座標の順序付きペアを表します"
type: docs
weight: 5760
url: /ja/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。

```csharp
public struct Point
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Point](point/#constructor_1)(int) | `Point` 構造体の新しいインスタンスを、整数値で指定された座標を使用して初期化します。 |
| [Point](point/#constructor)(Size) | `Point` 構造体の新しいインスタンスを、[`Size`](../size/) 構造体から初期化します。 |
| [Point](point/#constructor_2)(int, int) | `Point` 構造体の新しいインスタンスを、指定された座標で初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | `Point` 構造体の新しいインスタンスを取得します。このインスタンスは [`X`](./x/) と [`Y`](./y/) の値がゼロに設定されています。 |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | この `Point` が空かどうかを示す値を取得します。 |
| [X](../../aspose.psd/point/x/) { get; set; } | この `Point` の x 座標を取得または設定します。 |
| [Y](../../aspose.psd/point/y/) { get; set; } | この `Point` の y 座標を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | 指定された `Point` に、指定された [`Size`](../size/) を加算します。 |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | 指定された [`PointF`](../pointf/) の値を次の整数に切り上げて、`Point` に変換します。 |
| static [Round](../../aspose.psd/point/round/)(PointF) | 指定された [`PointF`](../pointf/) の値を最も近い整数に丸めて、`Point` オブジェクトに変換します。 |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | 指定された `Point` から指定された [`Size`](../size/) を減算した結果を返します。 |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | 指定された [`PointF`](../pointf/) の値を切り捨てて、`Point` に変換します。 |
| override [Equals](../../aspose.psd/point/equals/)(object) | この `Point` が指定されたオブジェクトと同じ座標を持つかどうかを指定します。 |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | この `Point` のハッシュコードを返します。 |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | この `Point` を指定された `Point` で平行移動します。 |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | この `Point` を指定された量だけ平行移動します。 |
| override [ToString](../../aspose.psd/point/tostring/)() | この `Point` を人間が読みやすい文字列に変換します。 |
| [operator +](../../aspose.psd/point/op_addition/) | `Point` を指定された [`Size`](../size/) で平行移動します。 |
| [operator ==](../../aspose.psd/point/op_equality/) | 2つの `Point` オブジェクトを比較します。結果は、2つの `Point` オブジェクトの [`X`](./x/) および [`Y`](./y/) プロパティの値が等しいかどうかを示します。 |
| [explicit operator](../../aspose.psd/point/op_explicit/) | 指定された `Point` 構造体を [`Size`](../size/) 構造体に変換します。 |
| [implicit operator](../../aspose.psd/point/op_implicit/) | 指定された `Point` 構造体を [`PointF`](../pointf/) 構造体に変換します。 |
| [operator !=](../../aspose.psd/point/op_inequality/) | 2つの `Point` オブジェクトを比較します。結果は、2つの `Point` オブジェクトの [`X`](./x/) または [`Y`](./y/) プロパティの値が等しくないかどうかを示します。 |
| [operator -](../../aspose.psd/point/op_subtraction/) | 指定された [`Size`](../size/) の負の値で `Point` を平行移動します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



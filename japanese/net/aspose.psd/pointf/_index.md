---
title: "構造体 PointF"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.PointF 構造体。2 次元平面上の点を定義する、浮動小数点の x と y 座標の順序付きペアを表します。"
type: docs
weight: 5770
url: /ja/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

2 次元平面上の点を定義する浮動小数点の x および y 座標の順序付きペアを表します。

```csharp
public struct PointF
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PointF](pointf/)(float, float) | 指定された座標で `PointF` 構造体の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | `PointF` 構造体の新しいインスタンスを取得します。このインスタンスは [`X`](./x/) と [`Y`](./y/) の値が 0 に設定されています。 |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | この `PointF` が空かどうかを示す値を取得します。 |
| [X](../../aspose.psd/pointf/x/) { get; set; } | この `PointF` の x 座標を取得または設定します。 |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | この `PointF` の y 座標を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | 指定された [`Size`](../size/) で与えられた `PointF` を平行移動します。 |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | 指定された [`SizeF`](../sizef/) で与えられた `PointF` を平行移動します。 |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | 指定されたサイズの負の値で `PointF` を平行移動します。 |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | 指定されたサイズの負の値で `PointF` を平行移動します。 |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | この `PointF` が指定されたオブジェクトと同じ座標を含むかどうかを指定します。 |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | この `PointF` 構造体のハッシュコードを返します。 |
| override [ToString](../../aspose.psd/pointf/tostring/)() | この `PointF` を人間が読みやすい文字列に変換します。 |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | 与えられた [`Size`](../size/) で `PointF` を平行移動します。（演算子 2 つ） |
| [operator ==](../../aspose.psd/pointf/op_equality/) | 2 つの `PointF` 構造体を比較します。結果は、2 つの `PointF` 構造体の [`X`](./x/) および [`Y`](./y/) プロパティの値が等しいかどうかを指定します。 |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | 指定された点の座標が等しくないかどうかを判定します。 |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | 与えられた [`Size`](../size/) の負の値で `PointF` を平行移動します。（演算子 2 つ） |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



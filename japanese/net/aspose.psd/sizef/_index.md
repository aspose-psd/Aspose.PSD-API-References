---
title: "構造体 SizeF"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.SizeF 構造体。通常は矩形の幅と高さである浮動小数点数の順序付きペアを格納します。"
type: docs
weight: 6060
url: /ja/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

通常は矩形の幅と高さとなる、順序付けられた浮動小数点数のペアを格納します。

```csharp
public struct SizeF
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | 指定された [`PointF`](../pointf/) から `SizeF` 構造体の新しいインスタンスを初期化します。 |
| [SizeF](sizef/#constructor_1)(SizeF) | 指定された `SizeF` から `SizeF` 構造体の新しいインスタンスを初期化します。 |
| [SizeF](sizef/#constructor_2)(float, float) | 指定された寸法から `SizeF` 構造体の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | `SizeF` 構造体の新しいインスタンスを取得します。そのインスタンスは [`Width`](./width/) と [`Height`](./height/) の値がゼロに設定されています。 |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | この `SizeF` の垂直成分を取得または設定します。 |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | この `SizeF` の幅と高さがゼロかどうかを示す値を取得します。 |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | この `SizeF` の水平成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | ある `SizeF` 構造体の幅と高さを別の `SizeF` 構造体の幅と高さに加算します。 |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | ある `SizeF` 構造体の幅と高さを別の `SizeF` 構造体の幅と高さから減算します。 |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | 指定されたオブジェクトがこの `SizeF` と同じ寸法の `SizeF` かどうかをテストします。 |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | この [`Size`](../size/) 構造体のハッシュコードを返します。 |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | `SizeF` を [`PointF`](../pointf/) に変換します。 |
| [ToSize](../../aspose.psd/sizef/tosize/)() | `SizeF` を切り捨てたサイズ値を持つ [`Size`](../size/) 構造体に変換します。 |
| override [ToString](../../aspose.psd/sizef/tostring/)() | この `SizeF` を表す人間が読みやすい文字列を作成します。 |
| [operator +](../../aspose.psd/sizef/op_addition/) | ある `SizeF` 構造体の幅と高さを別の `SizeF` 構造体の幅と高さに加算します。 |
| [operator ==](../../aspose.psd/sizef/op_equality/) | 2 つの `SizeF` 構造体が等しいかどうかをテストします。 |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | 指定された `SizeF` を [`PointF`](../pointf/) に変換します。 |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | 2 つの `SizeF` 構造体が異なるかどうかをテストします。 |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | ある `SizeF` 構造体の幅と高さを別の `SizeF` 構造体の幅と高さから減算します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



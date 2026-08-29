---
title: "構造体 Size"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Size 構造体。サイズを表します。"
type: docs
weight: 6050
url: /ja/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

サイズを表します。

```csharp
public struct Size
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Size](size/#constructor)(Point) | 指定された [`Point`](../point/) から `Size` 構造体の新しいインスタンスを初期化します。 |
| [Size](size/#constructor_1)(int, int) | 指定された寸法から `Size` 構造体の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | [`Width`](./width/) と [`Height`](./height/) の値が 0 に設定された `Size` 構造体の新しいインスタンスを取得します。 |
| [Height](../../aspose.psd/size/height/) { get; set; } | この `Size` の垂直成分を取得または設定します。 |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | `Size` の幅と高さが 0 であるかどうかを示す値を取得します。 |
| [Width](../../aspose.psd/size/width/) { get; set; } | この `Size` の水平成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | ある `Size` 構造体の幅と高さを別の `Size` 構造体の幅と高さに加算します。 |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | 指定された [`SizeF`](../sizef/) 構造体を `Size` 構造体に変換し、`SizeF` の値を次の整数に切り上げます。 |
| static [Round](../../aspose.psd/size/round/)(SizeF) | 指定された [`SizeF`](../sizef/) 構造体を `Size` 構造体に変換し、[`SizeF`](../sizef/) の値を最も近い整数に丸めます。 |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | ある `Size` 構造体の幅と高さを別の `Size` 構造体の幅と高さから減算します。 |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | 指定された [`SizeF`](../sizef/) 構造体を `Size` 構造体に変換し、[`SizeF`](../sizef/) の値を次の整数に切り捨てます。 |
| override [Equals](../../aspose.psd/size/equals/)(object) | 指定されたオブジェクトがこの `Size` と同じ寸法の `Size` かどうかをテストします。 |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | この `Size` 構造体のハッシュコードを返します。 |
| override [ToString](../../aspose.psd/size/tostring/)() | この `Size` を表す人間が読みやすい文字列を作成します。 |
| [operator +](../../aspose.psd/size/op_addition/) | ある `Size` 構造体の幅と高さを別の `Size` 構造体の幅と高さに加算します。 |
| [operator ==](../../aspose.psd/size/op_equality/) | 2 つの `Size` 構造体が等しいかどうかをテストします。 |
| [explicit operator](../../aspose.psd/size/op_explicit/) | 指定された `Size` を [`Point`](../point/) に変換します。 |
| [implicit operator](../../aspose.psd/size/op_implicit/) | 指定された `Size` を [`SizeF`](../sizef/) に変換します。 |
| [operator !=](../../aspose.psd/size/op_inequality/) | 2 つの `Size` 構造体が異なるかどうかをテストします。 |
| [operator -](../../aspose.psd/size/op_subtraction/) | ある `Size` 構造体の幅と高さを別の `Size` 構造体の幅と高さから減算します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Struct Size
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Size 構造体. サイズを表します
type: docs
weight: 5550
url: /ja/net/aspose.psd/size/
---
## Size structure

サイズを表します。

```csharp
public struct Size
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Size](size/#constructor)(Point) | の新しいインスタンスを初期化します`Size`指定された構造[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | の新しいインスタンスを初期化します`Size`指定された次元からの構造. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | の新しいインスタンスを取得します`Size`持つ構造[`Width`](./width/)と[`Height`](./height/)ゼロに設定された値. |
| [Height](../../aspose.psd/size/height/) { get; set; } | この垂直コンポーネントを取得または設定します`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | かどうかを示す値を取得します。`Size`幅と高さは 0. です |
| [Width](../../aspose.psd/size/width/) { get; set; } | この水平成分を取得または設定します`Size` . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | 1 の幅と高さを加算します`Size`別の幅と高さの構造`Size`構造体. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | 指定された[`SizeF`](../sizef/)への構造`Size`の値を四捨五入して構造化します。`Size`次に高い整数値への構造。 |
| static [Round](../../aspose.psd/size/round/)(SizeF) | 指定された[`SizeF`](../sizef/)への構造`Size`の値を四捨五入して構造化します。[`SizeF`](../sizef/)最も近い整数値への構造. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | 幅と高さを 1 減算します`Size`別の幅と高さからの構造`Size`構造体. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | 指定された[`SizeF`](../sizef/)への構造`Size`の値を切り捨てて構造化する[`SizeF`](../sizef/)構造体を次に低い整数値に変換します. |
| override [Equals](../../aspose.psd/size/equals/)(object) | 指定されたオブジェクトが`Size`これと同じ寸法で`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | このハッシュコードを返します`Size`構造体. |
| override [ToString](../../aspose.psd/size/tostring/)() | これを表す人間が読める文字列を作成します`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | 1 の幅と高さを加算します`Size`別の幅と高さの構造`Size`構造体. |
| [operator ==](../../aspose.psd/size/op_equality/) | 2 つの`Size`構造は等しい. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | 指定された`Size`に[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | 指定された`Size`に[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | 2 つの`Size`構造が異なります. |
| [operator -](../../aspose.psd/size/op_subtraction/) | 幅と高さを 1 減算します`Size`別の幅と高さからの構造`Size`構造体. |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



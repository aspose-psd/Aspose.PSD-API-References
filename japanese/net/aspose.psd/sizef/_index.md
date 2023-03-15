---
title: Struct SizeF
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.SizeF 構造体. 浮動小数点数の順序付けられたペア 通常は四角形の幅と高さ を格納します
type: docs
weight: 5560
url: /ja/net/aspose.psd/sizef/
---
## SizeF structure

浮動小数点数の順序付けられたペア (通常は四角形の幅と高さ) を格納します。

```csharp
public struct SizeF
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | の新しいインスタンスを初期化します`SizeF`指定された構造[`PointF`](../pointf/) . |
| [SizeF](sizef/#constructor_1)(SizeF) | の新しいインスタンスを初期化します`SizeF`指定された構造`SizeF` . |
| [SizeF](sizef/#constructor_2)(float, float) | の新しいインスタンスを初期化します`SizeF`指定された次元からの構造. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | の新しいインスタンスを取得します`SizeF`持つ構造[`Width`](./width/)と[`Height`](./height/)ゼロに設定された値. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | この垂直コンポーネントを取得または設定します`SizeF` . |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | かどうかを示す値を取得します。`SizeF`幅と高さがゼロです。 |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | この水平成分を取得または設定します`SizeF` . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | 1 の幅と高さを加算します`SizeF`別の幅と高さの構造`SizeF`構造体. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | 幅と高さを 1 減算します`SizeF`別の幅と高さからの構造`SizeF`構造体. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | 指定されたオブジェクトが`SizeF`これと同じ寸法で`SizeF` . |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | このハッシュコードを返します[`Size`](../size/)構造体. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | を変換します`SizeF`に[`PointF`](../pointf/) . |
| [ToSize](../../aspose.psd/sizef/tosize/)() | を変換します`SizeF`に[`Size`](../size/)サイズ値が切り捨てられた構造体. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | これを表す人間が読める文字列を作成します`SizeF` . |
| [operator +](../../aspose.psd/sizef/op_addition/) | 1 の幅と高さを加算します`SizeF`別の幅と高さの構造`SizeF`構造体. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | 2 つの`SizeF`構造は等しい. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | 指定された`SizeF`に[`PointF`](../pointf/) . |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | 2 つの`SizeF`構造が異なります. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | 幅と高さを 1 減算します`SizeF`別の幅と高さからの構造`SizeF`構造体. |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



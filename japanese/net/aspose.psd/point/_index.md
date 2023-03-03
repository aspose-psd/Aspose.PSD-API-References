---
title: Struct Point
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Point 構造体. 2 次元平面内の点を定義する整数 x 座標と y 座標の順序付けられたペアを表します
type: docs
weight: 5260
url: /ja/net/aspose.psd/point/
---
## Point structure

2 次元平面内の点を定義する整数 x 座標と y 座標の順序付けられたペアを表します。

```csharp
public struct Point
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Point](point/#constructor_1)(int) | の新しいインスタンスを初期化します`Point`整数値で指定された座標を使用する構造体. |
| [Point](point/#constructor)(Size) | の新しいインスタンスを初期化します`Point`からの構造[`Size`](../size/)構造体. |
| [Point](point/#constructor_2)(int, int) | の新しいインスタンスを初期化します`Point`指定された座標を持つ構造体. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | の新しいインスタンスを取得します`Point`持つ構造[`X`](./x/)と[`Y`](./y/)ゼロに設定された値. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | かどうかを示す値を取得します。`Point`空です. |
| [X](../../aspose.psd/point/x/) { get; set; } | この x 座標を取得または設定します`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | この y 座標を取得または設定します`Point` . |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | 指定された[`Size`](../size/)指定された`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | 指定された[`PointF`](../pointf/)に`Point`の値を丸めることによって[`PointF`](../pointf/)次に高い整数値へ. |
| static [Round](../../aspose.psd/point/round/)(PointF) | 指定された[`PointF`](../pointf/)に`Point`オブジェクトを丸めて`Point`最も近い整数への値. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | 指定された減算の結果を返します[`Size`](../size/)指定から`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | 指定された[`PointF`](../pointf/)に`Point`の値を切り捨てることによって`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | これが`Point`指定されたものと同じ座標を含むObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | このハッシュコードを返します`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | これを翻訳します`Point`指定された`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | これを翻訳します`Point`指定された量によって. |
| override [ToString](../../aspose.psd/point/tostring/)() | これを変換`Point`人間が読める文字列. |
| [operator +](../../aspose.psd/point/op_addition/) | を変換します`Point`与えられた[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | 2 つの比較`Point`オブジェクト。結果は、[`X`](./x/)と[`Y`](./y/)二つの性質`Point`オブジェクトは等しい. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | 指定された`Point`への構造[`Size`](../size/)構造体. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | 指定された`Point`への構造[`PointF`](../pointf/)構造体. |
| [operator !=](../../aspose.psd/point/op_inequality/) | 2 つの比較`Point`オブジェクト。結果は、[`X`](./x/)また[`Y`](./y/)二つの性質`Point`オブジェクトが等しくありません. |
| [operator -](../../aspose.psd/point/op_subtraction/) | を変換します`Point`与えられたの負によって[`Size`](../size/) . |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



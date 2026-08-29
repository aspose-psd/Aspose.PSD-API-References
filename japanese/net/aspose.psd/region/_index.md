---
title: "クラス Region"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Region クラス。矩形とパスで構成されたグラフィック形状の内部を記述します。このクラスは継承できません。"
type: docs
weight: 5860
url: /ja/net/aspose.psd/region/
---
{{< psd/tize >}}
## Region class

矩形とパスで構成されたグラフィックシェイプの内部を記述します。このクラスは継承できません。

```csharp
public sealed class Region
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Region](region/#constructor)() | 新しい `Region` を初期化します。 |
| [Region](region/#constructor_1)(GraphicsPath) | 指定された [`GraphicsPath`](../graphicspath/) を使用して新しい `Region` を初期化します。 |
| [Region](region/#constructor_2)(Rectangle) | 指定された [`Rectangle`](../rectangle/) 構造体から新しい `Region` を初期化します。 |
| [Region](region/#constructor_3)(RectangleF) | 指定された [`RectangleF`](../rectanglef/) 構造体から新しい `Region` を初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | この `Region` と交差しない、指定された [`GraphicsPath`](../graphicspath/) の部分を含むようにこの `Region` を更新します。 |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | この `Region` と交差しない、指定された [`Rectangle`](../rectangle/) 構造体の部分を含むようにこの `Region` を更新します。 |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | この `Region` を更新して、指定された [`RectangleF`](../rectanglef/) 構造体のうち、この `Region` と交差しない部分を含むようにします。 |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | この `Region` を更新して、指定された `Region` のうち、この `Region` と交差しない部分を含むようにします。 |
| [DeepClone](../../aspose.psd/region/deepclone/)() | この `Region` の正確なディープコピーを作成します。 |
| override [Equals](../../aspose.psd/region/equals/#equals_1)(object) | オブジェクトが等しいかどうかを確認します。 |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | 指定された描画サーフェス上で、指定された `Region` がこの `Region` と同一かどうかをテストします。 |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | この `Region` を更新して、指定された [`GraphicsPath`](../graphicspath/) と交差しない内部の部分のみを含むようにします。 |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | この `Region` を更新して、指定された [`Rectangle`](../rectangle/) 構造体と交差しない内部の部分のみを含むようにします。 |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | この `Region` を更新して、指定された [`RectangleF`](../rectanglef/) 構造体と交差しない内部の部分のみを含むようにします。 |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | この `Region` を更新して、指定された `Region` と交差しない内部の部分のみを含むようにします。 |
| override [GetHashCode](../../aspose.psd/region/gethashcode/)() | 現在のオブジェクトのハッシュコードを取得します。 |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | この `Region` を更新して、指定された [`GraphicsPath`](../graphicspath/) との交差部分に設定します。 |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | この `Region` を更新して、指定された [`Rectangle`](../rectangle/) 構造体との交差部分に設定します。 |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | この `Region` を更新して、指定された [`RectangleF`](../rectanglef/) 構造体との交差部分に設定します。 |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | この `Region` を更新して、指定された `Region` との交差部分に設定します。 |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | 指定された描画サーフェス上で、この `Region` の内部が空かどうかをテストします。 |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | 指定された描画サーフェス上で、この `Region` の内部が無限かどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | 指定された [`Point`](../point/) 構造体がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | 指定された [`PointF`](../pointf/) 構造体がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | 指定された [`Rectangle`](../rectangle/) 構造体の任意の部分がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | 指定された [`RectangleF`](../rectanglef/) 構造体の任意の部分がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | 指定されたポイントがこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画した場合に、指定された [`Point`](../point/) 構造体がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画した場合に、指定された [`PointF`](../pointf/) 構造体がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画した場合に、指定された [`Rectangle`](../rectangle/) 構造体の任意の部分がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画した場合に、指定された [`RectangleF`](../rectanglef/) 構造体の任意の部分がこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画した場合に、指定されたポイントがこの `Region` に含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | 指定された [`Graphics`](../graphics/) オブジェクトを使用して描画した場合に、指定されたポイントがこの `Region` オブジェクトに含まれるかどうかをテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | 指定された矩形の任意の部分がこの `Region` に含まれているかテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | 指定された矩形の任意の部分がこの `Region` に含まれているかテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画された場合に、指定された矩形の任意の部分がこの `Region` に含まれているかテストします。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | 指定された [`Graphics`](../graphics/) を使用して描画された場合に、指定された矩形の任意の部分がこの `Region` に含まれているかテストします。 |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | この `Region` を空の内部に初期化します。 |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | この `Region` オブジェクトを無限の内部に初期化します。 |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | 指定された [`Matrix`](../matrix/) によってこの `Region` を変換します。 |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | 指定された量だけこの `Region` の座標をオフセットします。 |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | 指定された量だけこの `Region` の座標をオフセットします。 |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | この `Region` を自身と指定された [`GraphicsPath`](../graphicspath/) の合成に更新します。 |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | この `Region` を自身と指定された [`Rectangle`](../rectangle/) 構造体の合成に更新します。 |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | この `Region` を自身と指定された [`RectangleF`](../rectanglef/) 構造体の合成に更新します。 |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | この `Region` を自身と指定された `Region` の合成に更新します。 |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | この `Region` を自身と指定された [`GraphicsPath`](../graphicspath/) の交差部分を除いた合成に更新します。 |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | この `Region` を自身と指定された [`Rectangle`](../rectangle/) 構造体の交差部分を除いた合成に更新します。 |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | この `Region` を自身と指定された [`RectangleF`](../rectanglef/) 構造体の交差部分を除いた合成に更新します。 |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | この `Region` を自身と指定された `Region` の交差部分を除いた合成に更新します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



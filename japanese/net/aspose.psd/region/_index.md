---
title: Class Region
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Region クラス. 四角形とパスで構成されるグラフィック形状の内部を記述しますこのクラスは継承できません.
type: docs
weight: 5360
url: /ja/net/aspose.psd/region/
---
## Region class

四角形とパスで構成されるグラフィック形状の内部を記述します。このクラスは継承できません.

```csharp
public sealed class Region
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Region](region/#constructor)() | 新しい`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | 新しい`Region`指定された[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | 新しい`Region`指定から[`Rectangle`](../rectangle/)構造体. |
| [Region](region/#constructor_3)(RectangleF) | 新しい`Region`指定から[`RectangleF`](../rectanglef/)構造体. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | これを更新します`Region`指定された部分を含む[`GraphicsPath`](../graphicspath/)これと交差しない`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | これを更新します`Region`指定された部分を含む[`Rectangle`](../rectangle/)これと交差しない構造`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | これを更新します`Region`指定された部分を含む[`RectangleF`](../rectanglef/)これと交差しない構造`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | これを更新します`Region`指定された部分を含む`Region`これと交差しない`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | これの正確なディープ コピーを作成します`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | 指定された`Region`これと同じです`Region`指定された描画面で. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | これを更新します`Region`指定されたものと交差しない内部の部分のみを含む[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | これを更新します`Region`指定されたものと交差しない内部の部分のみを含む[`Rectangle`](../rectangle/)構造体. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | これを更新します`Region`指定されたものと交差しない内部の部分のみを含む[`RectangleF`](../rectanglef/)構造体. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | これを更新します`Region`指定されたものと交差しない内部の部分のみを含む`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | これを更新します`Region`指定された[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | これを更新します`Region`指定された[`Rectangle`](../rectangle/)構造体. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | これを更新します`Region`指定された[`RectangleF`](../rectanglef/)構造体. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | これを更新します`Region`指定された`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | これが`Region`指定された描画面に空の内部があります. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | これが`Region`指定された描画面に無限の内部があります. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | 指定された[`Point`](../point/)構造はこの中に含まれています`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | 指定された[`PointF`](../pointf/)構造はこの中に含まれています`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | 指定された[`Rectangle`](../rectangle/)構造はこの中に含まれています`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | 指定された[`RectangleF`](../rectanglef/)構造はこの中に含まれています`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | 指定したポイントがこの範囲内に含まれているかどうかをテストします`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | 指定された[`Point`](../point/)構造はこの中に含まれています`Region`指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | 指定された[`PointF`](../pointf/)構造はこの中に含まれています`Region`指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | 指定された[`Rectangle`](../rectangle/)構造はこの中に含まれています`Region`指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | 指定された[`RectangleF`](../rectanglef/)構造はこの中に含まれています`Region`指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | 指定したポイントがこの範囲内に含まれているかどうかをテストします`Region`指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | 指定したポイントがこの範囲内に含まれているかどうかをテストします`Region`指定されたオブジェクトを使用して描画された場合[`Graphics`](../graphics/)object. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | 指定された長方形の一部がこの中に含まれているかどうかをテストします`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | 指定された長方形の一部がこの中に含まれているかどうかをテストします`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | 指定された長方形の一部がこの中に含まれているかどうかをテストします`Region`指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | 指定された長方形の一部がこの中に含まれているかどうかをテストします`Region`指定された[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | これを初期化します`Region`空の内部へ. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | これを初期化します`Region`無限の内部へのオブジェクト. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | これを変換します`Region`指定された[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | この座標をオフセットします`Region`指定された量によって. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | この座標をオフセットします`Region`指定された量によって. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | これを更新します`Region`それ自体と指定されたものの結合に[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | これを更新します`Region`それ自体と指定されたものの結合に[`Rectangle`](../rectangle/)構造体. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | これを更新します`Region`それ自体と指定されたものの結合に[`RectangleF`](../rectanglef/)構造体. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | これを更新します`Region`それ自体と指定されたものの結合に`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | これを更新します`Region`和集合から指定されたものとの交点を引いたもの[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | これを更新します`Region`和集合から指定されたものとの交点を引いたもの[`Rectangle`](../rectangle/)構造体. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | これを更新します`Region`和集合から指定されたものとの交点を引いたもの[`RectangleF`](../rectanglef/)構造体. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | これを更新します`Region`和集合から指定されたものとの交点を引いたもの`Region` . |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



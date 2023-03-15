---
title: Class CurveShape
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Shapes.CurveShape クラス. 曲線のスプライン形状を表します
type: docs
weight: 5480
url: /ja/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

曲線のスプライン形状を表します。

```csharp
public sealed class CurveShape : PolygonShape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | の新しいインスタンスを初期化します`CurveShape`class. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | の新しいインスタンスを初期化します`CurveShape`クラス。デフォルトの張力 0.5 が使用されます。 |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | の新しいインスタンスを初期化します`CurveShape`クラス。デフォルトの張力 0.5 が使用されます。 |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | の新しいインスタンスを初期化します`CurveShape`class. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | の新しいインスタンスを初期化します`CurveShape`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | 形状の中心を取得します。 |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 形状の終了点を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 形状が閉じているかどうかを示す値を取得または設定します。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 曲線ポイントを取得または設定します。 |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | 形状セグメントを取得します。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 形状の開始点を取得します。 |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | 曲線の張力を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | このシェイプのポイントの順序を逆にします。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 指定された変換を形状に適用します。 |

### 関連項目

* class [PolygonShape](../polygonshape/)
* 名前空間 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 組み立て [Aspose.PSD](../../)



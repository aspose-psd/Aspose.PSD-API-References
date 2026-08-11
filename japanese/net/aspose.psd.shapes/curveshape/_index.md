---
title: "クラス CurveShape"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Shapes.CurveShape クラス。曲線スプラインシェイプを表します"
type: docs
weight: 5980
url: /ja/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

曲線スプライン形状を表します。

```csharp
public sealed class CurveShape : PolygonShape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | `CurveShape` クラスの新しいインスタンスを初期化します。 |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | `CurveShape` クラスの新しいインスタンスを初期化します。デフォルトのテンション 0.5 が使用されます。 |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | `CurveShape` クラスの新しいインスタンスを初期化します。デフォルトのテンション 0.5 が使用されます。 |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | `CurveShape` クラスの新しいインスタンスを初期化します。 |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | `CurveShape` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | 形状の中心を取得します。 |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | シェイプの終了点を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | シェイプが閉じているかどうかを示す値を取得または設定します。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 曲線のポイントを取得または設定します。 |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | シェイプのセグメントを取得します。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | シェイプの開始点を取得します。 |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | 曲線のテンションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | このシェイプのポイントの順序を逆にします。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 指定された変換をシェイプに適用します。 |

### 関連項目

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



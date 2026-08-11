---
title: "RectangleProjectedShape クラス。"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Shapes.RectangleProjectedShape クラス。特定の向きに回転させた矩形上に投影される形状を表します。4 つの点で指定され、空間内で回転させても辺の長さは同じで、隣接する辺の間は 90 度を保ちます。"
type: docs
weight: 6020
url: /ja/net/aspose.psd.shapes/rectangleprojectedshape/
---
{{< psd/tize >}}
## RectangleProjectedShape class

特定の向きに回転させた矩形上に投影された形状を表します。4 つの点で指定され、空間内で回転させてもエッジの長さは同じで、隣接エッジ間は 90 度を保ちます。

```csharp
public abstract class RectangleProjectedShape : Shape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [RectangleProjectedShape](rectangleprojectedshape/#constructor)() | `RectangleProjectedShape` クラスの新しいインスタンスを初期化します。 |
| [RectangleProjectedShape](rectangleprojectedshape/#constructor_1)(RectangleF) | `RectangleProjectedShape` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 形状の中心を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 左下の矩形点を取得します。 |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 左上の矩形点を取得します。 |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 矩形の高さを取得します。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 矩形の幅を取得します。 |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 矩形の右下の点を取得します。 |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 矩形の右上の点を取得します。 |
| abstract [Segments](../../aspose.psd/shape/segments/) { get; } | シェイプのセグメントを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 指定された変換をシェイプに適用します。 |

### 関連項目

* class [Shape](../../aspose.psd/shape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



---
title: Class ArcShape
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Shapes.ArcShape クラス. 円弧形状を表します
type: docs
weight: 5460
url: /ja/net/aspose.psd.shapes/arcshape/
---
## ArcShape class

円弧形状を表します。

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | の新しいインスタンスを初期化します`ArcShape`class. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | の新しいインスタンスを初期化します`ArcShape`class. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | の新しいインスタンスを初期化します`ArcShape`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 形状の中心を取得します。 |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | 形状の終了点を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | 順序付けられた形状が閉じているかどうかを示す値を取得または設定します。閉じた順序付けられた形状を処理する場合、開始点と終了点は意味を持ちません. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 左下の長方形の点を取得します. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 左上の長方形の点を取得します. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 長方形の高さを取得します。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 長方形の幅を取得します. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 右下の長方形の点を取得します. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 右上の長方形ポイントを取得します。 |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | 形状セグメントを取得します。 |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | 開始角度を取得または設定します。 |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | 形状の開始点を取得します。 |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | スイープ角度を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | このシェイプのポイントの順序を逆にします。 |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 指定された変換を形状に適用します。 |

### 例

この例では、新しいイメージを作成し、イメージ サーフェスで Figure と GraphicsPath を使用してさまざまな形状を描画します。

```csharp
[C#]

//Image のインスタンスを作成する
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics クラスのインスタンスを作成して初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // グラフィック サーフェスをクリアする
    graphics.Clear(Color.Wheat);

    // GraphicsPath クラスのインスタンスを作成します
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // Figure クラスのインスタンスを作成
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // Figure オブジェクトに Shape を追加
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // Figure クラスのインスタンスを作成
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // Figure オブジェクトに Shape を追加
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //GraphicsPath に Figure オブジェクトを追加
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //色が黒の Pen オブジェクトでパスを描画します
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // エクスポート オプションを作成して初期化します。
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // すべての変更を保存します。
    image.Save("c:\\temp\\output.bmp", options);
}
```

### 関連項目

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* 名前空間 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 組み立て [Aspose.PSD](../../)



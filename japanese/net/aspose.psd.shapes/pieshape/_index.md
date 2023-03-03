---
title: Class PieShape
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Shapes.PieShape クラス. パイの形を表します
type: docs
weight: 5500
url: /ja/net/aspose.psd.shapes/pieshape/
---
## PieShape class

パイの形を表します。

```csharp
public class PieShape : EllipseShape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PieShape](pieshape/#constructor)() | の新しいインスタンスを初期化します`PieShape`class. |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | の新しいインスタンスを初期化します`PieShape`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 形状の中心を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 左下の長方形の点を取得します. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 左上の長方形の点を取得します. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 長方形の高さを取得します。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 長方形の幅を取得します. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 右下の長方形の点を取得します. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 右上の長方形ポイントを取得します。 |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | 形状セグメントを取得します。 |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | 開始角度を取得または設定します。 |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | スイープ角度を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | オブジェクトの境界を取得します。 |
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

* class [EllipseShape](../ellipseshape/)
* 名前空間 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 組み立て [Aspose.PSD](../../)



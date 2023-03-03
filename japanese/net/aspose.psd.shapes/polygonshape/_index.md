---
title: Class PolygonShape
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Shapes.PolygonShape クラス. 多角形を表します
type: docs
weight: 5510
url: /ja/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

多角形を表します。

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | の新しいインスタンスを初期化します`PolygonShape`class. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | の新しいインスタンスを初期化します`PolygonShape`class. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | の新しいインスタンスを初期化します`PolygonShape`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | オブジェクトの境界を取得します。 |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | 形状の中心を取得します。 |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 形状の終了点を取得します。 |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 形状が閉じているかどうかを示す値を取得または設定します。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 曲線ポイントを取得または設定します。 |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | 形状セグメントを取得します。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 形状の開始点を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | このシェイプのポイントの順序を逆にします。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 指定された変換を形状に適用します。 |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* 名前空間 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 組み立て [Aspose.PSD](../../)



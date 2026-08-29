---
title: "クラス Figure"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Figure クラス。図形。シェイプのコンテナです。"
type: docs
weight: 1210
url: /ja/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

図。形状のコンテナです。

```csharp
public class Figure : ObjectWithBounds
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Figure](figure/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | オブジェクトの境界を取得または設定します。 |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | この図形が閉じているかどうかを示す値を取得または設定します。閉じた図形は、最初のシェイプと最後のシェイプが連続したシェイプである場合にのみ影響があります。その場合、最初のシェイプの最初の点は、最後のシェイプの最後の点から直線で接続されます。 |
| [Segments](../../aspose.psd/figure/segments/) { get; } | 図形全体のセグメントを取得します。 |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | 図形のシェイプを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | 図形にシェイプを追加します。 |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | 図形にシェイプの範囲を追加します。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | 図形からシェイプを削除します。 |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | 図形からシェイプの範囲を削除します。 |
| [Reverse](../../aspose.psd/figure/reverse/)() | この図形のシェイプ順序とシェイプのポイント順序を逆にします。 |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | 指定された変換をシェイプに適用します。 |

## 例

この例では GraphicsPath クラスと Graphics クラスを使用して、Image 表面上に Figure を作成および操作します。例では新しい Image を作成し、GraphicsPath クラスを使用してパスを描画します。最後に Graphics クラスが提供する DrawPath メソッドが呼び出され、表面上にパスが描画されます。最終的に画像は Tiff ファイル形式にエクスポートされます。

```csharp
[C#]

//Image のインスタンスを作成します。
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します。
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします。
    graphics.Clear(Color.Wheat);

    //GraphicsPath クラスのインスタンスを作成します。
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure クラスのインスタンスを作成します。
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure オブジェクトにシェイプを追加します。
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath に Figure オブジェクトを追加します。
    graphicspath.AddFigure(figure);

    //黒色の Pen オブジェクトでパスを描画します。
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions のインスタンスを作成し、さまざまなプロパティを設定します。
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 関連項目

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



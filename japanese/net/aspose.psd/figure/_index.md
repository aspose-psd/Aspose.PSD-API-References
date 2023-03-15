---
title: Class Figure
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Figure クラス. フィギュア形状のコンテナ.
type: docs
weight: 1200
url: /ja/net/aspose.psd/figure/
---
## Figure class

フィギュア。形状のコンテナ.

```csharp
public class Figure : ObjectWithBounds
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Figure](figure/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | オブジェクトの境界を取得または設定します。 |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | この図が閉じているかどうかを示す値を取得または設定します。閉じた図形は、 最初と最後の図形の形状が連続した形状である場合にのみ違いを生みます。このような場合、最初のシェイプの最初のポイントは、最後のシェイプの最後のポイントから直線で接続された になります. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | 図形セグメント全体を取得します。 |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | 図形の形状を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Figure に形状を追加します。 |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Figure に形状の範囲を追加します。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Figure から形状を削除します。 |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Figure から一定範囲の形状を削除します。 |
| [Reverse](../../aspose.psd/figure/reverse/)() | この図形の形状の順序と形状の点の順序を逆にします。 |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | 指定された変換を形状に適用します。 |

### 例

この例では、GraphicsPath および Graphics クラスを使用して、イメージ サーフェス上に Figure を作成および操作します。例では、新しい Image を作成し、GraphicsPath クラスを使用してパスを描画します。最後に、Graphics クラスによって公開された DrawPath メソッドが呼び出され、表面にパスがレンダリングされます。最後に、画像が Tiff ファイル形式にエクスポートされます。

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Figure オブジェクトにシェイプを追加
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath に Figure オブジェクトを追加
    graphicspath.AddFigure(figure);

    //色が黒の Pen オブジェクトでパスを描画します
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // TiffOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 関連項目

* class [ObjectWithBounds](../objectwithbounds/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



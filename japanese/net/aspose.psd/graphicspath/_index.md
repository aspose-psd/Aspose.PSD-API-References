---
title: "クラス GraphicsPath"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.GraphicsPath クラス。接続された直線と曲線の系列を表します。このクラスは継承できません。"
type: docs
weight: 4790
url: /ja/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

接続された直線と曲線の系列を表します。このクラスは継承できません。

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | `GraphicsPath` クラスの新しいインスタンスを初期化します。 |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | `GraphicsPath` クラスの新しいインスタンスを初期化します。 |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | `GraphicsPath` クラスの新しいインスタンスを初期化します。 |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | `GraphicsPath` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | オブジェクトの境界を取得または設定します。 |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | パス図形を取得します。 |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | `GraphicsPath` 内のシェイプの内部がどのように塗りつぶされるかを決定する [`FillMode`](../fillmode/) 列挙型を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | 新しい図形を追加します。 |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | 新しい図形を追加します。 |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | 指定された `GraphicsPath` をこのパスに追加します。 |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 指定された `GraphicsPath` をこのパスに追加します。 |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | このグラフィック パスのディープ クローンを実行します。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | このパス内の各曲線を連続した線分のシーケンスに変換します。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | 指定された変換を適用し、次にこの `GraphicsPath` の各曲線を連続した線分のシーケンスに変換します。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | この `GraphicsPath` の各曲線を連続した線分のシーケンスに変換します。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 指定されたポイントが、指定された [`Pen`](../pen/) で描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 指定されたポイントが、指定された [`Pen`](../pen/) で描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 指定されたポイントが、指定された [`Pen`](../pen/) で描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 指定されたポイントが、指定された [`Pen`](../pen/) で描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 指定されたポイントが、指定された [`Pen`](../pen/) と指定された [`Graphics`](../graphics/) を使用して描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 指定されたポイントが、指定された [`Pen`](../pen/) と指定された [`Graphics`](../graphics/) を使用して描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 指定されたポイントが、指定された [`Pen`](../pen/) と指定された [`Graphics`](../graphics/) を使用して描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 指定されたポイントが、指定された [`Pen`](../pen/) と指定された [`Graphics`](../graphics/) を使用して描画されたときにこの `GraphicsPath` の輪郭（内部）に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | 指定されたポイントがこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | 指定されたポイントがこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | 指定されたポイントがこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | 指定されたポイントがこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 指定されたポイントがこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 指定されたポイントがこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 指定されたポイントが、指定された [`Graphics`](../graphics/) の可視クリップ領域内でこの `GraphicsPath` の内部に含まれるかどうかを示します。 |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 指定された [`Graphics`](../graphics/) を使用して、この `GraphicsPath` の内部に指定されたポイントが含まれるかどうかを示します。 |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | 図形を削除します。 |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | 図形を削除します。 |
| [Reset](../../aspose.psd/graphicspath/reset/)() | グラフィック パスを空にし、[`FillMode`](../fillmode/) を Alternate に設定します。 |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | この `GraphicsPath` の各シェイプ内の図形、シェイプ、ポイントの順序を逆にします。 |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | 指定された変換をシェイプに適用します。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | 矩形と平行四辺形で定義されたワープ変換をこの `GraphicsPath` に適用します。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 矩形と平行四辺形で定義されたワープ変換をこの `GraphicsPath` に適用します。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 矩形と平行四辺形で定義されたワープ変換をこの `GraphicsPath` に適用します。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 矩形と平行四辺形で定義されたワープ変換をこの `GraphicsPath` に適用します。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | パスに追加の輪郭を加えます。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | `GraphicsPath` に追加の輪郭を加えます。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | この `GraphicsPath` を、指定されたペンでこのパスが描画されたときに塗りつぶされる領域を囲む曲線に置き換えます。 |

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



---
title: Class GraphicsPath
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.GraphicsPath クラス. 一連の接続された直線と曲線を表しますこのクラスは継承できません.
type: docs
weight: 4320
url: /ja/net/aspose.psd/graphicspath/
---
## GraphicsPath class

一連の接続された直線と曲線を表します。このクラスは継承できません.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | の新しいインスタンスを初期化します`GraphicsPath`class. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | の新しいインスタンスを初期化します`GraphicsPath`class. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | の新しいインスタンスを初期化します`GraphicsPath`class. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | の新しいインスタンスを初期化します`GraphicsPath`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | オブジェクトの境界を取得または設定します。 |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | パス図形を取得します。 |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | を取得または設定します[`FillMode`](../fillmode/)この内の形状の内部をどのように決定するかを決定する列挙`GraphicsPath`満たされています. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | 新しい図形を追加します。 |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | 新しい図を追加します。 |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | 指定された`GraphicsPath`このパスに. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 指定された`GraphicsPath`このパスに. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | このグラフィックス パスのディープ クローンを実行します。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | このパスの各曲線を一連の接続された線分に変換します。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | 指定された変換を適用してから、この中の各曲線を変換します`GraphicsPath`一連の接続された線分に変換します。 |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | この中の各曲線を変換します`GraphicsPath`一連の接続された線分に変換します。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | オブジェクトの境界を取得します。 |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | オブジェクトの境界を取得します。 |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/)指定された[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/)指定された[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/)指定された[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 指定されたポイントがこのアウトライン内 (下) に含まれているかどうかを示します`GraphicsPath`指定で描画した場合[`Pen`](../pen/)指定された[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath`指定されたの可視クリップ領域で[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 指定したポイントがこの範囲内に含まれているかどうかを示します`GraphicsPath` 、指定された[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | 図形を削除します。 |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | 図形を削除します。 |
| [Reset](../../aspose.psd/graphicspath/reset/)() | グラフィックス パスを空にし、[`FillMode`](../fillmode/)にAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | この各形状の図形、形状、点の順序を逆にします`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | 指定された変換を形状に適用します。 |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | 長方形と平行四辺形で定義されたワープ変換をこれに適用します`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 長方形と平行四辺形で定義されたワープ変換をこれに適用します`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 長方形と平行四辺形で定義されたワープ変換をこれに適用します`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 長方形と平行四辺形で定義されたワープ変換をこれに適用します`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | パスにアウトラインを追加します。 |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | に追加のアウトラインを追加します`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | これを置き換えます`GraphicsPath`このパスが指定されたペンで描かれたときに塗りつぶされる領域を囲む曲線で. |

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



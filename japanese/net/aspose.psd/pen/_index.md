---
title: Class Pen
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Pen クラス. 直線曲線図形の描画に使用するオブジェクトを定義します.
type: docs
weight: 5200
url: /ja/net/aspose.psd/pen/
---
## Pen class

直線、曲線、図形の描画に使用するオブジェクトを定義します.

```csharp
public class Pen : TransparencySupporter
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | の新しいインスタンスを初期化します`Pen`指定されたクラス[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | の新しいインスタンスを初期化します`Pen`指定された色のクラス. |
| [Pen](pen/#constructor_1)(Brush, float) | の新しいインスタンスを初期化します`Pen`指定されたクラス[`Brush`](./brush/)と[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | の新しいインスタンスを初期化します`Pen`指定されたクラス[`Color`](./color/)と[`Width`](./width/)プロパティ. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | この配置を取得または設定します`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | を取得または設定します[`Brush`](./brush/)これの属性を決定する`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | この色を取得または設定します`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | 複合ペンを指定する値の配列を取得または設定します。複合ペンは、平行線とスペースで構成される複合線を描画します。 |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | これで描画された線の最後に使用するカスタム キャップを取得または設定します`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | これで描画された線の始点で使用するカスタム キャップを取得または設定します`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | これで描画される破線を構成する破線の端で使用されるキャップ スタイルを取得または設定します`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | 線の始点から破線パターンの始点までの距離を取得または設定します。 |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | カスタム ダッシュとスペースの配列を取得または設定します。 |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | これで描かれた破線に使用されるスタイルを取得または設定します`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | これで描画された線の終点で使用されるキャップ スタイルを取得または設定します`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | これで描画された 2 つの連続する線の端の結合スタイルを取得または設定します`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | 留め継ぎコーナーの接合部の厚さの制限を取得または設定します. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | オブジェクトの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はオブジェクトが完全に表示されることを意味し、値 1 はオブジェクトが完全に不透明であることを意味します。 |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | これで描かれた線のスタイルを取得します`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | これで描画される線の始点で使用されるキャップ スタイルを取得または設定します`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | この幾何学的変換のコピーを取得または設定します`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | この幅を取得または設定します`Pen`、描画に使用される Graphics オブジェクトの単位。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | この変換行列を乗算します`Pen`指定された[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | この変換行列を乗算します`Pen`指定された[`Matrix`](../matrix/)指定された順序で. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | この幾何変換行列をリセットします`Pen`identity. へ |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | 指定した角度でローカル ジオメトリック トランスフォームを回転します。このメソッドは、変換の前に回転を追加します. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 指定された順序で、指定された角度だけローカル ジオメトリック変換を回転させます。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | 指定された係数でローカル ジオメトリック トランスフォームをスケーリングします。このメソッドは、スケーリング マトリックスを変換の先頭に追加します。 |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 指定された順序で、指定された係数によってローカル ジオメトリック変換をスケーリングします。 |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | これによって描画された線を終了するために使用されるキャップのスタイルを決定する値を設定します`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | 指定された次元でローカル ジオメトリック変換を変換します。このメソッドは、変換を変換の先頭に追加します。 |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 指定された順序で、指定された次元でローカル ジオメトリック変換を変換します。 |

### 例

この例は、Pen オブジェクトの作成と使用を示しています。この例では、新しい Image を作成し、Image 表面に Rectangles を描画します。

```csharp
[C#]

//Image のインスタンスを作成する
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics のインスタンスを作成し、Image オブジェクトで初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics sutface を白色でクリアする
    graphics.Clear(Aspose.PSD.Color.White);

    // 色が赤で幅が 5 の Pen のインスタンスを作成する
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush のインスタンスを作成し、そのプロパティを設定します
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    // Pen のインスタンスを作成する
    //HatchBrush オブジェクトと幅で初期化します
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //ペンオブジェクトを指定して長方形を描画
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //ペンオブジェクトを指定して長方形を描画
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // エクスポート オプションを作成して初期化します。
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // すべての変更を保存します。
    image.Save("c:\\temp\\output.jp2", options);
}
```

### 関連項目

* class [TransparencySupporter](../transparencysupporter/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



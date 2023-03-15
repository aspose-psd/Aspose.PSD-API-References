---
title: Class SolidBrush
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Brushes.SolidBrush クラス. ソリッド ブラシは特定の色で連続して描画することを目的としていますこのクラスは継承できません.
type: docs
weight: 200
url: /ja/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

ソリッド ブラシは、特定の色で連続して描画することを目的としています。このクラスは継承できません.

```csharp
public sealed class SolidBrush : Brush
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | の新しいインスタンスを初期化します`SolidBrush`class. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | の新しいインスタンスを初期化します`SolidBrush`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | ブラシの色を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はブラシが完全に表示されることを意味し、値 1 はブラシが完全に不透明であることを意味します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の新しいディープ クローンを作成します。[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

### 例

この例では、Graphics クラスを使用して、イメージ サーフェス上にプリミティブ シェイプを作成します。操作を示すために、この例では PSD 形式で新しい画像を作成し、Graphics クラスによって公開された Draw メソッドを使用して画像表面にプリミティブ形状を描画し、それを PSD ファイル形式にエクスポートします。

```csharp
[C#]

//Image のインスタンスを作成する 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics クラスのインスタンスを作成して初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // グラフィック サーフェスをクリアする
    graphics.Clear(Color.Wheat);

    //黒色のペンオブジェクトを指定して円弧を描き、 
    //円弧、開始角度、およびスイープ角度を囲む長方形
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //青色で座標ポイントを持つ Pen オブジェクトを指定して、ベジエを描画します。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //緑色のペン オブジェクトとポイントの配列を指定して、曲線を描画します
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen オブジェクトと周囲の Rectangle を使用して Ellipse を描画します
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //線を引く 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //円のセグメントを描画します
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //赤色の Pen オブジェクトと Point の配列を指定して Polygon を描画します
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //長方形を描く
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush オブジェクトを作成し、さまざまなプロパティを設定します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush オブジェクトと Font を使用して、特定の Point に文字列を描画します
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    // PngOptions のインスタンスを作成し、さまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 関連項目

* class [Brush](../../aspose.psd/brush/)
* 名前空間 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 組み立て [Aspose.PSD](../../)



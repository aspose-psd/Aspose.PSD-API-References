---
title: Class HatchBrush
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Brushes.HatchBrush クラス. ハッチング スタイル前景色および背景色を持つ長方形のブラシを定義しますこのクラスは継承できません.
type: docs
weight: 130
url: /ja/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

ハッチング スタイル、前景色、および背景色を持つ長方形のブラシを定義します。このクラスは継承できません.

```csharp
public sealed class HatchBrush : Brush
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [HatchBrush](hatchbrush/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | ハッチ線の間のスペースの色を取得または設定します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | ハッチ線の色を取得または設定します。 |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | このブラシのハッチ スタイルを取得または設定します。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。値 0 はブラシが完全に表示されることを意味し、値 1 はブラシが完全に不透明であることを意味します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 現在の新しいディープ クローンを作成します。[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

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

* class [Brush](../../aspose.psd/brush/)
* 名前空間 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 組み立て [Aspose.PSD](../../)



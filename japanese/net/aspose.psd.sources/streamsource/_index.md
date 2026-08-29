---
title: "クラス StreamSource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Sources.StreamSource クラス。ストリーム ソースを表します"
type: docs
weight: 6120
url: /ja/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

ストリーム ソースを表します。

```csharp
public sealed class StreamSource : Source
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | 新しい `StreamSource` クラスのインスタンスを初期化します。 |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | 新しい `StreamSource` クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | コンテナが破棄されるたびにストリームを破棄すべきかどうかを示す値を取得します。 |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | ストリームを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | ストリーム コンテナを取得します。 |

## 例

この例では Graphics クラスを使用して画像表面上に基本形状を作成します。操作を示すために、例では PSD 形式の新しい Image を作成し、Graphics クラスが提供する Draw メソッドを使用して画像表面上に基本形状を描画し、最後に PSD ファイル形式へエクスポートします。

```csharp
[C#]

//Image のインスタンスを作成します。
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します。
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします。
    graphics.Clear(Color.Wheat);

    //Pen オブジェクトで黒色を指定して円弧を描画します、
    //円弧を囲む矩形、開始角度およびスイープ角度
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Pen オブジェクトで青色と座標ポイントを指定してベジェ曲線を描画します。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Pen オブジェクトで緑色とポイントの配列を指定して曲線を描画します
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen オブジェクトとそれを囲む矩形を使用して楕円を描画します
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //直線を描画します
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //パイセグメントを描画します
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Pen オブジェクトで赤色とポイントの配列を指定して多角形を描画します
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //矩形を描画します
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush オブジェクトを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush オブジェクトと Font を使用して、特定の Point で文字列を描画します
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 関連項目

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)



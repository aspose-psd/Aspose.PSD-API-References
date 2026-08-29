---
title: "クラス FileCreateSource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Sources.FileCreateSource クラス。作成用のファイル ソースを表します"
type: docs
weight: 6090
url: /ja/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

作成用のファイル ソースを表します。

```csharp
public sealed class FileCreateSource : FileSource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | `FileCreateSource` クラスの新しいインスタンスを初期化します。 |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | `FileCreateSource` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | 作成するファイルのパスを取得します。 |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | ファイルが一時的かどうかを示す値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | ストリーム コンテナを取得します。 |

## 例

この例では、Font クラスと SolidBrush クラスを使用して Image 表面に文字列を描画する方法を示します。例では新しい Image を作成し、Figures と GraphicsPath を使用して図形を描画します。

```csharp
[C#]

//Image のインスタンスを作成します
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします
    graphics.Clear(Color.Wheat);

    //Font のインスタンスを作成します
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //赤色の SolidBrush のインスタンスを作成します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //文字列を描画します
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // エクスポート オプションを作成します。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.gif", options);
}
```

### 関連項目

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)



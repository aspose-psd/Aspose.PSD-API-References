---
title: Class FileCreateSource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Sources.FileCreateSource クラス. 作成するファイルソースを表します.
type: docs
weight: 5590
url: /ja/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

作成するファイルソースを表します.

```csharp
public sealed class FileCreateSource : FileSource
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | の新しいインスタンスを初期化します`FileCreateSource`class. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | の新しいインスタンスを初期化します`FileCreateSource`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | 作成するファイル パスを取得します。 |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | ファイルがテンポラルかどうかを示す値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | ストリーム コンテナーを取得します。 |

### 例

この例では、Font および SolidBrush クラスを使用して、イメージ サーフェスに文字列を描画する方法を示します。この例では、新しい画像を作成し、Figure と GraphicsPath を使用して図形を描画します

```csharp
[C#]

//Image のインスタンスを作成します
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics クラスのインスタンスを作成して初期化します
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // グラフィック サーフェスをクリアします
    graphics.Clear(Color.Wheat);

    //Font のインスタンスを作成します
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //赤色の SolidBrush のインスタンスを作成します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //文字列を描画
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // エクスポート オプションを作成します。
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // すべての変更を保存
    image.Save("C:\\temp\\output.gif", options);
}
```

### 関連項目

* class [FileSource](../filesource/)
* 名前空間 [Aspose.PSD.Sources](../../aspose.psd.sources/)
* 組み立て [Aspose.PSD](../../)



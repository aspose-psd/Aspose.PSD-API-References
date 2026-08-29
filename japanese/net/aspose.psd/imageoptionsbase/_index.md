---
title: "クラス ImageOptionsBase"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageOptionsBase クラス。画像の基本オプション"
type: docs
weight: 5480
url: /ja/net/aspose.psd/imageoptionsbase/
---
{{< psd/tize >}}
## ImageOptionsBase class

画像の基本オプション。

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートするときにテキスト描画に使用されるフォント）。デフォルトフォント名を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | フルフレームかどうかを示す値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページオプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラーパレットを取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 取得または設定するのは、進行状況イベント ハンドラーです。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 画像を作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクターラスタライズオプションを取得または設定します。 |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP メタデータ コンテナを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスをクローンします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

### 関連項目

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



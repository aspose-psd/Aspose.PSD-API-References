---
title: Class ImageOptionsBase
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageOptionsBase クラス. 画像ベース オプション.
type: docs
weight: 4990
url: /ja/net/aspose.psd/imageoptionsbase/
---
## ImageOptionsBase class

画像ベース オプション.

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します (PSD ファイル内の既存のレイヤー フォントがシステムに表示されない場合、ラスターにエクスポートするときにテキストの描画に使用されるフォント)。 デフォルト フォントの適切な名前を取得するには、次のコード スニペットを使用できます。 : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] ファミリー = col.Families; 文字列 defaultFontName = ファミリー[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [フル フレーム] かどうかを示す値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページ オプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラー パレットを取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 進行状況イベント ハンドラーを取得または設定します。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | でイメージを作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクター ラスター化オプションを取得または設定します。 |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP メタデータ コンテナーを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスを複製します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

### 関連項目

* class [DisposableObject](../disposableobject/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



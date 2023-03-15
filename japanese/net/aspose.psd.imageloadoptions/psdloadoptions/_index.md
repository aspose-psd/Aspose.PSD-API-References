---
title: Class PsdLoadOptions
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions クラス. Psd 読み込みオプション
type: docs
weight: 4770
url: /ja/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Psd 読み込みオプション

```csharp
public class PsdLoadOptions : LoadOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | ワープ トランスフォームを使用して、または使用せずに、レンダリングされたイメージと共に保存するかどうかを取得または設定します。 |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | を取得または設定します[`Image`](../../aspose.psd/image/)バックグラウンド[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | データ復旧モードを取得または設定します。 |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | [アルファ チャネルを無視する]かどうかを示す値を取得または設定します。 |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | UpdateText 操作の実行時に PSD テキスト レイヤーの固定幅を無視するかどうかを示す値を取得または設定します。 |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | [負荷がリソースに影響する] (デフォルトではリソースは読み込まれない) かどうかを示す値を取得または設定します。このオプションを設定すると、サポートされている効果のみが最終的なマージされた画像にレンダリングされます. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | 進行状況イベント ハンドラーを取得または設定します。 |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | [読み取り専用モードを使用する]かどうかを示す値を取得または設定します。これは読み取り専用モードで、Adobe Photoshop との同一の互換性のためにサポートされています。 このオプションが設定されている場合、レイヤーに適用されたすべての変更は最終イメージに保存されません。すべてのデータは ImageData セクションから使用されるため、Photoshop と同じです。 デフォルトでは、ロードされたすべての画像は、Adobe Photoshop と互換性があるものと同一ではありません。 |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | [エフェクト リソースのロードにディスクを使用する] (デフォルトではエフェクト リソースのロードにディスクを使用しますが、この値を false に設定することで十分な場合はメモリを使用できます) かどうかを示す値を取得または設定します。 |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | ICC プロファイル変換を適用するかどうかを示す値を取得または設定します。 |

### 例

次の例は、ドキュメント変換の進行状況が例外なく正しく機能することを示しています。

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### 関連項目

* class [LoadOptions](../../aspose.psd/loadoptions/)
* 名前空間 [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* 組み立て [Aspose.PSD](../../)



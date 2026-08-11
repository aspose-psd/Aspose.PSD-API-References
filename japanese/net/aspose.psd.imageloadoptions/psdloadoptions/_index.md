---
title: "クラス PsdLoadOptions"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions クラス。PSD のロード オプション"
type: docs
weight: 5250
url: /ja/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Psd ロードオプション

```csharp
public class PsdLoadOptions : LoadOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | 取得または設定するのは、レイヤーが変更されていない場合に、レンダリング中に元のレイヤー ピクセルを保持するかどうかです。 |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | 取得または設定するのは、ワープ変換の有無にかかわらず、レンダリングされた画像とともに保存するかどうかです。 |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | 取得または設定するのは、[`Image`](../../aspose.psd/image/) の背景 [`Color`](../../aspose.psd/color/) です。 |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | 取得または設定するのは、データ復旧モードです。 |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | 取得または設定するのは、[alpha チャネルを無視する]かどうかを示す値です。 |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | 取得または設定するのは、UpdateText 操作の実行時に PSD テキストレイヤーの固定幅を無視するかどうかを示す値です。 |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | 取得または設定するのは、[エフェクトリソースをロードする]かどうかを示す値です（デフォルトではリソースはロードされません）。このオプションを設定すると、サポートされているエフェクトのみが最終的に結合された画像にレンダリングされます。 |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | 取得または設定するのは、進行状況イベント ハンドラーです。 |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | 取得または設定するのは、[読み取り専用モードを使用する]かどうかを示す値です。これは Adobe Photoshop と同一の互換性を提供する読み取り専用モードです。このオプションを設定すると、レイヤーに対するすべての変更が最終画像に保存されません。すべてのデータは ImageData セクションから使用されるため、Photoshop と同一になります。デフォルトでは、ロードされたすべての画像は Adobe Photoshop と同一の互換性がありません。 |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | 取得または設定するのは、PSD 画像をロードする際に使用される読み取り専用モードです。 |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | 取得または設定するのは、[エフェクトリソースのロードにディスクを使用する]かどうかを示す値です（デフォルトではディスクが使用されますが、この値を false に設定すればメモリを使用できます）。 |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | 取得または設定するのは、ICC プロファイル変換を適用すべきかどうかを示す値です。 |

## 例

次の例は、ドキュメント変換の進行状況が正しく例外なしで動作することを示しています。

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
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)



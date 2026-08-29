---
title: "デリゲート ProgressEventHandler"
second_title: "Aspose.PSD for .NET API Reference"
description: "進捗イベントハンドラ関数の参照"
type: docs
weight: 5780
url: /ja/net/aspose.psd/progresseventhandler/
---
{{< psd/tize >}}
## ProgressEventHandler delegate

進捗イベントハンドラ関数の参照

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 情報 | ProgressEventHandlerInfo | プログレスイベントハンドラのデータです。 |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



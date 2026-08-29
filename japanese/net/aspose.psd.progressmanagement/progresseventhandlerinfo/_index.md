---
title: "クラス ProgressEventHandlerInfo"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo クラス。このクラスは、画像のロード/保存/エクスポート操作の進行状況に関する情報を表し、外部アプリケーションで変換進行状況をエンドユーザーに表示するために使用できます。"
type: docs
weight: 5800
url: /ja/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

このクラスは、画像の読み込み/保存/エクスポート操作の進行状況に関する情報を表し、外部アプリケーションで変換の進行状況をエンドユーザーに表示するために使用できます

```csharp
public class ProgressEventHandlerInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | イベントの説明を取得します |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | イベントのタイプを取得します。 |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | 上限の進行値を取得します。 |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | 現在の進行値を取得します。 |

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

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)



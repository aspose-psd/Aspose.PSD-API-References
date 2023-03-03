---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo クラス. このクラスは画像のロード/保存/エクスポート操作の進行状況に関する情報を表します. 外部アプリケーションで使用して変換の進行状況をエンド ユーザーに表示できます
type: docs
weight: 5300
url: /ja/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

このクラスは、画像のロード/保存/エクスポート操作の進行状況に関する情報を表します. 外部アプリケーションで使用して、変換の進行状況をエンド ユーザーに表示できます

```csharp
public class ProgressEventHandlerInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | イベントの説明を取得します |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | イベントのタイプを取得します。 |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | 進捗値の上限を取得します。 |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | 現在の進捗値を取得します。 |

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

* 名前空間 [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* 組み立て [Aspose.PSD](../../)



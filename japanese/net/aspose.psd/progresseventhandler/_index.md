---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD for .NET API リファレンス
description: Progress イベントハンドラ関数 reference
type: docs
weight: 5280
url: /ja/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Progress イベントハンドラ関数 reference

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | 進行状況イベント ハンドラー データ。 |

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

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)



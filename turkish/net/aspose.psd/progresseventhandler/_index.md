---
title: "Delege ProgressEventHandler"
second_title: "Aspose.PSD for .NET API Referansı"
description: "İlerleme olayı işleyici fonksiyon referansı"
type: docs
weight: 5810
url: /tr/net/aspose.psd/progresseventhandler/
---
{{< psd/tize >}}
## ProgressEventHandler delegate

İlerleme olayı işleyici fonksiyon referansı

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bilgi | ProgressEventHandlerInfo | İlerleme olayı işleyici verileri. |

## Örnekler

Aşağıdaki örnek, belge dönüştürme ilerlemesinin doğru ve istisna olmadan çalıştığını gösterir.

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

### Ayrıca Bakınız

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



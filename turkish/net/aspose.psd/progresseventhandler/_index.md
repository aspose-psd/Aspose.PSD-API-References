---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD for .NET API Referansı
description: İlerleme olay işleyici işlevi reference
type: docs
weight: 5280
url: /tr/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

İlerleme olay işleyici işlevi reference

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | İlerleme olayı işleyici verileri. |

### Örnekler

Aşağıdaki örnek, belge dönüştürme ilerlemesinin doğru ve istisnasız çalıştığını göstermektedir.

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

### Ayrıca bakınız

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)



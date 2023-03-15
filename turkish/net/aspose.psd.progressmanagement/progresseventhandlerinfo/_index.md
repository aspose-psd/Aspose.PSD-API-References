---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo sınıf. Bu sınıf son user ye dönüştürme ilerlemesini göstermek için harici uygulamada kullanılabilen görüntü yükleme/kaydetme/dışa aktarma işlemlerinin ilerleme durumu hakkında bilgileri temsil eder.
type: docs
weight: 5300
url: /tr/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Bu sınıf, son user 'ye dönüştürme ilerlemesini göstermek için harici uygulamada kullanılabilen görüntü yükleme/kaydetme/dışa aktarma işlemlerinin ilerleme durumu hakkında bilgileri temsil eder.

```csharp
public class ProgressEventHandlerInfo
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Olayın açıklamasını alır |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Olayın türünü alır. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Üst ilerleme değeri sınırını alır. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Mevcut ilerleme değerini alır. |

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

* ad alanı [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* toplantı [Aspose.PSD](../../)



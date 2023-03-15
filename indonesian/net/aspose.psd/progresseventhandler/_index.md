---
title: Delegate ProgressEventHandler
second_title: Aspose.PSD untuk Referensi .NET API
description: Referensi fungsi event handler progres
type: docs
weight: 5280
url: /id/net/aspose.psd/progresseventhandler/
---
## ProgressEventHandler delegate

Referensi fungsi event handler progres

```csharp
public delegate void ProgressEventHandler(ProgressEventHandlerInfo info);
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| info | ProgressEventHandlerInfo | Data penangan kejadian progres. |

### Contoh

Contoh berikut menunjukkan bahwa progres konversi dokumen bekerja dengan benar dan tanpa pengecualian.

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

### Lihat juga

* class [ProgressEventHandlerInfo](../../aspose.psd.progressmanagement/progresseventhandlerinfo/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



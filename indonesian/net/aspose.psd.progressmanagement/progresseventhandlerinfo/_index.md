---
title: "Kelas ProgressEventHandlerInfo"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo. Kelas ini mewakili informasi tentang kemajuan operasi memuat/menyimpan/mengekspor gambar yang dapat digunakan dalam aplikasi eksternal untuk menampilkan kemajuan konversi kepada pengguna akhir"
type: docs
weight: 5800
url: /id/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Kelas ini mewakili informasi tentang kemajuan operasi memuat/menyimpan/mengekspor gambar, yang dapat digunakan dalam aplikasi eksternal untuk menampilkan kemajuan konversi kepada pengguna akhir

```csharp
public class ProgressEventHandlerInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Mendapatkan deskripsi acara |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Mendapatkan tipe acara. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Mendapatkan batas nilai kemajuan atas. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Mendapatkan nilai kemajuan saat ini. |

## Contoh

Contoh berikut menunjukkan bahwa kemajuan konversi dokumen berfungsi dengan benar dan tanpa pengecualian.

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

### Lihat Juga

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)



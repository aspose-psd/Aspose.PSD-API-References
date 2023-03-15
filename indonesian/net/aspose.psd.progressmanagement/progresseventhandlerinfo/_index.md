---
title: Class ProgressEventHandlerInfo
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo kelas. Kelas ini merepresentasikan informasi tentang progres operasi pemuatan/penyimpanan/ekspor gambar yang dapat digunakan di aplikasi eksternal untuk menampilkan progres konversi ke pengguna akhir
type: docs
weight: 5300
url: /id/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

Kelas ini merepresentasikan informasi tentang progres operasi pemuatan/penyimpanan/ekspor gambar, yang dapat digunakan di aplikasi eksternal untuk menampilkan progres konversi ke pengguna akhir

```csharp
public class ProgressEventHandlerInfo
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Mendapat deskripsi acara |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Mendapatkan jenis acara. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Mendapat batas nilai progres atas. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Mendapat nilai progres saat ini. |

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

* ruang nama [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* perakitan [Aspose.PSD](../../)



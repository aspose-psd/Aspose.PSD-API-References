---
title: "Kelas PsdLoadOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageLoadOptions.PsdLoadOptions. Opsi pemuatan Psd"
type: docs
weight: 5250
url: /id/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Psd opsi pemuatan

```csharp
public class PsdLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Mendapatkan atau mengatur latar belakang [`Image`](../../aspose.psd/image/) [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Mendapatkan atau mengatur mode pemulihan data. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada pelaksanaan operasi UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [load effects resource] (secara default sumber daya tidak dimuat). Ketika opsi ini diatur, hanya efek yang didukung yang akan dirender ke gambar gabungan akhir. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use read only mode]. Ini adalah mode hanya-baca, didukung untuk kompatibilitas identik dengan Adobe Photoshop. Ketika opsi ini diatur, semua perubahan yang diterapkan pada lapisan tidak akan disimpan ke gambar akhir. Semua data diambil dari bagian ImageData, sehingga identik dengan Photoshop. Secara default semua gambar yang dimuat tidak identik dengan kompatibilitas Adobe Photoshop. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Mendapatkan atau mengatur mode hanya-baca yang digunakan saat memuat gambar PSD. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [use disk for load effects resource] (secara default menggunakan disk untuk memuat sumber daya efek, tetapi dapat menggunakan memori jika cukup dengan mengatur nilai ini ke false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |

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

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)



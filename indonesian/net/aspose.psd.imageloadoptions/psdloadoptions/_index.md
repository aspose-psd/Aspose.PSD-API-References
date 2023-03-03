---
title: Class PsdLoadOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions kelas. Opsi pemuatan psd
type: docs
weight: 4770
url: /id/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Opsi pemuatan psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Mendapatkan atau menyetel apakah akan menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Mendapat atau menyetel[`Image`](../../aspose.psd/image/) latar belakang[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Mendapatkan atau menyetel mode pemulihan data. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah [abaikan saluran alfa]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lebar tetap lapisan teks PSD akan diabaikan pada eksekusi operasi UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [memuat sumber daya efek] (secara default sumber daya tidak dimuat). Saat menyetel opsi ini, hanya efek yang didukung yang akan dirender ke gambar gabungan akhir. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah [gunakan mode hanya baca]. Ini adalah mode hanya-baca, didukung untuk kompatibilitas yang identik dengan Adobe Photoshop. Saat opsi ini disetel, semua perubahan yang diterapkan untuk lapisan tidak akan disimpan ke gambar akhir. Semua data digunakan dari bagian ImageData, jadi identik dengan Photoshop. Secara default, semua gambar yang dimuat tidak identik dengan yang kompatibel dengan Adobe Photoshop. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [gunakan disk untuk memuat sumber daya efek] (secara default disk digunakan untuk memuat sumber daya efek, tetapi dapat digunakan memori jika cukup dengan menyetel nilai ini ke false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah konversi profil ICC harus diterapkan. |

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

* class [LoadOptions](../../aspose.psd/loadoptions/)
* ruang nama [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* perakitan [Aspose.PSD](../../)



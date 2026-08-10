---
title: "Class Jpeg2000Options"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.Jpeg2000Options. Opsi format file Jpeg2000"
type: docs
weight: 5320
url: /id/net/aspose.psd.imageoptions/jpeg2000options/
---
{{< psd/tize >}}
## Jpeg2000Options class

Opsi format file Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Menginisialisasi instance baru dari kelas `Jpeg2000Options`. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Menginisialisasi instance baru dari kelas `Jpeg2000Options`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | Mendapatkan atau mengatur codec JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Mendapatkan atau mengatur penanda komentar Jpeg. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Mendapatkan atau mengatur array rasio kompresi. Rasio kompresi yang berbeda untuk lapisan berturut-turut. Tingkat yang ditentukan untuk setiap tingkat kualitas adalah faktor kompresi yang diinginkan. Rasio yang menurun diperlukan. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah menggunakan DWT 9-7 irreversible (true) atau menggunakan kompresi DWT 5-3 lossless (default). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | Mendapatkan atau mengatur kontainer metadata XMP. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Mengkloning instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

## Contoh

Contoh ini menunjukkan penggunaan berbagai kelas dari Namespace SaveOptions untuk tujuan ekspor. Gambar berjenis Psd dimuat ke dalam instance Image dan kemudian diekspor ke beberapa format.

```csharp
[C#]

//Muat gambar yang ada dalam instance kelas Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Ekspor ke format file BMP menggunakan opsi default
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Ekspor ke format file JPEG menggunakan opsi default
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Ekspor ke format file JPEG 2000 menggunakan opsi default
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Ekspor ke format file PNG menggunakan opsi default
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Ekspor ke format file TIFF menggunakan opsi default
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Lihat Juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



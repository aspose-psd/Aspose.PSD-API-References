---
title: "Kelas BmpOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.BmpOptions. Opsi pembuatan format file bmp"
type: docs
weight: 5280
url: /id/net/aspose.psd.imageoptions/bmpoptions/
---
{{< psd/tize >}}
## BmpOptions class

Opsi pembuatan format file bmp.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | Menginisialisasi instance baru dari kelas `BmpOptions`. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | Menginisialisasi instance baru dari kelas `BmpOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | Mendapatkan atau mengatur jumlah bit per piksel gambar. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | Mendapatkan atau mengatur kompresi. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Mendapatkan atau mengatur kontainer metadata XMP. |

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



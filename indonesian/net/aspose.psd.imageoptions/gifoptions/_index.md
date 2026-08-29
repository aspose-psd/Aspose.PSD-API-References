---
title: "Kelas GifOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.GifOptions. Opsi pembuatan format file gif"
type: docs
weight: 5300
url: /id/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

Opsi pembuatan format file gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Menginisialisasi instance baru dari kelas `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Menginisialisasi instance baru dari kelas `GifOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Mendapatkan atau mengatur indeks warna latar belakang GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Mendapatkan atau mengatur resolusi warna GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah koreksi palet diterapkan. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah GIF memiliki trailer. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Benar jika gambar harus diinterlaced. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah entri palet diurutkan. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Mendapatkan atau mengatur perbedaan piksel maksimum yang diizinkan. Jika lebih besar dari nol, kompresi lossy akan digunakan. Nilai yang direkomendasikan untuk kompresi lossy optimal adalah 80. 30 adalah kompresi sangat ringan, 200 adalah berat. Ini bekerja paling baik ketika hanya sedikit kehilangan yang diperkenalkan, dan karena keterbatasan algoritma kompresi, tingkat kehilangan yang sangat tinggi tidak akan memberikan banyak keuntungan. Rentang nilai yang diizinkan adalah [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Mendapatkan atau mengatur rasio aspek piksel GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Mendapatkan atau mengatur kontainer metadata XMP. |

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



---
title: Class GifOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptions.GifOptions kelas. Opsi pembuatan format file gif.
type: docs
weight: 4810
url: /id/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Opsi pembuatan format file gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Menginisialisasi instance baru dari`GifOptions` kelas. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Menginisialisasi instance baru dari`GifOptions` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Mendapat atau menyetel indeks warna latar belakang GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Mendapat atau menyetel resolusi warna GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah koreksi palet diterapkan. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah GIF memiliki trailer. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Benar jika gambar harus disisipkan. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah entri palet diurutkan. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Mendapat atau menyetel perbedaan piksel maksimum yang diizinkan. Jika lebih besar dari nol, kompresi lossy akan digunakan. Nilai yang disarankan untuk kompresi lossy yang optimal adalah 80. 30 adalah kompresi yang sangat ringan, 200 adalah berat. Ini bekerja paling baik ketika hanya sedikit kerugian yang terjadi, dan karena keterbatasan algoritme kompresi tingkat kerugian yang sangat tinggi tidak akan memberikan banyak keuntungan. Kisaran nilai yang diperbolehkan adalah [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Mendapatkan atau menyetel rasio aspek piksel GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapat atau menyetel pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau menyetel sumber untuk membuat gambar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapat atau menyetel opsi rasterisasi vektor. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Mendapat atau menyetel penampung metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Menggandakan instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

### Contoh

Contoh ini menunjukkan penggunaan kelas yang berbeda dari SaveOptions Namespace untuk tujuan ekspor. Gambar bertipe Psd dimuat ke dalam instance Gambar dan kemudian diekspor ke beberapa format.

```csharp
[C#]

// Muat gambar yang ada dalam instance kelas Gambar
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

### Lihat juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ruang nama [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* perakitan [Aspose.PSD](../../)



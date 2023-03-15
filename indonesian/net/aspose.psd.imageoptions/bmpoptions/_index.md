---
title: Class BmpOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptions.BmpOptions kelas. Opsi pembuatan format file bmp.
type: docs
weight: 4790
url: /id/net/aspose.psd.imageoptions/bmpoptions/
---
## BmpOptions class

Opsi pembuatan format file bmp.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | Menginisialisasi instance baru dari`BmpOptions` kelas. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | Menginisialisasi instance baru dari`BmpOptions` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | Mendapat atau menyetel bit gambar per jumlah piksel. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | Mendapat atau menyetel kompresi. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapat atau menyetel pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau menyetel sumber untuk membuat gambar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapat atau menyetel opsi rasterisasi vektor. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Mendapat atau menyetel penampung metadata XMP. |

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



---
title: Class JpegOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptions.JpegOptions kelas. Format file jpeg buat opsi.
type: docs
weight: 4840
url: /id/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Format file jpeg buat opsi.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Menginisialisasi instance baru dari`JpegOptions` kelas. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Menginisialisasi instance baru dari`JpegOptions` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Mendapat atau menyetel bit per saluran untuk gambar jpeg lossless. Sekarang kami mendukung dari 2 hingga 8 bit per saluran. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Profil warna CMYK tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan RGBColorProfile untuk konversi warna yang benar. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Mendapat atau mengatur jenis warna untuk gambar jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Mendapat atau menyetel komentar file jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Mendapat atau menyetel jenis kompresi. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Dapatkan atau atur wadah data exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Mendapat atau menyetel subsampling horizontal untuk setiap komponen. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Mendapat atau menyetel jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Mendapat atau menyetel perbedaan JPEG-LS yang terikat untuk pengkodean hampir tanpa kerugian (parameter DEKAT dari spesifikasi JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Mendapat atau menyetel mode interleave JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Mendapat atau mengatur parameter preset JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika ada saluran alfa. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Mendapat atau menyetel kualitas gambar. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Mendapat atau menyetel pengaturan pengoptimal RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapat atau menyetel pengaturan resolusi. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Mendapat atau menyetel unit resolusi. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Profil warna RGB tujuan untuk gambar jpeg CMYK. Gunakan untuk menyimpan gambar. Harus dipasangkan dengan CMYKColorProfile untuk konversi warna yang benar. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Mendapatkan atau menyetel mode pembulatan sampel agar sesuai dengan nilai 8-bit ke nilai n-bit.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Kualitas berskala. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau menyetel sumber untuk membuat gambar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapat atau menyetel opsi rasterisasi vektor. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Mendapat atau mengatur subsampling vertikal untuk setiap komponen. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Mendapat atau menyetel penampung metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Menggandakan instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

### Contoh

Contoh ini menunjukkan penggunaan Aspose.PSD untuk .Net API untuk mengonversi Gambar ke format Jpeg. Untuk mencapai tujuan ini, contoh ini memuat gambar yang ada dan kemudian mengubahnya menjadi format file Jpeg.

```csharp
[C#]

//Membuat instance kelas gambar dan menginisialisasinya dengan file yang ada melalui jalur File
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Buat turunan kelas PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Setel kualitas ke 50% untuk memperkecil ukuran gambar keluaran.
    jpegOptions.Quality = 50;

    // Tetapkan komentar exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Simpan gambar ke lokasi disk dengan pengaturan JpegOptions yang disediakan
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Contoh ini menunjukkan penggunaan System.IO.Stream untuk Membuat file Gambar baru

```csharp
[C#]

//Membuat turunan dari PsdOptions dan menyetel berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat instance System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Tentukan properti sumber untuk instance PsdOptions
// Parameter boolean kedua menentukan apakah Stream dibuang setelah keluar dari ruang lingkup
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Membuat instance Image dan memanggil metode Create dengan PsdOptions sebagai parameter untuk menginisialisasi objek Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //melakukan beberapa pemrosesan gambar
}
```

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



---
title: "Kelas JpegOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.JpegOptions. Opsi pembuatan format file jpeg"
type: docs
weight: 5330
url: /id/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

Opsi pembuatan format file jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Menginisialisasi instance baru dari kelas `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Menginisialisasi instance baru dari kelas `JpegOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Mendapatkan atau mengatur bit per kanal untuk gambar jpeg lossless. Sekarang kami mendukung dari 2 hingga 8 bit per kanal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Profil warna CMYK tujuan untuk gambar jpeg CMYK. Digunakan untuk menyimpan gambar. Harus dipasangkan dengan RGBColorProfile untuk konversi warna yang tepat. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Mendapatkan atau mengatur tipe warna untuk gambar jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Mendapatkan atau mengatur komentar file jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Mendapatkan atau mengatur tipe kompresi. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Mendapatkan atau mengatur batas alokasi memori default. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Mendapatkan atau mengatur kontainer data exif. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Mendapatkan atau mengatur subsampling horizontal untuk setiap komponen. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Mendapatkan atau mengatur jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Mendapatkan atau mengatur batas perbedaan JPEG-LS untuk pengkodean near-lossless (parameter NEAR dari spesifikasi JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Mendapatkan atau mengatur mode interleave JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Mendapatkan atau mengatur parameter preset JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen merah, hijau, dan biru harus dicampur dengan warna latar belakang, jika saluran alfa hadir. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Mendapatkan atau mengatur kualitas gambar. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan optimizer RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Mendapatkan atau mengatur satuan resolusi. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Profil warna RGB tujuan untuk gambar jpeg CMYK. Digunakan untuk menyimpan gambar. Harus dipasangkan dengan CMYKColorProfile untuk konversi warna yang tepat. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Mendapatkan atau mengatur mode pembulatan sampel untuk menyesuaikan nilai 8-bit ke nilai n-bit. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Kualitas yang diskalakan. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Mendapatkan atau mengatur sub-sampling vertikal untuk setiap komponen. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Mendapatkan atau mengatur kontainer metadata XMP. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Mengkloning instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

## Contoh

Contoh ini menunjukkan penggunaan Aspose.PSD untuk .Net API untuk mengonversi Gambar ke format Jpeg. Untuk mencapai tujuan ini, contoh ini memuat gambar yang ada dan kemudian mengonversinya ke format file Jpeg.

```csharp
[C#]

//Membuat instance kelas image dan menginisialisasinya dengan file yang ada melalui jalur File.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Buat instance kelas PsdOptions.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Atur kualitas menjadi 50% untuk mengurangi ukuran gambar output.
    jpegOptions.Quality = 50;

    //Atur komentar exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Simpan gambar ke lokasi disk dengan pengaturan JpegOptions yang diberikan.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Contoh ini menunjukkan penggunaan System.IO.Stream untuk Membuat file Image baru.

```csharp
[C#]

//Membuat instance PsdOptions dan mengatur berbagai propertinya.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat instance System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Tentukan properti sumber untuk instance PsdOptions.
//Parameter boolean kedua menentukan apakah Stream dibuang setelah keluar dari ruang lingkup.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Membuat instance Image dan memanggil metode Create dengan PsdOptions sebagai parameter untuk menginisialisasi objek Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //lakukan beberapa pemrosesan gambar
}
```

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



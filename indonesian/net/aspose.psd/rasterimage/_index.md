---
title: Class RasterImage
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.RasterImage kelas. Mewakili gambar raster yang mendukung operasi grafik raster.
type: docs
weight: 5320
url: /id/net/aspose.psd/rasterimage/
---
## RasterImage class

Mewakili gambar raster yang mendukung operasi grafik raster.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah palet penyesuaian otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai untuk warna latar belakang. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Mendapat bit gambar per jumlah piksel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapat batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan[`Image`](../image/) wadah. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapat aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Mendapat nilai format file |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini memiliki alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Mendapat nilai yang menunjukkan apakah gambar berwarna transparan. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Mendapatkan tinggi gambar. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Mendapat atau menyetel resolusi horizontal, dalam piksel per inci, dari ini`RasterImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Mendapat opacity dari gambar ini. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapat atau menyetel monitor interupsi. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Mendapat nilai yang menunjukkan apakah data objek di-cache saat ini dan tidak diperlukan pembacaan data. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Mendapat nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapat atau menyetel palet warna. Palet warna tidak digunakan saat piksel direpresentasikan secara langsung. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah komponen gambar harus dikalikan sebelumnya. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Mendapat atau menyetel konverter warna khusus |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Mendapatkan format data mentah. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mendapat pengaturan data mentah saat ini. Perhatikan saat menggunakan setelan ini, data dimuat tanpa konversi. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Mendapat atau menyetel indeks fallback untuk digunakan saat indeks palet di luar batas |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Mendapat atau mengatur konverter warna yang diindeks |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Mendapat ukuran garis mentah dalam byte. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Mendapat warna transparan gambar. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah akan memperbarui metadata XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah saat pemuatan data mentah tersedia. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Mendapat atau menyetel resolusi vertikal, dalam piksel per inci, dari ini`RasterImage` . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Mendapatkan lebar gambar. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Mendapat atau menyetel metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Menyesuaikan kecerahan untuk gambar. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Kontras gambar |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Gamma-koreksi gambar. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-koreksi gambar. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Binarisasi gambar menggunakan algoritme ambang batas adaptif Bradley menggunakan ambang batas gambar integral |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisasi gambar menggunakan algoritme ambang batas adaptif Bradley menggunakan ambang batas gambar integral |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Binarisasi gambar dengan ambang yang ditentukan sebelumnya |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Binarisasi gambar dengan thresholding Otsu |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Meng-cache data dan memastikan tidak ada pemuatan data tambahan yang dilakukan dari dasarnya[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file tertentu yang diwakili oleh opsi penyimpanan yang diteruskan. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Memotong persegi panjang yang ditentukan. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Pangkas gambar dengan shift. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Melakukan dithering pada gambar saat ini. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Melakukan dithering pada gambar saat ini. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Memfilter persegi panjang yang ditentukan. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Mendapat gambar piksel ARGB 32-bit. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Mendapatkan susunan piksel ARGB 32-bit default. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapat opsi default. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Mendapatkan larik piksel default menggunakan pemuat piksel parsial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Mendapat larik data mentah default. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Mendapatkan larik data mentah default menggunakan pemuat piksel parsial. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Mendapatkan tanggal dan waktu gambar sumber daya terakhir diubah. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Hal ini berguna untuk menjaga kedalaman bit dan parameter lain dari gambar asli tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel lalu simpan menggunakan the [`Save`](../datastreamsupporter/save/) , gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan meneruskannya ke[`Save`](../image/save/)metode sebagai parameter kedua. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Mendapat piksel gambar. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Mendapatkan sudut kemiringan. Metode ini berlaku untuk dokumen teks yang dipindai, untuk menentukan sudut kemiringan saat memindai. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Transformasi gambar ke representasi skala abu-abunya |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Memuat piksel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Memuat piksel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Memuat piksel dalam format CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Memuat piksel ARGB 32-bit sebagian per paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Memuat piksel sebagian per paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Memuat piksel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pindaian miring. Metode ini menggunakan[`GetSkewAngle`](./getskewangle/) Dan[`Rotate`](./rotate/) metode. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pindaian miring. Metode ini menggunakan[`GetSkewAngle`](./getskewangle/) Dan[`Rotate`](./rotate/) metode. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Membaca seluruh baris pindai dengan indeks baris pindai yang ditentukan. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Membaca seluruh baris pindai dengan indeks baris pindai yang ditentukan. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | Mengganti satu warna ke warna lain dengan perbedaan yang diperbolehkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | Mengganti satu warna ke warna lain dengan perbedaan yang diperbolehkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Mengubah ukuran gambar dengan opsi tambahan. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Putar gambar di tengah. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Putar gambar di tengah. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran yang mendasarinya. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Menyimpan piksel ARGB 32-bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Menyimpan piksel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Menyimpan piksel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Menyimpan data mentah. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Mengatur piksel ARGB gambar 32-bit untuk posisi yang ditentukan. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Mengatur piksel gambar untuk posisi yang ditentukan. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Menetapkan resolusi untuk ini`RasterImage` . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Mengubah gambar raster menjadi bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Menulis seluruh baris pindai ke indeks baris pindai yang ditentukan. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Menulis seluruh baris pindai ke indeks baris pindai yang ditentukan. |

### Contoh

Contoh ini menunjukkan cara Memuat informasi Piksel dalam Larik Berjenis Warna, memanipulasi larik, dan mengaturnya kembali ke gambar. Untuk melakukan operasi ini, contoh ini membuat file Gambar baru (dalam format PSD) menggunakan objek MemoryStream.

```csharp
[C#]

//Buat instance dari MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Buat instance PsdOptions dan atur berbagai propertinya termasuk properti Sumber
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Buat instance dari Gambar
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // Dapatkan piksel gambar dengan menentukan area sebagai batas gambar
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // Ulangi Array dan atur warna piksel terindeks alrenatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Atur warna piksel yang diindeks menjadi kuning
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Atur warna piksel yang diindeks menjadi biru
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Terapkan perubahan piksel pada gambar
        image.SavePixels(image.Bounds, pixels);

        // simpan semua perubahan.
        image.Save();
    }

    // Tulis MemoryStream ke File
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Lihat juga

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



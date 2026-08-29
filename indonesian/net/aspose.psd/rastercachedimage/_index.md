---
title: "Kelas RasterCachedImage"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.RasterCachedImage. Mewakili gambar raster yang mendukung operasi grafik raster. Gambar ini menyimpan data piksel dalam cache bila diperlukan"
type: docs
weight: 5810
url: /id/net/aspose.psd/rastercachedimage/
---
{{< psd/tize >}}
## RasterCachedImage class

Mewakili gambar raster yang mendukung operasi grafik raster. Gambar ini menyimpan data piksel dalam cache bila diperlukan.

```csharp
public abstract class RasterCachedImage : RasterImage
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyesuaian palet otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Mendapatkan jumlah bit per piksel gambar. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapatkan batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan kontainer [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapatkan aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Mendapatkan nilai format file |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki alfa. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Mendapatkan tinggi gambar. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [`RasterImage`](../rasterimage/) ini. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Mendapatkan opasitas gambar ini. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapatkan atau mengatur monitor interupsi. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Mendapatkan atau mengatur konverter warna khusus |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Mendapatkan format data mentah. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mendapatkan pengaturan data mentah saat ini. Catatan saat menggunakan pengaturan ini data dimuat tanpa konversi. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Mendapatkan atau mengatur indeks fallback yang digunakan ketika indeks palet berada di luar batas. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Mendapatkan atau mengatur konverter warna terindeks. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Mendapatkan ukuran baris mentah dalam byte. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Mendapatkan warna transparan gambar. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan memperbarui metadata XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [`RasterImage`](../rasterimage/) ini. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Mendapatkan lebar gambar. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Mendapatkan atau mengatur metadata XMP. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Penyesuaian kecerahan untuk gambar. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Kontras gambar. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | Koreksi gamma pada gambar. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | Koreksi gamma pada gambar. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisasi gambar dengan ambang batas yang telah ditentukan |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisasi gambar dengan ambang Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) yang mendasarinya. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | Memotong gambar. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Memotong gambar dengan pergeseran. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Melakukan dithering pada gambar saat ini. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Melakukan dithering pada gambar saat ini. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Menyaring persegi panjang yang ditentukan. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Mendapatkan piksel ARGB 32-bit gambar. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Mendapatkan array piksel ARGB 32-bit default. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapatkan opsi default. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Mendapatkan array piksel default menggunakan pemuat piksel parsial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Mendapatkan array data mentah default. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Mendapatkan array data mentah default menggunakan pemuat piksel parsial. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Mendapatkan tanggal dan waktu gambar sumber terakhir dimodifikasi. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode [`Save`](../datastreamsupporter/save/), gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode [`Save`](../image/save/) sebagai parameter kedua. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Mendapatkan piksel gambar. Peringatan Kinerja: Hindari menggunakan metode ini untuk mengiterasi semua piksel gambar karena dapat menyebabkan masalah kinerja yang signifikan. Untuk manipulasi piksel yang lebih efisien, gunakan metode `LoadArgb32Pixels` untuk mengambil seluruh array piksel sekaligus. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Mendapatkan sudut kemiringan. Metode ini berlaku untuk dokumen teks yang dipindai, untuk menentukan sudut kemiringan saat pemindaian. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformasi gambar menjadi representasi skala abu-abu |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Memuat piksel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Memuat piksel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Memuat piksel dalam format CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Memuat piksel dalam format CMYK. Metode ini sudah usang. Silakan gunakan metode yang lebih efektif yaitu [`LoadCmyk32Pixels`](../rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Memuat sebagian piksel ARGB 32-bit per paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Memuat piksel sebagian per paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Memuat piksel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Menormalkan sudut. Metode ini dapat diterapkan pada dokumen teks yang dipindai untuk menghilangkan pemindaian yang miring. Metode ini menggunakan metode [`GetSkewAngle`](../rasterimage/getskewangle/) dan [`Rotate`](../rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Menormalkan sudut. Metode ini dapat diterapkan pada dokumen teks yang dipindai untuk menghilangkan pemindaian yang miring. Metode ini menggunakan metode [`GetSkewAngle`](../rasterimage/getskewangle/) dan [`Rotate`](../rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. NearestNeighbourResample default digunakan. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. NearestNeighbourResample default digunakan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Memutar gambar di sekitar pusat. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | Memutar gambar di sekitar pusat. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran dasar. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Menyimpan piksel ARGB 32-bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Menyimpan piksel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Menyimpan piksel. Metode ini sudah usang. Silakan gunakan metode yang lebih efektif yaitu [`SaveCmyk32Pixels`](../rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Menyimpan piksel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Menyimpan data mentah. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Mengatur piksel ARGB 32-bit gambar untuk posisi yang ditentukan. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Mengatur piksel gambar untuk posisi yang ditentukan. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Mengatur resolusi untuk [`RasterImage`](../rasterimage/) ini. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Mengonversi gambar raster menjadi bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |

## Contoh

Kode berikut menunjukkan kemampuan memotong gambar dengan persegi panjang tertentu.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // Simpan psd
    image.Save(exportPath, new PsdOptions());

    // Simpan png
    image.Save(exportPathPng, new PngOptions());
}
```

### Lihat Juga

* class [RasterImage](../rasterimage/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



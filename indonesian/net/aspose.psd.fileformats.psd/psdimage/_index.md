---
title: Class PsdImage
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.PsdImage kelas. Menentukan kelas PsdImage yang menyediakan kemampuan untuk memuat mengedit menyimpan file PSD serta memperbarui properti menambahkan tanda air melakukan operasi grafik atau mengonversi satu format file ke format lainnya. Aspose.PSD mendukung impor sebagai lapisan dan mengekspor ke format berikut Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb bersama dengan ekspor ke Pdf dengan teks yang dapat dipilih
type: docs
weight: 3590
url: /id/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Menentukan kelas PsdImage yang menyediakan kemampuan untuk memuat, mengedit, menyimpan file PSD serta memperbarui properti, menambahkan tanda air, melakukan operasi grafik, atau mengonversi satu format file ke format lainnya. Aspose.PSD mendukung impor sebagai lapisan dan mengekspor ke format berikut: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb bersama dengan ekspor ke Pdf dengan teks yang dapat dipilih

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Menginisialisasi instance baru dari`PsdImage`kelas dari gambar raster yang ada (bukan gambar psd) dengan mode warna RGB dengan 4 saluran 8 bit/saluran dan tanpa kompresi. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Menginisialisasi instance baru dari`PsdImage` kelas dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Menginisialisasi instance baru dari`PsdImage` kelas dari jalur yang ditentukan dari gambar raster (bukan gambar psd di jalur). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Menginisialisasi instance baru dari`PsdImage` kelas dengan lebar dan tinggi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari`PsdImage` kelas dari gambar raster yang ada (bukan gambar psd) dengan parameter konstruktor. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari`PsdImage` kelas dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran) dengan parameter konstruktor. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari`PsdImage` kelas dari jalur yang ditentukan dari gambar raster (bukan gambar psd di jalur) dengan parameter konstruktor. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari`PsdImage` kelas dengan lebar, tinggi, paleter, mode warna, jumlah saluran dan panjang bit saluran yang ditentukan dan parameter mode kompresi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Mendapat atau menyetel layer aktif. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah palet penyesuaian otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai untuk warna latar belakang. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Mendapat bit per saluran. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Mendapat bit gambar per jumlah piksel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapat batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Mendapatkan jumlah saluran PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Mendapatkan atau menyetel profil warna CMYK untuk gambar PSD CMYK. Harus dipasangkan dengan RgbColorProfile untuk konversi warna yang benar. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Mendapat atau menyetel mode warna. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Mendapatkan metode kompresi. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan[`Image`](../../aspose.psd/image/) wadah. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapat aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Mendapat nilai format file |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Mendapat atau mengatur sudut global. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Mendapat info layer mask global. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Mendapat atau menyetel sumber daya lapisan global. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Mendapatkan atau menyetel profil warna GREY (monokrom) untuk gambar PSD Grayscale. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Mendapat atau menyetel resolusi vertikal, dalam piksel per inci, dari ini[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Mendapat nilai yang menunjukkan apakah gambar berwarna transparan. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Mendapatkan tinggi gambar. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Mendapat atau menyetel resolusi horizontal, dalam piksel per inci, dari ini`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Mendapat opacity dari gambar ini. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Mendapat atau menyetel sumber daya gambar PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapat atau menyetel monitor interupsi. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Mendapat nilai yang menunjukkan apakah data gambar di-cache saat ini. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Mendapat nilai yang menunjukkan apakah gambar psd diratakan. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Mendapat nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Mendapat atau menyetel layer PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Mendapatkan pengelola lapisan tertaut. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapat atau menyetel palet warna. Palet warna tidak digunakan saat piksel direpresentasikan secara langsung. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah komponen gambar harus dikalikan sebelumnya. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Mendapat atau menyetel konverter warna khusus |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Mendapatkan format data mentah. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mendapat pengaturan data mentah saat ini. Perhatikan saat menggunakan setelan ini, data dimuat tanpa konversi. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Mendapat atau menyetel indeks fallback untuk digunakan saat indeks palet di luar batas |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Mendapat atau mengatur konverter warna yang diindeks |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Mendapat ukuran garis mentah dalam byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Mendapatkan atau menyetel profil warna RGB untuk gambar PSD CMYK. Harus dipasangkan dengan CmykColorProfile untuk konversi warna yang benar. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Mendapatkan penyedia objek pintar. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Mendapat warna transparan gambar. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah akan memperbarui metadata XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah saat pemuatan data mentah tersedia. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Mendapatkan atau menyetel versi. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Mendapat atau menyetel resolusi vertikal, dalam piksel per inci, dari ini`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Mendapatkan lebar gambar. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Mendapat atau menyetel metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Menambahkan lapisan penyesuaian hitam putih. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Menambahkan lapisan penyesuaian kecerahan/kontras. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Menambahkan lapisan penyesuaian mixer saluran dengan parameter default |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Menambahkan lapisan penyesuaian keseimbangan warna. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Menambahkan lapisan Penyesuaian Kurva. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Menambahkan lapisan penyesuaian eksposur. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Menambahkan lapisan penyesuaian rona/saturasi. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Menambahkan lapisan penyesuaian terbalik. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Menambahkan lapisan. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Menambahkan grup layer. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Menambahkan lapisan penyesuaian Tingkat. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Menambahkan lapisan PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Menambahkan lapisan reguler baru. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Menambahkan layer Teks baru. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Menambahkan lapisan penyesuaian Vibrance. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Menyesuaikan kecerahan untuk gambar. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Kontras gambar |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Gamma-koreksi gambar. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-koreksi gambar. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisasi gambar menggunakan algoritme ambang batas adaptif Bradley menggunakan ambang batas gambar integral |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisasi gambar menggunakan algoritme ambang batas adaptif Bradley menggunakan ambang batas gambar integral |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisasi gambar dengan ambang yang ditentukan sebelumnya |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisasi gambar dengan thresholding Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Meng-cache data dan memastikan tidak ada pemuatan data tambahan yang dilakukan dari dasarnya[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file tertentu yang diwakili oleh opsi penyimpanan yang diteruskan. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Mengubah format gambar ini menjadi format yang ditentukan dalam opsi. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Memotong gambar. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Pangkas gambar dengan shift. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Melakukan dithering pada gambar saat ini. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Melakukan dithering pada gambar saat ini. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Memfilter persegi panjang yang ditentukan. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Meratakan semua layer. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Mendapat gambar piksel ARGB 32-bit. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Mendapatkan susunan piksel ARGB 32-bit default. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapat opsi default. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Mendapatkan larik piksel default menggunakan pemuat piksel parsial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Mendapat larik data mentah default. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Mendapatkan larik data mentah default menggunakan pemuat piksel parsial. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Mendapatkan tanggal dan waktu gambar sumber daya terakhir diubah. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Hal ini berguna untuk menjaga kedalaman bit dan parameter lain dari gambar asli tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel lalu simpan menggunakan the [`Save`](../../aspose.psd/datastreamsupporter/save/) , gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan meneruskannya ke[`Save`](../../aspose.psd/image/save/)metode sebagai parameter kedua. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Mendapat piksel gambar. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Mendapatkan sudut kemiringan. Metode ini berlaku untuk dokumen teks yang dipindai, untuk menentukan sudut kemiringan saat memindai. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformasi gambar ke representasi skala abu-abunya |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Memuat piksel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Memuat piksel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Memuat piksel dalam format CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Memuat piksel ARGB 32-bit sebagian per paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Memuat piksel sebagian per paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Memuat piksel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Menggabungkan layer. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pindaian miring. Metode ini menggunakan[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Dan[`Rotate`](../../aspose.psd/rasterimage/rotate/) metode. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pindaian miring. Metode ini menggunakan[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Dan[`Rotate`](../../aspose.psd/rasterimage/rotate/) metode. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Membaca seluruh baris pindai dengan indeks baris pindai yang ditentukan. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Membaca seluruh baris pindai dengan indeks baris pindai yang ditentukan. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Mengganti satu warna ke warna lain dengan perbedaan yang diperbolehkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Mengganti satu warna ke warna lain dengan perbedaan yang diperbolehkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Putar gambar di tengah. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Putar gambar di tengah. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran yang mendasarinya. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Menyimpan piksel ARGB 32-bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Menyimpan piksel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Menyimpan piksel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Menyimpan data mentah. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Mengatur piksel ARGB gambar 32-bit untuk posisi yang ditentukan. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Mengatur piksel gambar untuk posisi yang ditentukan. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Menetapkan resolusi untuk ini[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Mengubah gambar raster menjadi bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Menulis seluruh baris pindai ke indeks baris pindai yang ditentukan. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Menulis seluruh baris pindai ke indeks baris pindai yang ditentukan. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Versi PSD default. |

### Contoh

Kode berikut menunjukkan kemampuan untuk memutar gambar dengan nilai sudut tertentu.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Seluruh gambar berputar
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Lapisan berputar
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Lihat juga

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* perakitan [Aspose.PSD](../../)



---
title: "Kelas PsdImage"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.PsdImage. Mendefinisikan kelas PsdImage yang menyediakan kemampuan untuk memuat, mengedit, menyimpan file PSD serta memperbarui properti, menambahkan watermark, melakukan operasi grafis, atau mengonversi satu format file ke format lain. Aspose.PSD mendukung impor sebagai lapisan dan ekspor ke format berikut: Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb serta ekspor ke Pdf dengan teks yang dapat dipilih."
type: docs
weight: 4050
url: /id/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Menentukan kelas PsdImage yang menyediakan kemampuan untuk memuat, mengedit, menyimpan file PSD serta memperbarui properti, menambahkan watermark, melakukan operasi grafis, atau mengonversi satu format file ke format lain. Aspose.PSD mendukung impor sebagai lapisan dan ekspor ke format berikut: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb serta ekspor ke Pdf dengan teks yang dapat dipilih

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Menginisialisasi instance baru dari kelas `PsdImage` dari gambar raster yang ada (bukan gambar psd) dengan mode warna RGB dengan 4 saluran 8 bit/saluran dan tanpa kompresi. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Menginisialisasi instance baru dari kelas `PsdImage` dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Menginisialisasi instance baru dari kelas `PsdImage` dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Menginisialisasi instance baru dari kelas `PsdImage` dengan lebar dan tinggi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari kelas `PsdImage` dari gambar raster yang ada (bukan gambar psd) dengan parameter konstruktor. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari kelas `PsdImage` dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran) dengan parameter konstruktor. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari kelas `PsdImage` dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur) dengan parameter konstruktor. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Menginisialisasi instance baru dari kelas `PsdImage` dengan lebar, tinggi, paletter, mode warna, jumlah saluran, panjang bit saluran, dan parameter mode kompresi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Mendapatkan atau mengatur lapisan aktif. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyesuaian palet otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Mendapatkan bit per saluran. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Mendapatkan jumlah bit per piksel gambar. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapatkan batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Mendapatkan jumlah saluran PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Mendapatkan atau mengatur profil warna CMYK untuk gambar PSD CMYK. Harus dipasangkan dengan RgbColorProfile untuk konversi warna yang tepat. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Mendapatkan atau mengatur mode warna. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Mendapatkan metode kompresi. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan kontainer [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapatkan aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Mendapatkan nilai format file |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Mendapatkan atau mengatur sudut global. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Mendapatkan info masker lapisan global. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Mendapatkan atau mengatur sumber daya lapisan global. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Mendapatkan atau mengatur profil warna GRAY (monokrom) untuk gambar PSD Grayscale. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Mendapatkan tinggi gambar. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari `PsdImage` ini. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Mendapatkan opasitas gambar ini. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Mendapatkan atau mengatur sumber daya gambar PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapatkan atau mengatur monitor interupsi. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Mendapatkan nilai yang menunjukkan apakah gambar psd telah diratakan. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Mendapatkan atau mengatur lapisan PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Mendapatkan manajer lapisan yang ditautkan. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Mendapatkan atau mengatur konverter warna khusus |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Mendapatkan format data mentah. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mendapatkan pengaturan data mentah saat ini. Catatan saat menggunakan pengaturan ini data dimuat tanpa konversi. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Mendapatkan atau mengatur indeks fallback yang digunakan ketika indeks palet berada di luar batas. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Mendapatkan atau mengatur konverter warna terindeks. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Mendapatkan ukuran baris mentah dalam byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Mendapatkan atau mengatur profil warna RGB untuk gambar PSD CMYK. Harus dipasangkan dengan CmykColorProfile untuk konversi warna yang tepat. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Mendapatkan penyedia objek pintar. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Mendapatkan [`Timeline`](./timeline/) dari `PsdImage` ini. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Mendapatkan warna transparan gambar. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan memperbarui metadata XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Mendapatkan atau mengatur versi. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari `PsdImage` ini. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Mendapatkan lebar gambar. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Mendapatkan atau mengatur metadata XMP. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Menambahkan lapisan penyesuaian hitam putih. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Menambahkan lapisan penyesuaian kecerahan/kontras. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Menambahkan lapisan penyesuaian pencampur kanal dengan parameter default |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Menambahkan lapisan penyesuaian keseimbangan warna. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Menambahkan lapisan Penyesuaian Kurva. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Menambahkan lapisan penyesuaian eksposur. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Menambahkan lapisan Penyesuaian PetaGradien. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Menambahkan lapisan penyesuaian hue/saturasi. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Menambahkan lapisan penyesuaian invers. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Menambahkan lapisan. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Menambahkan grup lapisan. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Menambahkan lapisan penyesuaian Tingkat. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Menambahkan lapisan FilterFoto. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Menambahkan lapisan Penyesuaian Posterize. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Menambahkan lapisan reguler baru. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Menambahkan lapisan penyesuaian warna selektif. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Menambahkan lapisan Bentuk kosong. Tanpa jalur. Mereka harus ditambahkan ke lapisan bentuk sebelum disimpan. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Menambahkan lapisan Teks baru. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Menambahkan lapisan penyesuaian Ambang. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Menambahkan lapisan penyesuaian Vibransi. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Penyesuaian kecerahan untuk gambar. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Kontras gambar. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Koreksi gamma pada gambar. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Koreksi gamma pada gambar. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisasi gambar menggunakan algoritma ambang adaptif Bradley dengan ambang gambar integral. |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisasi gambar dengan ambang batas yang telah ditentukan |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisasi gambar dengan ambang Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) yang mendasarinya. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Mengonversi format gambar ini ke format yang ditentukan dalam opsi. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Memotong gambar. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Memotong gambar dengan pergeseran. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Melakukan dithering pada gambar saat ini. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Melakukan dithering pada gambar saat ini. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Menyaring persegi panjang yang ditentukan. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Meratakan semua lapisan. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Mendapatkan piksel ARGB 32-bit gambar. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Mendapatkan array piksel ARGB 32-bit default. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapatkan opsi default. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Mendapatkan array piksel default menggunakan pemuat piksel parsial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Mendapatkan array data mentah default. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Mendapatkan array data mentah default menggunakan pemuat piksel parsial. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Mendapatkan tanggal dan waktu gambar sumber terakhir dimodifikasi. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode [`Save`](../../aspose.psd/datastreamsupporter/save/), gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode [`Save`](../../aspose.psd/image/save/) sebagai parameter kedua. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Mendapatkan piksel gambar. Peringatan Kinerja: Hindari menggunakan metode ini untuk mengiterasi semua piksel gambar karena dapat menyebabkan masalah kinerja yang signifikan. Untuk manipulasi piksel yang lebih efisien, gunakan metode `LoadArgb32Pixels` untuk mengambil seluruh array piksel sekaligus. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Mendapatkan sudut kemiringan. Metode ini berlaku untuk dokumen teks yang dipindai, untuk menentukan sudut kemiringan saat pemindaian. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformasi gambar menjadi representasi skala abu-abu |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Memuat piksel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Memuat piksel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Memuat piksel dalam format CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Memuat piksel dalam format CMYK. Metode ini sudah tidak dipakai lagi. Silakan gunakan metode [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) yang lebih efektif. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Memuat sebagian piksel ARGB 32-bit per paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Memuat piksel sebagian per paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Memuat piksel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Menggabungkan lapisan-lapisan. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pemindaian yang miring. Metode ini menggunakan metode [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) dan [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pemindaian yang miring. Metode ini menggunakan metode [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) dan [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. NearestNeighbourResample default digunakan. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. NearestNeighbourResample default digunakan. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Memutar gambar di sekitar pusat. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Memutar gambar di sekitar pusat. |
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
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Menyimpan piksel. Metode ini sudah usang. Silakan gunakan metode [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) yang lebih efektif. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Menyimpan piksel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Menyimpan data mentah. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Mengatur piksel ARGB 32-bit gambar untuk posisi yang ditentukan. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Mengatur piksel gambar untuk posisi yang ditentukan. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Mengatur resolusi untuk `PsdImage` ini. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Mengonversi gambar raster menjadi bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Versi PSD default. |

## Contoh

Kode berikut menunjukkan kemampuan memutar gambar dengan nilai sudut tertentu.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotasi seluruh gambar
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

// Rotasi lapisan
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

### Lihat Juga

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



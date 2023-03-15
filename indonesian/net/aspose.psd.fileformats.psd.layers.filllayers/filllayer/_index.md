---
title: Class FillLayer
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.FillLayers.FillLayer kelas. Isi lapisan. Isi Warna Isi Gradien atau Lapisan Isi Pola yang berbedaFillSettings
type: docs
weight: 1910
url: /id/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/
---
## FillLayer class

Isi lapisan. Isi Warna, Isi Gradien atau Lapisan Isi Pola yang berbeda[`FillSettings`](./fillsettings/)

```csharp
public class FillLayer : Layer
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah palet penyesuaian otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai untuk warna latar belakang. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Mendapat bit gambar per jumlah piksel. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Mendapatkan opsi pencampuran. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Mendapat atau menyetel kunci mode campuran. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Mendapat tanda tangan mode campuran. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Mendapat atau mengatur posisi layer bawah. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapat batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Mendapat atau menyetel informasi saluran. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Mendapatkan jumlah saluran lapisan. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Mendapat atau menyetel kliping layer. 0 = alas, 1 = bukan alas. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan[`Image`](../../aspose.psd/image/) wadah. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapat aliran data objek. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Mendapat atau menyetel nama tampilan layer. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Mendapat panjang informasi tambahan lapisan dalam byte. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Mendapat nilai format file |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Mendapat atau menyetel pengisi lapisan. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Mendapat atau menyetel opasitas isian. |
| [FillSettings](../../aspose.psd.fileformats.psd.layers.filllayers/filllayer/fillsettings/) { get; } | Mendapat pengaturan isian. |
| [FillType](../../aspose.psd.fileformats.psd.layers.filllayers/filllayer/filltype/) { get; } | Mendapat jenis isian. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Mendapat atau menyetel flag layer. bit 0 = transparansi dilindungi; bit 1 = terlihat; bit 2 = usang; bit 3 = 1 untuk Photoshop 5.0 dan yang lebih baru, beri tahu jika bit 4 memiliki informasi yang berguna; bit 4 = data piksel tidak relevan dengan tampilan dokumen. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini memiliki alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Mendapat nilai yang menunjukkan apakah gambar berwarna transparan. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Mendapatkan tinggi gambar. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Mendapat atau menyetel resolusi horizontal, dalam piksel per inci, dari ini[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Mendapat opacity dari gambar ini. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapat atau menyetel monitor interupsi. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Mendapat nilai yang menunjukkan apakah data gambar di-cache saat ini. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Mendapat nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Mendapat atau menyetel nilai yang menunjukkan apakah layer terlihat |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini terlihat dalam grup (Jika lapisan tidak ada dalam grup, berarti grup root). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Mendapat atau menyetel data rentang campuran lapisan. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Mendapat atau menyetel waktu tanggal pembuatan layer. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Mendapat atau menyetel kunci lapisan. Perhatikan bahwa jika bendera LayerFlags.TransparencyProtected disetel maka akan ditimpa oleh bendera kunci lapisan. Untuk mengembalikan LayerFlags.TransparencyProtected bendera perlu diterapkan untuk opsi lapisan layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Mendapat atau menyetel data layer mask. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Mendapat opsi lapisan. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Mendapat atau mengatur posisi layer kiri. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Mendapat panjang lapisan keseluruhan dalam byte. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Mendapat atau menetapkan nama layer. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Mendapat atau menyetel opacity layer. 0 = transparan, 255 = buram. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapat atau menyetel palet warna. Palet warna tidak digunakan saat piksel direpresentasikan secara langsung. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah komponen gambar harus dikalikan sebelumnya. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Mendapat atau menyetel konverter warna khusus |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Mendapatkan format data mentah. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Mendapat pengaturan data mentah saat ini. Perhatikan saat menggunakan setelan ini, data dimuat tanpa konversi. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Mendapat atau menyetel indeks fallback untuk digunakan saat indeks palet di luar batas |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Mendapat atau mengatur konverter warna yang diindeks |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Mendapat ukuran garis mentah dalam byte. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Mendapat atau menyetel sumber daya lapisan. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Mendapat atau mengatur posisi layer yang tepat. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Mendapat atau menyetel sorotan warna lembar dekoratif di daftar lapisan |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Mendapat atau mengatur posisi layer atas. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Mendapat warna transparan gambar. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah akan memperbarui metadata XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah akan menggunakan pemuatan data mentah saat pemuatan data mentah tersedia. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Mendapat atau menyetel resolusi vertikal, dalam piksel per inci, dari ini[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Mendapatkan lebar gambar. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Mendapat atau menyetel metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [CreateInstance](../../aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/)(FillType) | Bangun instance baru dari`FillLayer` kelas berdasarkan jenis isian. |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Menambahkan topeng ke lapisan saat ini. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Menyesuaikan kecerahan untuk gambar. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Kontras gambar |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Gamma-koreksi gambar. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-koreksi gambar. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisasi gambar menggunakan algoritme ambang batas adaptif Bradley menggunakan ambang batas gambar integral |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisasi gambar menggunakan algoritme ambang batas adaptif Bradley menggunakan ambang batas gambar integral |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisasi gambar dengan ambang yang ditentukan sebelumnya |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisasi gambar dengan thresholding Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Meng-cache data dan memastikan tidak ada pemuatan data tambahan yang dilakukan dari dasarnya[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file tertentu yang diwakili oleh opsi penyimpanan yang diteruskan. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Memotong gambar. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Pangkas gambar dengan shift. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Melakukan dithering pada gambar saat ini. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Melakukan dithering pada gambar saat ini. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Menggambar gambar pada layer. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Memfilter persegi panjang yang ditentukan. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Mendapat gambar piksel ARGB 32-bit. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Mendapatkan susunan piksel ARGB 32-bit default. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapat opsi default. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Mendapatkan larik piksel default menggunakan pemuat piksel parsial. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Mendapat larik data mentah default. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Mendapatkan larik data mentah default menggunakan pemuat piksel parsial. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Mendapatkan tanggal dan waktu gambar sumber daya terakhir diubah. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Hal ini berguna untuk menjaga kedalaman bit dan parameter lain dari gambar asli tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel lalu simpan menggunakan the [`Save`](../../aspose.psd/datastreamsupporter/save/) , gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan meneruskannya ke[`Save`](../../aspose.psd/image/save/)metode sebagai parameter kedua. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Mendapat piksel gambar. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Mendapatkan sudut kemiringan. Metode ini berlaku untuk dokumen teks yang dipindai, untuk menentukan sudut kemiringan saat memindai. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformasi gambar ke representasi skala abu-abunya |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Memuat piksel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Memuat piksel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Memuat piksel dalam format CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Memuat piksel ARGB 32-bit sebagian per paket. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Memuat piksel sebagian per paket. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Memuat piksel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Memuat data mentah. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Menggabungkan layer ke layer yang ditentukan |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pindaian miring. Metode ini menggunakan[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Dan[`Rotate`](../../aspose.psd/rasterimage/rotate/) metode. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Menormalkan sudut. Metode ini berlaku untuk dokumen teks yang dipindai untuk menghilangkan pindaian miring. Metode ini menggunakan[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) Dan[`Rotate`](../../aspose.psd/rasterimage/rotate/) metode. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Membaca seluruh baris pindai dengan indeks baris pindai yang ditentukan. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Membaca seluruh baris pindai dengan indeks baris pindai yang ditentukan. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Mengganti satu warna ke warna lain dengan perbedaan yang diperbolehkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Mengganti satu warna ke warna lain dengan perbedaan yang diperbolehkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Putar gambar di tengah. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Putar gambar di tengah. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran yang mendasarinya. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Menyimpan piksel ARGB 32-bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Menyimpan piksel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Menyimpan piksel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Menyimpan data mentah. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Mengatur piksel ARGB gambar 32-bit untuk posisi yang ditentukan. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Mengatur piksel gambar untuk posisi yang ditentukan. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Menetapkan resolusi untuk ini[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Membuat salinan dangkal dari Layer saat ini. Silakan[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) untuk penjelasan. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Mengubah gambar raster menjadi bitmap. |
| [Update](../../aspose.psd.fileformats.psd.layers.filllayers/filllayer/update/)() | Update Fill Layer Pixels Data sesuai aktual[`IFillSettings`](../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) . |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Menulis seluruh baris pindai ke indeks baris pindai yang ditentukan. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Menulis seluruh baris pindai ke indeks baris pindai yang ditentukan. |

### Contoh

Contoh berikut menunjukkan dukungan Gradient FillLayer dan opsi pengeditan IGradientFillSettings..

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string outputFile = "ComplexGradientFillLayer_output.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Gradient)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (IGradientFillSettings)fillLayer.FillSettings;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             settings.TransparencyPoints.Length != 3 ||
             settings.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - settings.TransparencyPoints[0].Opacity) > 0.25 ||
             settings.TransparencyPoints[0].Location != 0 ||
             settings.TransparencyPoints[0].MedianPointLocation != 50 ||
             settings.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             settings.ColorPoints[0].Location != 0 ||
             settings.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(settings.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(settings.TransparencyPoints);
            colorPoints.Add(new GradientColorPoint()
            {
                Color = Color.Violet,
                Location = 4096,
                MedianPointLocation = 75
            });
            colorPoints[1].Location = 3000;
            transparencyPoints.Add(new GradientTransparencyPoint()
            {
                Opacity = 80.0,
                Location = 4096,
                MedianPointLocation = 25
            });
            transparencyPoints[2].Location = 3000;
            settings.ColorPoints = colorPoints.ToArray();
            settings.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### Lihat juga

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../aspose.psd.fileformats.psd.layers.filllayers/)
* perakitan [Aspose.PSD](../../)



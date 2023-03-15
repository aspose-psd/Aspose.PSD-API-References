---
title: Class VectorImage
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.VectorImage kelas. Gambar vektor adalah kelas dasar untuk semua jenis gambar vektor.
type: docs
weight: 5720
url: /id/net/aspose.psd/vectorimage/
---
## VectorImage class

Gambar vektor adalah kelas dasar untuk semua jenis gambar vektor.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Mendapatkan tinggi gambar. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Mendapat tinggi objek, dalam inci. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapat atau menyetel monitor interupsi. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Mendapat nilai yang menunjukkan apakah data objek di-cache saat ini dan tidak diperlukan pembacaan data. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapat atau menyetel palet warna. Palet warna tidak digunakan saat piksel direpresentasikan secara langsung. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Mendapatkan ukuran objek, dalam inci. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Mendapatkan lebar gambar. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Mendapatkan lebar objek, dalam inci. |

## Metode

| Nama | Keterangan |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Meng-cache data dan memastikan tidak ada pemuatan data tambahan yang dilakukan dari dasarnya[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file tertentu yang diwakili oleh opsi penyimpanan yang diteruskan. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapat opsi default. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Hal ini berguna untuk menjaga kedalaman bit dan parameter lain dari gambar asli tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel lalu simpan menggunakan the [`Save`](../datastreamsupporter/save/) , gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan meneruskannya ke[`Save`](../image/save/)metode sebagai parameter kedua. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran yang mendasarinya. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |

### Lihat juga

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



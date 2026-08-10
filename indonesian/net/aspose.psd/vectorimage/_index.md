---
title: "Kelas VectorImage"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.VectorImage. Gambar vektor adalah kelas dasar untuk semua jenis gambar vektor."
type: docs
weight: 6220
url: /id/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

Gambar vektor adalah kelas dasar untuk semua jenis gambar vektor.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Mendapatkan tinggi gambar. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Mendapatkan tinggi objek, dalam inci. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapatkan atau mengatur monitor interupsi. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Mendapatkan nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Mendapatkan ukuran objek, dalam inci. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Mendapatkan lebar gambar. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Mendapatkan lebar objek, dalam inci. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) yang mendasarinya. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapatkan opsi default. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode [`Save`](../datastreamsupporter/save/), gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode [`Save`](../image/save/) sebagai parameter kedua. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. NearestNeighbourResample default digunakan. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. NearestNeighbourResample default digunakan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran dasar. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |

### Lihat Juga

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



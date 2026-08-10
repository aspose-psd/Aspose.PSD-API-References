---
title: "Kelas Image"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Image. Gambar merupakan kelas dasar untuk semua jenis gambar."
type: docs
weight: 5060
url: /id/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

Gambar adalah kelas dasar untuk semua jenis gambar.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyesuaian palet otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Mendapatkan jumlah bit per piksel gambar. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapatkan batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan kontainer `Image`. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapatkan aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Mendapatkan nilai format file |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Mendapatkan tinggi gambar. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapatkan atau mengatur monitor interupsi. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Mendapatkan nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Mendapatkan lebar gambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Membuat gambar baru menggunakan opsi pembuatan yang ditentukan. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Memuat gambar baru dari aliran yang ditentukan. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Memuat gambar baru dari file yang ditentukan. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Memuat gambar baru dari aliran yang ditentukan. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Memuat gambar baru dari file yang ditentukan. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) yang mendasarinya. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapatkan opsi default. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode [`Save`](../datastreamsupporter/save/), gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode [`Save`](./save/) sebagai parameter kedua. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Mengubah ukuran gambar. NearestNeighbourResample default digunakan. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Mengubah ukuran lebar secara proporsional. NearestNeighbourResample default digunakan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/#save)() | Menyimpan data gambar ke aliran dasar. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan opsional menggunakan *loadOptions* yang ditentukan. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan opsional menggunakan opsi buka yang ditentukan. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Mendapatkan format file. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Mendapatkan format file. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Mendapatkan tinggi proporsional. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Mendapatkan lebar proporsional. |

## Contoh

Contoh ini membuat file Image baru di lokasi disk tertentu sebagaimana ditentukan oleh properti Source dari instance PsdOptions. Beberapa properti untuk instance PsdOptions diatur sebelum membuat gambar sebenarnya. Khususnya properti Source, yang merujuk ke lokasi disk aktual dalam kasus ini.

```csharp
[C#]

//Buat sebuah instance dari PsdOptions dan atur berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat sebuah instance dari FileCreateSource dan tetapkan sebagai Source untuk instance PsdOptions
//Parameter Boolean kedua menentukan apakah file yang akan dibuat bersifat IsTemporal atau tidak
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Buat sebuah instance dari Image dan inisialisasi dengan instance PsdOptions dengan memanggil metode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //lakukan beberapa pemrosesan gambar

    // simpan semua perubahan
    image.Save();
}
```

### Lihat Juga

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



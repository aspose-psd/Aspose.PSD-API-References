---
title: "Kelas AiImage"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Ai.AiImage class. Gambar AI Adobe Illustrator"
type: docs
weight: 1270
url: /id/net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

Gambar Adobe Illustrator (AI).

```csharp
public sealed class AiImage : Image
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AiImage](aiimage/)() | Menginisialisasi sebuah instance baru dari kelas `AiImage`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | Mendapatkan atau mengatur indeks halaman aktif. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah penyesuaian palet otomatis. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Mendapatkan jumlah bit per piksel gambar. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Mendapatkan batas gambar. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [Container](../../aspose.psd/image/container/) { get; } | Mendapatkan kontainer [`Image`](../../aspose.psd/image/). |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Mendapatkan bagian data. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Mendapatkan aliran data objek. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Mendapatkan nilai format file. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Mendapatkan bagian finalisasi. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Mendapatkan header. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Mendapatkan tinggi gambar. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Mendapatkan atau mengatur monitor interupsi. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Mendapatkan nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Mendapatkan bagian lapisan. |
| [PageCount](../../aspose.psd.fileformats.ai/aiimage/pagecount/) { get; } | Jumlah halaman. Untuk gambar format AI lama selalu bernilai 0. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Mendapatkan bagian pengaturan. |
| [Size](../../aspose.psd/image/size/) { get; } | Mendapatkan ukuran gambar. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Mendapatkan versi format Adobe Illustrator. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Mendapatkan lebar gambar. |
| [XmpData](../../aspose.psd.fileformats.ai/aiimage/xmpdata/) { get; } | Mendapatkan metadata XMP. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Menambahkan bagian lapisan AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) yang mendasarinya. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Mendapatkan opsi default. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Mendapatkan opsi berdasarkan pengaturan file asli. Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah. Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan metode [`Save`](../../aspose.psd/datastreamsupporter/save/), gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan. Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke metode [`Save`](../../aspose.psd/image/save/) sebagai parameter kedua. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Mengubah ukuran gambar. NearestNeighbourResample default digunakan. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Mengubah ukuran gambar. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Mengubah ukuran gambar. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Mengubah ukuran tinggi secara proporsional. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Mengubah ukuran tinggi secara proporsional. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Mengubah ukuran lebar secara proporsional. NearestNeighbourResample default digunakan. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Mengubah ukuran lebar secara proporsional. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Mengubah ukuran lebar secara proporsional. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Memutar, membalik, atau memutar dan membalik gambar. |
| [Save](../../aspose.psd/image/save/)() | Menyimpan data gambar ke aliran dasar. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Menyimpan data objek ke aliran yang ditentukan. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Menyimpan data objek ke lokasi file yang ditentukan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Mengatur palet gambar. |

## Contoh

Contoh berikut menunjukkan cara Anda dapat mengekspor file Adobe Illustrator ke format PDF dalam Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Contoh berikut menunjukkan cara Anda dapat mengekspor file AI ke format PSD dan PNG dalam Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Contoh berikut menunjukkan dukungan pengeksporan format Ai ke format PSD, PNG, JPG, GIF, dan TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Lihat Juga

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



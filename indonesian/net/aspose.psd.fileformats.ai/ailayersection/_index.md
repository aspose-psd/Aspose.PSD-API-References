---
title: "Kelas AiLayerSection"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Ai.AiLayerSection. Bagian Layer format Ai"
type: docs
weight: 1280
url: /id/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

Bagian Lapisan format Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Mendapatkan atau mengatur komponen warna biru. |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | Mendapatkan atau mengatur indeks warna. Argumen ini dapat memiliki nilai antara –1 dan 26. Setiap integer mewakili warna yang dapat diberikan ke lapisan untuk tujuan identifikasi pengguna. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Mendapatkan atau mengatur nomor warna. -1 adalah nilai warna khusus dari properti Merah, Hijau, Biru. Menentukan pengaturan warna lapisan. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Mendapatkan atau mengatur nilai redup sebagai persentase. Mengurangi intensitas gambar terhubung dan gambar bitmap yang terdapat dalam lapisan ke persentase yang ditentukan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Mendapatkan atau mengatur komponen warna hijau. |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilapisan. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini diredupkan. Mengurangi intensitas gambar terhubung dan gambar bitmap yang terdapat dalam lapisan. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini terkunci. Mencegah perubahan pada item. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dalam pratinjau. Menampilkan karya seni yang terdapat dalam lapisan dengan warna alih-alih sebagai garis besar. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dicetak. Membuat karya seni yang terdapat dalam lapisan dapat dicetak jika true. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini ditampilkan. Menampilkan semua karya seni yang terdapat dalam lapisan pada papan gambar jika true. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini adalah lapisan templat. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Mendapatkan atau mengatur nama lapisan. Menentukan nama item sebagaimana muncul di panel Lapisan. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Mendapatkan gambar raster. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Mendapatkan atau mengatur komponen warna merah. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Menambahkan gambar raster. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Mendapatkan data string. |

## Contoh

Kode berikut menunjukkan cara memuat pengaturan Gambar Raster dalam File Format AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Lihat Juga

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



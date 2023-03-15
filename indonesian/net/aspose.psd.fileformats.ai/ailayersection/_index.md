---
title: Class AiLayerSection
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Ai.AiLayerSection kelas. Bagian Lapisan Format Ai
type: docs
weight: 1270
url: /id/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Bagian Lapisan Format Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Mendapat atau menyetel komponen warna biru. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Mendapat atau menetapkan nomor warna. -1 adalah nilai warna khusus dari properti Merah, Hijau, Biru. Menentukan pengaturan warna lapisan. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Mendapat atau menetapkan nilai redup sebagai persentase. Mengurangi intensitas gambar tertaut dan gambar bitmap yang terdapat dalam lapisan ke persentase yang ditentukan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Mendapat atau menyetel komponen warna hijau. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lapisan ini diredupkan. Mengurangi intensitas gambar terkait dan gambar bitmap yang terdapat dalam lapisan. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lapisan ini dikunci. Mencegah perubahan pada item. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lapisan ini adalah pratinjau. Menampilkan karya seni yang terkandung dalam lapisan dalam warna, bukan sebagai garis luar. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lapisan ini dicetak. Membuat karya seni yang terkandung dalam lapisan dapat dicetak jika benar. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lapisan ini ditampilkan. Menampilkan semua karya seni yang terkandung dalam lapisan di artboard jika benar. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah lapisan ini adalah lapisan template. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Mendapat atau menyetel nama lapisan. Menentukan nama item seperti yang muncul di panel Lapisan. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Mendapat gambar raster. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Mendapat atau menyetel komponen warna merah. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Menambahkan gambar raster. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Mendapat data string. |

### Contoh

Kode berikut menunjukkan cara memuat pengaturan Gambar Raster di File Format AI.

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

### Lihat juga

* class [AiDataSection](../aidatasection/)
* ruang nama [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* perakitan [Aspose.PSD](../../)



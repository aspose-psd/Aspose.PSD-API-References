---
title: Class PdfOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptions.PdfOptions kelas. Opsi PDF.
type: docs
weight: 4870
url: /id/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

Opsi PDF.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Mendapat atau mengatur ukuran halaman. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | Opsi inti PDF |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Mendapat atau menetapkan metadata untuk dokumen. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapat atau menyetel pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau menyetel sumber untuk membuat gambar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapat atau menyetel opsi rasterisasi vektor. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Mendapat atau menyetel penampung metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Menggandakan instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat mengekspor file Adobe Illustrator ke format PDF di Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Contoh berikut menunjukkan bahwa AsposePSD mendukung file PSB yang diekspor ke format PSD.

```csharp
[C#]

// Mendukung penyimpanan PSB sebagai PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Kode berikut menyimpan PsdImage sebagai dokumen PDF dengan teks yang dapat dipilih.

```csharp
[C#]

// Menyimpan PSD ke dalam PDF tidak menyediakan teks yang dapat dipilih
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Contoh berikut menunjukkan dukungan untuk mengekspor PsdImage ke format Pdf.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### Lihat juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ruang nama [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* perakitan [Aspose.PSD](../../)



---
title: Class VectorRasterizationOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptions.VectorRasterizationOptions kelas. Opsi rasterisasi vektor.
type: docs
weight: 4980
url: /id/net/aspose.psd.imageoptions/vectorrasterizationoptions/
---
## VectorRasterizationOptions class

Opsi rasterisasi vektor.

```csharp
public abstract class VectorRasterizationOptions : ImageOptionsBase
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Mendapat atau menyetel warna latar belakang. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Mendapat atau menyetel batas X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Mendapat atau mengatur perbatasan Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah gambar tengah. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Mendapat atau menyetel warna latar depan. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Mendapat atau mengatur tinggi halaman. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Mendapat atau mengatur ukuran halaman. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Mendapat atau mengatur lebar halaman. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapat atau menyetel pengaturan resolusi. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Mendapatkan atau menyetel mode smoothing. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau menyetel sumber untuk membuat gambar. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Mendapat atau menyetel petunjuk rendering teks. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapat atau menyetel opsi rasterisasi vektor. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Mendapat atau menyetel penampung metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Menggandakan instance ini. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Salin ke. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

### Lihat juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ruang nama [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* perakitan [Aspose.PSD](../../)



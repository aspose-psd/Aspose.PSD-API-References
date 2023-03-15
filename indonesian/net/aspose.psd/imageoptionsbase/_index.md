---
title: Class ImageOptionsBase
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptionsBase kelas. Opsi basis gambar.
type: docs
weight: 4990
url: /id/net/aspose.psd/imageoptionsbase/
---
## ImageOptionsBase class

Opsi basis gambar.

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
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

### Lihat juga

* class [DisposableObject](../disposableobject/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



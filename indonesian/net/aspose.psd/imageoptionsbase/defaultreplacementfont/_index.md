---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD untuk Referensi .NET API
description: ImageOptionsBase Properti. Mendapat atau menyetel font pengganti default font yang akan digunakan untuk menggambar teks saat mengekspor ke raster jika font layer yang ada di file PSD tidak disajikan di sistem. Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily keluarga  col.Families string defaultFontName  keluarga0.Nama PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /id/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Nilai properti

Font pengganti default.

### Contoh

Contoh berikut menunjukkan cara menggunakan properti DefaultReplacementFont untuk mengubah font pengganti default.

```csharp
[C#]

// Tolong, jangan instal Konstanting Font, karena tes ini harus menggantikan font yang tidak diinstal
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // Dengan cara ini Anda dapat menggunakan font yang berbeda untuk keluaran yang berbeda 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Lihat juga

* class [ImageOptionsBase](../)
* ruang nama [Aspose.PSD](../../imageoptionsbase/)
* perakitan [Aspose.PSD](../../../)



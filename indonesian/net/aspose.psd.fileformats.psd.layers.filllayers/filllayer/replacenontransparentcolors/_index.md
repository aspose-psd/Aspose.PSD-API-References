---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode FillLayer. Mengganti semua warna nontransparent dengan warna baru dan mempertahankan nilai alpha asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Mengganti semua warna tidak transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newColorArgb | Int32 | Nilai ARGB warna baru untuk menggantikan warna nontransparent. |

## Contoh

Kode berikut menunjukkan dukungan Mode Warna CMYK 16 bit dan kemampuan menggambar dengan menggunakan kelas Aspose.PSD.Graphics.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Lihat Juga

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)



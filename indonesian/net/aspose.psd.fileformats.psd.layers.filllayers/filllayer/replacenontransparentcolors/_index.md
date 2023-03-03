---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD untuk Referensi .NET API
description: FillLayer metode. Mengganti semua warna nontransparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan jika Anda menggunakannya pada gambar tanpa transparansi semua warna akan diganti dengan satu warna.
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk mempertahankan tepi yang halus. Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newColorArgb | Int32 | Nilai ARGB warna baru untuk menggantikan warna yang tidak transparan. |

### Contoh

Kode berikut menunjukkan dukungan CMYK ColorMode 16 bit dan kemampuan menggambar dengan menggunakan kelas Aspose.PSD.Graphics.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### Lihat juga

* class [FillLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* perakitan [Aspose.PSD](../../../)



---
title: "Kelas LayerMaskDataShort"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort class. Mendefinisikan kelas LayerMaskDataShort yang berisi informasi tentang data masker pada lapisan file PSD ketika lapisan hanya memiliki masker raster atau vektor tetapi tidak keduanya. Jika tidak, digunakan LayerMaskDataFull. Jika lapisan hanya memiliki masker raster, ImageData berisi byte data masker raster. Jika lapisan hanya memiliki masker vektor, ImageData berisi byte data vektor yang telah dirasterisasi dan disimpan dalam cache. Panjang byte ImageData harus sama dengan Width * Height dari properti MaskRectangle."
type: docs
weight: 2460
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Mendefinisikan kelas LayerMaskDataShort yang berisi informasi tentang data masker pada lapisan file PSD ketika lapisan hanya memiliki masker raster atau vektor tetapi tidak keduanya. Jika tidak, sebuah [`LayerMaskDataFull`](../layermaskdatafull/) digunakan. Jika lapisan hanya memiliki masker raster, ImageData berisi byte data masker raster. Jika lapisan hanya memiliki masker vektor, ImageData berisi byte data vektor yang dirasterisasi (cached). Panjang byte [`ImageData`](../layermaskdata/imagedata/) harus sama dengan Width * Height dari properti [`MaskRectangle`](../layermaskdata/maskrectangle/).

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Menginisialisasi instance baru dari kelas `LayerMaskDataShort`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan bagian bawah. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Mendapatkan ukuran data mask lapisan. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Mendapatkan atau mengatur warna default. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Mendapatkan atau mengatur flag mask lapisan. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Mendapatkan atau mengatur [`Rectangle`](../../aspose.psd/rectangle/) mask dari mask lapisan dalam file PSD. Ini mengambil properti kiri, kanan, atas, dan bawah serta membuat [`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Mendapatkan atau mengatur padding masker lapisan. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan atas. |

### Lihat Juga

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)



---
title: "Kelas LayerMaskData"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData class. Mendefinisikan kelas dasar LayerMaskData yang berisi informasi tentang data mask lapisan dalam file PSD. Ini dapat membantu memodifikasi file Adobe Photoshop secara programatis dan mengotomatiskan penyuntingan format PSD. Jika lapisan hanya memiliki mask raster, ImageData berisi byte data mask raster. Jika lapisan hanya memiliki mask vektor, ImageData berisi byte data cache mask vektor yang telah dirasterkan. Jika lapisan memiliki mask lapisan dan vektor, ImageData berisi mask raster dan mask vektor yang dirasterkan digabungkan. Panjang byte ImageData harus sama dengan Lebar * Tinggi properti MaskRectangle. Perhatikan bahwa hanya menghapus / menambahkan / memperbarui LayerMaskData tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui meskipun dapat memberikan rendering yang tepat. Metode AddLayerMask harus digunakan untuk itu."
type: docs
weight: 2440
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Menentukan kelas dasar LayerMaskData yang berisi informasi tentang data mask lapisan dalam file PSD. Ini dapat membantu memodifikasi file Adobe® Photoshop® secara programatis dan mengotomatiskan penyuntingan format PSD. Jika lapisan hanya memiliki mask raster, ImageData berisi byte data mask raster. Jika lapisan hanya memiliki mask vektor, ImageData berisi byte data mask vektor yang dirasterkan (cached). Jika lapisan memiliki mask lapisan dan vektor, ImageData berisi mask raster dan mask vektor yang dirasterkan digabungkan. Panjang byte [`ImageData`](./imagedata/) harus sama dengan Lebar * Tinggi properti [`MaskRectangle`](./maskrectangle/). Perhatikan bahwa hanya menghapus / menambahkan / memperbarui LayerMaskData tidak cukup untuk penyimpanan yang benar karena saluran tidak diperbarui; meskipun dapat memberikan rendering yang tepat. Metode [`AddLayerMask`](../layer/addlayermask/) harus digunakan untuk itu.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan atas. |

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)



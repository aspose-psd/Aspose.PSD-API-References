---
title: Class LayerMaskData
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData kelas. Menentukan kelas LayerMaskData dasar yang berisi informasi tentang data layer mask dalam file PSD. Ini dapat membantu memodifikasi file Adobe Photoshop secara terprogram dan mengotomatiskan pengeditan format PSD. Jika layer hanya memiliki masker raster ImageData berisi raster mask data bytes. Jika layer hanya memiliki mask vektor ImageData berisi byte data raster cache mask vektor. Jika layer memiliki layer dan mask vektor ImageData berisi masker raster dan masker vektor raster digabungkan. ItuImageDatapanjang byte harus sama dengan Lebar  TinggiMaskRectangle properties. Perhatikan bahwa menghapus / menambah / memperbarui LayerMaskData saja tidak cukup untuk menyimpan dengan benar karena saluran tidak diperbarui meskipun mungkin memberikan rendering yang benar. TheAddLayerMask metode harus digunakan untuk itu.
type: docs
weight: 2240
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Menentukan kelas LayerMaskData dasar yang berisi informasi tentang data layer mask dalam file PSD. Ini dapat membantu memodifikasi file Adobe® Photoshop® secara terprogram dan mengotomatiskan pengeditan format PSD. Jika layer hanya memiliki masker raster, ImageData berisi raster mask data bytes. Jika layer hanya memiliki mask vektor, ImageData berisi byte data raster (cache) mask vektor. Jika layer memiliki layer dan mask vektor, ImageData berisi masker raster dan masker vektor raster digabungkan. Itu[`ImageData`](./imagedata/)panjang byte harus sama dengan Lebar * Tinggi[`MaskRectangle`](./maskrectangle/) properties. Perhatikan, bahwa menghapus / menambah / memperbarui LayerMaskData saja tidak cukup untuk menyimpan dengan benar karena saluran tidak diperbarui; meskipun mungkin memberikan rendering yang benar. The[`AddLayerMask`](../layer/addlayermask/) metode harus digunakan untuk itu.

```csharp
public abstract class LayerMaskData
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Mendapat atau mengatur posisi layer mask bawah. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Mendapat ukuran data layer mask mask. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Mendapat atau menyetel warna default. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Mendapat atau menyetel bendera layer mask. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Mendapat atau mengatur data layer mask (atau gabungan / final mask jika ada topeng vektor) di file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Mendapat atau mengatur posisi layer mask kiri. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Mendapat atau menyetel topeng[`Rectangle`](../../aspose.psd/rectangle/)dari layer mask di file PSD. Dibutuhkan properti kiri, kanan, atas dan bawah dan membuat[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Mendapat atau mengatur posisi layer mask yang tepat. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Mendapat atau mengatur posisi top layer mask. |

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* perakitan [Aspose.PSD](../../)



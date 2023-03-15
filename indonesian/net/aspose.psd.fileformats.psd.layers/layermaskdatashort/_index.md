---
title: Class LayerMaskDataShort
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort kelas. Mendefinisikan kelas LayerMaskDataShort yang berisi informasi tentang data mask di file PSD layer ketika layer hanya memiliki mask raster atau vektor tetapi tidak keduanya. Jika tidak aLayerMaskDataFull digunakan. Jika layer hanya memiliki topeng raster ImageData berisi byte data topeng raster. Jika lapisan hanya memiliki topeng vektor ImageData berisi byte data raster cache topeng vektor. ImageDatapanjang byte harus sama dengan Lebar  TinggiMaskRectangle properti.
type: docs
weight: 2260
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Mendefinisikan kelas LayerMaskDataShort yang berisi informasi tentang data mask di file PSD layer ketika layer hanya memiliki mask raster atau vektor tetapi tidak keduanya. Jika tidak, a[`LayerMaskDataFull`](../layermaskdatafull/) digunakan. Jika layer hanya memiliki topeng raster, ImageData berisi byte data topeng raster. Jika lapisan hanya memiliki topeng vektor, ImageData berisi byte data raster (cache) topeng vektor. [`ImageData`](../layermaskdata/imagedata/)panjang byte harus sama dengan Lebar * Tinggi[`MaskRectangle`](../layermaskdata/maskrectangle/) properti.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Konstruktor default. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Mendapat atau menyetel padding layer mask. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Mendapat atau mengatur posisi layer mask yang tepat. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Mendapat atau mengatur posisi top layer mask. |

### Lihat juga

* class [LayerMaskData](../layermaskdata/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* perakitan [Aspose.PSD](../../)



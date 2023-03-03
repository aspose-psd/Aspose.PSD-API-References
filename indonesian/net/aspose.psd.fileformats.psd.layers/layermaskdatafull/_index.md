---
title: Class LayerMaskDataFull
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull kelas. Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data mask di file PSD layer saat layer memiliki layer dan mask vektor. Jika tidak aLayerMaskDataShort digunakan. ImageData berisi topeng raster dan gabungan topeng vektor raster. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width  MaskRectangle.Height.
type: docs
weight: 2250
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data mask di file PSD layer saat layer memiliki layer dan mask vektor. Jika tidak, a[`LayerMaskDataShort`](../layermaskdatashort/) digunakan. ImageData berisi topeng raster dan gabungan topeng vektor raster. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Mendapat atau mengatur warna latar belakang. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Mendapat atau mengatur posisi layer mask bawah. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Mendapat ukuran data layer mask mask. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Mendapat atau menyetel warna default. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Mendapat atau menyetel posisi topeng raster bawah terlampir di lapisan gambar PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Mendapat atau menyetel posisi topeng raster kiri terlampir di lapisan file PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Mendapat atau menyetel posisi topeng raster yang tepat di lapisan file PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Mendapat atau menyetel posisi atas penutup raster mask di lapisan gambar PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Mendapat atau menyetel bendera layer mask. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Mendapat atau mengatur data layer mask (atau gabungan / final mask jika ada topeng vektor) di file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Mendapat atau mengatur posisi layer mask kiri. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Mendapat atau menyetel topeng[`Rectangle`](../../aspose.psd/rectangle/)dari layer mask di file PSD. Dibutuhkan properti kiri, kanan, atas dan bawah dan membuat[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Mendapat atau mengatur flag layer mask yang digunakan untuk user / raster mask. Untuk topeng vektor, properti Bendera digunakan. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Mendapat atau mengatur posisi layer mask yang tepat. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Mendapat atau mengatur posisi top layer mask. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Mendapat atau menyetel data mask pengguna (raster) dari sebuah layer dalam file PSD. (Ada topeng vektor terukur di properti MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Mendapat atau menyetel persegi panjang topeng pengguna (menutup) di lapisan gambar PSD.. |

### Lihat juga

* class [LayerMaskData](../layermaskdata/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* perakitan [Aspose.PSD](../../)



---
title: "Kelas LayerMaskDataFull"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull class. Mendefinisikan kelas LayerMaskDataFull yang berisi informasi tentang data mask dalam lapisan file PSD ketika lapisan memiliki mask lapisan dan vektor. Jika tidak, digunakan LayerMaskDataShort. ImageData berisi mask raster dan mask vektor yang dirasterkan digabungkan. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width * MaskRectangle.Height."
type: docs
weight: 2450
url: /id/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Menentukan kelas LayerMaskDataFull yang berisi informasi tentang data mask dalam lapisan file PSD ketika lapisan memiliki mask lapisan dan vektor. Jika tidak, digunakan [`LayerMaskDataShort`](../layermaskdatashort/). ImageData berisi mask raster dan mask vektor yang dirasterkan digabungkan. Panjang byte ImageData harus sama dengan properti MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur warna latar belakang. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan bagian bawah. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Mendapatkan ukuran data mask lapisan. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Mendapatkan atau mengatur warna default. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Mendapatkan atau mengatur posisi raster mask bagian bawah yang melingkupi dalam lapisan gambar PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Mendapatkan atau mengatur posisi raster mask kiri yang melingkupi dalam lapisan file PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Mendapatkan atau mengatur posisi raster mask kanan yang melingkupi dalam lapisan file PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Mendapatkan atau mengatur posisi atas raster mask yang melingkupi dalam lapisan gambar PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Mendapatkan atau mengatur flag mask lapisan. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Mendapatkan atau mengatur data mask lapisan (atau mask gabungan / akhir jika ada mask vektor) dalam file PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan kiri. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Mendapatkan atau mengatur [`Rectangle`](../../aspose.psd/rectangle/) mask dari mask lapisan dalam file PSD. Ini mengambil properti kiri, kanan, atas, dan bawah serta membuat [`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Mendapatkan atau mengatur flag mask lapisan yang digunakan untuk mask pengguna / raster. Untuk mask vektor properti Flags digunakan. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan kanan. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Mendapatkan atau mengatur posisi mask lapisan atas. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Mendapatkan atau mengatur data mask pengguna (raster) dari sebuah lapisan dalam file PSD. (Ada mask vektor yang dirasterkan dalam properti MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Mendapatkan atau mengatur persegi panjang mask pengguna (melingkupi) dalam lapisan gambar PSD. |

### Lihat Juga

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)



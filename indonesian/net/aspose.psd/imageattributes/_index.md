---
title: Class ImageAttributes
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageAttributes kelas. AnImageAttributes objek berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama rendering. SebuahImageAttributes objek mempertahankan beberapa pengaturan penyesuaian warna termasuk matriks penyesuaian warna matriks penyesuaian skala abuabu nilai koreksi gamma tabel peta warna dan nilai ambang warna. Selama rendering warna dapat dikoreksi digelapkan diringankan dan dihilangkan. Untuk menerapkan manipulasi seperti itu inisialisasi anImageAttributeskeberatan dan lewati jalan ituImageAttributes objek bersama dengan jalur anImage  ke metode DrawImage.
type: docs
weight: 4610
url: /id/net/aspose.psd/imageattributes/
---
## ImageAttributes class

An`ImageAttributes` objek berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama rendering. Sebuah`ImageAttributes` objek mempertahankan beberapa pengaturan penyesuaian warna, termasuk matriks penyesuaian warna, matriks penyesuaian skala abu-abu, nilai koreksi gamma, tabel peta warna, dan nilai ambang warna. Selama rendering, warna dapat dikoreksi, digelapkan, diringankan, dan dihilangkan. Untuk menerapkan manipulasi seperti itu, inisialisasi an`ImageAttributes`keberatan dan lewati jalan itu`ImageAttributes` objek (bersama dengan jalur an[`Image`](../image/) ) ke metode DrawImage.

```csharp
public sealed class ImageAttributes
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Konstruktor default. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Menghapus tabel remap warna kuas ini`ImageAttributes` objek. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Menghapus kunci warna (rentang transparansi) untuk kategori default. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Menghapus kunci warna (rentang transparansi) untuk kategori tertentu. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Menghapus matriks penyesuaian warna untuk kategori default. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Menghapus matriks penyesuaian warna untuk kategori tertentu. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Menonaktifkan koreksi gamma untuk kategori default. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Menonaktifkan koreksi gamma untuk kategori tertentu. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Menghapus pengaturan NoOp untuk kategori default. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Menghapus pengaturan NoOp untuk kategori tertentu. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Menghapus pengaturan saluran output CMYK (cyan-magenta-kuning-hitam) untuk kategori default. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Menghapus pengaturan saluran keluaran (cyan-magenta-kuning-hitam) untuk kategori tertentu. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Menghapus pengaturan profil warna saluran keluaran untuk kategori default. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Menghapus pengaturan profil warna saluran keluaran untuk kategori tertentu. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Menghapus tabel remap warna untuk kategori default. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Menghapus tabel remap warna untuk kategori tertentu. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Menghapus nilai ambang untuk kategori default. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Menghapus nilai ambang untuk kategori tertentu. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Mengatur tabel remap warna untuk kategori kuas. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Mengatur kunci warna untuk kategori default. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Mengatur kunci warna (rentang transparansi) untuk kategori tertentu. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori tertentu. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Mengatur matriks penyesuaian warna untuk kategori tertentu. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Mengatur nilai gamma untuk kategori default. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Mengatur nilai gamma untuk kategori tertentu. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Menonaktifkan penyesuaian warna untuk kategori default. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Mematikan penyesuaian warna untuk kategori tertentu. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Mengatur saluran keluaran CMYK (cyan-magenta-kuning-hitam) untuk kategori default. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Mengatur saluran keluaran CMYK (cyan-magenta-kuning-hitam) untuk kategori tertentu. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Mengatur file profil warna saluran keluaran untuk kategori default. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Mengatur file profil warna saluran keluaran untuk kategori tertentu. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Mengatur tabel remap warna untuk kategori default. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Mengatur tabel remap warna untuk kategori tertentu. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Menetapkan ambang batas (rentang transparansi) untuk kategori default. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Menetapkan ambang batas (rentang transparansi) untuk kategori tertentu. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Mengatur mode bungkus yang digunakan untuk menentukan cara menyusun tekstur melintasi bentuk, atau pada batas bentuk. Tekstur disusun pada bentuk untuk diisi ketika tekstur lebih kecil dari bentuk yang diisi. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Mengatur mode bungkus dan warna yang digunakan untuk menentukan cara menyusun tekstur melintasi bentuk, atau pada batas bentuk. Tekstur disusun pada bentuk untuk diisi ketika tekstur lebih kecil dari bentuk yang diisi. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Mengatur mode bungkus dan warna yang digunakan untuk menentukan cara menyusun tekstur melintasi bentuk, atau pada batas bentuk. Tekstur disusun pada bentuk untuk diisi ketika tekstur lebih kecil dari bentuk yang diisi. |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



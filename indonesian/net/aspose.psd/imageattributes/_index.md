---
title: "Kelas ImageAttributes"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageAttributes. Sebuah objek ImageAttributes berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama proses rendering. Sebuah objek ImageAttributes mempertahankan beberapa pengaturan penyesuaian warna termasuk matriks penyesuaian warna, matriks penyesuaian skala abu-abu, nilai koreksi gamma, tabel peta warna, dan nilai ambang warna. Selama rendering, warna dapat dikoreksi, diperdalam, diterangkan, dan dihapus. Untuk menerapkan manipulasi tersebut, inisialisasikan objek ImageAttributes dan berikan jalur objek ImageAttributes tersebut bersama dengan jalur sebuah Image ke metode DrawImage."
type: docs
weight: 5080
url: /id/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Sebuah objek `ImageAttributes` berisi informasi tentang bagaimana warna bitmap dan metafile dimanipulasi selama proses rendering. Sebuah objek `ImageAttributes` mempertahankan beberapa pengaturan penyesuaian warna, termasuk matriks penyesuaian warna, matriks penyesuaian skala abu-abu, nilai koreksi gamma, tabel peta warna, dan nilai ambang warna. Selama rendering, warna dapat dikoreksi, diperdalam, diterangkan, dan dihapus. Untuk menerapkan manipulasi tersebut, inisialisasikan objek `ImageAttributes` dan berikan jalur objek `ImageAttributes` tersebut (bersama dengan jalur sebuah [`Image`](../image/)) ke metode DrawImage.

```csharp
public sealed class ImageAttributes
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Membersihkan tabel pemetaan ulang warna kuas dari objek `ImageAttributes` ini. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Membersihkan kunci warna (rentang transparansi) untuk kategori default. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Membersihkan kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Membersihkan matriks penyesuaian warna untuk kategori default. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Membersihkan matriks penyesuaian warna untuk kategori yang ditentukan. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Menonaktifkan koreksi gamma untuk kategori default. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Menonaktifkan koreksi gamma untuk kategori yang ditentukan. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Membersihkan pengaturan NoOp untuk kategori default. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Membersihkan pengaturan NoOp untuk kategori yang ditentukan. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Membersihkan pengaturan saluran keluaran CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Membersihkan pengaturan saluran keluaran (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Membersihkan pengaturan profil warna saluran keluaran untuk kategori default. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Membersihkan pengaturan profil warna saluran keluaran untuk kategori yang ditentukan. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Membersihkan tabel pemetaan ulang warna untuk kategori default. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Membersihkan tabel pemetaan ulang warna untuk kategori yang ditentukan. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Menghapus nilai ambang untuk kategori default. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Menghapus nilai ambang untuk kategori yang ditentukan. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Menetapkan tabel pemetaan ulang warna untuk kategori kuas. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Menetapkan kunci warna untuk kategori default. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Menetapkan kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Menetapkan matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Menetapkan matriks penyesuaian warna untuk kategori default. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Menetapkan matriks penyesuaian warna untuk kategori default. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Menetapkan matriks penyesuaian warna untuk kategori yang ditentukan. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Menetapkan nilai gamma untuk kategori default. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Menetapkan nilai gamma untuk kategori yang ditentukan. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Menonaktifkan penyesuaian warna untuk kategori default. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Menonaktifkan penyesuaian warna untuk kategori yang ditentukan. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Menetapkan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Menetapkan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Menetapkan berkas profil warna saluran output untuk kategori default. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Menetapkan berkas profil warna saluran output untuk kategori yang ditentukan. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Menetapkan tabel pemetaan ulang warna untuk kategori default. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Menetapkan tabel pemetaan ulang warna untuk kategori yang ditentukan. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Menetapkan ambang (rentang transparansi) untuk kategori default. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Menetapkan ambang (rentang transparansi) untuk kategori yang ditentukan. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Menetapkan mode pembungkus yang digunakan untuk memutuskan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. Tekstur ditata di seluruh bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Menetapkan mode pembungkus dan warna yang digunakan untuk memutuskan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. Tekstur ditata di seluruh bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Menetapkan mode pembungkus dan warna yang digunakan untuk memutuskan cara menata tekstur di seluruh bentuk, atau pada batas bentuk. Tekstur ditata di seluruh bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Enum ResizeType
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ResizeType enum. Menentukan jenis pengubahan ukuran.
type: docs
weight: 5370
url: /id/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Menentukan jenis pengubahan ukuran.

```csharp
public enum ResizeType
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| None | `0` | Piksel tidak dipertahankan selama operasi pengubahan ukuran. |
| LeftTopToLeftTop | `1` | Titik kiri atas gambar baru akan bertepatan dengan titik kiri atas gambar asli. Pemotongan akan terjadi jika diperlukan. |
| RightTopToRightTop | `2` | Titik kanan atas gambar baru akan bertepatan dengan titik kanan atas gambar asli. Pemotongan akan terjadi jika diperlukan. |
| RightBottomToRightBottom | `3` | Titik kanan bawah gambar baru akan bertepatan dengan titik kanan bawah gambar asli. Pemotongan akan terjadi jika diperlukan. |
| LeftBottomToLeftBottom | `4` | Titik kiri bawah gambar baru akan bertepatan dengan titik kiri bawah gambar asli. Pemotongan akan terjadi jika diperlukan. |
| CenterToCenter | `5` | Bagian tengah gambar baru akan bertepatan dengan bagian tengah gambar asli. Pemotongan akan terjadi jika diperlukan. |
| LanczosResample | `6` | Resample menggunakan algoritme lanczos dengan a=3. |
| NearestNeighbourResample | `7` | Contoh ulang menggunakan algoritma tetangga terdekat. |
| AdaptiveResample | `8` | Sampel ulang menggunakan algoritme adaptif berdasarkan fungsi rasional berbobot dan campuran serta algoritme interpolasi lanczos3. |
| BilinearResample | `9` | Resample menggunakan interpolasi bilinear. Pra-penyaringan gambar diperbolehkan untuk menghapus noice sebelum sampel ulang, bila diperlukan |
| HighQualityResample | `10` | Contoh kualitas tinggi |
| CatmullRom | `11` | Metode interpolasi kubik Catmull-Rom. |
| CubicConvolution | `12` | Metode interpolasi Konvolusi Kubik |
| CubicBSpline | `13` | Metode interpolasi kubik CubicBSpline |
| Mitchell | `14` | Metode interpolasi kubik Mitchell |
| SinC | `15` | Metode interpolasi kubik Sinc (Lanczos3) |
| Bell | `16` | Metode interpolasi Bell |

### Contoh

Kode berikut menunjukkan cara mengubah ukuran gambar dengan jenis pengubah ukuran SinC yang baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe pengubah ukuran Bell yang baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan jenis pengubah ukuran Mitchell yang baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe pengubahan ukuran CatmullRom yang baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe pengubahan ukuran CubicBSpline baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe pengubahan ukuran CubicConvolution baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Memuat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



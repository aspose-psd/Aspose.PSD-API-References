---
title: "Enum ResizeType"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.ResizeType. Menentukan jenis pengubahan ukuran."
type: docs
weight: 5870
url: /id/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Menentukan jenis pengubahan ukuran.

```csharp
public enum ResizeType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Piksel tidak dipertahankan selama operasi pengubahan ukuran. |
| LeftTopToLeftTop | `1` | Titik kiri atas gambar baru akan bertepatan dengan titik kiri atas gambar asli. Pemotongan akan terjadi jika diperlukan. |
| RightTopToRightTop | `2` | Titik kanan atas gambar baru akan bertepatan dengan titik kanan atas gambar asli. Pemotongan akan terjadi jika diperlukan. |
| RightBottomToRightBottom | `3` | Titik kanan bawah gambar baru akan bertepatan dengan titik kanan bawah gambar asli. Pemotongan akan terjadi jika diperlukan. |
| LeftBottomToLeftBottom | `4` | Titik kiri bawah gambar baru akan bertepatan dengan titik kiri bawah gambar asli. Pemotongan akan terjadi jika diperlukan. |
| CenterToCenter | `5` | Bagian tengah gambar baru akan bertepatan dengan bagian tengah gambar asli. Pemotongan akan terjadi jika diperlukan. |
| LanczosResample | `6` | Sampling ulang menggunakan algoritma lanczos dengan a=3. |
| NearestNeighbourResample | `7` | Sampling ulang menggunakan algoritma tetangga terdekat. |
| AdaptiveResample | `8` | Sampling ulang menggunakan algoritma adaptif berbasis fungsi rasional berbobot dan tercampur serta algoritma interpolasi lanczos3. |
| BilinearResample | `9` | Sampling ulang menggunakan interpolasi bilinear. Pra-filter gambar diizinkan untuk menghilangkan noise sebelum sampling ulang, bila diperlukan. |
| HighQualityResample | `10` | Sampling ulang berkualitas tinggi |
| CatmullRom | `11` | Metode interpolasi kubik Catmull-Rom. |
| CubicConvolution | `12` | Metode interpolasi Cubic Convolution |
| CubicBSpline | `13` | Metode interpolasi kubik CubicBSpline |
| Mitchell | `14` | Metode interpolasi kubik Mitchell |
| SinC | `15` | Metode interpolasi kubik Sinc (Lanczos3) |
| Bell | `16` | Metode interpolasi Bell |

## Contoh

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe resize SinC baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe resize Bell baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe resize Mitchell baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe resize CatmullRom baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe resize CubicBSpline baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Kode berikut menunjukkan cara mengubah ukuran gambar dengan tipe resize CubicConvolution baru.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Muat gambar yang ada ke dalam instance kelas PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



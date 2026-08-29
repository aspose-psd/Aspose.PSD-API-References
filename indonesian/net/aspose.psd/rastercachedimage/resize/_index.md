---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RasterCachedImage. Mengubah ukuran gambar"
type: docs
weight: 120
url: /id/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Mengubah ukuran gambar.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| resizeType | ResizeType | Jenis pengubahan ukuran. |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Mengubah ukuran gambar.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| pengaturan | ImageResizeSettings | Pengaturan pengubahan ukuran. |

### Lihat Juga

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



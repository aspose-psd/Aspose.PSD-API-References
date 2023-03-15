---
title: RasterCachedImage.Resize
second_title: Aspose.PSD untuk Referensi .NET API
description: RasterCachedImage metode. Mengubah ukuran gambar.
type: docs
weight: 120
url: /id/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Mengubah ukuran gambar.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Ketinggian baru. |
| resizeType | ResizeType | Jenis pengubahan ukuran. |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* ruang nama [Aspose.PSD](../../rastercachedimage/)
* perakitan [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Mengubah ukuran gambar.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Ketinggian baru. |
| settings | ImageResizeSettings | Pengaturan pengubahan ukuran. |

### Lihat juga

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* ruang nama [Aspose.PSD](../../rastercachedimage/)
* perakitan [Aspose.PSD](../../../)



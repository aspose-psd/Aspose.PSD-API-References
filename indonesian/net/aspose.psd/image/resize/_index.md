---
title: Image.Resize
second_title: Aspose.PSD untuk Referensi .NET API
description: Image metode. Mengubah ukuran gambar.
type: docs
weight: 190
url: /id/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Mengubah ukuran gambar.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| resizeType | ResizeType | Jenis pengubahan ukuran. |

### Lihat juga

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Mengubah ukuran gambar. DefaultLeftTopToLeftTopdigunakan.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |

### Contoh

Contoh berikut menunjukkan bagaimana mengubah ukuran gambar PSD dan hasil yang kita dapatkan dengan Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat juga

* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Mengubah ukuran gambar.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Ketinggian baru. |
| settings | ImageResizeSettings | Pengaturan pengubahan ukuran. |

### Lihat juga

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)



---
title: "Image.Resize"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Image. Mengubah ukuran gambar"
type: docs
weight: 200
url: /id/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Mengubah ukuran gambar.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| resizeType | ResizeType | Jenis pengubahan ukuran. |

### Lihat Juga

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Mengubah ukuran gambar. NearestNeighbourResample default digunakan.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |

## Contoh

Contoh berikut menunjukkan cara mengubah ukuran gambar PSD dan hasil yang kita dapatkan dengan Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat Juga

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Mengubah ukuran gambar.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newWidth | Int32 | Lebar baru. |
| newHeight | Int32 | Tinggi baru. |
| pengaturan | ImageResizeSettings | Pengaturan pengubahan ukuran. |

### Lihat Juga

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



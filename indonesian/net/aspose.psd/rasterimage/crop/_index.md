---
title: RasterImage.Crop
second_title: Aspose.PSD untuk Referensi .NET API
description: RasterImage metode. Memotong persegi panjang yang ditentukan.
type: docs
weight: 240
url: /id/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Memotong persegi panjang yang ditentukan.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| rectangle | Rectangle | Persegi panjang. |

### Contoh

Contoh kode berikut menunjukkan cara memangkas gambar dan menyimpannya.

```csharp
[C#]

// Terapkan metode Pangkas yang benar untuk file PSD.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat juga

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* ruang nama [Aspose.PSD](../../rasterimage/)
* perakitan [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Pangkas gambar dengan shift.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| leftShift | Int32 | Pergeseran kiri. |
| rightShift | Int32 | Pergeseran yang tepat. |
| topShift | Int32 | Pergeseran atas. |
| bottomShift | Int32 | Pergeseran bawah. |

### Lihat juga

* class [RasterImage](../)
* ruang nama [Aspose.PSD](../../rasterimage/)
* perakitan [Aspose.PSD](../../../)



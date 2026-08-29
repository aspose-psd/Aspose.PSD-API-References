---
title: "RasterImage.Crop"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RasterImage. Memotong persegi panjang yang ditentukan"
type: docs
weight: 240
url: /id/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Memotong persegi panjang yang ditentukan.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| persegi panjang | Rectangle | Persegi panjang. |

## Contoh

Contoh kode berikut menunjukkan cara memotong gambar dan menyimpannya.

```csharp
[C#]

// Implementasikan metode Crop yang benar untuk file PSD.
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

### Lihat Juga

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Memotong gambar dengan pergeseran.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| leftShift | Int32 | Perpindahan ke kiri. |
| rightShift | Int32 | Perpindahan ke kanan. |
| topShift | Int32 | Perpindahan ke atas. |
| bottomShift | Int32 | Perpindahan ke bawah. |

### Lihat Juga

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



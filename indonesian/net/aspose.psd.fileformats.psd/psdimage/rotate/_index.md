---
title: PsdImage.Rotate
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdImage metode. Putar gambar di tengah.
type: docs
weight: 610
url: /id/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

Putar gambar di tengah.

```csharp
public override void Rotate(float angle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| angle | Single | Sudut putar dalam derajat. Nilai positif akan berputar searah jarum jam. |

### Contoh

Kode berikut menunjukkan kemampuan untuk memutar gambar dengan nilai sudut tertentu.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Seluruh gambar berputar
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Lapisan berputar
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Lihat juga

* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Putar gambar di tengah.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| angle | Single | Sudut putar dalam derajat. Nilai positif akan berputar searah jarum jam. |
| resizeProportionally | Boolean | jika diatur ke`BENAR` Anda akan mengubah ukuran gambar Anda sesuai dengan proyeksi persegi panjang (titik sudut) yang diputar dalam kasus lain yang membuat dimensi tidak tersentuh dan hanya konten gambar internal yang diputar. |
| backgroundColor | Color | Warna latar belakang. |

### Lihat juga

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)



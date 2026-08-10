---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode PsdImage. Memutar gambar di sekitar pusat"
type: docs
weight: 670
url: /id/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Memutar gambar di sekitar pusat.

```csharp
public override void Rotate(float angle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | Single | Sudut rotasi dalam derajat. Nilai positif akan memutar searah jarum jam. |

## Contoh

Kode berikut menunjukkan kemampuan memutar gambar dengan nilai sudut tertentu.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotasi seluruh gambar
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

// Rotasi lapisan
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

### Lihat Juga

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Memutar gambar di sekitar pusat.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | Single | Sudut rotasi dalam derajat. Nilai positif akan memutar searah jarum jam. |
| resizeProportionally | Boolean | jika disetel ke `true` ukuran gambar Anda akan berubah sesuai proyeksi persegi panjang yang diputar (titik sudut); dalam kasus lain dimensi tetap tidak berubah dan hanya konten gambar internal yang diputar. |
| backgroundColor | Warna | Warna latar belakang. |

### Lihat Juga

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)



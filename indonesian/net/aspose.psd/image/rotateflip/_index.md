---
title: "Image.RotateFlip"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Image. Memutar, membalik, atau memutar dan membalik gambar"
type: docs
weight: 230
url: /id/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Memutar, membalik, atau memutar dan membalik gambar.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Jenis rotasi flip. |

## Contoh

Contoh ini menunjukkan penggunaan operasi Rotate pada sebuah gambar. Contoh memuat file gambar yang ada dari lokasi disk tertentu dan melakukan operasi Rotate pada gambar sesuai nilai Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Buat sebuah instance dari kelas image dan inisialisasi dengan file gambar yang ada melalui jalur File
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Putar gambar sebesar 180 derajat tentang sumbu X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // simpan semua perubahan.
    image.Save();
}
```

### Lihat Juga

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



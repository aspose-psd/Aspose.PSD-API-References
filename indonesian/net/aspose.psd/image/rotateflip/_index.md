---
title: Image.RotateFlip
second_title: Aspose.PSD untuk Referensi .NET API
description: Image metode. Memutar membalik atau memutar dan membalik gambar.
type: docs
weight: 220
url: /id/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Memutar, membalik, atau memutar dan membalik gambar.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Jenis flip putar. |

### Contoh

Contoh ini mendemonstrasikan penggunaan operasi Putar pada gambar. Contoh memuat file gambar yang ada dari beberapa lokasi disk dan melakukan operasi Putar pada gambar sesuai dengan nilai Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Buat instance kelas gambar dan inisialisasi dengan file gambar yang ada melalui jalur File
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Putar gambar 180 derajat terhadap sumbu X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // simpan semua perubahan.
    image.Save();
}
```

### Lihat juga

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)



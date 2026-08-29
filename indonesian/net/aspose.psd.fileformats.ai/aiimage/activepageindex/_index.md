---
title: "AiImage.ActivePageIndex"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti AiImage. Mendapatkan atau mengatur indeks halaman aktif"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Mendapatkan atau mengatur indeks halaman aktif.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Properti ini hanya berlaku untuk gambar AI berformat PDF. Jika gambar tidak berformat PDF atau tidak ada halaman, properti akan bernilai -1. Properti ini menunjukkan halaman mana dari gambar AI yang akan menjadi dasar untuk rendering.

## Contoh

Kode berikut menunjukkan dukungan kemampuan mengubah halaman aktif pada gambar Ai.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Muat gambar AI.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // Secara default, ActivePageIndex adalah 0.
    // Jadi jika Anda menyimpan gambar AI tanpa mengubah properti ini, halaman pertama akan dirender dan disimpan.
    image.Save(firstPageOutputPng, new PngOptions());

    // Ubah indeks halaman aktif ke halaman kedua.
    image.ActivePageIndex = 1;

    // Simpan halaman kedua gambar AI sebagai gambar PNG.
    image.Save(secondPageOutputPng, new PngOptions());

    // Ubah indeks halaman aktif ke halaman ketiga.
    image.ActivePageIndex = 2;

    // Simpan halaman ketiga gambar AI sebagai gambar PNG.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### Lihat Juga

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)



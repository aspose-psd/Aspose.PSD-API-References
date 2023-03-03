---
title: Image.Create
second_title: Aspose.PSD untuk Referensi .NET API
description: Image metode. Membuat gambar baru menggunakan opsi buat yang ditentukan.
type: docs
weight: 10
url: /id/net/aspose.psd/image/create/
---
## Image.Create method

Membuat gambar baru menggunakan opsi buat yang ditentukan.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Pilihan gambar. |
| width | Int32 | Lebar. |
| height | Int32 | Tinggi. |

### Nilai Pengembalian

Gambar yang baru dibuat.

### Contoh

Contoh ini membuat file Gambar baru di beberapa lokasi disk seperti yang ditentukan oleh properti Sumber dari instance PsdOptions. Beberapa properti untuk instance PsdOptions diatur sebelum membuat gambar sebenarnya. Terutama properti Sumber, yang mengacu pada lokasi disk sebenarnya dalam kasus ini.

```csharp
[C#]

//Buat instance PsdOptions dan atur berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat turunan FileCreateSource dan tetapkan sebagai Sumber untuk turunan PsdOptions
//Parameter Boolean kedua menentukan apakah file yang akan dibuat IsTemporal atau tidak
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Buat instance Image dan inisialisasi dengan instance PsdOptions dengan memanggil metode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //melakukan beberapa pemrosesan gambar

    // simpan semua perubahan
    image.Save();
}
```

### Lihat juga

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)



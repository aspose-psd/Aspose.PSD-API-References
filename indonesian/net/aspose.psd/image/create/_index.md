---
title: "Image.Create"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Image. Membuat gambar baru menggunakan opsi pembuatan yang ditentukan"
type: docs
weight: 10
url: /id/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Membuat gambar baru menggunakan opsi pembuatan yang ditentukan.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Opsi gambar. |
| lebar | Int32 | Lebar. |
| tinggi | Int32 | Tinggi. |

### Nilai Kembalian

Gambar yang baru dibuat.

## Contoh

Contoh ini membuat file Image baru di lokasi disk tertentu sebagaimana ditentukan oleh properti Source dari instance PsdOptions. Beberapa properti untuk instance PsdOptions diatur sebelum membuat gambar sebenarnya. Khususnya properti Source, yang merujuk ke lokasi disk aktual dalam kasus ini.

```csharp
[C#]

//Buat sebuah instance dari PsdOptions dan atur berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat sebuah instance dari FileCreateSource dan tetapkan sebagai Source untuk instance PsdOptions
//Parameter Boolean kedua menentukan apakah file yang akan dibuat bersifat IsTemporal atau tidak
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Buat sebuah instance dari Image dan inisialisasi dengan instance PsdOptions dengan memanggil metode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //lakukan beberapa pemrosesan gambar

    // simpan semua perubahan
    image.Save();
}
```

### Lihat Juga

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



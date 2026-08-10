---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "FileCreateSource constructor. Menginisialisasi instance baru dari kelas FileCreateSource"
type: docs
weight: 10
url: /id/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Menginisialisasi instance baru dari kelas [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk dibuat. |

## Contoh

Contoh ini membuat file Image baru di lokasi disk tertentu sebagaimana ditentukan oleh properti Source dari instance BmpOptions. Jika parameter kedua tidak diberikan ke konstruktor FileCreateSource, maka secara default file yang akan dibuat memiliki properti IsTemporal disetel ke True. Dengan IsTemporal disetel ke True, tidak ada file yang akan disimpan di disk pada akhir eksekusi.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Membuat instance PsdOptions dan mengatur berbagai propertinya.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat sebuah instance dari FileCreateSource dan tetapkan sebagai Source untuk instance PsdOptions
//Jika parameter kedua tidak diberikan, maka secara default file memiliki IsTemporal disetel ke True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Membuat instance dari Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //lakukan beberapa pemrosesan gambar
}
```

### Lihat Juga

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Menginisialisasi instance baru dari kelas [`FileCreateSource`](../).

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk dibuat. |
| isTemporal | Boolean | Jika disetel ke `true` file yang dibuat akan bersifat temporal. |

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

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)



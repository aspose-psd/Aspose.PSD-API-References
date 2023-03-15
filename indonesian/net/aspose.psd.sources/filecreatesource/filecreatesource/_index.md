---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD untuk Referensi .NET API
description: FileCreateSource konstruktor. Menginisialisasi instance baru dariFileCreateSource kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Menginisialisasi instance baru dari[`FileCreateSource`](../) kelas.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file yang akan dibuat. |

### Contoh

Contoh ini membuat file Gambar baru di beberapa lokasi disk seperti yang ditentukan oleh properti Sumber dari instance BmpOptions. Jika parameter kedua tidak diteruskan ke konstruktor FileCreateSource, maka secara default file yang akan dibuat memiliki properti IsTemporal yang disetel ke True. Dengan IsTemporal disetel ke True, tidak ada file yang akan disimpan di disk pada akhir eksekusi.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Membuat turunan dari PsdOptions dan menyetel berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat turunan FileCreateSource dan tetapkan sebagai Sumber untuk turunan PsdOptions
//Jika parameter kedua tidak diteruskan, maka secara default file IsTemporal disetel ke True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

// Membuat instance dari Gambar 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //melakukan beberapa pemrosesan gambar
}
```

### Lihat juga

* class [FileCreateSource](../)
* ruang nama [Aspose.PSD.Sources](../../filecreatesource/)
* perakitan [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Menginisialisasi instance baru dari[`FileCreateSource`](../) kelas.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file yang akan dibuat. |
| isTemporal | Boolean | Jika disetel ke`BENAR` file yang dibuat akan bersifat sementara. |

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

* class [FileCreateSource](../)
* ruang nama [Aspose.PSD.Sources](../../filecreatesource/)
* perakitan [Aspose.PSD](../../../)



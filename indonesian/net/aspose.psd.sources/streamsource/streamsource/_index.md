---
title: StreamSource.StreamSource
second_title: Aspose.PSD untuk Referensi .NET API
description: StreamSource konstruktor. Menginisialisasi instance baru dariStreamSource kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Menginisialisasi instance baru dari[`StreamSource`](../) kelas.

```csharp
public StreamSource(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran untuk membuka. |

### Contoh

Contoh ini menunjukkan cara Memuat informasi Piksel dalam Larik Berjenis Warna, memanipulasi larik, dan mengaturnya kembali ke gambar. Untuk melakukan operasi ini, contoh ini membuat file Gambar baru (dalam format PSD) menggunakan objek MemoryStream.

```csharp
[C#]

//Buat instance dari MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Buat instance PsdOptions dan atur berbagai propertinya termasuk properti Sumber
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Buat instance dari Gambar
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // Dapatkan piksel gambar dengan menentukan area sebagai batas gambar
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // Ulangi Array dan atur warna piksel terindeks alrenatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Atur warna piksel yang diindeks menjadi kuning
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Atur warna piksel yang diindeks menjadi biru
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Terapkan perubahan piksel pada gambar
        image.SavePixels(image.Bounds, pixels);

        // simpan semua perubahan.
        image.Save();
    }

    // Tulis MemoryStream ke File
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Lihat juga

* class [StreamSource](../)
* ruang nama [Aspose.PSD.Sources](../../streamsource/)
* perakitan [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Menginisialisasi instance baru dari[`StreamSource`](../) kelas.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran untuk membuka. |
| disposeStream | Boolean | jika diatur ke`BENAR` sungai akan dibuang. |

### Contoh

Contoh ini menunjukkan penggunaan System.IO.Stream untuk Membuat file Gambar baru

```csharp
[C#]

//Membuat turunan dari PsdOptions dan menyetel berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat instance System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Tentukan properti sumber untuk instance PsdOptions
// Parameter boolean kedua menentukan apakah Stream dibuang setelah keluar dari ruang lingkup
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Membuat instance Image dan memanggil metode Create dengan PsdOptions sebagai parameter untuk menginisialisasi objek Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //melakukan beberapa pemrosesan gambar
}
```

### Lihat juga

* class [StreamSource](../)
* ruang nama [Aspose.PSD.Sources](../../streamsource/)
* perakitan [Aspose.PSD](../../../)



---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor StreamSource. Menginisialisasi instance baru dari kelas StreamSource"
type: docs
weight: 10
url: /id/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

Menginisialisasi instance baru dari kelas [`StreamSource`](../).

```csharp
public StreamSource(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran yang akan dibuka. |

## Contoh

Contoh ini menunjukkan cara memuat informasi Piksel dalam Array bertipe Color, memanipulasi array tersebut, dan mengembalikannya ke gambar. Untuk melakukan operasi ini, contoh ini membuat file Image baru (dalam format PSD) menggunakan objek MemoryStream.

```csharp
[C#]

//Buat sebuah instance dari MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Buat sebuah instance dari PsdOptions dan atur berbagai propertinya termasuk properti Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Buat sebuah instance dari Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Dapatkan piksel gambar dengan menentukan area sebagai batas gambar
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Iterasi array dan atur warna piksel terindeks alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Atur warna piksel terindeks menjadi kuning
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Atur warna piksel terindeks menjadi biru
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Terapkan perubahan piksel ke gambar
        image.SavePixels(image.Bounds, pixels);

        // simpan semua perubahan.
        image.Save();
    }

    //Tulis MemoryStream ke File
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Lihat Juga

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Menginisialisasi instance baru dari kelas [`StreamSource`](../).

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran yang akan dibuka. |
| disposeStream | Boolean | Jika disetel ke `true` aliran akan dibuang. |

## Contoh

Contoh ini menunjukkan penggunaan System.IO.Stream untuk Membuat file Image baru.

```csharp
[C#]

//Membuat instance PsdOptions dan mengatur berbagai propertinya.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat instance System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Tentukan properti sumber untuk instance PsdOptions.
//Parameter boolean kedua menentukan apakah Stream dibuang setelah keluar dari ruang lingkup.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Membuat instance Image dan memanggil metode Create dengan PsdOptions sebagai parameter untuk menginisialisasi objek Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //lakukan beberapa pemrosesan gambar
}
```

### Lihat Juga

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)



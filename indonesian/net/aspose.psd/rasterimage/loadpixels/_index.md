---
title: "RasterImage.LoadPixels"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RasterImage. Memuat piksel"
type: docs
weight: 410
url: /id/net/aspose.psd/rasterimage/loadpixels/
---
{{< psd/tize >}}
## RasterImage.LoadPixels method

Memuat piksel.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| persegi panjang | Rectangle | Persegi panjang untuk memuat piksel. |

### Nilai Kembalian

Array piksel yang dimuat.

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

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



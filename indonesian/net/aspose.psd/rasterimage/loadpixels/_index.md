---
title: RasterImage.LoadPixels
second_title: Aspose.PSD untuk Referensi .NET API
description: RasterImage metode. Memuat piksel.
type: docs
weight: 400
url: /id/net/aspose.psd/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

Memuat piksel.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| rectangle | Rectangle | Persegi panjang untuk memuat piksel. |

### Nilai Pengembalian

Array piksel yang dimuat.

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

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* ruang nama [Aspose.PSD](../../rasterimage/)
* perakitan [Aspose.PSD](../../../)



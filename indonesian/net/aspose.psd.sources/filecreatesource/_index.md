---
title: Class FileCreateSource
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Sources.FileCreateSource kelas. Merupakan sumber file untuk pembuatan.
type: docs
weight: 5590
url: /id/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Merupakan sumber file untuk pembuatan.

```csharp
public sealed class FileCreateSource : FileSource
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Menginisialisasi instance baru dari`FileCreateSource` kelas. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Menginisialisasi instance baru dari`FileCreateSource` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Mendapatkan jalur file untuk dibuat. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Mendapat nilai yang menunjukkan apakah file akan temporal. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Mendapatkan wadah aliran. |

### Contoh

Contoh ini mendemonstrasikan penggunaan kelas Font dan SolidBrush untuk menggambar string pada permukaan Gambar. Contoh membuat Gambar baru dan menggambar bentuk menggunakan Figures dan GraphicsPath

```csharp
[C#]

// Membuat instance dari Gambar
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Grafik
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Membersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Membuat turunan dari Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Buat instance SolidBrush yang memiliki Warna Merah
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Gambar sebuah String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // buat opsi ekspor.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // simpan semua perubahan
    image.Save("C:\\temp\\output.gif", options);
}
```

### Lihat juga

* class [FileSource](../filesource/)
* ruang nama [Aspose.PSD.Sources](../../aspose.psd.sources/)
* perakitan [Aspose.PSD](../../)



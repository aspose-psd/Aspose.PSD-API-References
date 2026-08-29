---
title: "Kelas FileCreateSource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Sources.FileCreateSource. Mewakili sumber file untuk pembuatan"
type: docs
weight: 6090
url: /id/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Mewakili sumber file untuk pembuatan.

```csharp
public sealed class FileCreateSource : FileSource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Menginisialisasi instance baru dari kelas `FileCreateSource`. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Menginisialisasi instance baru dari kelas `FileCreateSource`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Mendapatkan jalur file untuk dibuat. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Mendapatkan nilai yang menunjukkan apakah file akan bersifat temporer. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Mendapatkan kontainer aliran. |

## Contoh

Contoh ini menunjukkan penggunaan kelas Font dan SolidBrush untuk menggambar string pada permukaan Image. Contoh ini membuat Image baru dan menggambar bentuk menggunakan Figures dan GraphicsPath

```csharp
[C#]

//Membuat instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Membersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Membuat instance dari Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Membuat instance SolidBrush dengan Warna Merah
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Menggambar String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // membuat opsi ekspor.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // simpan semua perubahan
    image.Save("C:\\temp\\output.gif", options);
}
```

### Lihat Juga

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)



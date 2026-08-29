---
title: "Kelas HatchBrush"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.HatchBrush. Mendefinisikan brush persegi panjang dengan gaya hatch, warna latar depan, dan warna latar belakang. Kelas ini tidak dapat diwariskan"
type: docs
weight: 130
url: /id/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Mendefinisikan kuas persegi panjang dengan gaya hatch, warna latar depan, dan warna latar belakang. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class HatchBrush : Brush
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Mendapatkan atau mengatur warna ruang di antara garis hatch. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Mendapatkan atau mengatur warna garis hatch. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Mendapatkan atau mengatur gaya hatch dari brush ini. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari [`Brush`](../../aspose.psd/brush/) saat ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

## Contoh

Contoh ini menunjukkan pembuatan dan penggunaan objek Pen. Contoh ini membuat Image baru dan menggambar Rectangles pada permukaan Image.

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat sebuah instance dari Graphics dan inisialisasi dengan objek Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics dengan Warna Putih
    graphics.Clear(Aspose.PSD.Color.White);

    //Buat sebuah instance dari Pen dengan warna Merah dan lebar 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Buat sebuah instance dari HatchBrush dan atur propertinya
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Buat sebuah instance dari Pen
    //inisialisasi dengan objek HatchBrush dan lebar
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Gambar Rectangles dengan menentukan objek Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Gambar Rectangles dengan menentukan objek Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Buat opsi ekspor dan inisialisasi mereka.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // simpan semua perubahan.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Lihat Juga

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



---
title: Class SolidBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.SolidBrush kelas. Kuas padat dimaksudkan untuk menggambar terus menerus dengan warna tertentu. Kelas ini tidak dapat diwariskan.
type: docs
weight: 200
url: /id/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

Kuas padat dimaksudkan untuk menggambar terus menerus dengan warna tertentu. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class SolidBrush : Brush
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Menginisialisasi instance baru dari`SolidBrush` kelas. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Menginisialisasi instance baru dari`SolidBrush` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Mendapat atau mengatur warna kuas. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari arus[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

### Contoh

Contoh ini menggunakan kelas Grafik untuk membuat bentuk primitif pada permukaan Gambar. Untuk mendemonstrasikan operasi, contoh membuat Gambar baru dalam format PSD dan menggambar bentuk primitif pada permukaan Gambar menggunakan metode Gambar yang diekspos oleh kelas Grafik lalu mengekspornya ke format file PSD.

```csharp
[C#]

//Buat instance dari Gambar 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Bersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Gambar Arc dengan menentukan objek Pena berwarna Hitam, 
    //Sebuah Persegi Panjang yang mengelilingi Lengkungan, Sudut Mulai, dan Sudut Sapuan
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Gambar Bezier dengan menentukan objek Pen yang memiliki warna Biru dan titik koordinat.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // Gambar Kurva dengan menentukan objek Pena yang memiliki warna Hijau dan larik Poin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Gambar Ellipse menggunakan objek Pen dan Rectangle di sekelilingnya
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Menarik garis 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Gambar segmen Pai
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // Gambar Poligon dengan menentukan objek Pena yang memiliki warna Merah dan larik Poin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Gambar Persegi Panjang
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Buat objek SolidBrush dan atur berbagai propertinya
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Gambar sebuah String menggunakan objek SolidBrush dan Font, pada Titik tertentu
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Buat instance PngOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Lihat juga

* class [Brush](../../aspose.psd/brush/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)



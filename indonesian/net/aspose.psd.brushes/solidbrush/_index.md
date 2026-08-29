---
title: "Kelas SolidBrush"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Brushes.SolidBrush. Solid brush dimaksudkan untuk menggambar secara terus-menerus dengan warna tertentu. Kelas ini tidak dapat diwariskan"
type: docs
weight: 200
url: /id/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Kuas solid dimaksudkan untuk menggambar secara berkelanjutan dengan warna tertentu. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class SolidBrush : Brush
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `SolidBrush`. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Menginisialisasi sebuah instance baru dari kelas `SolidBrush`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Mendapatkan atau mengatur warna kuas. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari [`Brush`](../../aspose.psd/brush/) saat ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

## Contoh

Contoh ini menggunakan kelas Graphics untuk membuat bentuk primitif pada permukaan Image. Untuk mendemonstrasikan operasi, contoh ini membuat Image baru dalam format PSD dan menggambar bentuk primitif pada permukaan Image menggunakan metode Draw yang disediakan oleh kelas Graphics, kemudian mengekspornya ke format file PSD.

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat dan inisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Gambar sebuah Arc dengan menentukan objek Pen yang berwarna Hitam, 
    //sebuah Rectangle yang mengelilingi Arc, Sudut Mulai, dan Sudut Penyapuan
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Gambar sebuah Bezier dengan menentukan objek Pen yang berwarna Biru dan Titik koordinat.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Gambar sebuah Curve dengan menentukan objek Pen yang berwarna Hijau dan sebuah array Titik
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Gambar sebuah Ellipse menggunakan objek Pen dan Rectangle yang mengelilinginya
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Gambar sebuah Garis 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Gambar sebuah segmen Pie
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Gambar sebuah Polygon dengan menentukan objek Pen yang berwarna Merah dan sebuah array Titik
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Gambar sebuah Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Buat objek SolidBrush dan atur berbagai propertinya
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Gambar sebuah String menggunakan objek SolidBrush dan Font, pada Point tertentu
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Buat sebuah instance dari PngOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Lihat Juga

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



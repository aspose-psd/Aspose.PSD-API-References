---
title: Class EllipseShape
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Shapes.EllipseShape kelas. Merupakan bentuk elips.
type: docs
weight: 5490
url: /id/net/aspose.psd.shapes/ellipseshape/
---
## EllipseShape class

Merupakan bentuk elips.

```csharp
public class EllipseShape : RectangleShape
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | Menginisialisasi instance baru dari`EllipseShape` kelas. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | Menginisialisasi instance baru dari`EllipseShape` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Mendapat batas objek. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Mendapatkan pusat bentuk. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Mendapat nilai yang menunjukkan apakah bentuk memiliki segmen. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Mendapat titik persegi panjang kiri bawah. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Mendapat titik persegi panjang kiri atas. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Mendapatkan tinggi persegi panjang. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Mendapatkan lebar persegi panjang. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Mendapat titik persegi panjang kanan bawah. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Mendapat titik persegi panjang kanan atas. |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | Mendapatkan segmen bentuk. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Mendapat batas objek. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Mendapat batas objek. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |

### Contoh

Contoh ini membuat Image baru dan menggambar berbagai bentuk menggunakan Figures dan GraphicsPath pada permukaan Image

```csharp
[C#]

//Buat instance dari Gambar
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Bersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Buat instance dari kelas GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Buat turunan dari kelas Gambar
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Tambahkan Bentuk ke objek Gambar
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Buat turunan dari kelas Gambar
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Tambahkan Bentuk ke objek Gambar
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    // Tambahkan objek Gambar ke GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Gambar jalur dengan objek Pena berwarna Hitam
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Buat opsi ekspor dan inisialisasi.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // simpan semua perubahan.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Lihat juga

* class [RectangleShape](../rectangleshape/)
* ruang nama [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* perakitan [Aspose.PSD](../../)



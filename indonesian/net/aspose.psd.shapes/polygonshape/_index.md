---
title: Class PolygonShape
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Shapes.PolygonShape kelas. Merupakan bentuk poligon.
type: docs
weight: 5510
url: /id/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

Merupakan bentuk poligon.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Menginisialisasi instance baru dari`PolygonShape` kelas. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Menginisialisasi instance baru dari`PolygonShape` kelas. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Menginisialisasi instance baru dari`PolygonShape` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Mendapat batas objek. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Mendapatkan pusat bentuk. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Mendapatkan titik bentuk akhir. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Mendapat nilai yang menunjukkan apakah bentuk memiliki segmen. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah bentuk tertutup. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Mendapat atau menetapkan titik kurva. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Mendapatkan segmen bentuk. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Mendapatkan titik bentuk awal. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Mendapat batas objek. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Mendapat batas objek. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Membalik urutan poin untuk bentuk ini. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* ruang nama [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* perakitan [Aspose.PSD](../../)



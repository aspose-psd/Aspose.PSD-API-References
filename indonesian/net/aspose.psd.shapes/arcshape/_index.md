---
title: "Kelas ArcShape"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Shapes.ArcShape. Mewakili bentuk busur"
type: docs
weight: 5960
url: /id/net/aspose.psd.shapes/arcshape/
---
{{< psd/tize >}}
## ArcShape class

Mewakili bentuk busur.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | Menginisialisasi instance baru dari kelas `ArcShape`. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | Menginisialisasi instance baru dari kelas `ArcShape`. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | Menginisialisasi instance baru dari kelas `ArcShape`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Mendapatkan batas objek. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Mendapatkan pusat bentuk. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | Mendapatkan titik akhir bentuk. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk terurut ditutup. Saat memproses bentuk terurut yang ditutup, titik awal dan akhir tidak memiliki arti. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Mendapatkan titik kiri bawah persegi panjang. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Mendapatkan titik kiri atas persegi panjang. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Mendapatkan tinggi persegi panjang. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Mendapatkan lebar persegi panjang. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Mendapatkan titik kanan bawah persegi panjang. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Mendapatkan titik kanan atas persegi panjang. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | Mendapatkan segmen bentuk. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Mendapatkan atau mengatur sudut awal. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | Mendapatkan titik awal bentuk. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Mendapatkan atau mengatur sudut sapuan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | Mendapatkan batas objek. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | Mendapatkan batas objek. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | Membalik urutan titik untuk bentuk ini. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |

## Contoh

Contoh ini membuat Image baru dan menggambar berbagai bentuk menggunakan Figures dan GraphicsPath pada permukaan Image

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat dan inisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Buat sebuah instance dari kelas GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Buat sebuah instance dari kelas Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Tambahkan Shape ke objek Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Buat sebuah instance dari kelas Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Tambahkan Shape ke objek Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Tambahkan objek Figure ke GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Gambar jalur dengan objek Pen berwarna Hitam
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Buat opsi ekspor dan inisialisasi mereka.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // simpan semua perubahan.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Lihat Juga

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



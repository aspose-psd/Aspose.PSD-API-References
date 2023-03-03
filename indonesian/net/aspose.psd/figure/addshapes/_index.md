---
title: Figure.AddShapes
second_title: Aspose.PSD untuk Referensi .NET API
description: Figure metode. Menambahkan rentang bentuk ke gambar.
type: docs
weight: 70
url: /id/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

Menambahkan rentang bentuk ke gambar.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| shapes | Shape[] | Bentuk untuk ditambahkan. |

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

* class [Shape](../../shape/)
* class [Figure](../)
* ruang nama [Aspose.PSD](../../figure/)
* perakitan [Aspose.PSD](../../../)



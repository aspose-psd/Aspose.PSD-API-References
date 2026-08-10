---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode GraphicsPath. Menambahkan figur baru"
type: docs
weight: 60
url: /id/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

Menambahkan figur-figur baru.

```csharp
public void AddFigures(Figure[] figures)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figur | Figure[] | Figur-figur yang akan ditambahkan. |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



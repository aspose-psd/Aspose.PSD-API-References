---
title: Figure.AddShape
second_title: Aspose.PSD untuk Referensi .NET API
description: Figure metode. Menambahkan bentuk ke gambar.
type: docs
weight: 60
url: /id/net/aspose.psd/figure/addshape/
---
## Figure.AddShape method

Menambahkan bentuk ke gambar.

```csharp
public void AddShape(Shape shape)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| shape | Shape | Bentuk untuk ditambahkan. |

### Contoh

Contoh ini menggunakan kelas GraphicsPath dan Graphics untuk membuat dan memanipulasi Angka pada permukaan Gambar. Contoh membuat Gambar baru dan menggambar jalur dengan bantuan kelas GraphicsPath. Pada akhirnya metode DrawPath yang diekspos oleh kelas Graphics dipanggil untuk merender jalur di permukaan. Akhirnya gambar diekspor ke format file Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Tambahkan Bentuk ke objek Figur
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // Tambahkan objek Gambar ke GraphicsPath
    graphicspath.AddFigure(figure);

    // Gambar jalur dengan objek Pena berwarna Hitam
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Buat instance TiffOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Lihat juga

* class [Shape](../../shape/)
* class [Figure](../)
* ruang nama [Aspose.PSD](../../figure/)
* perakitan [Aspose.PSD](../../../)



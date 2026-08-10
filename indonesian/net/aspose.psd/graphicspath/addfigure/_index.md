---
title: "GraphicsPath.AddFigure"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode GraphicsPath. Menambahkan sebuah figur baru"
type: docs
weight: 50
url: /id/net/aspose.psd/graphicspath/addfigure/
---
{{< psd/tize >}}
## GraphicsPath.AddFigure method

Menambahkan sebuah figur baru.

```csharp
public void AddFigure(Figure figure)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | Gambar | Figur yang akan ditambahkan. |

## Contoh

Contoh ini menggunakan kelas GraphicsPath dan Graphics untuk membuat dan memanipulasi Figure pada permukaan Image. Contoh membuat Image baru dan menggambar jalur dengan bantuan kelas GraphicsPath. Pada akhirnya metode DrawPath yang disediakan oleh kelas Graphics dipanggil untuk merender jalur pada permukaan. Akhirnya image diekspor ke format file Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Tambahkan Shape ke objek Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Tambahkan objek Figure ke GraphicsPath
    graphicspath.AddFigure(figure);

    //Gambar jalur dengan objek Pen berwarna Hitam
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Buat sebuah instance dari TiffOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Lihat Juga

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



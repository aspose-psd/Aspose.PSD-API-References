---
title: "Kelas Figure"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Figure. Figure. Sebuah kontainer untuk bentuk."
type: docs
weight: 1210
url: /id/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

Gambar. Kontainer untuk bentuk.

```csharp
public class Figure : ObjectWithBounds
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Figure](figure/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Mendapatkan atau mengatur batas objek. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah figure ini tertutup. Figure yang tertutup hanya akan berpengaruh bila bentuk pertama dan terakhir dari figure merupakan bentuk kontinu. Dalam kasus tersebut, titik pertama dari bentuk pertama akan dihubungkan dengan garis lurus dari titik terakhir bentuk terakhir. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Mendapatkan semua segmen figure. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Mendapatkan bentuk-bentuk figure. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Menambahkan bentuk ke figure. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Menambahkan rentang bentuk ke gambar. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Mendapatkan batas objek. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Mendapatkan batas objek. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Menghapus satu bentuk dari gambar. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Menghapus rentang bentuk dari gambar. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Membalik urutan bentuk pada gambar ini serta urutan titik bentuk. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



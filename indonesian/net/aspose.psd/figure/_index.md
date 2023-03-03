---
title: Class Figure
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Figure kelas. Angka. Wadah untuk shape.
type: docs
weight: 1200
url: /id/net/aspose.psd/figure/
---
## Figure class

Angka. Wadah untuk shape.

```csharp
public class Figure : ObjectWithBounds
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Figure](figure/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Mendapat atau menyetel batas objek. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah angka ini ditutup. Gambar tertutup akan membuat perbedaan hanya jika bentuk gambar pertama dan terakhir adalah bentuk kontinu. Dalam kasus seperti itu, titik pertama bentuk pertama akan dihubungkan dengan garis lurus dari titik terakhir bentuk terakhir. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Mendapat seluruh segmen gambar. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Mendapatkan bentuk figur. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Menambahkan bentuk ke gambar. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Menambahkan rentang bentuk ke gambar. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Mendapat batas objek. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Mendapat batas objek. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Menghapus bentuk dari gambar. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Menghapus rentang bentuk dari gambar. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Membalik urutan bentuk gambar ini dan urutan titik bentuk. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



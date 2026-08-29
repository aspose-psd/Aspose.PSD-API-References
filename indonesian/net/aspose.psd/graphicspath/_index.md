---
title: "Kelas GraphicsPath"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.GraphicsPath. Mewakili serangkaian garis dan kurva yang terhubung. Kelas ini tidak dapat diwariskan."
type: docs
weight: 4790
url: /id/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Mewakili serangkaian garis dan kurva yang terhubung. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Menginisialisasi instance baru dari kelas `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Menginisialisasi instance baru dari kelas `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Menginisialisasi instance baru dari kelas `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Menginisialisasi instance baru dari kelas `GraphicsPath`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Mendapatkan atau mengatur batas objek. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Mengambil figur jalur. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Mendapatkan atau mengatur enumerasi [`FillMode`](../fillmode/) yang menentukan bagaimana interior bentuk dalam `GraphicsPath` ini diisi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Menambahkan sebuah figur baru. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Menambahkan figur-figur baru. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Menambahkan `GraphicsPath` yang ditentukan ke jalur ini. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Menambahkan `GraphicsPath` yang ditentukan ke jalur ini. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Melakukan kloning mendalam dari jalur grafis ini. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Mengonversi setiap kurva dalam jalur ini menjadi urutan segmen garis yang terhubung. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Menerapkan transformasi yang ditentukan, lalu mengonversi setiap kurva dalam `GraphicsPath` ini menjadi urutan segmen garis yang terhubung. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Mengonversi setiap kurva dalam `GraphicsPath` ini menjadi urutan segmen garis yang terhubung. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Mendapatkan batas objek. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Mendapatkan batas objek. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan dan menggunakan [`Graphics`](../graphics/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan dan menggunakan [`Graphics`](../graphics/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan dan menggunakan [`Graphics`](../graphics/) yang ditentukan. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur `GraphicsPath` ini ketika digambar dengan [`Pen`](../pen/) yang ditentukan dan menggunakan [`Graphics`](../graphics/) yang ditentukan. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini dalam wilayah klip yang terlihat dari [`Graphics`](../graphics/) yang ditentukan. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Menunjukkan apakah titik yang ditentukan berada di dalam `GraphicsPath` ini, menggunakan [`Graphics`](../graphics/) yang ditentukan. |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Menghapus sebuah figur. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Menghapus figur-figur. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Mengosongkan jalur grafis dan mengatur [`FillMode`](../fillmode/) ke Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Membalik urutan figur, bentuk, dan titik dalam setiap bentuk pada `GraphicsPath` ini. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke `GraphicsPath` ini. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke `GraphicsPath` ini. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke `GraphicsPath` ini. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke `GraphicsPath` ini. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Menambahkan kontur tambahan ke jalur. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Menambahkan kontur tambahan ke `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Mengganti `GraphicsPath` ini dengan kurva yang melingkupi area yang diisi ketika jalur ini digambar oleh pen yang ditentukan. |

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



---
title: Class GraphicsPath
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.GraphicsPath kelas. Merupakan rangkaian garis dan kurva yang terhubung. Kelas ini tidak dapat diwariskan.
type: docs
weight: 4320
url: /id/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Merupakan rangkaian garis dan kurva yang terhubung. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Menginisialisasi instance baru dari`GraphicsPath` kelas. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Menginisialisasi instance baru dari`GraphicsPath` kelas. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Menginisialisasi instance baru dari`GraphicsPath` kelas. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Menginisialisasi instance baru dari`GraphicsPath` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Mendapat atau menyetel batas objek. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Mendapat angka path. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Mendapat atau menyetel a[`FillMode`](../fillmode/) pencacahan yang menentukan bagaimana interior bentuk dalam hal ini`GraphicsPath` sudah terisi. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Menambahkan angka baru. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Menambahkan angka baru. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Menambahkan yang ditentukan`GraphicsPath` ke jalur ini. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Menambahkan yang ditentukan`GraphicsPath` ke jalur ini. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Melakukan tiruan mendalam dari jalur grafis ini. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Mengubah setiap kurva di jalur ini menjadi urutan segmen garis yang terhubung. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Menerapkan transformasi yang ditentukan dan kemudian mengonversi setiap kurva dalam hal ini`GraphicsPath` menjadi urutan segmen garis yang terhubung. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Mengonversi setiap kurva dalam hal ini`GraphicsPath` menjadi urutan segmen garis yang terhubung. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Mendapat batas objek. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Mendapat batas objek. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) dan menggunakan yang ditentukan[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) dan menggunakan yang ditentukan[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) dan menggunakan yang ditentukan[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalam (di bawah) garis besar ini`GraphicsPath` saat digambar dengan yang ditentukan[`Pen`](../pen/) dan menggunakan yang ditentukan[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` di wilayah klip yang terlihat dari yang ditentukan[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Menunjukkan apakah titik yang ditentukan terkandung di dalamnya`GraphicsPath` , menggunakan yang ditentukan[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Menghapus angka. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Menghapus angka. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Mengosongkan jalur grafik dan menyetel[`FillMode`](../fillmode/) keAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Membalik urutan angka, bentuk, dan titik di setiap bentuk ini`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Menerapkan transformasi warp, ditentukan oleh persegi panjang dan jajaran genjang, untuk ini`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Menambahkan kerangka tambahan ke jalur. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Menambahkan kerangka tambahan ke`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Menggantikan ini`GraphicsPath` dengan kurva yang melingkupi area yang diisi saat jalur ini digambar dengan pena yang ditentukan. |

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



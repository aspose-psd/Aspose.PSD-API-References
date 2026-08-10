---
title: "Class Graphics"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Graphics. Mewakili grafik sesuai dengan mesin grafik yang digunakan dalam assembly saat ini."
type: docs
weight: 4780
url: /id/net/aspose.psd/graphics/
---
{{< psd/tize >}}
## Graphics class

Mewakili grafik sesuai dengan mesin grafis yang digunakan dalam assembly saat ini.

```csharp
public sealed class Graphics
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Graphics](graphics/)(Image) | Menginisialisasi instance baru dari kelas `Graphics`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Mendapatkan atau mengatur wilayah klip. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Mendapatkan atau mengatur kualitas komposit. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Mendapatkan resolusi horizontal dari Aspose.PSD.Graphics ini. |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Mendapatkan resolusi vertikal dari Aspose.PSD.Graphics ini. |
| [Image](../../aspose.psd/graphics/image/) { get; } | Mendapatkan gambar. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Mengambil atau mengatur mode interpolasi. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Mendapatkan nilai yang menunjukkan apakah grafik berada dalam keadaan pemanggilan BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Mendapatkan atau mengatur skala antara satuan dunia dan satuan halaman untuk Aspose.PSD.Graphics ini. |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Mendapatkan atau mengatur satuan ukuran yang digunakan untuk koordinat halaman dalam Aspose.PSD.Graphics ini. |
| [PaintableImageOptions](../../aspose.psd/graphics/paintableimageoptions/) { get; set; } | Mendapatkan atau mengatur opsi gambar, yang digunakan untuk membuat gambar vektor yang dapat digambar. |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Mendapatkan atau mengatur mode penghalusan. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Mendapatkan atau mengatur petunjuk rendering teks. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Mendapatkan atau mengatur salinan transformasi dunia geometris untuk `Graphics` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Memulai caching operasi grafik berikut. Efek grafik yang diterapkan setelahnya tidak akan diterapkan secara langsung; sebaliknya EndUpdate akan menyebabkan penerapan semua efek sekaligus. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Membersihkan permukaan grafik menggunakan warna yang ditentukan. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur [`Rectangle`](../rectangle/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur [`RectangleF`](../rectanglef/). |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Menggambar spline Bézier yang didefinisikan oleh empat struktur [`Point`](../point/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Menggambar spline Bézier yang didefinisikan oleh empat struktur [`PointF`](../pointf/). |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Menggambar spline Bézier yang didefinisikan oleh empat pasangan terurut koordinat yang mewakili titik. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Menggambar serangkaian spline Bézier dari sebuah array struktur [`PointF`](../pointf/). |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Menggambar serangkaian spline Bézier dari sebuah array struktur [`Point`](../point/). |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`PointF`](../pointf/). Metode ini menggunakan ketegangan default 0,5 dan mode isi Alternate. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`Point`](../point/). Metode ini menggunakan ketegangan default 0,5 dan mode isi Alternate. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`PointF`](../pointf/) menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi Alternate default. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`Point`](../point/) menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi Alternate default. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Menggambar spline kardinal melalui sebuah array struktur [`PointF`](../pointf/) yang ditentukan. Metode ini menggunakan ketegangan default 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Menggambar spline kardinal melalui sebuah array struktur [`Point`](../point/) yang ditentukan. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Menggambar spline kardinal melalui sebuah array struktur [`PointF`](../pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Menggambar spline kardinal melalui sebuah array struktur [`Point`](../point/) yang ditentukan menggunakan ketegangan yang ditentukan. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Menggambar spline kardinal melalui sebuah array struktur [`PointF`](../pointf/) yang ditentukan. Penggambaran dimulai dengan offset dari awal array. Metode ini menggunakan ketegangan default 0,5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Menggambar spline kardinal melalui sebuah array struktur [`PointF`](../pointf/) yang ditentukan menggunakan ketegangan yang ditentukan. Penggambaran dimulai dengan offset dari awal array. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Menggambar spline kardinal melalui sebuah array struktur [`Point`](../point/) yang ditentukan menggunakan ketegangan yang ditentukan. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Menggambar elips yang ditentukan oleh struktur [`Rectangle`](../rectangle/) pembatas. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Menggambar elips yang didefinisikan oleh sebuah [`RectangleF`](../rectanglef/) pembatas. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Menggambar elips yang didefinisikan oleh sebuah persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Menggambar elips yang didefinisikan oleh sebuah persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Menggambar [`Image`](./image/), menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Menggambar [`Image`](./image/), menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Menggambar [`Image`](./image/), menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Menggambar gambar yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan oleh sepasang koordinat. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Menggambar bagian yang ditentukan dari *image* yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Menggambar [`Image`](./image/) yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan oleh sepasang koordinat. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Menggambar gambar yang ditentukan tanpa skala dan memotongnya, jika diperlukan, agar sesuai dalam persegi panjang yang ditentukan. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Menggambar sebuah garis yang menghubungkan dua struktur [`Point`](../point/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Menggambar sebuah garis yang menghubungkan dua struktur [`PointF`](../pointf/). |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Menggambar sebuah garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Menggambar sebuah garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Menggambar serangkaian segmen garis yang menghubungkan sebuah array struktur [`PointF`](../pointf/). |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Menggambar serangkaian segmen garis yang menghubungkan sebuah array struktur [`Point`](../point/). |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Menggambar sebuah [`GraphicsPath`](../graphicspath/). |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Menggambar bentuk pai yang didefinisikan oleh sebuah elips yang ditentukan oleh struktur [`Rectangle`](../rectangle/) dan dua garis radial. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Menggambar bentuk pai yang didefinisikan oleh sebuah elips yang ditentukan oleh struktur [`RectangleF`](../rectanglef/) dan dua garis radial. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Menggambar bentuk pai yang didefinisikan oleh sebuah elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Menggambar bentuk pai yang didefinisikan oleh sebuah elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Menggambar sebuah poligon yang didefinisikan oleh sebuah array struktur [`PointF`](../pointf/). |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Menggambar sebuah poligon yang didefinisikan oleh sebuah array struktur [`Point`](../point/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Menggambar sebuah persegi panjang yang ditentukan oleh struktur [`Rectangle`](../rectangle/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Menggambar sebuah persegi panjang yang ditentukan oleh struktur [`RectangleF`](../rectanglef/). |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Menggambar sebuah persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Menggambar sebuah persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [`RectangleF`](../rectanglef/). |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [`Rectangle`](../rectangle/). |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../brush/) dan [`Font`](../font/) yang ditentukan. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [`Brush`](../brush/) dan [`Font`](../font/) yang ditentukan. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../brush/) dan [`Font`](../font/) yang ditentukan. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../brush/) dan [`Font`](../font/) menggunakan atribut format dari [`StringFormat`](../stringformat/) yang ditentukan. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [`Brush`](../brush/) dan [`Font`](../font/) menggunakan atribut format dari [`StringFormat`](../stringformat/) yang ditentukan. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../brush/) dan [`Font`](../font/) menggunakan atribut format dari [`StringFormat`](../stringformat/) yang ditentukan. |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Menyelesaikan caching operasi grafis yang dimulai setelah BeginUpdate dipanggil. Operasi grafis sebelumnya akan diterapkan sekaligus saat memanggil metode ini. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`PointF`](../pointf/). Metode ini menggunakan ketegangan default 0,5 dan mode isi Alternate. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`Point`](../point/). Metode ini menggunakan ketegangan default 0,5 dan mode isi Alternate. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`PointF`](../pointf/) menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh sebuah array struktur [`Point`](../point/) menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0,5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Mengisi bagian dalam kurva spline kardinal tertutup yang didefinisikan oleh array struktur [`PointF`](../pointf/) menggunakan mode isi dan ketegangan yang ditentukan. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Mengisi bagian dalam kurva spline kardinal tertutup yang didefinisikan oleh array struktur [`Point`](../point/) menggunakan mode isi dan ketegangan yang ditentukan. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur [`Rectangle`](../rectangle/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur [`RectangleF`](../rectanglef/). |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Mengisi bagian dalam [`GraphicsPath`](../graphicspath/). |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Mengisi bagian dalam segmen pai yang didefinisikan oleh elips yang ditentukan oleh struktur [`RectangleF`](../rectanglef/) dan dua garis radial. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Mengisi bagian dalam segmen pai yang didefinisikan oleh elips yang ditentukan oleh struktur [`RectangleF`](../rectanglef/) dan dua garis radial. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Mengisi bagian dalam segmen pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Mengisi bagian dalam segmen pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [`PointF`](../pointf/) dan Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [`Point`](../point/) dan Alternate. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [`PointF`](../pointf/) menggunakan mode isi yang ditentukan. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur [`Point`](../point/) menggunakan mode isi yang ditentukan. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Mengisi bagian dalam persegi panjang yang ditentukan oleh struktur [`Rectangle`](../rectangle/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Mengisi bagian dalam persegi panjang yang ditentukan oleh struktur [`RectangleF`](../rectanglef/). |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Mengisi bagian dalam serangkaian persegi panjang yang ditentukan oleh struktur [`RectangleF`](../rectanglef/). |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Mengisi bagian dalam serangkaian persegi panjang yang ditentukan oleh struktur [`Rectangle`](../rectangle/). |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Mengisi bagian dalam [`Region`](../region/). |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Mengalikan [`Matrix`](../matrix/) yang merepresentasikan transformasi geometris lokal dari `Graphics` ini dengan [`Matrix`](../matrix/) yang ditentukan dengan menambahkan [`Matrix`](../matrix/) yang ditentukan di depan. |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Mengalikan [`Matrix`](../matrix/) yang merepresentasikan transformasi geometris lokal dari `Graphics` ini dengan [`Matrix`](../matrix/) yang ditentukan dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Mengatur ulang properti [`Transform`](./transform/) ke identitas. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi di depan. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Menskalakan transformasi geometris lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi di depan. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan nilai yang ditentukan dalam urutan yang ditentukan. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi di depan. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Mentraslasikan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

## Contoh

Contoh ini menggunakan kelas Graphics untuk membuat bentuk primitif pada permukaan Image. Untuk mendemonstrasikan operasi, contoh ini membuat Image baru dalam format PSD dan menggambar bentuk primitif pada permukaan Image menggunakan metode Draw yang disediakan oleh kelas Graphics, kemudian mengekspornya ke format file PSD.

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat dan inisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Gambar sebuah Arc dengan menentukan objek Pen yang berwarna Hitam, 
    //sebuah Rectangle yang mengelilingi Arc, Sudut Mulai, dan Sudut Penyapuan
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Gambar sebuah Bezier dengan menentukan objek Pen yang berwarna Biru dan Titik koordinat.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Gambar sebuah Curve dengan menentukan objek Pen yang berwarna Hijau dan sebuah array Titik
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Gambar sebuah Ellipse menggunakan objek Pen dan Rectangle yang mengelilinginya
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Gambar sebuah Garis 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Gambar sebuah segmen Pie
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Gambar sebuah Polygon dengan menentukan objek Pen yang berwarna Merah dan sebuah array Titik
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Gambar sebuah Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Buat objek SolidBrush dan atur berbagai propertinya
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Gambar sebuah String menggunakan objek SolidBrush dan Font, pada Point tertentu
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Buat sebuah instance dari PngOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



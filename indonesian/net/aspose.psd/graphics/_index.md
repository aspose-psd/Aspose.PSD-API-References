---
title: Class Graphics
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Graphics kelas. Mewakili grafis sesuai dengan mesin grafis yang digunakan dalam perakitan saat ini.
type: docs
weight: 4310
url: /id/net/aspose.psd/graphics/
---
## Graphics class

Mewakili grafis sesuai dengan mesin grafis yang digunakan dalam perakitan saat ini.

```csharp
public sealed class Graphics
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Graphics](graphics/)(Image) | Menginisialisasi instance baru dari`Graphics` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Clip](../../aspose.psd/graphics/clip/) { get; set; } | Mendapat atau menyetel wilayah klip. |
| [CompositingQuality](../../aspose.psd/graphics/compositingquality/) { get; set; } | Mendapatkan atau menyetel kualitas pengomposisian. |
| [DpiX](../../aspose.psd/graphics/dpix/) { get; } | Mendapatkan resolusi horizontal dari Aspose.PSD.Graphics. ini |
| [DpiY](../../aspose.psd/graphics/dpiy/) { get; } | Mendapatkan resolusi vertikal Aspose.PSD.Graphics. ini |
| [Image](../../aspose.psd/graphics/image/) { get; } | Mendapatkan gambar. |
| [InterpolationMode](../../aspose.psd/graphics/interpolationmode/) { get; set; } | Mendapat atau menyetel mode interpolasi. |
| [IsInBeginUpdateCall](../../aspose.psd/graphics/isinbeginupdatecall/) { get; } | Mendapat nilai yang menunjukkan apakah grafik dalam status panggilan BeginUpdate. |
| [PageScale](../../aspose.psd/graphics/pagescale/) { get; set; } | Mendapat atau mengatur penskalaan antara unit dunia dan unit halaman untuk Aspose.PSD.Graphics. ini |
| [PageUnit](../../aspose.psd/graphics/pageunit/) { get; set; } | Mendapat atau menetapkan satuan ukuran yang digunakan untuk koordinat halaman di Aspose.PSD.Graphics. ini |
| [SmoothingMode](../../aspose.psd/graphics/smoothingmode/) { get; set; } | Mendapatkan atau menyetel mode smoothing. |
| [TextRenderingHint](../../aspose.psd/graphics/textrenderinghint/) { get; set; } | Mendapat atau menyetel petunjuk rendering teks. |
| [Transform](../../aspose.psd/graphics/transform/) { get; set; } | Mendapatkan atau menyetel salinan transformasi dunia geometris untuk ini`Graphics` . |

## Metode

| Nama | Keterangan |
| --- | --- |
| [BeginUpdate](../../aspose.psd/graphics/beginupdate/)() | Memulai caching dari operasi grafis berikut. Efek grafik yang diterapkan setelahnya tidak akan langsung diterapkan, melainkan EndUpdate akan menyebabkan penerapan semua efek sekaligus. |
| [Clear](../../aspose.psd/graphics/clear/)(Color) | Membersihkan permukaan grafik menggunakan warna yang ditentukan. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc)(Pen, Rectangle, float, float) | Menggambar busur yang mewakili sebagian elips yang ditentukan oleh a[`Rectangle`](../rectangle/)struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_1)(Pen, RectangleF, float, float) | Menggambar busur yang mewakili sebagian elips yang ditentukan oleh a[`RectangleF`](../rectanglef/)struktur. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_3)(Pen, float, float, float, float, float, float) | Menggambar busur yang mewakili sebagian elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [DrawArc](../../aspose.psd/graphics/drawarc/#drawarc_2)(Pen, int, int, int, int, int, int) | Menggambar busur yang mewakili sebagian elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier)(Pen, Point, Point, Point, Point) | Menggambar spline Bézier yang ditentukan oleh empat[`Point`](../point/) struktur. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Menggambar spline Bézier yang ditentukan oleh empat[`PointF`](../pointf/) struktur. |
| [DrawBezier](../../aspose.psd/graphics/drawbezier/#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Menggambar spline Bézier yang ditentukan oleh empat pasang koordinat berurutan yang mewakili titik. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers)(Pen, PointF[]) | Menggambar serangkaian Bézier splines dari array[`PointF`](../pointf/) struktur. |
| [DrawBeziers](../../aspose.psd/graphics/drawbeziers/#drawbeziers_1)(Pen, Point[]) | Menggambar serangkaian Bézier splines dari array[`Point`](../point/) struktur. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve)(Pen, PointF[]) | Menggambar spline kardinal tertutup yang ditentukan oleh larik[`PointF`](../pointf/) struktur. Metode ini menggunakan tegangan default 0,5 danAlternate isi mode. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_2)(Pen, Point[]) | Menggambar spline kardinal tertutup yang ditentukan oleh larik[`Point`](../point/) struktur. Metode ini menggunakan tegangan default 0,5 danAlternate isi mode. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_1)(Pen, PointF[], float) | Menggambar spline kardinal tertutup yang ditentukan oleh larik[`PointF`](../pointf/) struktur menggunakan tegangan tertentu. Metode ini menggunakan defaultAlternate isi mode. |
| [DrawClosedCurve](../../aspose.psd/graphics/drawclosedcurve/#drawclosedcurve_3)(Pen, Point[], float) | Menggambar spline kardinal tertutup yang ditentukan oleh larik[`Point`](../point/) struktur menggunakan tegangan tertentu. Metode ini menggunakan defaultAlternate isi mode. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve)(Pen, PointF[]) | Menggambar spline kardinal melalui array tertentu[`PointF`](../pointf/) struktur. Metode ini menggunakan tegangan default 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_4)(Pen, Point[]) | Menggambar spline kardinal melalui array tertentu[`Point`](../point/) struktur. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_3)(Pen, PointF[], float) | Menggambar spline kardinal melalui array tertentu[`PointF`](../pointf/) struktur menggunakan tegangan tertentu. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_6)(Pen, Point[], float) | Menggambar spline kardinal melalui array tertentu[`Point`](../point/) struktur menggunakan tegangan tertentu. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_1)(Pen, PointF[], int, int) | Menggambar spline kardinal melalui array tertentu[`PointF`](../pointf/) struktur. Gambar dimulai dari awal array. Metode ini menggunakan tegangan default 0.5. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_2)(Pen, PointF[], int, int, float) | Menggambar spline kardinal melalui array tertentu[`PointF`](../pointf/) struktur menggunakan tegangan tertentu. Gambar dimulai dari awal array. |
| [DrawCurve](../../aspose.psd/graphics/drawcurve/#drawcurve_5)(Pen, Point[], int, int, float) | Menggambar spline kardinal melalui array tertentu[`Point`](../point/) struktur menggunakan tegangan tertentu. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse)(Pen, Rectangle) | Menggambar elips yang ditentukan oleh pembatas[`Rectangle`](../rectangle/)struktur. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_1)(Pen, RectangleF) | Menggambar elips yang ditentukan oleh pembatas[`RectangleF`](../rectanglef/) . |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_3)(Pen, float, float, float, float) | Menggambar elips yang ditentukan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [DrawEllipse](../../aspose.psd/graphics/drawellipse/#drawellipse_2)(Pen, int, int, int, int) | Menggambar elips yang ditentukan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage)(Image, Point) | Menggambar yang ditentukan[`Image`](./image/) , menggunakan ukuran fisik aslinya, di lokasi yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_1)(Image, PointF) | Menggambar yang ditentukan[`Image`](./image/) , menggunakan ukuran fisik aslinya, di lokasi yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_2)(Image, PointF[]) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_6)(Image, Point[]) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_10)(Image, Rectangle) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_15)(Image, RectangleF) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_22)(Image, float, float) | Menggambar yang ditentukan[`Image`](./image/) , menggunakan ukuran fisik aslinya, di lokasi yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_20)(Image, int, int) | Menggambar gambar yang ditentukan, menggunakan ukuran fisik aslinya, di lokasi yang ditentukan oleh pasangan koordinat. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_3)(Image, PointF[], RectangleF) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_7)(Image, Point[], Rectangle) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_11)(Image, Rectangle, GraphicsUnit) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_16)(Image, RectangleF, GraphicsUnit) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_23)(Image, float, float, float, float) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_21)(Image, int, int, int, int) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Menggambar bagian yang ditentukan dari yang ditentukan*image* di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImage](../../aspose.psd/graphics/drawimage/#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Menggambar yang ditentukan[`Image`](./image/) di lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled)(Image, Point) | Menggambar gambar tertentu menggunakan ukuran fisik aslinya di lokasi tertentu. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_1)(Image, Rectangle) | Menggambar gambar tertentu menggunakan ukuran fisik aslinya di lokasi tertentu. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_2)(Image, int, int) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya di lokasi yang ditentukan oleh pasangan koordinat. |
| [DrawImageUnscaled](../../aspose.psd/graphics/drawimageunscaled/#drawimageunscaled_3)(Image, int, int, int, int) | Menggambar gambar tertentu menggunakan ukuran fisik aslinya di lokasi tertentu. |
| [DrawImageUnscaledAndClipped](../../aspose.psd/graphics/drawimageunscaledandclipped/)(Image, Rectangle) | Menggambar gambar yang ditentukan tanpa penskalaan dan memotongnya, jika perlu, agar sesuai dengan persegi panjang yang ditentukan. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline)(Pen, Point, Point) | Menggambar garis yang menghubungkan dua[`Point`](../point/) struktur. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_1)(Pen, PointF, PointF) | Menggambar garis yang menghubungkan dua[`PointF`](../pointf/) struktur. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_3)(Pen, float, float, float, float) | Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [DrawLine](../../aspose.psd/graphics/drawline/#drawline_2)(Pen, int, int, int, int) | Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines)(Pen, PointF[]) | Menggambar serangkaian segmen garis yang menghubungkan array[`PointF`](../pointf/) struktur. |
| [DrawLines](../../aspose.psd/graphics/drawlines/#drawlines_1)(Pen, Point[]) | Menggambar serangkaian segmen garis yang menghubungkan array[`Point`](../point/) struktur. |
| [DrawPath](../../aspose.psd/graphics/drawpath/)(Pen, GraphicsPath) | Draw a[`GraphicsPath`](../graphicspath/) . |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie)(Pen, Rectangle, float, float) | Menggambar bentuk pai yang ditentukan oleh elips yang ditentukan oleh a[`Rectangle`](../rectangle/) struktur dan dua garis radial. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_1)(Pen, RectangleF, float, float) | Menggambar bentuk pai yang ditentukan oleh elips yang ditentukan oleh a[`RectangleF`](../rectanglef/) struktur dan dua garis radial. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_3)(Pen, float, float, float, float, float, float) | Menggambar bentuk pai yang ditentukan oleh elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial. |
| [DrawPie](../../aspose.psd/graphics/drawpie/#drawpie_2)(Pen, int, int, int, int, int, int) | Menggambar bentuk pai yang ditentukan oleh elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon)(Pen, PointF[]) | Menggambar poligon yang ditentukan oleh larik[`PointF`](../pointf/) struktur. |
| [DrawPolygon](../../aspose.psd/graphics/drawpolygon/#drawpolygon_1)(Pen, Point[]) | Menggambar poligon yang ditentukan oleh larik[`Point`](../point/) struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle)(Pen, Rectangle) | Menggambar persegi panjang yang ditentukan oleh a[`Rectangle`](../rectangle/)struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_1)(Pen, RectangleF) | Menggambar persegi panjang yang ditentukan oleh a[`RectangleF`](../rectanglef/)struktur. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_3)(Pen, float, float, float, float) | Menggambar persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi. |
| [DrawRectangle](../../aspose.psd/graphics/drawrectangle/#drawrectangle_2)(Pen, int, int, int, int) | Menggambar persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles)(Pen, RectangleF[]) | Menggambar serangkaian persegi panjang yang ditentukan oleh[`RectangleF`](../rectanglef/) struktur. |
| [DrawRectangles](../../aspose.psd/graphics/drawrectangles/#drawrectangles_1)(Pen, Rectangle[]) | Menggambar serangkaian persegi panjang yang ditentukan oleh[`Rectangle`](../rectangle/) struktur. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring)(string, Font, Brush, PointF) | Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../brush/) Dan[`Font`](../font/) objek. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_2)(string, Font, Brush, RectangleF) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan yang ditentukan[`Brush`](../brush/) Dan[`Font`](../font/) objek. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_4)(string, Font, Brush, float, float) | Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../brush/) Dan[`Font`](../font/) objek. |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../brush/) Dan[`Font`](../font/) objek menggunakan atribut pemformatan yang ditentukan[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan yang ditentukan[`Brush`](../brush/) Dan[`Font`](../font/) objek menggunakan atribut pemformatan yang ditentukan[`StringFormat`](../stringformat/) . |
| [DrawString](../../aspose.psd/graphics/drawstring/#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../brush/) Dan[`Font`](../font/) objek menggunakan atribut pemformatan yang ditentukan[`StringFormat`](../stringformat/) . |
| [EndUpdate](../../aspose.psd/graphics/endupdate/)() | Menyelesaikan caching dari operasi grafik yang dimulai setelah BeginUpdate dipanggil. Operasi grafik sebelumnya akan diterapkan sekaligus saat memanggil metode ini. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve)(Brush, PointF[]) | Mengisi bagian dalam kurva spline kardinal tertutup yang ditentukan oleh larik[`PointF`](../pointf/) struktur. Metode ini menggunakan tegangan default 0,5 danAlternate isi mode. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_3)(Brush, Point[]) | Mengisi bagian dalam kurva spline kardinal tertutup yang ditentukan oleh larik[`Point`](../point/) struktur. Metode ini menggunakan tegangan default 0,5 danAlternate isi mode. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_1)(Brush, PointF[], FillMode) | Mengisi bagian dalam kurva spline kardinal tertutup yang ditentukan oleh larik[`PointF`](../pointf/) struktur menggunakan mode pengisian yang ditentukan. Metode ini menggunakan tegangan default 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_4)(Brush, Point[], FillMode) | Mengisi bagian dalam kurva spline kardinal tertutup yang ditentukan oleh larik[`Point`](../point/) struktur menggunakan mode pengisian yang ditentukan. Metode ini menggunakan tegangan default 0.5. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Mengisi bagian dalam kurva spline kardinal tertutup yang ditentukan oleh larik[`PointF`](../pointf/) struktur menggunakan mode pengisian dan ketegangan yang ditentukan. |
| [FillClosedCurve](../../aspose.psd/graphics/fillclosedcurve/#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Mengisi bagian dalam kurva spline kardinal tertutup yang ditentukan oleh larik[`Point`](../point/) struktur menggunakan mode pengisian dan ketegangan yang ditentukan. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse)(Brush, Rectangle) | Mengisi bagian dalam elips yang ditentukan oleh persegi panjang pembatas yang ditentukan oleh a[`Rectangle`](../rectangle/)struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_1)(Brush, RectangleF) | Mengisi bagian dalam elips yang ditentukan oleh persegi panjang pembatas yang ditentukan oleh a[`RectangleF`](../rectanglef/)struktur. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_3)(Brush, float, float, float, float) | Mengisi bagian dalam elips yang ditentukan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [FillEllipse](../../aspose.psd/graphics/fillellipse/#fillellipse_2)(Brush, int, int, int, int) | Mengisi bagian dalam elips yang ditentukan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [FillPath](../../aspose.psd/graphics/fillpath/)(Brush, GraphicsPath) | Mengisi bagian dalam a[`GraphicsPath`](../graphicspath/) . |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie)(Brush, Rectangle, float, float) | Mengisi interior bagian pai yang ditentukan oleh elips yang ditentukan oleh a[`RectangleF`](../rectanglef/) struktur dan dua garis radial. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_1)(Brush, RectangleF, float, float) | Mengisi interior bagian pai yang ditentukan oleh elips yang ditentukan oleh a[`RectangleF`](../rectanglef/) struktur dan dua garis radial. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_3)(Brush, float, float, float, float, float, float) | Mengisi interior bagian pai yang ditentukan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [FillPie](../../aspose.psd/graphics/fillpie/#fillpie_2)(Brush, int, int, int, int, int, int) | Mengisi interior bagian pai yang ditentukan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon)(Brush, PointF[]) | Mengisi bagian dalam poligon yang ditentukan oleh larik titik yang ditentukan oleh[`PointF`](../pointf/) struktur danAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_2)(Brush, Point[]) | Mengisi bagian dalam poligon yang ditentukan oleh larik titik yang ditentukan oleh[`Point`](../point/) struktur danAlternate . |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_1)(Brush, PointF[], FillMode) | Mengisi bagian dalam poligon yang ditentukan oleh larik titik yang ditentukan oleh[`PointF`](../pointf/) struktur menggunakan mode isian yang ditentukan. |
| [FillPolygon](../../aspose.psd/graphics/fillpolygon/#fillpolygon_3)(Brush, Point[], FillMode) | Mengisi bagian dalam poligon yang ditentukan oleh larik titik yang ditentukan oleh[`Point`](../point/) struktur menggunakan mode isian yang ditentukan. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle)(Brush, Rectangle) | Mengisi interior persegi panjang yang ditentukan oleh a[`Rectangle`](../rectangle/)struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_1)(Brush, RectangleF) | Mengisi interior persegi panjang yang ditentukan oleh a[`RectangleF`](../rectanglef/)struktur. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_3)(Brush, float, float, float, float) | Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar dan tinggi. |
| [FillRectangle](../../aspose.psd/graphics/fillrectangle/#fillrectangle_2)(Brush, int, int, int, int) | Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar dan tinggi. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles)(Brush, RectangleF[]) | Mengisi interior rangkaian persegi panjang yang ditentukan oleh[`RectangleF`](../rectanglef/) struktur. |
| [FillRectangles](../../aspose.psd/graphics/fillrectangles/#fillrectangles_1)(Brush, Rectangle[]) | Mengisi interior rangkaian persegi panjang yang ditentukan oleh[`Rectangle`](../rectangle/) struktur. |
| [FillRegion](../../aspose.psd/graphics/fillregion/)(Brush, Region) | Mengisi bagian dalam a[`Region`](../region/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform)(Matrix) | Mengalikan[`Matrix`](../matrix/) yang mewakili transformasi geometris lokal ini`Graphics` oleh yang ditentukan[`Matrix`](../matrix/) dengan mendahului yang ditentukan[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/graphics/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Mengalikan[`Matrix`](../matrix/) yang mewakili transformasi geometris lokal ini`Graphics` oleh yang ditentukan[`Matrix`](../matrix/) dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd/graphics/resettransform/)() | Mereset[`Transform`](./transform/) properti ke identitas. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform)(float) | Memutar transformasi geometrik lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke transform. |
| [RotateTransform](../../aspose.psd/graphics/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Memutar transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform)(float, float) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan matriks penskalaan ke transformasi. |
| [ScaleTransform](../../aspose.psd/graphics/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform)(float, float) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan terjemahan ke transform. |
| [TranslateTransform](../../aspose.psd/graphics/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

### Contoh

Contoh ini menggunakan kelas Grafik untuk membuat bentuk primitif pada permukaan Gambar. Untuk mendemonstrasikan operasi, contoh membuat Gambar baru dalam format PSD dan menggambar bentuk primitif pada permukaan Gambar menggunakan metode Gambar yang diekspos oleh kelas Grafik lalu mengekspornya ke format file PSD.

```csharp
[C#]

//Buat instance dari Gambar 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Bersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Gambar Arc dengan menentukan objek Pena berwarna Hitam, 
    //Sebuah Persegi Panjang yang mengelilingi Lengkungan, Sudut Mulai, dan Sudut Sapuan
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Gambar Bezier dengan menentukan objek Pen yang memiliki warna Biru dan titik koordinat.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // Gambar Kurva dengan menentukan objek Pena yang memiliki warna Hijau dan larik Poin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Gambar Ellipse menggunakan objek Pen dan Rectangle di sekelilingnya
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Menarik garis 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Gambar segmen Pai
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // Gambar Poligon dengan menentukan objek Pena yang memiliki warna Merah dan larik Poin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Gambar Persegi Panjang
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Buat objek SolidBrush dan atur berbagai propertinya
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Gambar sebuah String menggunakan objek SolidBrush dan Font, pada Titik tertentu
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Buat instance PngOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



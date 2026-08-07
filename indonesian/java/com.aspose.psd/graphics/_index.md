---
title: "Graphics"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili grafik sesuai dengan mesin grafik yang digunakan dalam assembly saat ini."
type: docs
weight: 49
url: /id/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Mewakili grafik sesuai dengan mesin grafik yang digunakan dalam assembly saat ini.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Menginisialisasi instance baru dari kelas  Graphics . |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Mendapatkan koefisien ukuran gaya teks tebal |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | Mendapatkan koefisien ukuran gaya teks miring |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Menerapkan efek. |
| [beginUpdate()](#beginUpdate--) | Memulai caching operasi grafis berikut. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Membersihkan permukaan grafis menggunakan warna yang ditentukan. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur  Rectangle . |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur  RectangleF . |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Menggambar spline Bézier yang didefinisikan oleh empat struktur  Point . |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Menggambar spline Bézier yang didefinisikan oleh empat struktur  PointF . |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Menggambar spline Bézier yang didefinisikan oleh empat pasangan koordinat berurutan yang mewakili titik. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Menggambar serangkaian spline Bézier dari sebuah array dari struktur  PointF . |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Menggambar serangkaian spline Bézier dari sebuah array dari struktur  Point . |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array dari struktur  PointF . |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array dari struktur  PointF  menggunakan ketegangan yang ditentukan. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array dari struktur  Point . |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Menggambar spline kardinal tertutup yang didefinisikan oleh sebuah array dari struktur  Point  menggunakan ketegangan yang ditentukan. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  PointF . |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  PointF  menggunakan ketegangan yang ditentukan. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  PointF . |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  PointF  menggunakan ketegangan yang ditentukan. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  Point . |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  Point  menggunakan ketegangan yang ditentukan. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  Point  menggunakan ketegangan yang ditentukan. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Menggambar elips yang ditentukan oleh struktur  Rectangle  pembatas. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Menggambar elips yang didefinisikan oleh pembatas  RectangleF . |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Menggambar  Image , yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Menggambar  Image , yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Menggambar  Image , yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Menggambar gambar yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan oleh sepasang koordinat. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan oleh sepasang koordinat. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Menggambar gambar yang ditentukan tanpa skala dan memotongnya, jika perlu, agar sesuai dalam persegi panjang yang ditentukan. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | Menggambar garis yang menghubungkan dua struktur  Point . |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Menggambar garis yang menghubungkan dua struktur  PointF . |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Menggambar serangkaian segmen garis yang menghubungkan sebuah array dari struktur  PointF . |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Menggambar serangkaian segmen garis yang menghubungkan array struktur  Point  . |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Menggambar sebuah  com.aspose.psd.graphicsPath . |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur  Rectangle  dan dua garis radial. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur  RectangleF  dan dua garis radial. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Menggambar poligon yang didefinisikan oleh array struktur  PointF . |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) | Menggambar poligon yang didefinisikan oleh array struktur  Point . |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Menggambar persegi panjang yang ditentukan oleh struktur  Rectangle . |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Menggambar persegi panjang yang ditentukan oleh struktur  RectangleF . |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Menggambar persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Menggambar persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) | Menggambar serangkaian persegi panjang yang ditentukan oleh struktur  RectangleF . |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) | Menggambar serangkaian persegi panjang yang ditentukan oleh struktur  Rectangle . |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Menggambar string teks yang ditentukan dengan cara yang kompatibel dengan Adobe dalam persegi panjang yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Menggambar string teks yang ditentukan dengan cara yang kompatibel dengan Adobe pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan. |
| [endUpdate()](#endUpdate--) | Menyelesaikan caching operasi grafis yang dimulai setelah BeginUpdate dipanggil. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.PointF . |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.PointF  menggunakan mode pengisian yang ditentukan. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.PointF  menggunakan mode pengisian dan ketegangan yang ditentukan. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.Point . |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.Point  menggunakan mode pengisian yang ditentukan. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.Point  menggunakan mode pengisian dan ketegangan yang ditentukan. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur  com.aspose.psd.Rectangle  . |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur  com.aspose.psd.RectangleF  . |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) | Mengisi bagian dalam  com.aspose.psd.graphicsPath . |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh struktur  com.aspose.psd.RectangleF  dan dua garis radial. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh struktur  com.aspose.psd.RectangleF  dan dua garis radial. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.PointF  dan  FillMode.Alternate . |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.PointF  menggunakan mode isi yang ditentukan. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.Point  dan  FillMode.Alternate . |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.Point  menggunakan mode isi yang ditentukan. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Mengisi bagian dalam persegi panjang yang ditentukan oleh struktur  Rectangle . |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Mengisi bagian dalam persegi panjang yang ditentukan oleh struktur  RectangleF . |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | Mengisi bagian dalam serangkaian persegi panjang yang ditentukan oleh struktur  RectangleF . |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Mengisi bagian dalam serangkaian persegi panjang yang ditentukan oleh struktur  Rectangle . |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | Mengisi bagian dalam  com.aspose.psd.region . |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Mendapatkan atau mengatur wilayah klip. |
| [getCompositingQuality()](#getCompositingQuality--) | Mendapatkan atau mengatur kualitas komposit. |
| [getDpiX()](#getDpiX--) | Mendapatkan resolusi horizontal dari  com.aspose.psd.graphics . |
| [getDpiY()](#getDpiY--) | Mendapatkan resolusi vertikal dari  com.aspose.psd.graphics . |
| [getImage()](#getImage--) | Mendapatkan gambar. |
| [getInterpolationMode()](#getInterpolationMode--) | Mendapatkan atau mengatur mode interpolasi. |
| [getPageScale()](#getPageScale--) | Mendapatkan atau mengatur skala antara satuan dunia dan satuan halaman untuk  com.aspose.psd.graphics . |
| [getPageUnit()](#getPageUnit--) | Mendapatkan atau mengatur satuan ukuran yang digunakan untuk koordinat halaman dalam  com.aspose.psd.graphics . |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Mendapatkan atau mengatur opsi gambar, yang digunakan untuk membuat gambar vektor yang dapat digambar. |
| [getSmoothingMode()](#getSmoothingMode--) | Mendapatkan atau mengatur mode penghalusan. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Mendapatkan atau mengatur petunjuk perenderan teks. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur salinan transformasi dunia geometris untuk ini  com.aspose.psd.graphics . |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Mendapatkan nilai yang menunjukkan apakah grafik berada dalam keadaan pemanggilan BeginUpdate. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Mengukur string menggunakan kelas [GraphicsPath](../../com.aspose.psd/graphicspath). |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Mengukur string. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Mengukur string teks yang ditentukan dengan parameter yang ditentukan |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Mengalikan  com.aspose.psd.Matrix  yang mewakili transformasi geometris lokal dari ini  com.aspose.psd.Graphics  dengan  com.aspose.psd.Matrix  yang ditentukan dengan menambahkan di depan  com.aspose.psd.matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Mengalikan  com.aspose.psd.Matrix  yang mewakili transformasi geometris lokal dari ini  com.aspose.psd.Graphics  dengan  com.aspose.psd.Matrix  yang ditentukan dalam urutan yang ditentukan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Mengatur ulang properti  com.aspose.psd.graphics.Transform  menjadi identitas. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Mendapatkan atau mengatur wilayah klip. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Mendapatkan atau mengatur kualitas komposit. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Mendapatkan atau mengatur mode interpolasi. |
| [setPageScale(float value)](#setPageScale-float-) | Mendapatkan atau mengatur skala antara satuan dunia dan satuan halaman untuk  com.aspose.psd.graphics . |
| [setPageUnit(int value)](#setPageUnit-int-) | Mendapatkan atau mengatur satuan ukuran yang digunakan untuk koordinat halaman dalam  com.aspose.psd.graphics . |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Mendapatkan atau mengatur opsi gambar, yang digunakan untuk membuat gambar vektor yang dapat digambar. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Mendapatkan atau mengatur mode penghalusan. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Mendapatkan atau mengatur petunjuk perenderan teks. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Mendapatkan atau mengatur salinan transformasi dunia geometris untuk ini  com.aspose.psd.graphics . |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Menginisialisasi instance baru dari kelas  Graphics .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar sumber. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Mendapatkan koefisien ukuran gaya teks tebal

Menggunakan angka ajaib karena GDI selalu menyediakan pengukuran hanya untuk gaya Regular.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


Mendapatkan koefisien ukuran gaya teks miring

Menggunakan angka ajaib karena GDI selalu menyediakan pengukuran hanya untuk gaya Regular.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Menerapkan efek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| efek | com.aspose.internal.IEffect | Efek yang akan diterapkan. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Memulai caching operasi grafik berikut. Efek grafik yang diterapkan setelahnya tidak akan diterapkan secara langsung, melainkan EndUpdate akan menyebabkan penerapan semua efek sekaligus.

Catatan: efek setelah BeginUpdate dipanggil tidak akan diterapkan jika EndUpdate tidak dipanggil.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Membersihkan permukaan grafis menggunakan warna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Warna yang digunakan untuk membersihkan permukaan grafik. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur  Rectangle .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya busur. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur RectangleF  yang mendefinisikan batas-batas elips. |
| startAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweepAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter  startAngle  ke titik akhir busur. |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh struktur  RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya busur. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF  yang mendefinisikan batas-batas elips. |
| startAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweepAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter  startAngle  ke titik akhir busur. |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya busur. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| lebar | float | Lebar persegi panjang yang mendefinisikan elips. |
| tinggi | float | Tinggi persegi panjang yang mendefinisikan elips. |
| startAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweepAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter  startAngle  ke titik akhir busur. |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Menggambar busur yang mewakili bagian dari elips yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya busur. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang mendefinisikan elips. |
| lebar | int | Lebar persegi panjang yang mendefinisikan elips. |
| tinggi | int | Tinggi persegi panjang yang mendefinisikan elips. |
| startAngle | int | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke titik awal busur. |
| sweepAngle | int | Sudut dalam derajat yang diukur searah jarum jam dari parameter  startAngle  ke titik akhir busur. |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Menggambar spline Bézier yang didefinisikan oleh empat struktur  Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Struktur Pen yang menentukan warna, lebar, dan gaya kurva. |
| pt1 | [Point](../../com.aspose.psd/point) | Struktur Point yang merepresentasikan titik awal kurva. |
| pt2 | [Point](../../com.aspose.psd/point) | Struktur Point yang merepresentasikan titik kontrol pertama untuk kurva. |
| pt3 | [Point](../../com.aspose.psd/point) | Struktur Point yang merepresentasikan titik kontrol kedua untuk kurva. |
| pt4 | [Point](../../com.aspose.psd/point) | Struktur Point yang merepresentasikan titik akhir kurva. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Menggambar spline Bézier yang didefinisikan oleh empat struktur  PointF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya kurva. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang merepresentasikan titik awal kurva. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang merepresentasikan titik kontrol pertama untuk kurva. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang merepresentasikan titik kontrol kedua untuk kurva. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang merepresentasikan titik akhir kurva. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Menggambar spline Bézier yang didefinisikan oleh empat pasangan koordinat berurutan yang mewakili titik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya kurva. |
| x1 | float | Koordinat x dari titik awal kurva. |
| y1 | float | Koordinat y dari titik awal kurva. |
| x2 | float | Koordinat x dari titik kontrol pertama kurva. |
| y2 | float | Koordinat y dari titik kontrol pertama kurva. |
| x3 | float | Koordinat x dari titik kontrol kedua kurva. |
| y3 | float | Koordinat y dari titik kontrol kedua kurva. |
| x4 | float | Koordinat x dari titik akhir kurva. |
| y4 | float | Koordinat y dari titik akhir kurva. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Menggambar serangkaian spline Bézier dari sebuah array dari struktur  PointF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mewakili titik-titik yang menentukan kurva. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Menggambar serangkaian spline Bézier dari sebuah array dari struktur  Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya kurva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mewakili titik-titik yang menentukan kurva. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur  PointF . Metode ini menggunakan ketegangan default 0.5 dan mode isi  FillMode.Alternate .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mendefinisikan spline. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur  PointF  menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi default  FillMode.Alternate .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mendefinisikan spline. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur  Point . Metode ini menggunakan ketegangan default 0.5 dan mode isi  FillMode.Alternate .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mendefinisikan spline. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Menggambar spline kardinal tertutup yang didefinisikan oleh array struktur  Point  menggunakan ketegangan yang ditentukan. Metode ini menggunakan mode isi default  FillMode.Alternate .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mendefinisikan spline. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Menggambar spline kardinal melalui array struktur  PointF  yang ditentukan. Metode ini menggunakan ketegangan default 0.5.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mendefinisikan spline. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  PointF  menggunakan ketegangan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mewakili titik-titik yang mendefinisikan kurva. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Menggambar spline kardinal melalui array struktur  PointF  yang ditentukan. Penggambaran dimulai dengan offset dari awal array. Metode ini menggunakan ketegangan default 0.5.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mendefinisikan spline. |
| offset | int | Offset dari elemen pertama dalam array parameter  points  ke titik awal pada kurva. |
| numberOfSegments | int | Jumlah segmen setelah titik awal yang akan dimasukkan ke dalam kurva. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Menggambar spline kardinal melalui array struktur  PointF  yang ditentukan menggunakan ketegangan yang ditentukan. Penggambaran dimulai dengan offset dari awal array.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mendefinisikan spline. |
| offset | int | Offset dari elemen pertama dalam array parameter  points  ke titik awal pada kurva. |
| numberOfSegments | int | Jumlah segmen setelah titik awal yang akan dimasukkan ke dalam kurva. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mendefinisikan spline. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  Point  menggunakan ketegangan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mendefinisikan spline. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Menggambar spline kardinal melalui sebuah array yang ditentukan dari struktur  Point  menggunakan ketegangan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan tinggi kurva. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mendefinisikan spline. |
| offset | int | Offset dari elemen pertama dalam array parameter  points  ke titik awal pada kurva. |
| numberOfSegments | int | Jumlah segmen setelah titik awal yang akan dimasukkan ke dalam kurva. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Menggambar elips yang ditentukan oleh struktur  Rectangle  pembatas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya elips. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  Rectangle  yang mendefinisikan batas-batas elips. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Menggambar elips yang didefinisikan oleh pembatas  RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya elips. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF  yang mendefinisikan batas-batas elips. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya elips. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| lebar | float | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Menggambar elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, tinggi, dan lebar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya elips. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| lebar | int | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Menggambar  Image , yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| point | [Point](../../com.aspose.psd/point) | Struktur Point yang mewakili lokasi sudut kiri atas gambar yang digambar. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Menggambar  Image , yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| point | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang mewakili sudut kiri atas gambar yang digambar. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang sumber. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang sumber. |
| srcUnit | int | Satuan ukuran. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang sumber. |
| srcUnit | int | Satuan ukuran. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Atribut gambar. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang sumber. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang sumber. |
| srcUnit | int | Satuan ukuran. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Menggambar bagian yang ditentukan dari  image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Array tiga struktur PointF yang mendefinisikan sebuah paralelogram. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang sumber. |
| srcUnit | int | Satuan ukuran. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Atribut gambar. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Rectangle yang menentukan lokasi dan ukuran gambar yang digambar. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Rect sumber. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Rect tujuan. |
| graphicsUnit | int | Unit grafis. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Rect sumber. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Rect tujuan. |
| graphicsUnit | int | Unit grafis. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Atribut gambar. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang tujuan. |
| graphicsUnit | int | Unit grafis. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang tujuan. |
| graphicsUnit | int | Unit grafis. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Atribut gambar. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF yang menentukan lokasi dan ukuran gambar yang digambar. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Rect sumber. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Rect tujuan. |
| graphicsUnit | int | Unit grafis. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang sumber. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang tujuan. |
| graphicsUnit | int | Unit grafis yang akan digunakan. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Atribut gambar yang akan digunakan. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang tujuan. |
| graphicsUnit | int | Unit grafis. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang tujuan untuk menggambar. |
| graphicsUnit | int | Unit grafis. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Atribut gambar. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Menggambar  Image , yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | float | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | float | Koordinat y dari sudut kiri atas gambar yang digambar. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | float | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | float | Koordinat y dari sudut kiri atas gambar yang digambar. |
| lebar | float | Lebar gambar yang digambar. |
| tinggi | float | Tinggi gambar yang digambar. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Menggambar gambar yang ditentukan, menggunakan ukuran fisik aslinya, pada lokasi yang ditentukan oleh sepasang koordinat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Menggambar  Image  yang ditentukan pada lokasi yang ditentukan dan dengan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |
| lebar | int | Lebar gambar yang digambar. |
| tinggi | int | Tinggi gambar yang digambar. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| point | [Point](../../com.aspose.psd/point) | Point  struktur yang menentukan sudut kiri atas gambar yang digambar. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  yang menentukan sudut kiri atas gambar yang digambar. Properti X dan Y dari rectangle menentukan sudut kiri atas. Properti Width dan Height diabaikan. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan oleh sepasang koordinat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Menggambar gambar yang ditentukan menggunakan ukuran fisik aslinya pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| x | int | Koordinat x dari sudut kiri atas gambar yang digambar. |
| y | int | Koordinat y dari sudut kiri atas gambar yang digambar. |
| lebar | int | Parameter tidak digunakan. |
| tinggi | int | Parameter tidak digunakan. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Menggambar gambar yang ditentukan tanpa skala dan memotongnya, jika perlu, agar sesuai dalam persegi panjang yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Gambar yang akan digambar dengan. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle yang digunakan untuk menggambar gambar. |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


Menggambar garis yang menghubungkan dua struktur  Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya garis. |
| point1 | [Point](../../com.aspose.psd/point) | Struktur Point yang mewakili titik pertama untuk dihubungkan. |
| point2 | [Point](../../com.aspose.psd/point) | Struktur Point yang mewakili titik kedua untuk dihubungkan. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


Menggambar garis yang menghubungkan dua struktur  PointF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya garis. |
| point1 | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang mewakili titik pertama untuk dihubungkan. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Struktur PointF yang mewakili titik kedua untuk dihubungkan. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya garis. |
| x1 | float | Koordinat x dari titik pertama. |
| y1 | float | Koordinat y dari titik pertama. |
| x2 | float | Koordinat x dari titik kedua. |
| y2 | float | Koordinat y dari titik kedua. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Menggambar garis yang menghubungkan dua titik yang ditentukan oleh pasangan koordinat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya garis. |
| x1 | int | Koordinat x dari titik pertama. |
| y1 | int | Koordinat y dari titik pertama. |
| x2 | int | Koordinat x dari titik kedua. |
| y2 | int | Koordinat y dari titik kedua. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Menggambar serangkaian segmen garis yang menghubungkan sebuah array dari struktur  PointF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya segmen garis. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array of  PointF  struktur yang mewakili titik-titik yang akan dihubungkan. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Menggambar serangkaian segmen garis yang menghubungkan array struktur  Point  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya segmen garis. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array of  Point  struktur yang mewakili titik-titik yang akan dihubungkan. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Menggambar sebuah  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | com.aspose.psd.Pen yang menentukan warna, lebar, dan gaya jalur. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath untuk menggambar. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur  Rectangle  dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya bentuk pai. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Rectangle yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| startAngle | float | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweepAngle | float | Sudut yang diukur dalam derajat searah jarum jam dari parameter startAngle ke sisi kedua bentuk pai. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh struktur  RectangleF  dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya bentuk pai. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| startAngle | float | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweepAngle | float | Sudut yang diukur dalam derajat searah jarum jam dari parameter startAngle ke sisi kedua bentuk pai. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya bentuk pai. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| y | float | Koordinat y dari sudut kiri atas dari persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| lebar | float | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| startAngle | float | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweepAngle | float | Sudut yang diukur dalam derajat searah jarum jam dari parameter startAngle ke sisi kedua bentuk pai. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Menggambar bentuk pai yang didefinisikan oleh elips yang ditentukan oleh pasangan koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yang menentukan warna, lebar, dan gaya bentuk pai. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| y | int | Koordinat y dari sudut kiri atas dari persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| lebar | int | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bentuk pai berasal. |
| startAngle | int | Sudut yang diukur dalam derajat searah jarum jam dari sumbu x ke sisi pertama bentuk pai. |
| sweepAngle | int | Sudut yang diukur dalam derajat searah jarum jam dari parameter startAngle ke sisi kedua bentuk pai. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


Menggambar poligon yang didefinisikan oleh array struktur  PointF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya poligon. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur  PointF  yang mewakili titik sudut poligon. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Menggambar poligon yang didefinisikan oleh array struktur  Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya poligon. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur  Point  yang mewakili titik sudut poligon. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


Menggambar persegi panjang yang ditentukan oleh struktur  Rectangle .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Sebuah Pen  yang menentukan warna, lebar, dan gaya persegi panjang. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Sebuah struktur  Rectangle  yang mewakili persegi panjang yang akan digambar. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


Menggambar persegi panjang yang ditentukan oleh struktur  RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Sebuah Pen  yang menentukan warna, lebar, dan gaya persegi panjang. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah struktur  RectangleF  yang mewakili persegi panjang yang akan digambar. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Menggambar persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Sebuah Pen  yang menentukan warna, lebar, dan gaya persegi panjang. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan digambar. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan digambar. |
| lebar | float | Lebar persegi panjang yang akan digambar. |
| tinggi | float | Tinggi persegi panjang yang akan digambar. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Menggambar persegi panjang yang ditentukan oleh pasangan koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya persegi panjang. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan digambar. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan digambar. |
| lebar | int | Lebar persegi panjang yang akan digambar. |
| tinggi | int | Tinggi persegi panjang yang akan digambar. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


Menggambar serangkaian persegi panjang yang ditentukan oleh struktur  RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya garis tepi persegi panjang. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array dari struktur  RectangleF  yang mewakili persegi panjang yang akan digambar. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


Menggambar serangkaian persegi panjang yang ditentukan oleh struktur  Rectangle .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  yang menentukan warna, lebar, dan gaya garis tepi persegi panjang. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array dari struktur  Rectangle  yang mewakili persegi panjang yang akan digambar. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  structure yang menentukan sudut kiri atas teks yang digambar. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF  structure yang menentukan sudut kiri atas teks yang digambar. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur yang menentukan lokasi teks yang digambar. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur yang menentukan lokasi teks yang digambar. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| x | float | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | float | Koordinat y dari sudut kiri atas teks yang digambar. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| x | float | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | float | Koordinat y dari sudut kiri atas teks yang digambar. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Menggambar string teks yang ditentukan dengan cara yang kompatibel dengan Adobe dalam persegi panjang yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan menggunakan atribut pemformatan dari  com.aspose.psd.stringFormat  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF struktur yang menentukan lokasi teks yang digambar. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat  yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Menggambar string teks yang ditentukan dengan cara yang kompatibel dengan Adobe pada lokasi yang ditentukan dengan objek  com.aspose.psd.Brush  dan  com.aspose.psd.Font  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | java.lang.String | String yang akan digambar. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font  yang mendefinisikan format teks dari string. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush  yang menentukan warna dan tekstur teks yang digambar. |
| x | float | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | float | Koordinat y dari sudut kiri atas teks yang digambar. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


Menyelesaikan caching operasi grafis yang dimulai setelah BeginUpdate dipanggil. Operasi grafis sebelumnya akan diterapkan sekaligus saat memanggil metode ini.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur com.aspose.psd.PointF. Metode ini menggunakan ketegangan default 0,5 dan mode isi FillMode.Alternate.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan spline. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur com.aspose.psd.PointF menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0,5.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan spline. |
| fillmode | int | Anggota enumerasi com.aspose.psd.FillMode yang menentukan bagaimana kurva diisi. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.PointF  menggunakan mode pengisian dan ketegangan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Sebuah com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan spline. |
| fillmode | int | Anggota enumerasi com.aspose.psd.FillMode yang menentukan bagaimana kurva diisi. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur com.aspose.psd.Point. Metode ini menggunakan ketegangan default 0,5 dan mode isi FillMode.Alternate.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array struktur com.aspose.psd.Point yang mendefinisikan spline. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur com.aspose.psd.Point menggunakan mode isi yang ditentukan. Metode ini menggunakan ketegangan default 0,5.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array struktur com.aspose.psd.Point yang mendefinisikan spline. |
| fillmode | int | Anggota enumerasi com.aspose.psd.FillMode yang menentukan bagaimana kurva diisi. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Mengisi interior kurva spline kardinal tertutup yang didefinisikan oleh array struktur  com.aspose.psd.Point  menggunakan mode pengisian dan ketegangan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array struktur com.aspose.psd.Point yang mendefinisikan spline. |
| fillmode | int | Anggota enumerasi com.aspose.psd.FillMode yang menentukan bagaimana kurva diisi. |
| ketegangan | float | Nilai yang lebih besar atau sama dengan 0.0F yang menentukan ketegangan kurva. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur  com.aspose.psd.Rectangle  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | struktur com.aspose.psd.Rectangle yang mewakili persegi panjang pembatas yang mendefinisikan elips. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh struktur  com.aspose.psd.RectangleF  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | struktur com.aspose.psd.RectangleF yang mewakili persegi panjang pembatas yang mendefinisikan elips. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| lebar | float | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Mengisi bagian dalam elips yang didefinisikan oleh persegi panjang pembatas yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips. |
| lebar | int | Lebar persegi panjang pembatas yang mendefinisikan elips. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


Mengisi bagian dalam  com.aspose.psd.graphicsPath .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath yang mewakili jalur untuk diisi. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh struktur  com.aspose.psd.RectangleF  dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | struktur com.aspose.psd.Rectangle yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| startAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweepAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter startAngle ke sisi kedua bagian pai. |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh struktur  com.aspose.psd.RectangleF  dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | struktur com.aspose.psd.RectangleF yang mewakili persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| startAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweepAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter startAngle ke sisi kedua bagian pai. |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| x | float | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| lebar | float | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| tinggi | float | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| startAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweepAngle | float | Sudut dalam derajat yang diukur searah jarum jam dari parameter startAngle ke sisi kedua bagian pai. |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Mengisi bagian dalam irisan pai yang didefinisikan oleh elips yang ditentukan oleh sepasang koordinat, lebar, tinggi, dan dua garis radial.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| x | int | Koordinat x dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| lebar | int | Lebar persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| tinggi | int | Tinggi persegi panjang pembatas yang mendefinisikan elips tempat bagian pai berasal. |
| startAngle | int | Sudut dalam derajat yang diukur searah jarum jam dari sumbu x ke sisi pertama bagian pai. |
| sweepAngle | int | Sudut dalam derajat yang diukur searah jarum jam dari parameter startAngle ke sisi kedua bagian pai. |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.PointF  dan  FillMode.Alternate .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur com.aspose.psd.PointF yang mewakili titik‑titik sudut poligon yang akan diisi. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.PointF  menggunakan mode isi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array dari struktur com.aspose.psd.PointF yang mewakili titik‑titik sudut poligon yang akan diisi. |
| fillMode | int | Anggota enumerasi com.aspose.psd.FillMode yang menentukan gaya pengisian. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.Point  dan  FillMode.Alternate .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur com.aspose.psd.Point yang mewakili titik‑titik sudut poligon yang akan diisi. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Mengisi bagian dalam poligon yang didefinisikan oleh array titik yang ditentukan oleh struktur  com.aspose.psd.Point  menggunakan mode isi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| points | [Point\[\]](../../com.aspose.psd/point) | Array dari struktur com.aspose.psd.Point yang mewakili titik‑titik sudut poligon yang akan diisi. |
| fillMode | int | Anggota enumerasi com.aspose.psd.FillMode yang menentukan gaya pengisian. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Mengisi bagian dalam persegi panjang yang ditentukan oleh struktur  Rectangle .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik pengisian. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur Rectangle yang mewakili persegi panjang yang akan diisi. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


Mengisi bagian dalam persegi panjang yang ditentukan oleh struktur  RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik pengisian. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur RectangleF yang mewakili persegi panjang yang akan diisi. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik pengisian. |
| x | float | Koordinat x sudut kiri atas persegi panjang yang akan diisi. |
| y | float | Koordinat y sudut kiri atas persegi panjang yang akan diisi. |
| lebar | float | Lebar persegi panjang yang akan diisi. |
| tinggi | float | Tinggi persegi panjang yang akan diisi. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Mengisi bagian dalam persegi panjang yang ditentukan oleh sepasang koordinat, lebar, dan tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik pengisian. |
| x | int | Koordinat x sudut kiri atas persegi panjang yang akan diisi. |
| y | int | Koordinat y sudut kiri atas persegi panjang yang akan diisi. |
| lebar | int | Lebar persegi panjang yang akan diisi. |
| tinggi | int | Tinggi persegi panjang yang akan diisi. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


Mengisi bagian dalam serangkaian persegi panjang yang ditentukan oleh struktur  RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik pengisian. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Array dari struktur Rectangle yang mewakili persegi panjang yang akan diisi. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Mengisi bagian dalam serangkaian persegi panjang yang ditentukan oleh struktur  Rectangle .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik pengisian. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Array dari struktur Rectangle yang mewakili persegi panjang yang akan diisi. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


Mengisi bagian dalam  com.aspose.psd.region .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush yang menentukan karakteristik isi. |
| region | [Region](../../com.aspose.psd/region) | com.aspose.psd.Region yang mewakili area yang akan diisi. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClip() {#getClip--}
```
public Region getClip()
```


Mendapatkan atau mengatur wilayah klip.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Mendapatkan atau mengatur kualitas komposit.

**Returns:**
int - Kualitas komposit.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Mendapatkan resolusi horizontal dari  com.aspose.psd.graphics .

**Returns:**
float - Nilai, dalam dot per inci, untuk resolusi horizontal yang didukung oleh com.aspose.psd.graphics ini.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Mendapatkan resolusi vertikal dari  com.aspose.psd.graphics .

**Returns:**
float - Nilai, dalam dot per inci, untuk resolusi vertikal yang didukung oleh com.aspose.psd.graphics ini.
### getImage() {#getImage--}
```
public Image getImage()
```


Mendapatkan gambar.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Mendapatkan atau mengatur mode interpolasi.

**Returns:**
int - Mode interpolasi.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Mendapatkan atau mengatur skala antara satuan dunia dan satuan halaman untuk  com.aspose.psd.graphics .

**Returns:**
float - Skala antara satuan dunia dan satuan halaman untuk com.aspose.psd.graphics ini.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Mendapatkan atau mengatur satuan ukuran yang digunakan untuk koordinat halaman dalam  com.aspose.psd.graphics .

**Returns:**
int - Satuan ukuran yang digunakan untuk koordinat halaman dalam com.aspose.psd.graphics ini.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Mendapatkan atau mengatur opsi gambar, yang digunakan untuk membuat gambar vektor yang dapat digambar.

Nilai: Opsi gambar, digunakan untuk membuat gambar vektor yang dapat dilukis.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Mendapatkan atau mengatur mode penghalusan.

**Returns:**
int - Mode penghalusan.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Mendapatkan atau mengatur petunjuk perenderan teks.

**Returns:**
int - Petunjuk perenderan teks.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Mendapatkan atau mengatur salinan transformasi dunia geometris untuk ini  com.aspose.psd.graphics .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  com.aspose.psd.Matrix  that represents the geometric world transformation for this  com.aspose.psd.graphics .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInBeginUpdateCall() {#isInBeginUpdateCall--}
```
public boolean isInBeginUpdateCall()
```


Mendapatkan nilai yang menunjukkan apakah grafik berada dalam keadaan pemanggilan BeginUpdate.

**Returns:**
boolean - True jika grafik berada dalam keadaan pemanggilan BeginUpdate; jika tidak, false.
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Mengukur string menggunakan kelas [GraphicsPath](../../com.aspose.psd/graphicspath).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Font. |
| teks | java.lang.String | Teks. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Mengukur string.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Font. |
|  | teks | java.lang.String | Teks. |

--------------------

Hasil GDI hampir selalu tidak valid untuk gaya Italic dan sering tidak valid untuk gaya Bold. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Mengukur string teks yang ditentukan dengan parameter yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks yang akan diukur. |
| font | [Font](../../com.aspose.psd/font) | Font yang akan diukur. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Area tata letak. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Format string. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Pengambilan cache font pribadi. |
| useMagicNumbersForStyles | boolean | jika diatur ke true [gunakan magic numbers untuk gaya]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Mengalikan  com.aspose.psd.Matrix  yang mewakili transformasi geometris lokal dari ini  com.aspose.psd.Graphics  dengan  com.aspose.psd.Matrix  yang ditentukan dengan menambahkan di depan  com.aspose.psd.matrix .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix com.aspose.psd.Matrix yang digunakan untuk mengalikan transformasi geometris. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Mengalikan  com.aspose.psd.Matrix  yang mewakili transformasi geometris lokal dari ini  com.aspose.psd.Graphics  dengan  com.aspose.psd.Matrix  yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix com.aspose.psd.Matrix yang digunakan untuk mengalikan transformasi geometris. |
| urutan | int | Sebuah com.aspose.psd.MatrixOrder yang menentukan urutan pengalian dua matriks. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Mengatur ulang properti  com.aspose.psd.graphics.Transform  menjadi identitas.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Memutar transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Memutar transformasi geometris lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |
| urutan | int | Sebuah com.aspose.psd.MatrixOrder yang menentukan apakah menambahkan atau mendahului matriks rotasi. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Menskala transformasi geometris lokal dengan jumlah yang ditentukan. Metode ini menyisipkan matriks skala ke transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah skala transformasi pada arah sumbu x. |
| sy | float | Jumlah skala transformasi pada arah sumbu y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometris lokal dengan jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Jumlah skala transformasi pada arah sumbu x. |
| sy | float | Jumlah skala transformasi pada arah sumbu y. |
| urutan | int | Sebuah com.aspose.psd.MatrixOrder yang menentukan apakah menambahkan atau mendahului matriks skala. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Mendapatkan atau mengatur wilayah klip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Wilayah klip. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Mendapatkan atau mengatur kualitas komposit.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Kualitas komposit. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Mendapatkan atau mengatur mode interpolasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Mode interpolasi. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Mendapatkan atau mengatur skala antara satuan dunia dan satuan halaman untuk  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Skala antara satuan dunia dan satuan halaman untuk com.aspose.psd.graphics ini. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Mendapatkan atau mengatur satuan ukuran yang digunakan untuk koordinat halaman dalam  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Satuan ukuran yang digunakan untuk koordinat halaman dalam com.aspose.psd.graphics ini. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Mendapatkan atau mengatur opsi gambar, yang digunakan untuk membuat gambar vektor yang dapat digambar.

Nilai: Opsi gambar, digunakan untuk membuat gambar vektor yang dapat dilukis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Mendapatkan atau mengatur mode penghalusan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Mode penghalusan. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Mendapatkan atau mengatur petunjuk perenderan teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Petunjuk perenderan teks. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Mendapatkan atau mengatur salinan transformasi dunia geometris untuk ini  com.aspose.psd.graphics .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Salinan com.aspose.psd.Matrix yang mewakili transformasi dunia geometris untuk com.aspose.psd.graphics ini. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menyisipkan translasi ke transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| urutan | int | Urutan (menyisipkan di awal atau menambahkan di akhir) penerapan translasi. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


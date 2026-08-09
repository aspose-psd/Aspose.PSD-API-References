---
title: "Graphics"
second_title: "Java için Aspose.PSD API Referansı"
description: "Geçerli derlemede kullanılan grafik motoruna göre grafikleri temsil eder."
type: docs
weight: 49
url: /tr/java/com.aspose.psd/graphics/
---

**Inheritance:**
java.lang.Object
```
public final class Graphics
```

Geçerli derlemede kullanılan grafik motoruna göre grafikleri temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Graphics(Image sourceImage)](#Graphics-com.aspose.psd.Image-) | Graphics sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BoldStyleSizeCoefficient_internalized](#BoldStyleSizeCoefficient-internalized) | Kalın metin stili boyut katsayısını alır. |
| [ItalicStyleSizeCoefficient_internalized](#ItalicStyleSizeCoefficient-internalized) | İtalik metin stili boyut katsayısını alır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyEffect_internalized(IEffect effect)](#applyEffect-internalized-com.aspose.internal.IEffect-) | Etkiyi uygular. |
| [beginUpdate()](#beginUpdate--) | Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. |
| [clear(Color color)](#clear-com.aspose.psd.Color-) | Belirtilen rengi kullanarak grafik yüzeyini temizler. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Bir  Rectangle  yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Bir  RectangleF  yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-) | Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-) | Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer. |
| [drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-) | Dört  Point  yapısı ile tanımlanan bir Bézier eğrisi çizer. |
| [drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Dört  PointF  yapısı ile tanımlanan bir Bézier eğrisi çizer. |
| [drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)](#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-) | Nokta temsil eden dört sıralı koordinat çifti ile tanımlanan bir Bézier eğrisi çizer. |
| [drawBeziers(Pen pen, PointF[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Bir dizi  PointF  yapısından Bézier eğrileri serisi çizer. |
| [drawBeziers(Pen pen, Point[] points)](#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---) | Bir dizi  Point  yapısından Bézier eğrileri serisi çizer. |
| [drawClosedCurve(Pen pen, PointF[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Bir dizi  PointF  yapısı ile tanımlanan kapalı bir cardinal spline çizer. |
| [drawClosedCurve(Pen pen, PointF[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Belirli bir gerilim kullanarak, bir dizi  PointF  yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. |
| [drawClosedCurve(Pen pen, Point[] points)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Bir dizi  Point  yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. |
| [drawClosedCurve(Pen pen, Point[] points, float tension)](#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Belirli bir gerilim kullanarak, bir dizi  Point  yapısı tarafından tanımlanan kapalı bir kardinal spline çizer. |
| [drawCurve(Pen pen, PointF[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Belirli bir dizi  PointF  yapısı üzerinden bir kardinal spline çizer. |
| [drawCurve(Pen pen, PointF[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-) | Belirli bir gerilim kullanarak, belirli bir dizi  PointF  yapısı üzerinden bir kardinal spline çizer. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-) | Belirli bir dizi  PointF  yapısı üzerinden bir kardinal spline çizer. |
| [drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-) | Belirli bir gerilim kullanarak, belirli bir dizi  PointF  yapısı üzerinden bir kardinal spline çizer. |
| [drawCurve(Pen pen, Point[] points)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---) | Belirli bir dizi  Point  yapısı üzerinden bir kardinal spline çizer. |
| [drawCurve(Pen pen, Point[] points, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-) | Belirli bir gerilim kullanarak, belirli bir dizi  Point  yapısı üzerinden bir kardinal spline çizer. |
| [drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)](#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-) | Belirli bir gerilim kullanarak, belirli bir dizi  Point  yapısı üzerinden bir kardinal spline çizer. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) | Sınırlayıcı bir  Rectangle  yapısı tarafından belirlenen bir elips çizer. |
| [drawEllipse(Pen pen, RectangleF rect)](#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) | Sınırlayıcı bir  RectangleF  tarafından tanımlanan bir elips çizer. |
| [drawEllipse(Pen pen, float x, float y, float width, float height)](#drawEllipse-com.aspose.psd.Pen-float-float-float-float-) | Bir çift koordinat, bir yükseklik ve bir genişlik tarafından belirlenen sınırlayıcı bir dikdörtgen ile tanımlanan bir elips çizer. |
| [drawEllipse(Pen pen, int x, int y, int width, int height)](#drawEllipse-com.aspose.psd.Pen-int-int-int-int-) | Bir çift koordinat, bir yükseklik ve bir genişlik tarafından belirlenen sınırlayıcı bir dikdörtgen ile tanımlanan bir elips çizer. |
| [drawImage(Image sourceImage, Point point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-) | Belirtilen  Image  öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [drawImage(Image sourceImage, PointF point)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-) | Belirtilen  Image  öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [drawImage(Image image, PointF[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, Point[] destPoints)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, Rectangle rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, RectangleF rect)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)](#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, float x, float y)](#drawImage-com.aspose.psd.Image-float-float-) | Belirtilen  Image  öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer. |
| [drawImage(Image sourceImage, float x, float y, float width, float height)](#drawImage-com.aspose.psd.Image-float-float-float-float-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImage(Image sourceImage, int x, int y)](#drawImage-com.aspose.psd.Image-int-int-) | Bir koordinat çiftiyle belirtilen konumda, özgün fiziksel boyutunu kullanarak, belirtilen resmi çizer. |
| [drawImage(Image sourceImage, int x, int y, int width, int height)](#drawImage-com.aspose.psd.Image-int-int-int-int-) | Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer. |
| [drawImageUnscaled(Image sourceImage, Point point)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [drawImageUnscaled(Image sourceImage, Rectangle rect)](#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [drawImageUnscaled(Image sourceImage, int x, int y)](#drawImageUnscaled-com.aspose.psd.Image-int-int-) | Bir koordinat çiftiyle belirtilen konumda, özgün fiziksel boyutunu kullanarak, belirtilen resmi çizer. |
| [drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)](#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-) | Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer. |
| [drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)](#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-) | Belirtilen resmi ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığdırmak için kırpar. |
| [drawLine(Pen pen, Point point1, Point point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-) | İki  Point  yapısını bağlayan bir çizgi çizer. |
| [drawLine(Pen pen, PointF point1, PointF point2)](#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-) | İki  PointF  yapısını bağlayan bir çizgi çizer. |
| [drawLine(Pen pen, float x1, float y1, float x2, float y2)](#drawLine-com.aspose.psd.Pen-float-float-float-float-) | Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.psd.Pen-int-int-int-int-) | Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer. |
| [drawLines(Pen pen, PointF[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---) | Bir dizi  PointF  yapısını bağlayan bir dizi çizgi segmenti çizer. |
| [drawLines(Pen pen, Point[] points)](#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---) | Bir dizi  Point  yapısını bağlayan bir dizi çizgi segmenti çizer. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-) | Bir  com.aspose.psd.graphicsPath  çizer. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-) | Bir  Rectangle  yapısı ve iki radyal çizgiyle belirlenen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-) | Bir  RectangleF  yapısı ve iki radyal çizgiyle belirlenen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)](#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-) | Koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)](#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-) | Koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer. |
| [drawPolygon(Pen pen, PointF[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---) |   PointF  yapı dizisiyle tanımlanan bir çokgen çizer. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---) |   Point  yapı dizisiyle tanımlanan bir çokgen çizer. |
| [drawRectangle(Pen pen, Rectangle rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-) |   Rectangle  yapısıyla belirtilen bir dikdörtgen çizer. |
| [drawRectangle(Pen pen, RectangleF rect)](#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-) |   RectangleF  yapısıyla belirtilen bir dikdörtgen çizer. |
| [drawRectangle(Pen pen, float x, float y, float width, float height)](#drawRectangle-com.aspose.psd.Pen-float-float-float-float-) | Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.psd.Pen-int-int-int-int-) | Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer. |
| [drawRectangles(Pen pen, RectangleF[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---) |   RectangleF  yapılarına göre belirtilen bir dizi dikdörtgen çizer. |
| [drawRectangles(Pen pen, Rectangle[] rects)](#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---) |   Rectangle  yapılarına göre belirtilen bir dizi dikdörtgen çizer. |
| [drawString(String s, Font font, Brush brush, PointF point)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-) | Belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen konumda belirtilen metin dizesini çizer. |
| [drawString(String s, Font font, Brush brush, PointF point, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-) | Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak belirtilen konumda belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | Belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen dikdörtgende belirtilen metin dizesini çizer. |
| [drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak belirtilen dikdörtgende belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer. |
| [drawString(String s, Font font, Brush brush, float x, float y)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen konumda belirtilen metin dizesini çizer. |
| [drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)](#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-) | Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak belirtilen konumda belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-) | Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak, Adobe uyumlu şekilde, belirtilen dikdörtgende belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer. |
| [drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)](#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-) | Belirtilen konumda Adobe uyumlu şekilde, belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer. |
| [endUpdate()](#endUpdate--) | BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleğe alınmasını tamamlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillClosedCurve(Brush brush, PointF[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---) |   com.aspose.psd.PointF  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | Belirtilen doldurma kipini kullanarak,  com.aspose.psd.PointF  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. |
| [fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-) | Belirtilen doldurma kipini ve gerilimi kullanarak,  com.aspose.psd.PointF  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. |
| [fillClosedCurve(Brush brush, Point[] points)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---) |   com.aspose.psd.Point  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | Belirtilen doldurma kipini kullanarak,  com.aspose.psd.Point  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. |
| [fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)](#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-) | Belirtilen doldurma kipini ve gerilimi kullanarak,  com.aspose.psd.Point  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) |   com.aspose.psd.Rectangle  yapısıyla belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fillEllipse(Brush brush, RectangleF rect)](#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) |   com.aspose.psd.RectangleF  yapısıyla belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fillEllipse(Brush brush, float x, float y, float width, float height)](#fillEllipse-com.aspose.psd.Brush-float-float-float-float-) | Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fillEllipse(Brush brush, int x, int y, int width, int height)](#fillEllipse-com.aspose.psd.Brush-int-int-int-int-) | Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur. |
| [fillPath(Brush brush, GraphicsPath path)](#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-) |   com.aspose.psd.graphicsPath  nesnesinin içini doldurur. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-) | Bir elips tarafından tanımlanan ve bir com.aspose.psd.RectangleF yapısı ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur. |
| [fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-) | Bir elips tarafından tanımlanan ve bir com.aspose.psd.RectangleF yapısı ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur. |
| [fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)](#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-) | Bir elips tarafından tanımlanan ve bir çift koordinat, bir genişlik, bir yükseklik ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur. |
| [fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)](#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-) | Bir elips tarafından tanımlanan ve bir çift koordinat, bir genişlik, bir yükseklik ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur. |
| [fillPolygon(Brush brush, PointF[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---) | com.aspose.psd.PointF yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan ve FillMode.Alternate ile belirtilen çokgenin içini doldurur. |
| [fillPolygon(Brush brush, PointF[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-) | com.aspose.psd.PointF yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan çokgenin, belirtilen doldurma modu kullanılarak içini doldurur. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---) | com.aspose.psd.Point yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan ve FillMode.Alternate ile belirtilen çokgenin içini doldurur. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-) | com.aspose.psd.Point yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan çokgenin, belirtilen doldurma modu kullanılarak içini doldurur. |
| [fillRectangle(Brush brush, Rectangle rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-) | Rectangle yapısı ile belirtilen bir dikdörtgenin içini doldurur. |
| [fillRectangle(Brush brush, RectangleF rect)](#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-) | RectangleF yapısı ile belirtilen bir dikdörtgenin içini doldurur. |
| [fillRectangle(Brush brush, float x, float y, float width, float height)](#fillRectangle-com.aspose.psd.Brush-float-float-float-float-) | Bir çift koordinat, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fillRectangle(Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.psd.Brush-int-int-int-int-) | Bir çift koordinat, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgenin içini doldurur. |
| [fillRectangles(Brush brush, RectangleF[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---) | RectangleF yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fillRectangles(Brush brush, Rectangle[] rects)](#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---) | Rectangle yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur. |
| [fillRegion(Brush brush, Region region)](#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-) | com.aspose.psd.region'un içini doldurur. |
| [getClass()](#getClass--) |  |
| [getClip()](#getClip--) | Kırpma bölgesini alır veya ayarlar. |
| [getCompositingQuality()](#getCompositingQuality--) | Bileşim kalitesini alır veya ayarlar. |
| [getDpiX()](#getDpiX--) | Bu com.aspose.psd.graphics'in yatay çözünürlüğünü alır. |
| [getDpiY()](#getDpiY--) | Bu com.aspose.psd.graphics'in dikey çözünürlüğünü alır. |
| [getImage()](#getImage--) | Görüntüyü alır. |
| [getInterpolationMode()](#getInterpolationMode--) | Ara değerleme modunu alır veya ayarlar. |
| [getPageScale()](#getPageScale--) | Bu com.aspose.psd.graphics için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar. |
| [getPageUnit()](#getPageUnit--) | Bu com.aspose.psd.graphics içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| [getPaintableImageOptions()](#getPaintableImageOptions--) | Çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılan görüntü seçeneklerini alır veya ayarlar. |
| [getSmoothingMode()](#getSmoothingMode--) | Yumuşatma modunu alır veya ayarlar. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Metin renderleme ipucunu alır veya ayarlar. |
| [getTransform()](#getTransform--) | Bu com.aspose.psd.graphics için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isInBeginUpdateCall()](#isInBeginUpdateCall--) | Grafiğin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değeri alır. |
| [measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)](#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-) | Diziyi [GraphicsPath](../../com.aspose.psd/graphicspath) sınıfını kullanarak ölçer. |
| [measureString_internalized(Font font, String text)](#measureString-internalized-com.aspose.psd.Font-java.lang.String-) | Diziyi ölçer. |
| [measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)](#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-) | Belirtilen metin dizisini belirtilen parametrelerle ölçer. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Bu com.aspose.psd.Graphics nesnesinin yerel geometrik dönüşümünü temsil eden com.aspose.psd.Matrix i, belirtilen com.aspose.psd.Matrix ile, belirtilen com.aspose.psd.matrix i ön ekleyerek çarpar. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Bu com.aspose.psd.Graphics nesnesinin yerel geometrik dönüşümünü temsil eden com.aspose.psd.Matrix i, belirtilen com.aspose.psd.Matrix ile belirtilen sırada çarpar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | com.aspose.psd.graphics.Transform özelliğini birim haline sıfırlar. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Yerel geometrik dönüşümü belirtilen miktarda döndürür. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Yerel geometrik dönüşümü belirtilen miktarda ve belirtilen sırada döndürür. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Yerel geometrik dönüşümü belirtilen ölçeklerle ölçeklendirir. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen ölçeklerle ve belirtilen sırada ölçeklendirir. |
| [setClip(Region value)](#setClip-com.aspose.psd.Region-) | Kırpma bölgesini alır veya ayarlar. |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Bileşim kalitesini alır veya ayarlar. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Ara değerleme modunu alır veya ayarlar. |
| [setPageScale(float value)](#setPageScale-float-) | Bu com.aspose.psd.graphics için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar. |
| [setPageUnit(int value)](#setPageUnit-int-) | Bu com.aspose.psd.graphics içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar. |
| [setPaintableImageOptions(ImageOptionsBase value)](#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-) | Çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılan görüntü seçeneklerini alır veya ayarlar. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Yumuşatma modunu alır veya ayarlar. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Metin renderleme ipucunu alır veya ayarlar. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Bu com.aspose.psd.graphics için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Yerel geometrik dönüşümü belirtilen boyutlarla ve belirtilen sırada çevirir. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graphics(Image sourceImage) {#Graphics-com.aspose.psd.Image-}
```
public Graphics(Image sourceImage)
```


Graphics sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Kaynak görüntü. |

### BoldStyleSizeCoefficient_internalized {#BoldStyleSizeCoefficient-internalized}
```
public static final float BoldStyleSizeCoefficient_internalized
```


Kalın metin stili boyut katsayısını alır.

GDI yalnızca Regular stil için ölçüm sağladığından sihirli sayılar kullanılıyor.

### ItalicStyleSizeCoefficient_internalized {#ItalicStyleSizeCoefficient-internalized}
```
public static final float ItalicStyleSizeCoefficient_internalized
```


İtalik metin stili boyut katsayısını alır.

GDI yalnızca Regular stil için ölçüm sağladığından sihirli sayılar kullanılıyor.

### applyEffect_internalized(IEffect effect) {#applyEffect-internalized-com.aspose.internal.IEffect-}
```
public void applyEffect_internalized(IEffect effect)
```


Etkiyi uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| efekt | com.aspose.internal.IEffect | Uygulanacak efekt. |

### beginUpdate() {#beginUpdate--}
```
public void beginUpdate()
```


Aşağıdaki grafik işlemlerinin önbelleğe alınmasını başlatır. Sonradan uygulanan grafik efektleri hemen uygulanmaz, bunun yerine EndUpdate tüm efektlerin bir kerede uygulanmasını sağlar.

BeginUpdate çağrıldıktan sonraki efektlerin, EndUpdate çağrılmadığı takdirde uygulanmayacağını unutmayın.

### clear(Color color) {#clear-com.aspose.psd.Color-}
```
public void clear(Color color)
```


Belirtilen rengi kullanarak grafik yüzeyini temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Grafik yüzeyini temizlemek için kullanılan renk. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Bir  Rectangle  yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yayının renk, genişlik ve stilini belirler. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Ellipse'in sınırlarını tanımlayan RectangleF yapısı. |
| startAngle | float | Yayının başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | float | Yayının bitiş noktasına,  startAngle  parametresinden saat yönünde ölçülen açı (derece). |

### drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Bir  RectangleF  yapısı ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yayının renk, genişlik ve stilini belirler. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Ellipse'in sınırlarını tanımlayan RectangleF yapısı. |
| startAngle | float | Yayının başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | float | Yayının bitiş noktasına,  startAngle  parametresinden saat yönünde ölçülen açı (derece). |

### drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawArc-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawArc(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yayının renk, genişlik ve stilini belirler. |
| x | float | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Ellipse'i tanımlayan dikdörtgenin genişliği. |
| height | float | Ellipse'i tanımlayan dikdörtgenin yüksekliği. |
| startAngle | float | Yayının başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | float | Yayının bitiş noktasına,  startAngle  parametresinden saat yönünde ölçülen açı (derece). |

### drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawArc-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Koordinat çifti, genişlik ve yükseklik ile belirtilen elipsin bir bölümünü temsil eden bir yay çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen yayının renk, genişlik ve stilini belirler. |
| x | int | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Ellipse'i tanımlayan dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Ellipse'i tanımlayan dikdörtgenin genişliği. |
| height | int | Ellipse'i tanımlayan dikdörtgenin yüksekliği. |
| startAngle | int | Yayının başlangıç noktasına x ekseninden saat yönünde ölçülen açı (derece). |
| sweepAngle | int | Yayının bitiş noktasına,  startAngle  parametresinden saat yönünde ölçülen açı (derece). |

### drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Dört  Point  yapısı ile tanımlanan bir Bézier eğrisi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve stilini belirleyen Pen yapısı. |
| pt1 | [Point](../../com.aspose.psd/point) | Point  yapısı, eğrinin başlangıç noktasını temsil eder. |
| pt2 | [Point](../../com.aspose.psd/point) | Point  yapısı, eğri için ilk kontrol noktasını temsil eder. |
| pt3 | [Point](../../com.aspose.psd/point) | Point  yapısı, eğri için ikinci kontrol noktasını temsil eder. |
| pt4 | [Point](../../com.aspose.psd/point) | Point  yapısı, eğrinin bitiş noktasını temsil eder. |

### drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawBezier-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Dört  PointF  yapısı ile tanımlanan bir Bézier eğrisi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  eğrinin renk, genişlik ve stilini belirler. |
| pt1 | [PointF](../../com.aspose.psd/pointf) | PointF  yapısı, eğrinin başlangıç noktasını temsil eder. |
| pt2 | [PointF](../../com.aspose.psd/pointf) | PointF  yapısı, eğri için ilk kontrol noktasını temsil eder. |
| pt3 | [PointF](../../com.aspose.psd/pointf) | PointF  yapısı, eğri için ikinci kontrol noktasını temsil eder. |
| pt4 | [PointF](../../com.aspose.psd/pointf) | PointF  yapısı, eğrinin bitiş noktasını temsil eder. |

### drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4) {#drawBezier-com.aspose.psd.Pen-float-float-float-float-float-float-float-float-}
```
public void drawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, float x4, float y4)
```


Nokta temsil eden dört sıralı koordinat çifti ile tanımlanan bir Bézier eğrisi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  eğrinin renk, genişlik ve stilini belirler. |
| x1 | float | Eğrinin başlangıç noktasının x koordinatı. |
| y1 | float | Eğrinin başlangıç noktasının y koordinatı. |
| x2 | float | Eğrinin ilk kontrol noktasının x koordinatı. |
| y2 | float | Eğrinin ilk kontrol noktasının y koordinatı. |
| x3 | float | Eğrinin ikinci kontrol noktasının x koordinatı. |
| y3 | float | Eğrinin ikinci kontrol noktasının y koordinatı. |
| x4 | float | Eğrinin bitiş noktasının x koordinatı. |
| y4 | float | Eğrinin bitiş noktasının y koordinatı. |

### drawBeziers(Pen pen, PointF[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawBeziers(Pen pen, PointF[] points)
```


Bir dizi  PointF  yapısından Bézier eğrileri serisi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  eğrinin renk, genişlik ve stilini belirler. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Eğriyi belirleyen noktaları temsil eden PointF yapıların dizisi. |

### drawBeziers(Pen pen, Point[] points) {#drawBeziers-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawBeziers(Pen pen, Point[] points)
```


Bir dizi  Point  yapısından Bézier eğrileri serisi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen  eğrinin renk, genişlik ve stilini belirler. |
| points | [Point\[\]](../../com.aspose.psd/point) | Eğriyi belirleyen noktaları temsil eden Point yapıların dizisi. |

### drawClosedCurve(Pen pen, PointF[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawClosedCurve(Pen pen, PointF[] points)
```


Bir PointF yapı dizisiyle tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi ve FillMode.Alternate doldurma modunu kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan PointF yapıların dizisi. |

### drawClosedCurve(Pen pen, PointF[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawClosedCurve(Pen pen, PointF[] points, float tension)
```


Belirli bir gerilim kullanarak, bir PointF yapı dizisiyle tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan FillMode.Alternate doldurma modunu kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan PointF yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### drawClosedCurve(Pen pen, Point[] points) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawClosedCurve(Pen pen, Point[] points)
```


Bir Point yapı dizisiyle tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimi ve FillMode.Alternate doldurma modunu kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan Point yapıların dizisi. |

### drawClosedCurve(Pen pen, Point[] points, float tension) {#drawClosedCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawClosedCurve(Pen pen, Point[] points, float tension)
```


Belirli bir gerilim kullanarak, bir Point yapı dizisiyle tanımlanan kapalı bir kardinal spline çizer. Bu yöntem varsayılan FillMode.Alternate doldurma modunu kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan Point yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### drawCurve(Pen pen, PointF[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawCurve(Pen pen, PointF[] points)
```


Belirtilen PointF yapı dizisi üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilimini kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan PointF yapıların dizisi. |

### drawCurve(Pen pen, PointF[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---float-}
```
public void drawCurve(Pen pen, PointF[] points, float tension)
```


Belirli bir gerilim kullanarak, belirli bir dizi  PointF  yapısı üzerinden bir kardinal spline çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Eğriyi tanımlayan noktaları temsil eden PointF yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```


Belirtilen PointF yapı dizisi üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar. Bu yöntem varsayılan 0.5 gerilimini kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan PointF yapıların dizisi. |
| offset | int | points parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına kadar olan offset. |
| numberOfSegments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |

### drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.PointF---int-int-float-}
```
public void drawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```


Belirli bir gerilim kullanarak, belirtilen PointF yapı dizisi üzerinden bir kardinal spline çizer. Çizim, dizinin başından bir offset ile başlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan PointF yapıların dizisi. |
| offset | int | points parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına kadar olan offset. |
| numberOfSegments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### drawCurve(Pen pen, Point[] points) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawCurve(Pen pen, Point[] points)
```


Belirli bir dizi  Point  yapısı üzerinden bir kardinal spline çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan Point yapıların dizisi. |

### drawCurve(Pen pen, Point[] points, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---float-}
```
public void drawCurve(Pen pen, Point[] points, float tension)
```


Belirli bir gerilim kullanarak, belirli bir dizi  Point  yapısı üzerinden bir kardinal spline çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan Point yapıların dizisi. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension) {#drawCurve-com.aspose.psd.Pen-com.aspose.psd.Point---int-int-float-}
```
public void drawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```


Belirli bir gerilim kullanarak, belirli bir dizi  Point  yapısı üzerinden bir kardinal spline çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Eğrinin renk, genişlik ve yüksekliğini belirleyen Pen. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan Point yapıların dizisi. |
| offset | int | points parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına kadar olan offset. |
| numberOfSegments | int | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Sınırlayıcı bir  Rectangle  yapısı tarafından belirlenen bir elips çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen Pen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Elipsin sınırlarını tanımlayan Rectangle yapısı. |

### drawEllipse(Pen pen, RectangleF rect) {#drawEllipse-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawEllipse(Pen pen, RectangleF rect)
```


Sınırlayıcı bir  RectangleF  tarafından tanımlanan bir elips çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen Pen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Ellipse'in sınırlarını tanımlayan RectangleF yapısı. |

### drawEllipse(Pen pen, float x, float y, float width, float height) {#drawEllipse-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawEllipse(Pen pen, float x, float y, float width, float height)
```


Bir çift koordinat, bir yükseklik ve bir genişlik tarafından belirlenen sınırlayıcı bir dikdörtgen ile tanımlanan bir elips çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen Pen. |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### drawEllipse(Pen pen, int x, int y, int width, int height) {#drawEllipse-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawEllipse(Pen pen, int x, int y, int width, int height)
```


Bir çift koordinat, bir yükseklik ve bir genişlik tarafından belirlenen sınırlayıcı bir dikdörtgen ile tanımlanan bir elips çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Elipsin renk, genişlik ve stilini belirleyen Pen. |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### drawImage(Image sourceImage, Point point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImage(Image sourceImage, Point point)
```


Belirtilen  Image  öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| point | [Point](../../com.aspose.psd/point) | Point  yapısı, çizilen görüntünün sol üst köşesinin konumunu temsil eder. |

### drawImage(Image sourceImage, PointF point) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF-}
```
public void drawImage(Image sourceImage, PointF point)
```


Belirtilen  Image  öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| point | [PointF](../../com.aspose.psd/pointf) | PointF  yapısı, çizilen görüntünün sol üst köşesini temsil eder. |

### drawImage(Image image, PointF[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---}
```
public void drawImage(Image image, PointF[] destPoints)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Kaynak dikdörtgen. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Kaynak dikdörtgen. |
| srcUnit | int | Ölçü birimleri. |

### drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.PointF---com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, PointF[] destPoints, RectangleF srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Kaynak dikdörtgen. |
| srcUnit | int | Ölçü birimleri. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### drawImage(Image image, Point[] destPoints) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---}
```
public void drawImage(Image image, Point[] destPoints)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Kaynak dikdörtgen. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Kaynak dikdörtgen. |
| srcUnit | int | Ölçü birimleri. |

### drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Point---com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image image, Point[] destPoints, Rectangle srcRect, int srcUnit, ImageAttributes imageAttributes)
```


Belirtilen  image  öğesinin belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.psd/image) | Çizilecek görüntü. |
| destPoints | [Point\[\]](../../com.aspose.psd/point) | Paralelkenarı tanımlayan üç PointF yapısından oluşan dizi. |
| srcRect | [Rectangle](../../com.aspose.psd/rectangle) | Kaynak dikdörtgen. |
| srcUnit | int | Ölçü birimleri. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### drawImage(Image sourceImage, Rectangle rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImage(Image sourceImage, Rectangle rect)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  yapısı, çizilen görüntünün konum ve boyutunu belirtir. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Kaynak dikdörtgen. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |

### drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectSource | [Rectangle](../../com.aspose.psd/rectangle) | Kaynak dikdörtgen. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |

### drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.Rectangle-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, Rectangle rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectDestination | [Rectangle](../../com.aspose.psd/rectangle) | Hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### drawImage(Image sourceImage, RectangleF rect) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-}
```
public void drawImage(Image sourceImage, RectangleF rect)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | RectangleF  yapısı, çizilen görüntünün konum ve boyutunu belirtir. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Kaynak dikdörtgen. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |

### drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectSource | [RectangleF](../../com.aspose.psd/rectanglef) | Kaynak dikdörtgen. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Hedef dikdörtgen. |
| graphicsUnit | int | Kullanılacak grafik birimi. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Kullanılacak görüntü öznitelikleri. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |

### drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes) {#drawImage-com.aspose.psd.Image-com.aspose.psd.RectangleF-int-com.aspose.psd.ImageAttributes-}
```
public void drawImage(Image sourceImage, RectangleF rectDestination, int graphicsUnit, ImageAttributes imageAttributes)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rectDestination | [RectangleF](../../com.aspose.psd/rectanglef) | Çizim yapılacak hedef dikdörtgen. |
| graphicsUnit | int | Grafik birimi. |
| imageAttributes | [ImageAttributes](../../com.aspose.psd/imageattributes) | Görüntü öznitelikleri. |

### drawImage(Image sourceImage, float x, float y) {#drawImage-com.aspose.psd.Image-float-float-}
```
public void drawImage(Image sourceImage, float x, float y)
```


Belirtilen  Image  öğesini, özgün fiziksel boyutunu kullanarak, belirtilen konumda çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### drawImage(Image sourceImage, float x, float y, float width, float height) {#drawImage-com.aspose.psd.Image-float-float-float-float-}
```
public void drawImage(Image sourceImage, float x, float y, float width, float height)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| x | float | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | float | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | float | Çizilen görüntünün genişliği. |
| height | float | Çizilen görüntünün yüksekliği. |

### drawImage(Image sourceImage, int x, int y) {#drawImage-com.aspose.psd.Image-int-int-}
```
public void drawImage(Image sourceImage, int x, int y)
```


Bir koordinat çiftiyle belirtilen konumda, özgün fiziksel boyutunu kullanarak, belirtilen resmi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### drawImage(Image sourceImage, int x, int y, int width, int height) {#drawImage-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImage(Image sourceImage, int x, int y, int width, int height)
```


Belirtilen  Image  öğesini, belirtilen konumda ve belirtilen boyutta çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Çizilen görüntünün genişliği. |
| height | int | Çizilen görüntünün yüksekliği. |

### drawImageUnscaled(Image sourceImage, Point point) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Point-}
```
public void drawImageUnscaled(Image sourceImage, Point point)
```


Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| point | [Point](../../com.aspose.psd/point) | Point  yapısı, çizilen görüntünün sol üst köşesini belirtir. |

### drawImageUnscaled(Image sourceImage, Rectangle rect) {#drawImageUnscaled-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaled(Image sourceImage, Rectangle rect)
```


Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle  , çizilen görüntünün sol üst köşesini belirtir. Dikdörtgenin X ve Y özellikleri sol üst köşeyi tanımlar. Width ve Height özellikleri yok sayılır. |

### drawImageUnscaled(Image sourceImage, int x, int y) {#drawImageUnscaled-com.aspose.psd.Image-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y)
```


Bir koordinat çiftiyle belirtilen konumda, özgün fiziksel boyutunu kullanarak, belirtilen resmi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |

### drawImageUnscaled(Image sourceImage, int x, int y, int width, int height) {#drawImageUnscaled-com.aspose.psd.Image-int-int-int-int-}
```
public void drawImageUnscaled(Image sourceImage, int x, int y, int width, int height)
```


Belirtilen bir resmi, özgün fiziksel boyutunu kullanarak, belirtilen bir konumda çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| x | int | Çizilen görüntünün sol üst köşesinin x koordinatı. |
| y | int | Çizilen görüntünün sol üst köşesinin y koordinatı. |
| width | int | Parametre kullanılmaz. |
| height | int | Parametre kullanılmaz. |

### drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect) {#drawImageUnscaledAndClipped-com.aspose.psd.Image-com.aspose.psd.Rectangle-}
```
public void drawImageUnscaledAndClipped(Image sourceImage, Rectangle rect)
```


Belirtilen resmi ölçeklendirmeden çizer ve gerekirse, belirtilen dikdörtgene sığdırmak için kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [Image](../../com.aspose.psd/image) | Çizim için kullanılacak görüntü. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Görüntünün çizileceği  Rectangle  . |

### drawLine(Pen pen, Point point1, Point point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public void drawLine(Pen pen, Point point1, Point point2)
```


İki  Point  yapısını bağlayan bir çizgi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Çizginin renk, genişlik ve stilini belirleyen  Pen . |
| point1 | [Point](../../com.aspose.psd/point) | Bağlanacak ilk noktayı temsil eden  Point  yapısı. |
| point2 | [Point](../../com.aspose.psd/point) | Bağlanacak ikinci noktayı temsil eden  Point  yapısı. |

### drawLine(Pen pen, PointF point1, PointF point2) {#drawLine-com.aspose.psd.Pen-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public void drawLine(Pen pen, PointF point1, PointF point2)
```


İki  PointF  yapısını bağlayan bir çizgi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Çizginin renk, genişlik ve stilini belirleyen  Pen . |
| point1 | [PointF](../../com.aspose.psd/pointf) | Bağlanacak ilk noktayı temsil eden  PointF  yapısı. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Bağlanacak ikinci noktayı temsil eden  PointF  yapısı. |

### drawLine(Pen pen, float x1, float y1, float x2, float y2) {#drawLine-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawLine(Pen pen, float x1, float y1, float x2, float y2)
```


Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Çizginin renk, genişlik ve stilini belirleyen  Pen . |
| x1 | float | İlk noktanın x koordinatı. |
| y1 | float | İlk noktanın y koordinatı. |
| x2 | float | İkinci noktanın x koordinatı. |
| y2 | float | İkinci noktanın y koordinatı. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Koordinat çiftleriyle belirtilen iki noktayı bağlayan bir çizgi çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Çizginin renk, genişlik ve stilini belirleyen  Pen . |
| x1 | int | İlk noktanın x koordinatı. |
| y1 | int | İlk noktanın y koordinatı. |
| x2 | int | İkinci noktanın x koordinatı. |
| y2 | int | İkinci noktanın y koordinatı. |

### drawLines(Pen pen, PointF[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawLines(Pen pen, PointF[] points)
```


Bir dizi  PointF  yapısını bağlayan bir dizi çizgi segmenti çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Çizgi segmentlerinin renk, genişlik ve stilini belirleyen  Pen . |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Bağlanacak noktaları temsil eden  PointF  yapı dizisi. |

### drawLines(Pen pen, Point[] points) {#drawLines-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawLines(Pen pen, Point[] points)
```


Bir dizi  Point  yapısını bağlayan bir dizi çizgi segmenti çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Çizgi segmentlerinin renk, genişlik ve stilini belirleyen  Pen . |
| points | [Point\[\]](../../com.aspose.psd/point) | Bağlanacak noktaları temsil eden  Point  yapı dizisi. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.psd.Pen-com.aspose.psd.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Bir  com.aspose.psd.graphicsPath  çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Yolun renk, genişlik ve stilini belirleyen  com.aspose.psd.Pen . |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Çizmek için  com.aspose.psd.GraphicsPath . |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Bir  Rectangle  yapısı ve iki radyal çizgiyle belirlenen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pasta diliminin renk, genişlik ve stilini belirleyen  Pen . |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden  Rectangle  yapısı. |
| startAngle | float | Pasta diliminin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | float | Pasta diliminin ikinci kenarına  startAngle  parametresinden saat yönünde derece cinsinden ölçülen açı. |

### drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-com.aspose.psd.RectangleF-float-float-}
```
public void drawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```


Bir  RectangleF  yapısı ve iki radyal çizgiyle belirlenen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pasta diliminin renk, genişlik ve stilini belirleyen  Pen . |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden  RectangleF  yapısı. |
| startAngle | float | Pasta diliminin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | float | Pasta diliminin ikinci kenarına  startAngle  parametresinden saat yönünde derece cinsinden ölçülen açı. |

### drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle) {#drawPie-com.aspose.psd.Pen-float-float-float-float-float-float-}
```
public void drawPie(Pen pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pasta diliminin renk, genişlik ve stilini belirleyen  Pen . |
| x | float | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | float | Pasta diliminin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | float | Pasta diliminin ikinci kenarına  startAngle  parametresinden saat yönünde derece cinsinden ölçülen açı. |

### drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle) {#drawPie-com.aspose.psd.Pen-int-int-int-int-int-int-}
```
public void drawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Koordinat çifti, bir genişlik, bir yükseklik ve iki radyal çizgiyle belirtilen bir elips tarafından tanımlanan bir pasta şekli çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pasta diliminin renk, genişlik ve stilini belirleyen  Pen . |
| x | int | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Pasta diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | int | Pasta diliminin ilk kenarına x ekseninden saat yönünde derece cinsinden ölçülen açı. |
| sweepAngle | int | Pasta diliminin ikinci kenarına  startAngle  parametresinden saat yönünde derece cinsinden ölçülen açı. |

### drawPolygon(Pen pen, PointF[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.PointF---}
```
public void drawPolygon(Pen pen, PointF[] points)
```


  PointF  yapı dizisiyle tanımlanan bir çokgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Poligonun renk, genişlik ve stilini belirleyen  Pen . |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Poligonun köşelerini temsil eden PointF yapıların dizisi. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.psd.Pen-com.aspose.psd.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


  Point  yapı dizisiyle tanımlanan bir çokgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Poligonun renk, genişlik ve stilini belirleyen  Pen . |
| points | [Point\[\]](../../com.aspose.psd/point) | Poligonun köşelerini temsil eden Point yapıların dizisi. |

### drawRectangle(Pen pen, Rectangle rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rect)
```


  Rectangle  yapısıyla belirtilen bir dikdörtgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen Pen. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Çizilecek dikdörtgeni temsil eden Rectangle yapısı. |

### drawRectangle(Pen pen, RectangleF rect) {#drawRectangle-com.aspose.psd.Pen-com.aspose.psd.RectangleF-}
```
public void drawRectangle(Pen pen, RectangleF rect)
```


  RectangleF  yapısıyla belirtilen bir dikdörtgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen Pen. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Çizilecek dikdörtgeni temsil eden RectangleF yapısı. |

### drawRectangle(Pen pen, float x, float y, float width, float height) {#drawRectangle-com.aspose.psd.Pen-float-float-float-float-}
```
public void drawRectangle(Pen pen, float x, float y, float width, float height)
```


Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen Pen. |
| x | float | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Çizilecek dikdörtgenin genişliği. |
| height | float | Çizilecek dikdörtgenin yüksekliği. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.psd.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Dikdörtgenin renk, genişlik ve stilini belirleyen Pen. |
| x | int | Çizilecek dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Çizilecek dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Çizilecek dikdörtgenin genişliği. |
| height | int | Çizilecek dikdörtgenin yüksekliği. |

### drawRectangles(Pen pen, RectangleF[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.RectangleF---}
```
public void drawRectangles(Pen pen, RectangleF[] rects)
```


  RectangleF  yapılarına göre belirtilen bir dizi dikdörtgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Dikdörtgenlerin kenarlarının renk, genişlik ve stilini belirleyen Pen. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Çizilecek dikdörtgenleri temsil eden RectangleF yapıların dizisi. |

### drawRectangles(Pen pen, Rectangle[] rects) {#drawRectangles-com.aspose.psd.Pen-com.aspose.psd.Rectangle---}
```
public void drawRectangles(Pen pen, Rectangle[] rects)
```


  Rectangle  yapılarına göre belirtilen bir dizi dikdörtgen çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Dikdörtgenlerin kenarlarının renk, genişlik ve stilini belirleyen Pen. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Çizilecek dikdörtgenleri temsil eden Rectangle yapıların dizisi. |

### drawString(String s, Font font, Brush brush, PointF point) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-}
```
public void drawString(String s, Font font, Brush brush, PointF point)
```


Belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen konumda belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF yapısı, çizilen metnin sol üst köşesini belirtir. |

### drawString(String s, Font font, Brush brush, PointF point, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.PointF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, PointF point, StringFormat format)
```


Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak belirtilen konumda belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF yapısı, çizilen metnin sol üst köşesini belirtir. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirtir. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle)
```


Belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen dikdörtgende belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yapısı, çizilen metnin konumunu belirtir. |

### drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak belirtilen dikdörtgende belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yapısı, çizilen metnin konumunu belirtir. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirtir. |

### drawString(String s, Font font, Brush brush, float x, float y) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawString(String s, Font font, Brush brush, float x, float y)
```


Belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen konumda belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |

### drawString(String s, Font font, Brush brush, float x, float y, StringFormat format) {#drawString-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-com.aspose.psd.StringFormat-}
```
public void drawString(String s, Font font, Brush brush, float x, float y, StringFormat format)
```


Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak belirtilen konumda belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirtir. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-com.aspose.psd.RectangleF-com.aspose.psd.StringFormat-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, RectangleF layoutRectangle, StringFormat format)
```


Belirtilen  com.aspose.psd.stringFormat  biçimlendirme özniteliklerini kullanarak, Adobe uyumlu şekilde, belirtilen dikdörtgende belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| layoutRectangle | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yapısı, çizilen metnin konumunu belirtir. |
| format | [StringFormat](../../com.aspose.psd/stringformat) | com.aspose.psd.StringFormat, çizilen metne uygulanan satır aralığı ve hizalama gibi biçimlendirme özelliklerini belirtir. |

### drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y) {#drawStringAdobe-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.Brush-float-float-}
```
public void drawStringAdobe_internalized(String s, Font font, Brush brush, float x, float y)
```


Belirtilen konumda Adobe uyumlu şekilde, belirtilen  com.aspose.psd.Brush  ve  com.aspose.psd.Font  nesneleriyle belirtilen metin dizesini çizer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | java.lang.String | Çizilecek dize. |
| font | [Font](../../com.aspose.psd/font) | com.aspose.psd.Font, dize metin biçimini tanımlar. |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, çizilen metnin renk ve dokusunu belirler. |
| x | float | Çizilen metnin sol üst köşesinin x koordinatı. |
| y | float | Çizilen metnin sol üst köşesinin y koordinatı. |

### endUpdate() {#endUpdate--}
```
public void endUpdate()
```


BeginUpdate çağrıldıktan sonra başlatılan grafik işlemlerinin önbelleklemesi tamamlanır. Önceki grafik işlemleri bu yöntem çağrıldığında bir kerede uygulanır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillClosedCurve(Brush brush, PointF[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillClosedCurve(Brush brush, PointF[] points)
```


Kapalı bir kardinal spline eğrisinin içini, bir dizi com.aspose.psd.PointF yapısı ile tanımlanmış şekilde doldurur. Bu yöntem, varsayılan 0.5 gerilim ve FillMode.Alternate doldurma modunu kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan com.aspose.psd.PointF yapılarının dizisi. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode)
```


Belirtilen doldurma modu kullanılarak, bir dizi com.aspose.psd.PointF yapısı ile tanımlanmış kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0.5 gerilim kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan com.aspose.psd.PointF yapılarının dizisi. |
| doldurma modu | int | Eğrinin nasıl doldurulacağını belirleyen com.aspose.psd.FillMode enum üyesi. |

### fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.PointF---int-float-}
```
public void fillClosedCurve(Brush brush, PointF[] points, int fillmode, float tension)
```


Belirtilen doldurma kipini ve gerilimi kullanarak,  com.aspose.psd.PointF  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen bir com.aspose.psd.Brush. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Spline'ı tanımlayan com.aspose.psd.PointF yapılarının dizisi. |
| doldurma modu | int | Eğrinin nasıl doldurulacağını belirleyen com.aspose.psd.FillMode enum üyesi. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### fillClosedCurve(Brush brush, Point[] points) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillClosedCurve(Brush brush, Point[] points)
```


Kapalı bir kardinal spline eğrisinin içini, bir dizi com.aspose.psd.Point yapısı ile tanımlanmış şekilde doldurur. Bu yöntem varsayılan 0.5 gerilim ve FillMode.Alternate doldurma modunu kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan com.aspose.psd.Point yapılarının dizisi. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode)
```


Belirtilen doldurma modu kullanılarak, bir dizi com.aspose.psd.Point yapısı ile tanımlanmış kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0.5 gerilim kullanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan com.aspose.psd.Point yapılarının dizisi. |
| doldurma modu | int | Eğrinin nasıl doldurulacağını belirleyen com.aspose.psd.FillMode enum üyesi. |

### fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension) {#fillClosedCurve-com.aspose.psd.Brush-com.aspose.psd.Point---int-float-}
```
public void fillClosedCurve(Brush brush, Point[] points, int fillmode, float tension)
```


Belirtilen doldurma kipini ve gerilimi kullanarak,  com.aspose.psd.Point  yapı dizisiyle tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [Point\[\]](../../com.aspose.psd/point) | Spline'ı tanımlayan com.aspose.psd.Point yapılarının dizisi. |
| doldurma modu | int | Eğrinin nasıl doldurulacağını belirleyen com.aspose.psd.FillMode enum üyesi. |
| gerilim | float | Eğrinin gerilimini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


  com.aspose.psd.Rectangle  yapısıyla belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden com.aspose.psd.Rectangle yapısı. |

### fillEllipse(Brush brush, RectangleF rect) {#fillEllipse-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillEllipse(Brush brush, RectangleF rect)
```


  com.aspose.psd.RectangleF  yapısıyla belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden com.aspose.psd.RectangleF yapısı. |

### fillEllipse(Brush brush, float x, float y, float width, float height) {#fillEllipse-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillEllipse(Brush brush, float x, float y, float width, float height)
```


Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| x | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### fillEllipse(Brush brush, int x, int y, int width, int height) {#fillEllipse-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillEllipse(Brush brush, int x, int y, int width, int height)
```


Koordinat çifti, bir genişlik ve bir yükseklik ile belirtilen sınırlayıcı dikdörtgenle tanımlanan bir elipsin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| x | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | Elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |

### fillPath(Brush brush, GraphicsPath path) {#fillPath-com.aspose.psd.Brush-com.aspose.psd.GraphicsPath-}
```
public void fillPath(Brush brush, GraphicsPath path)
```


  com.aspose.psd.graphicsPath  nesnesinin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | doldurulacak yolu temsil eden com.aspose.psd.GraphicsPath. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Bir elips tarafından tanımlanan ve bir com.aspose.psd.RectangleF yapısı ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden com.aspose.psd.Rectangle yapısı. |
| startAngle | float | x ekseninden saat yönünde ölçülen, pay diliminin ilk kenarına kadar olan açı (derece). |
| sweepAngle | float | startAngle parametresinden saat yönünde ölçülen, pay diliminin ikinci kenarına kadar olan açı (derece). |

### fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-com.aspose.psd.RectangleF-float-float-}
```
public void fillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```


Bir elips tarafından tanımlanan ve bir com.aspose.psd.RectangleF yapısı ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgeni temsil eden com.aspose.psd.RectangleF yapısı. |
| startAngle | float | x ekseninden saat yönünde ölçülen, pay diliminin ilk kenarına kadar olan açı (derece). |
| sweepAngle | float | startAngle parametresinden saat yönünde ölçülen, pay diliminin ikinci kenarına kadar olan açı (derece). |

### fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle) {#fillPie-com.aspose.psd.Brush-float-float-float-float-float-float-}
```
public void fillPie(Brush brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


Bir elips tarafından tanımlanan ve bir çift koordinat, bir genişlik, bir yükseklik ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| x | float | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | float | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | float | x ekseninden saat yönünde ölçülen, pay diliminin ilk kenarına kadar olan açı (derece). |
| sweepAngle | float | startAngle parametresinden saat yönünde ölçülen, pay diliminin ikinci kenarına kadar olan açı (derece). |

### fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle) {#fillPie-com.aspose.psd.Brush-int-int-int-int-int-int-}
```
public void fillPie(Brush brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


Bir elips tarafından tanımlanan ve bir çift koordinat, bir genişlik, bir yükseklik ve iki radyal çizgi ile belirtilen pasta diliminin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| x | int | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin genişliği. |
| height | int | pay diliminin geldiği elipsi tanımlayan sınırlayıcı dikdörtgenin yüksekliği. |
| startAngle | int | x ekseninden saat yönünde ölçülen, pay diliminin ilk kenarına kadar olan açı (derece). |
| sweepAngle | int | startAngle parametresinden saat yönünde ölçülen, pay diliminin ikinci kenarına kadar olan açı (derece). |

### fillPolygon(Brush brush, PointF[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---}
```
public void fillPolygon(Brush brush, PointF[] points)
```


com.aspose.psd.PointF yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan ve FillMode.Alternate ile belirtilen çokgenin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | doldurulacak çokgenin köşe noktalarını temsil eden com.aspose.psd.PointF yapılarının dizisi. |

### fillPolygon(Brush brush, PointF[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.PointF---int-}
```
public void fillPolygon(Brush brush, PointF[] points, int fillMode)
```


com.aspose.psd.PointF yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan çokgenin, belirtilen doldurma modu kullanılarak içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | doldurulacak çokgenin köşe noktalarını temsil eden com.aspose.psd.PointF yapılarının dizisi. |
| fillMode | int | doldurmanın stilini belirleyen com.aspose.psd.FillMode enum üyesi. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


com.aspose.psd.Point yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan ve FillMode.Alternate ile belirtilen çokgenin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [Point\[\]](../../com.aspose.psd/point) | doldurulacak çokgenin köşe noktalarını temsil eden com.aspose.psd.Point yapılarının dizisi. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.psd.Brush-com.aspose.psd.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


com.aspose.psd.Point yapılarıyla belirtilen bir dizi nokta tarafından tanımlanan çokgenin, belirtilen doldurma modu kullanılarak içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| points | [Point\[\]](../../com.aspose.psd/point) | doldurulacak çokgenin köşe noktalarını temsil eden com.aspose.psd.Point yapılarının dizisi. |
| fillMode | int | doldurmanın stilini belirleyen com.aspose.psd.FillMode enum üyesi. |

### fillRectangle(Brush brush, Rectangle rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rect)
```


Rectangle yapısı ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen Brush. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Doldurulacak dikdörtgeni temsil eden Rectangle yapısı. |

### fillRectangle(Brush brush, RectangleF rect) {#fillRectangle-com.aspose.psd.Brush-com.aspose.psd.RectangleF-}
```
public void fillRectangle(Brush brush, RectangleF rect)
```


RectangleF yapısı ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen Brush. |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Doldurulacak dikdörtgeni temsil eden RectangleF yapısı. |

### fillRectangle(Brush brush, float x, float y, float width, float height) {#fillRectangle-com.aspose.psd.Brush-float-float-float-float-}
```
public void fillRectangle(Brush brush, float x, float y, float width, float height)
```


Bir çift koordinat, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen Brush. |
| x | float | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | float | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | float | Doldurulacak dikdörtgenin genişliği. |
| height | float | Doldurulacak dikdörtgenin yüksekliği. |

### fillRectangle(Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.psd.Brush-int-int-int-int-}
```
public void fillRectangle(Brush brush, int x, int y, int width, int height)
```


Bir çift koordinat, bir genişlik ve bir yükseklik ile belirtilen bir dikdörtgenin içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen Brush. |
| x | int | Doldurulacak dikdörtgenin sol üst köşesinin x koordinatı. |
| y | int | Doldurulacak dikdörtgenin sol üst köşesinin y koordinatı. |
| width | int | Doldurulacak dikdörtgenin genişliği. |
| height | int | Doldurulacak dikdörtgenin yüksekliği. |

### fillRectangles(Brush brush, RectangleF[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.RectangleF---}
```
public void fillRectangles(Brush brush, RectangleF[] rects)
```


RectangleF yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen Brush. |
| rects | [RectangleF\[\]](../../com.aspose.psd/rectanglef) | Doldurulacak dikdörtgenleri temsil eden Rectangle yapılarını içeren dizi. |

### fillRectangles(Brush brush, Rectangle[] rects) {#fillRectangles-com.aspose.psd.Brush-com.aspose.psd.Rectangle---}
```
public void fillRectangles(Brush brush, Rectangle[] rects)
```


Rectangle yapılarıyla belirtilen bir dizi dikdörtgenin içlerini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Doldurmanın özelliklerini belirleyen Brush. |
| rects | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Doldurulacak dikdörtgenleri temsil eden Rectangle yapılarını içeren dizi. |

### fillRegion(Brush brush, Region region) {#fillRegion-com.aspose.psd.Brush-com.aspose.psd.Region-}
```
public void fillRegion(Brush brush, Region region)
```


com.aspose.psd.region'un içini doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | com.aspose.psd.Brush, doldurmanın özelliklerini belirler. |
| region | [Region](../../com.aspose.psd/region) | Doldurulacak alanı temsil eden com.aspose.psd.Region. |

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


Kırpma bölgesini alır veya ayarlar.

**Returns:**
[Region](../../com.aspose.psd/region) - The clip region.
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Bileşim kalitesini alır veya ayarlar.

**Returns:**
int - Birleştirme kalitesi.
### getDpiX() {#getDpiX--}
```
public float getDpiX()
```


Bu com.aspose.psd.graphics'in yatay çözünürlüğünü alır.

**Returns:**
float - Bu com.aspose.psd.graphics tarafından desteklenen yatay çözünürlük için inç başına nokta cinsinden değer.
### getDpiY() {#getDpiY--}
```
public float getDpiY()
```


Bu com.aspose.psd.graphics'in dikey çözünürlüğünü alır.

**Returns:**
float - Bu com.aspose.psd.graphics tarafından desteklenen dikey çözünürlük için inç başına nokta cinsinden değer.
### getImage() {#getImage--}
```
public Image getImage()
```


Görüntüyü alır.

**Returns:**
[Image](../../com.aspose.psd/image) - The graphics image.
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Ara değerleme modunu alır veya ayarlar.

**Returns:**
int - Ara değerleme modu.
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Bu com.aspose.psd.graphics için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar.

**Returns:**
float - Bu com.aspose.psd.graphics için dünya birimleri ile sayfa birimleri arasındaki ölçekleme.
### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Bu com.aspose.psd.graphics içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar.

**Returns:**
int - Bu com.aspose.psd.graphics içindeki sayfa koordinatları için kullanılan ölçü birimi.
### getPaintableImageOptions() {#getPaintableImageOptions--}
```
public final ImageOptionsBase getPaintableImageOptions()
```


Çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılan görüntü seçeneklerini alır veya ayarlar.

Değer: Çizim için boyanabilir vactor görüntüleri oluşturmakta kullanılan görüntü seçenekleri.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Yumuşatma modunu alır veya ayarlar.

**Returns:**
int - Yumuşatma modu.
### getTextRenderingHint() {#getTextRenderingHint--}
```
public int getTextRenderingHint()
```


Metin renderleme ipucunu alır veya ayarlar.

**Returns:**
int - Metin renderleme ipucu.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Bu com.aspose.psd.graphics için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar.

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


Grafiğin BeginUpdate çağrı durumunda olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean -  True  eğer grafik BeginUpdate çağrı durumundaysa; aksi takdirde,  false .
### measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache) {#measureStringByPath-internalized-com.aspose.psd.Font-java.lang.String-com.aspose.internal.GetPrivateFontCache-}
```
public static RectangleF measureStringByPath_internalized(Font textFont, String text, GetPrivateFontCache getPrivateFontCache)
```


Diziyi [GraphicsPath](../../com.aspose.psd/graphicspath) sınıfını kullanarak ölçer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFont | [Font](../../com.aspose.psd/font) | Yazı tipi. |
| metin | java.lang.String | Metin. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The bounds of the string
### measureString_internalized(Font font, String text) {#measureString-internalized-com.aspose.psd.Font-java.lang.String-}
```
public static SizeF measureString_internalized(Font font, String text)
```


Diziyi ölçer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| font | [Font](../../com.aspose.psd/font) | Yazı tipi. |
|  | metin | java.lang.String | Metin. |

--------------------

GDI sonucu neredeyse her zaman Italic için geçerli değildir ve genellikle Bold stilleri için geçerli değildir. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The width and height of the string
### measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles) {#measureString-internalized-java.lang.String-com.aspose.psd.Font-com.aspose.psd.SizeF-com.aspose.psd.StringFormat-com.aspose.internal.GetPrivateFontCache-boolean-}
```
public static SizeF measureString_internalized(String text, Font font, SizeF layoutArea, StringFormat stringFormat, GetPrivateFontCache getPrivateFontCache, boolean useMagicNumbersForStyles)
```


Belirtilen metin dizisini belirtilen parametrelerle ölçer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Ölçülecek metin. |
| font | [Font](../../com.aspose.psd/font) | Ölçülecek yazı tipi. |
| layoutArea | [SizeF](../../com.aspose.psd/sizef) | Düzen alanı. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | Dize biçimi. |
| getPrivateFontCache | com.aspose.internal.GetPrivateFontCache | Özel yazı tipi önbelleğini al. |
| useMagicNumbersForStyles | boolean | eğer true olarak ayarlanırsa [stil için sihirli sayıları kullan]. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - Size in pixels of measured text string
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Bu com.aspose.psd.Graphics nesnesinin yerel geometrik dönüşümünü temsil eden com.aspose.psd.Matrix i, belirtilen com.aspose.psd.Matrix ile, belirtilen com.aspose.psd.matrix i ön ekleyerek çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılan com.aspose.psd.Matrix. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Bu com.aspose.psd.Graphics nesnesinin yerel geometrik dönüşümünü temsil eden com.aspose.psd.Matrix i, belirtilen com.aspose.psd.Matrix ile belirtilen sırada çarpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Geometrik dönüşümü çarpmak için kullanılan com.aspose.psd.Matrix. |
| order | int | İki matrisi hangi sırayla çarpacağını belirten com.aspose.psd.MatrixOrder. |

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


com.aspose.psd.graphics.Transform özelliğini birim haline sıfırlar.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Yerel geometrik dönüşümü belirtilen miktarda döndürür. Bu yöntem dönüşüme rotasyonu ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönüşüm açısı. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Yerel geometrik dönüşümü belirtilen miktarda ve belirtilen sırada döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | float | Dönüşüm açısı. |
| order | int | Rotasyon matrisini ekleme ya da başa ekleme belirten com.aspose.psd.MatrixOrder. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Yerel geometrik dönüşümü belirtilen miktarlarda ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Yerel geometrik dönüşümü belirtilen ölçeklerle ve belirtilen sırada ölçeklendirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | float | Dönüşümün x ekseni yönünde ölçeklenecek miktarı. |
| sy | float | Dönüşümün y ekseni yönünde ölçeklenecek miktarı. |
| order | int | Ölçekleme matrisini ekleme ya da başa ekleme belirten com.aspose.psd.MatrixOrder. |

### setClip(Region value) {#setClip-com.aspose.psd.Region-}
```
public void setClip(Region value)
```


Kırpma bölgesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Region](../../com.aspose.psd/region) | Kırpma bölgesi. |

### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Bileşim kalitesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bileşim kalitesi. |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Ara değerleme modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Aradeğerleme modu. |

### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Bu com.aspose.psd.graphics için dünya birimleri ile sayfa birimleri arasındaki ölçeklemeyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Bu com.aspose.psd.graphics için dünya birimleri ile sayfa birimleri arasındaki ölçekleme. |

### setPageUnit(int value) {#setPageUnit-int-}
```
public void setPageUnit(int value)
```


Bu com.aspose.psd.graphics içindeki sayfa koordinatları için kullanılan ölçü birimini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu com.aspose.psd.graphics içindeki sayfa koordinatları için kullanılan ölçü birimi. |

### setPaintableImageOptions(ImageOptionsBase value) {#setPaintableImageOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setPaintableImageOptions(ImageOptionsBase value)
```


Çizim için boyanabilir vektör görüntüleri oluşturmakta kullanılan görüntü seçeneklerini alır veya ayarlar.

Değer: Çizim için boyanabilir vactor görüntüleri oluşturmakta kullanılan görüntü seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Yumuşatma modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yumuşatma modu. |

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public void setTextRenderingHint(int value)
```


Metin renderleme ipucunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Metin renderleme ipucu. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Bu com.aspose.psd.graphics için geometrik dünya dönüşümünün bir kopyasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Bu com.aspose.psd.graphics için geometrik dünya dönüşümünü temsil eden com.aspose.psd.Matrix'in bir kopyası. |

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


Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem çeviriyi dönüşüme ön ek olarak ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Yerel geometrik dönüşümü belirtilen boyutlarla ve belirtilen sırada çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx | float | x eksenindeki çevirinin değeri. |
| dy | float | y eksenindeki çevirinin değeri. |
| order | int | Çevirinin uygulanacağı sıra (ön ekleme veya ekleme). |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


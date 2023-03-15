---
title: Class PieShape
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Shapes.PieShape sınıf. Bir pasta şeklini temsil eder.
type: docs
weight: 5500
url: /tr/net/aspose.psd.shapes/pieshape/
---
## PieShape class

Bir pasta şeklini temsil eder.

```csharp
public class PieShape : EllipseShape
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PieShape](pieshape/#constructor)() | Yeni bir örneğini başlatır.`PieShape` sınıf. |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | Yeni bir örneğini başlatır.`PieShape` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Şeklin merkezini alır. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Şeklin segmentleri olup olmadığını gösteren bir değer alır. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Sol alttaki dikdörtgen noktasını alır. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Sol üst dikdörtgen noktasını alır. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Dikdörtgen yüksekliğini alır. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Dikdörtgen genişliğini alır. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Sağ alttaki dikdörtgen noktasını alır. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Sağ üst dikdörtgen noktasını alır. |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | Şekil segmentlerini alır. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Başlangıç açısını alır veya ayarlar. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Tarama açısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

### Örnekler

Bu örnek, yeni bir Görüntü oluşturur ve Görüntü yüzeyinde Figures ve GraphicsPath kullanarak çeşitli şekiller çizer.

```csharp
[C#]

//Görüntünün bir örneğini oluştur
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    // GraphicsPath sınıfının bir örneğini oluşturun
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // Figure sınıfının bir örneğini oluştur
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Şekil nesnesine Şekil ekle
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // Figure sınıfının bir örneğini oluştur
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Şekil nesnesine Şekil ekle
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    // Figure nesnesini GraphicsPath'e ekle
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Siyah renkli Kalem nesnesiyle yol çizin
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Dışa aktarma seçenekleri oluşturun ve bunları başlatın.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // tüm değişiklikleri kaydet.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Ayrıca bakınız

* class [EllipseShape](../ellipseshape/)
* ad alanı [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* toplantı [Aspose.PSD](../../)



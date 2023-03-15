---
title: Class PolygonShape
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Shapes.PolygonShape sınıf. Çokgen şeklini temsil eder.
type: docs
weight: 5510
url: /tr/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

Çokgen şeklini temsil eder.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Yeni bir örneğini başlatır.`PolygonShape` sınıf. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Yeni bir örneğini başlatır.`PolygonShape` sınıf. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Yeni bir örneğini başlatır.`PolygonShape` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Şeklin merkezini alır. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Bitiş şekil noktasını alır. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Şeklin segmentleri olup olmadığını gösteren bir değer alır. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Şeklin kapalı olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Eğri noktalarını alır veya ayarlar. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Şekil segmentlerini alır. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Başlangıç şekil noktasını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Bu şekil için noktaların sırasını tersine çevirir. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* ad alanı [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* toplantı [Aspose.PSD](../../)



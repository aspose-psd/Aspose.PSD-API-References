---
title: "Sınıf PolygonShape"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Shapes.PolygonShape sınıfı. Çokgen bir şekli temsil eder"
type: docs
weight: 6040
url: /tr/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Bir çokgen şekli temsil eder.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | `PolygonShape` sınıfının yeni bir örneğini başlatır. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | `PolygonShape` sınıfının yeni bir örneğini başlatır. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | `PolygonShape` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Şeklin merkezini alır. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Şeklin son noktasını alır. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Eğri noktalarını alır veya ayarlar. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Şekil segmentlerini alır. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Şeklin başlangıç noktasını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Bu şekil için nokta sırasını tersine çevirir. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

## Örnekler

Bu örnek yeni bir Image oluşturur ve Image yüzeyinde Figures ve GraphicsPath kullanarak çeşitli şekiller çizer.

```csharp
[C#]

//Image bir örneği oluşturun.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturun ve başlatın.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizleyin.
    graphics.Clear(Color.Wheat);

    //GraphicsPath sınıfının bir örneğini oluşturun.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure sınıfının bir örneğini oluşturun.
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Figure nesnesine Shape ekle
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Figure sınıfının bir örneğini oluşturun.
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Figure nesnesine Shape ekle
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Figure nesnesini GraphicsPath'e ekleyin.
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Siyah renkli Pen nesnesiyle yolu çizin.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Dışa aktarma seçeneklerini oluşturun ve başlatın.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // tüm değişiklikleri kaydet.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Ayrıca Bakınız

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



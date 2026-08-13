---
title: "Sınıf RectangleShape"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Shapes.RectangleShape sınıfı. Dikdörtgen bir şekil temsil eder"
type: docs
weight: 6060
url: /tr/net/aspose.psd.shapes/rectangleshape/
---
{{< psd/tize >}}
## RectangleShape class

Bir dikdörtgen şekli temsil eder.

```csharp
public class RectangleShape : RectangleProjectedShape
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | `RectangleShape` sınıfının yeni bir örneğini başlatır. |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | `RectangleShape` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Nesnenin sınırlarını alır. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Şeklin merkezini alır. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Sol alt dikdörtgen noktasını alır. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Sol üst dikdörtgen noktasını alır. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Dikdörtgen yüksekliğini alır. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Dikdörtgen genişliğini alır. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Sağ alt dikdörtgen noktasını alır. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Sağ üst dikdörtgen noktasını alır. |
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | Şekil segmentlerini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

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

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



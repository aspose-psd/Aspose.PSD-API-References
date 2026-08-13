---
title: "Figure.AddShapes"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Figure yöntemi. Figüre bir dizi şekil ekler."
type: docs
weight: 70
url: /tr/net/aspose.psd/figure/addshapes/
---
{{< psd/tize >}}
## Figure.AddShapes method

Şekle bir dizi şekil ekler.

```csharp
public void AddShapes(Shape[] shapes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| şekiller | Shape[] | Eklenecek şekiller. |

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

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



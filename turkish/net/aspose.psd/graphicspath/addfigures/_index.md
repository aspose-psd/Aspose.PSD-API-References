---
title: GraphicsPath.AddFigures
second_title: Aspose.PSD for .NET API Referansı
description: GraphicsPath yöntem. Yeni rakamlar ekler.
type: docs
weight: 60
url: /tr/net/aspose.psd/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

Yeni rakamlar ekler.

```csharp
public void AddFigures(Figure[] figures)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| figures | Figure[] | Eklenecek rakamlar. |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* ad alanı [Aspose.PSD](../../graphicspath/)
* toplantı [Aspose.PSD](../../../)



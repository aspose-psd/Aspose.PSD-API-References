---
title: Figure.AddShape
second_title: Aspose.PSD for .NET API Referansı
description: Figure yöntem. Şekle bir şekil ekler.
type: docs
weight: 60
url: /tr/net/aspose.psd/figure/addshape/
---
## Figure.AddShape method

Şekle bir şekil ekler.

```csharp
public void AddShape(Shape shape)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| shape | Shape | Eklenecek şekil. |

### Örnekler

Bu örnekler, bir Image yüzeyinde Figures oluşturmak ve bunları değiştirmek için GraphicsPath ve Graphics sınıfını kullanır. Örnek yeni bir Image oluşturur ve GraphicsPath sınıfının yardımıyla yolları çizer. Sonunda, yolları yüzeyde işlemek için Graphics sınıfı tarafından sunulan DrawPath yöntemi çağrılır. Son olarak görüntü, Tiff dosya biçiminde dışa aktarılır.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Şekil nesnesine Şekiller ekleyin
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // Figure nesnesini GraphicsPath'e ekle
    graphicspath.AddFigure(figure);

    //Siyah renkli Kalem nesnesiyle yol çizin
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Bir TiffOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ayrıca bakınız

* class [Shape](../../shape/)
* class [Figure](../)
* ad alanı [Aspose.PSD](../../figure/)
* toplantı [Aspose.PSD](../../../)



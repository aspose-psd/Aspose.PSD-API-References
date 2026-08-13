---
title: "Figure.AddShape"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Figure yöntemi. Şekle bir şekil ekler."
type: docs
weight: 60
url: /tr/net/aspose.psd/figure/addshape/
---
{{< psd/tize >}}
## Figure.AddShape method

Şekle bir şekil ekler.

```csharp
public void AddShape(Shape shape)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| şekil | Şekil | Eklenecek şekil. |

## Örnekler

Bu örnekler, bir Görüntü yüzeyinde Şekiller oluşturmak ve manipüle etmek için GraphicsPath ve Graphics sınıflarını kullanır. Örnek, yeni bir Görüntü oluşturur ve GraphicsPath sınıfının yardımıyla yollar çizer. Sonunda, Graphics sınıfı tarafından sunulan DrawPath yöntemi, yolları yüzeye render etmek için çağrılır. Son olarak görüntü Tiff dosya formatına dışa aktarılır.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturun.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturun ve başlatın.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizleyin.
    graphics.Clear(Color.Wheat);

    //GraphicsPath sınıfının bir örneğini oluşturun.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure sınıfının bir örneğini oluşturun.
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure nesnesine Şekiller ekleyin.
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure nesnesini GraphicsPath'e ekleyin.
    graphicspath.AddFigure(figure);

    //Siyah renkli Pen nesnesiyle yolu çizin.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions sınıfının bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ayrıca Bakınız

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



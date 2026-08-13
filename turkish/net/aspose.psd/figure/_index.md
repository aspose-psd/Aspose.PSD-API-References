---
title: "Sınıf Figure"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Figure sınıfı. Şekil. Şekiller için bir kapsayıcı"
type: docs
weight: 1210
url: /tr/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

Şekil. Şekiller için bir konteyner.

```csharp
public class Figure : ObjectWithBounds
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Figure](figure/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Nesnenin sınırlarını alır veya ayarlar. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Bu şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı bir şekil, yalnızca ilk ve son şeklin parçaları sürekli şekiller olduğunda fark yaratır. Bu durumda, ilk şeklin ilk noktası, son şeklin son noktasından düz bir çizgiyle bağlanır. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Tüm şekil segmentlerini alır. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Şeklin şekillerini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Şekle bir şekil ekler. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Şekle bir dizi şekil ekler. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Şekilden bir şekil kaldırır. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Şekilden bir dizi şekil kaldırır. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



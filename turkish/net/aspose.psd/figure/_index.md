---
title: Class Figure
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Figure sınıf. Şekil. Şekiller için bir kapsayıcı.
type: docs
weight: 1200
url: /tr/net/aspose.psd/figure/
---
## Figure class

Şekil. Şekiller için bir kapsayıcı.

```csharp
public class Figure : ObjectWithBounds
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Figure](figure/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Nesnenin sınırlarını alır veya ayarlar. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Bu rakamın kapalı olup olmadığını gösteren bir değer alır veya ayarlar. Kapalı bir şekil, yalnızca ilk ve son şeklin şekillerinin sürekli şekiller olması durumunda fark yaratacaktır. Böyle bir durumda, ilk şeklin ilk noktası, son şeklin son noktasından düz bir çizgiyle bağlanacaktır. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Tüm şekil segmentlerini alır. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Şekil şekillerini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Şekle bir şekil ekler. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Şekle bir dizi şekil ekler. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Nesnenin sınırlarını alır. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Nesnenin sınırlarını alır. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Şekilden bir şekli kaldırır. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Şekilden bir dizi şekli kaldırır. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Bu şeklin sırasını tersine çevirir ve nokta sırasını şekillendirir. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Belirtilen dönüşümü şekle uygular. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)



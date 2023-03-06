---
title: Class StreamSource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Sources.StreamSource sınıf. Bir akış kaynağını temsil eder.
type: docs
weight: 5620
url: /tr/net/aspose.psd.sources/streamsource/
---
## StreamSource class

Bir akış kaynağını temsil eder.

```csharp
public sealed class StreamSource : Source
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Yeni bir örneğini başlatır.`StreamSource` sınıf. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Yeni bir örneğini başlatır.`StreamSource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Konteyner atıldığında akışın atılması gerekip gerekmediğini gösteren bir değer alır. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Akışı alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Akış kapsayıcısını alır. |

### Örnekler

Bu örnek, Image yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PSD biçiminde yeni bir Görüntü oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Görüntü yüzeyinde ilkel şekiller çizer ve ardından bunu PSD dosya biçimine dışa aktarır.

```csharp
[C#]

//Görüntünün bir örneğini oluştur 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    //Siyah renkli Kalem nesnesini belirterek bir Yay çizin, 
    //Yay, Başlangıç Açısı ve Tarama Açısını çevreleyen bir Dikdörtgen
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Mavi renk ve koordinat Noktalarına sahip Kalem nesnesini belirterek bir Bezier çizin.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Yeşil renge ve bir Nokta dizisine sahip Kalem nesnesini belirterek bir Eğri çizin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Kalem nesnesini ve çevreleyen Dikdörtgeni kullanarak bir Elips çizin
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Bir çizgi çiz 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Pasta parçası çiz
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Kırmızı renge ve Nokta dizisine sahip Kalem nesnesini belirterek bir Çokgen çizin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dikdörtgen Çiz
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Belirli Noktada SolidBrush nesnesini ve Fontu kullanarak bir String çizin
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions örneğini oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ayrıca bakınız

* class [Source](../../aspose.psd/source/)
* ad alanı [Aspose.PSD.Sources](../../aspose.psd.sources/)
* toplantı [Aspose.PSD](../../)



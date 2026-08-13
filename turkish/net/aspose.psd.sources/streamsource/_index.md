---
title: "Sınıf StreamSource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Sources.StreamSource sınıfı. Bir akış kaynağını temsil eder."
type: docs
weight: 6150
url: /tr/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

Bir akış kaynağını temsil eder.

```csharp
public sealed class StreamSource : Source
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | `StreamSource` sınıfının yeni bir örneğini başlatır. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | `StreamSource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Akışın, kapsayıcı atıldığında atılıp atılmayacağını gösteren bir değeri alır. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Akışı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Akış kapsayıcısını alır. |

## Örnekler

Bu örnek, Image yüzeyinde temel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PSD formatında yeni bir Image oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Image yüzeyinde temel şekiller çizer, ardından PSD dosya formatına dışa aktarır.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturun.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturun ve başlatın.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizleyin.
    graphics.Clear(Color.Wheat);

    //Siyah renkli Pen nesnesini belirterek bir Yay çizin, 
    //Yayı çevreleyen bir Dikdörtgen, Başlangıç Açısı ve Tarama Açısı
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Mavi renkli Pen nesnesini ve koordinat noktalarını belirterek bir Bezier çizin.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Yeşil renkli Pen nesnesini ve bir dizi Nokta'yı belirterek bir Eğri çizin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen nesnesini ve çevreleyen bir Dikdörtgeni kullanarak bir Elips çizin
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Bir Çizgi çizin 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Bir Pasta dilimi çizin
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Kırmızı renkli Pen nesnesini ve bir dizi Nokta'yı belirterek bir Çokgen çizin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Bir Dikdörtgen çizin
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush nesnesi ve Font kullanarak belirli bir Noktada bir Dize çizin
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ayrıca Bakınız

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)



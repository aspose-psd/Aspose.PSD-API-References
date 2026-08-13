---
title: "SolidBrush sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.SolidBrush sınıfı. Solid brush, belirli bir renk ile sürekli çizim yapmak için tasarlanmıştır. Bu sınıf kalıtılamaz."
type: docs
weight: 200
url: /tr/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Katı fırça, belirli bir renk ile sürekli çizim yapmak için tasarlanmıştır. Bu sınıf devralınamaz.

```csharp
public sealed class SolidBrush : Brush
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | `SolidBrush` sınıfının yeni bir örneğini başlatır. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | `SolidBrush` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Fırça rengini alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Mevcut [`Brush`](../../aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

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

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



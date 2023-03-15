---
title: Class SolidBrush
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.SolidBrush sınıf. Düz fırça belirli bir renkle sürekli çizim yapmak için tasarlanmıştır. Bu sınıf miras alınamaz.
type: docs
weight: 200
url: /tr/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

Düz fırça, belirli bir renkle sürekli çizim yapmak için tasarlanmıştır. Bu sınıf miras alınamaz.

```csharp
public sealed class SolidBrush : Brush
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Yeni bir örneğini başlatır.`SolidBrush` sınıf. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Yeni bir örneğini başlatır.`SolidBrush` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Fırça rengini alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Geçerli olanın yeni bir derin klonunu oluşturur.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

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

* class [Brush](../../aspose.psd/brush/)
* ad alanı [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* toplantı [Aspose.PSD](../../)



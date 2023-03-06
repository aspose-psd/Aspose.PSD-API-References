---
title: Class HatchBrush
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Brushes.HatchBrush sınıf. Tarama stili ön plan rengi ve arka plan rengi olan dikdörtgen bir fırça tanımlar. Bu sınıf miras alınamaz.
type: docs
weight: 130
url: /tr/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Tarama stili, ön plan rengi ve arka plan rengi olan dikdörtgen bir fırça tanımlar. Bu sınıf miras alınamaz.

```csharp
public sealed class HatchBrush : Brush
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Tarama çizgileri arasındaki boşlukların rengini alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Tarama çizgilerinin rengini alır veya ayarlar. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Bu fırçanın tarama stilini alır veya ayarlar. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Geçerli olanın yeni bir derin klonunu oluşturur.[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

### Örnekler

Bu örnek, Kalem nesnelerinin oluşturulmasını ve kullanılmasını göstermektedir. Örnek, yeni bir Görüntü oluşturur ve Görüntü yüzeyinde Dikdörtgenler çizer.

```csharp
[C#]

//Görüntünün bir örneğini oluştur
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Bir Graphics örneği oluştur ve onu Image nesnesi ile başlat
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini Beyaz Renk ile temizleyin
    graphics.Clear(Aspose.PSD.Color.White);

    //Kırmızı renkli ve genişliği 5 olan bir Kalem örneği oluşturun
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Bir HatchBrush örneği oluşturun ve özelliklerini ayarlayın
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen örneğini oluştur
    // HatchBrush nesnesi ve genişliği ile başlat
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen nesnesini belirterek Dikdörtgenler çizin
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen nesnesini belirterek Dikdörtgenler çizin
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Dışa aktarma seçenekleri oluşturun ve bunları başlatın.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // tüm değişiklikleri kaydet.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Ayrıca bakınız

* class [Brush](../../aspose.psd/brush/)
* ad alanı [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* toplantı [Aspose.PSD](../../)



---
title: "Sınıf HatchBrush"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Brushes.HatchBrush sınıfı. Bir hatch stili, ön plan rengi ve arka plan rengi ile dikdörtgen bir fırça tanımlar. Bu sınıf kalıtılamaz"
type: docs
weight: 130
url: /tr/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Tarama stiline, ön plan rengine ve arka plan rengine sahip dikdörtgen bir fırça tanımlar. Bu sınıf devralınamaz.

```csharp
public sealed class HatchBrush : Brush
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Hatch çizgileri arasındaki boşlukların rengini alır veya ayarlar. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Hatch çizgilerinin rengini alır veya ayarlar. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Bu fırçanın hatch stilini alır veya ayarlar. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Fırça opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri fırçanın tamamen görünür olduğu, 1 değeri ise fırçanın tamamen opak olduğu anlamına gelir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Mevcut [`Brush`](../../aspose.psd/brush/) nesnesinin yeni bir derin kopyasını oluşturur. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

## Örnekler

Bu örnek, Pen nesnelerinin oluşturulmasını ve kullanımını gösterir. Örnek yeni bir Image oluşturur ve Image yüzeyine Rectangles çizer.

```csharp
[C#]

//Image bir örneği oluşturun.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturun ve Image nesnesiyle başlatın.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini Beyaz Renk ile temizleyin.
    graphics.Clear(Aspose.PSD.Color.White);

    //Renk Kırmızı ve genişlik 5 olan bir Pen örneği oluşturun.
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //HatchBrush sınıfının bir örneğini oluşturun ve özelliklerini ayarlayın.
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Pen sınıfının bir örneğini oluşturun.
    //Bunu HatchBrush nesnesi ve genişlik ile başlatın.
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Pen nesnesini belirterek Rectangles çizin.
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Pen nesnesini belirterek Rectangles çizin.
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Dışa aktarma seçeneklerini oluşturun ve başlatın.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // tüm değişiklikleri kaydet.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Ayrıca Bakınız

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



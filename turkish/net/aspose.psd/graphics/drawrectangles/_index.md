---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics metodu. RectangleF yapılarıyla tanımlanan bir dizi dikdörtgen çizer."
type: docs
weight: 320
url: /tr/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Belirtilen [`RectangleF`](../../rectanglef/) yapılarıyla bir dizi dikdörtgen çizer.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) dikdörtgenlerin kenar çizgilerinin rengini, genişliğini ve stilini belirler. |
| rects | RectangleF[] | Çizilecek dikdörtgenleri temsil eden [`RectangleF`](../../rectanglef/) yapılarının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *rects* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Belirtilen [`Rectangle`](../../rectangle/) yapılarıyla bir dizi dikdörtgen çizer.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) dikdörtgenlerin kenar çizgilerinin rengini, genişliğini ve stilini belirler. |
| rects | Rectangle[] | Çizilecek dikdörtgenleri temsil eden [`Rectangle`](../../rectangle/) yapılarının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *rects* null. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



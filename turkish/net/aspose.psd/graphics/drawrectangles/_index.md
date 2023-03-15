---
title: Graphics.DrawRectangles
second_title: Aspose.PSD for .NET API Referansı
description: Graphics yöntem. tarafından belirtilen bir dizi dikdörtgen çizer.RectangleF yapılar.
type: docs
weight: 310
url: /tr/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

tarafından belirtilen bir dizi dikdörtgen çizer.[`RectangleF`](../../rectanglef/) yapılar.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) dikdörtgenlerin ana hatlarının rengini, genişliğini ve stilini belirler. |
| rects | RectangleF[] | dizisi[`RectangleF`](../../rectanglef/) çizilecek dikdörtgenleri temsil eden yapılar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *rects* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

tarafından belirtilen bir dizi dikdörtgen çizer.[`Rectangle`](../../rectangle/) yapılar.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) dikdörtgenlerin ana hatlarının rengini, genişliğini ve stilini belirler. |
| rects | Rectangle[] | dizisi[`Rectangle`](../../rectangle/) çizilecek dikdörtgenleri temsil eden yapılar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *rects* boş. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)



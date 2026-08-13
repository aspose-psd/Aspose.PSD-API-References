---
title: "Class Pen"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Pen sınıfı. Çizgileri, eğrileri ve şekilleri çizmeye yarayan bir nesneyi tanımlar."
type: docs
weight: 5720
url: /tr/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Çizgileri, eğrileri ve şekilleri çizmek için kullanılan bir nesneyi tanımlar.

```csharp
public class Pen : TransparencySupporter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Belirtilen [`Brush`](./brush/) ile `Pen` sınıfının yeni bir örneğini başlatır. |
| [Pen](pen/#constructor_2)(Color) | Belirtilen renk ile `Pen` sınıfının yeni bir örneğini başlatır. |
| [Pen](pen/#constructor_1)(Brush, float) | Belirtilen [`Brush`](./brush/) ve [`Width`](./width/) ile `Pen` sınıfının yeni bir örneğini başlatır. |
| [Pen](pen/#constructor_3)(Color, float) | Belirtilen [`Color`](./color/) ve [`Width`](./width/) özellikleriyle `Pen` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Bu `Pen` için hizalamayı alır veya ayarlar. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Bu `Pen`in özelliklerini belirleyen [`Brush`](./brush/) öğesini alır veya ayarlar. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Bu `Pen`in rengini alır veya ayarlar. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Bir bileşik kalemi belirten değerler dizisini alır veya ayarlar. Bileşik kalem, paralel çizgiler ve boşluklardan oluşan bir bileşik çizgi çizer. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Bu `Pen` ile çizilen satırların sonunda kullanılacak özel bir uç (cap) alır veya ayarlar. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Bu `Pen` ile çizilen satırların başlangıcında kullanılacak özel bir kapak alır veya ayarlar. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Bu `Pen` ile çizilen kesikli satırları oluşturan tirelerin sonunda kullanılan kapak stilini alır veya ayarlar. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Bir satırın başlangıcından tire deseninin başlangıcına olan mesafeyi alır veya ayarlar. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Özel tire ve boşluklardan oluşan bir dizi alır veya ayarlar. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Bu `Pen` ile çizilen kesikli satırlar için kullanılan stili alır veya ayarlar. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Bu `Pen` ile çizilen satırların sonunda kullanılan kapak stilini alır veya ayarlar. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Bu `Pen` ile çizilen iki ardışık satırın uçları için birleşim stilini alır veya ayarlar. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Köşeli bir köşedeki birleşimin kalınlık sınırını alır veya ayarlar. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Nesnenin opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri nesnenin tamamen görünür olduğunu, 1 değeri nesnenin tamamen opak olduğunu gösterir. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Bu `Pen` ile çizilen satırların stilini alır. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Bu `Pen` ile çizilen satırların başlangıcında kullanılan kapak stilini alır veya ayarlar. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Bu `Pen` için geometrik dönüşümün bir kopyasını alır veya ayarlar. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Bu `Pen`in genişliğini, çizim için kullanılan Graphics nesnesinin birimlerinde alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Bu `Pen` için dönüşüm matrisini belirtilen [`Matrix`](../matrix/) ile çarpar. |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Bu `Pen` için dönüşüm matrisini belirtilen sırada belirtilen [`Matrix`](../matrix/) ile çarpar. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Bu `Pen` için geometrik dönüşüm matrisini birim matrisine sıfırlar. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen açıyla döndürür. Bu yöntem dönüşüme rotasyonu ön ekler. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırada döndürür. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Yerel geometrik dönüşümü belirtilen faktörlerle ölçeklendirir. Bu yöntem dönüşüme ölçekleme matrisini ön ekler. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen faktörlerle belirtilen sırada ölçeklendirir. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Bu `Pen` ile çizilen satırların sonlandırılmasında kullanılan kapak stilini belirleyen değerleri ayarlar. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlarla çevirir. Bu yöntem dönüşüme çevirme işlemini ön ekler. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen boyutlarla belirtilen sırada çevirir. |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



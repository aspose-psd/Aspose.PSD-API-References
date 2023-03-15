---
title: Class Pen
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Pen sınıf. Çizgiler eğriler ve şekiller çizmek için kullanılan bir nesneyi tanımlar.
type: docs
weight: 5200
url: /tr/net/aspose.psd/pen/
---
## Pen class

Çizgiler, eğriler ve şekiller çizmek için kullanılan bir nesneyi tanımlar.

```csharp
public class Pen : TransparencySupporter
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Yeni bir örneğini başlatır.`Pen` belirtilen sınıf[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Yeni bir örneğini başlatır.`Pen` belirtilen color. ile sınıf |
| [Pen](pen/#constructor_1)(Brush, float) | Yeni bir örneğini başlatır.`Pen` belirtilen sınıf[`Brush`](./brush/) Ve[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Yeni bir örneğini başlatır.`Pen` belirtilen sınıf[`Color`](./color/) Ve[`Width`](./width/) özellikler. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Bunun için hizalamayı alır veya ayarlar`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Şunu alır veya ayarlar:[`Brush`](./brush/) bunun özelliklerini belirleyen`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Bunun rengini alır veya ayarlar`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Bileşik kalemi belirten bir dizi değer alır veya ayarlar. Bileşik kalem, paralel çizgilerden ve boşluklardan oluşan bileşik bir çizgi çizer. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Bununla çizilen çizgilerin sonunda kullanılacak özel bir sınır alır veya ayarlar`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Bununla çizilen çizgilerin başında kullanmak için özel bir sınır alır veya ayarlar.`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Bununla çizilen kesikli çizgileri oluşturan tirelerin sonunda kullanılan başlık stilini alır veya ayarlar.`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Çizginin başlangıcından kısa çizgi deseninin başlangıcına olan mesafeyi alır veya ayarlar. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Bir dizi özel çizgi ve boşluk alır veya ayarlar. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Bununla çizilen kesik çizgiler için kullanılan stili alır veya ayarlar`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Bununla çizilen çizgilerin sonunda kullanılan başlık stilini alır veya ayarlar.`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Bununla çizilen ardışık iki çizginin uçları için birleştirme stilini alır veya ayarlar.`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Azaltılmış bir köşede birleştirmenin kalınlık sınırını alır veya ayarlar. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Nesnenin opaklığını alır veya ayarlar. Değer 0 ile 1 arasında olmalıdır. 0 değeri, nesnenin tamamen görünür olduğu, 1 değeri ise nesnenin tamamen opak olduğu anlamına gelir. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Bununla çizilen çizgilerin stilini alır`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Bununla çizilen çizgilerin başında kullanılan büyük harf stilini alır veya ayarlar.`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Bunun için geometrik dönüşümün bir kopyasını alır veya ayarlar`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Bunun genişliğini alır veya ayarlar`Pen` , çizim için kullanılan Graphics nesnesinin birimlerinde. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Bunun için dönüşüm matrisini çarpar`Pen` belirtilen tarafından[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Bunun için dönüşüm matrisini çarpar`Pen` belirtilen tarafından[`Matrix`](../matrix/) belirtilen sırada. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Bunun için geometrik dönüşüm matrisini sıfırlar`Pen` kimliğe. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Yerel geometrik dönüşümü belirtilen açı kadar döndürür. Bu yöntem, dönüşü dönüşümün başına ekler. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Yerel geometrik dönüşümü belirtilen açıyla belirtilen sırayla döndürür. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Belirtilen faktörlere göre yerel geometrik dönüşümü ölçeklendirir. Bu yöntem, ölçeklendirme matrisini dönüşümün başına ekler. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Belirtilen sırada belirtilen faktörlere göre yerel geometrik dönüşümü ölçeklendirir. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Bunun çizdiği çizgileri sonlandırmak için kullanılan büyük harf stilini belirleyen değerleri ayarlar.`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Yerel geometrik dönüşümü belirtilen boyutlara çevirir. Bu yöntem, çeviriyi dönüşümün başına ekler. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Belirtilen sırada belirtilen boyutlara göre yerel geometrik dönüşümü çevirir. |

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

* class [TransparencySupporter](../transparencysupporter/)
* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)



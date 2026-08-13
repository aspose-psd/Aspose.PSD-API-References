---
title: "Class Font"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Font sınıfı. Yazı tipinin yüz boyutu ve stil özellikleri dahil olmak üzere metin için belirli bir biçim tanımlar. Bu sınıf kalıtılamaz."
type: docs
weight: 4780
url: /tr/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Yazı tipi, boyut ve stil özellikleri dahil olmak üzere metin için belirli bir biçim tanımlar. Bu sınıf devralınamaz.

```csharp
public sealed class Font
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Belirtilen mevcut `Font` ve [`FontStyle`](../fontstyle/) enumarasyonunu kullanan yeni bir `Font` başlatır. |
| [Font](font/#constructor_1)(string, float) | Belirtilen bir boyut kullanarak yeni bir `Font` başlatır. Karakter kümesi Default, grafik birimi Point, yazı tipi stili Regular olarak ayarlanır. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Belirtilen bir boyut ve stil kullanarak yeni bir `Font` başlatır. Karakter kümesi Default, grafik birimi Point olarak ayarlanır. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Belirtilen bir boyut ve birim kullanarak yeni bir `Font` başlatır. Karakter kümesi Default, stil Regular olarak ayarlanır. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Belirtilen bir boyut, stil ve birim kullanarak yeni bir `Font` başlatır. Karakter kümesi Default, stil Regular olarak ayarlanır. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Belirtilen boyut, stil, birim ve karakter kümesini kullanarak yeni bir `Font` başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Bu `Font`un kalın olup olmadığını gösteren bir değeri alır. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Bu `Font`un kullandığı karakter kümesini belirten bir bayt değerini alır. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Bu `Font`un italik olup olmadığını gösteren bir değeri alır. |
| [Name](../../aspose.psd/font/name/) { get; } | Bu `Font`un yüz adı değerini alır. |
| [Size](../../aspose.psd/font/size/) { get; } | Bu `Font`un, [`Unit`](./unit/) özelliği tarafından belirtilen birimlerde ölçülen em-boyutunu alır. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Bu `Font`un üzerinden yatay bir çizgi belirttiğini gösteren bir değeri alır. |
| [Style](../../aspose.psd/font/style/) { get; } | Bu `Font` için stil bilgilerini alır. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Bu `Font`un altı çizili olup olmadığını gösteren bir değeri alır. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Bu `Font`un ölçü birimini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Bu `Font`un tam bir derin kopyasını oluşturur. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Belirtilen nesnenin bir `Font` olup olmadığını ve bu `Font` ile aynı özellik değerlerine sahip olup olmadığını gösterir. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Bu `Font` için karma kodunu alır. |
| override [ToString](../../aspose.psd/font/tostring/)() | Bu `Font`un insan tarafından okunabilir bir dize temsili döndürür. |

## Örnekler

Bu örnek, Font ve SolidBrush sınıfının Image yüzeyine metin çizmek için kullanımını gösterir. Örnek yeni bir Image oluşturur ve Figures ve GraphicsPath kullanarak şekiller çizer.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturur
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics sınıfının bir örneğini oluşturur ve başlatır
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics yüzeyini temizler
    graphics.Clear(Color.Wheat);

    //Font sınıfının bir örneğini oluşturur
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Kırmızı renkli bir SolidBrush örneği oluşturur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Bir dize çizer
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // dışa aktarma seçeneklerini oluştur.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // tüm değişiklikleri kaydet
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



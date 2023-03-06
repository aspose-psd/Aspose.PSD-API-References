---
title: Class Font
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Font sınıf. Yazı tipi yüzü boyutu ve stil nitelikleri dahil olmak üzere metin için belirli bir format tanımlar. Bu sınıf miras alınamaz.
type: docs
weight: 4280
url: /tr/net/aspose.psd/font/
---
## Font class

Yazı tipi yüzü, boyutu ve stil nitelikleri dahil olmak üzere metin için belirli bir format tanımlar. Bu sınıf miras alınamaz.

```csharp
public sealed class Font
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Yeni bir başlatır`Font` belirtilen mevcut olanı kullanan`Font` Ve[`FontStyle`](../fontstyle/) numaralandırma. |
| [Font](font/#constructor_1)(string, float) | Yeni bir başlatır`Font` belirli bir boyut kullanarak. Karakter seti şu şekilde ayarlanmıştır:Default , grafik birimiPoint , yazı tipi stiliRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Yeni bir başlatır`Font` belirli bir boyut ve stil kullanarak. Karakter seti şu şekilde ayarlanmıştır:Default , grafik birimiPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Yeni bir başlatır`Font` belirli bir boyut ve birim kullanarak. Karakter seti şu şekilde ayarlanmıştır:Default stil şu şekilde ayarlanır:Regular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Yeni bir başlatır`Font` belirtilen bir boyut, stil ve birim kullanarak. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Yeni bir başlatır`Font` belirtilen bir boyut, stil, birim ve karakter seti kullanarak. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Bunun olup olmadığını gösteren bir değer alır.`Font` kalın. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Bu karakter kümesini belirten bir bayt değeri alır.`Font` kullanır. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Bunun olup olmadığını gösteren bir değer alır.`Font`italiktir. |
| [Name](../../aspose.psd/font/name/) { get; } | Bunun yüz adını alır`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Bunun em boyutunu alır`Font` tarafından belirtilen birimlerde ölçülür.[`Unit`](./unit/) özellik. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Bunun olup olmadığını gösteren bir değer alır.`Font` font. boyunca yatay bir çizgi belirtir. |
| [Style](../../aspose.psd/font/style/) { get; } | Bunun için stil bilgisi alır`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Bunun olup olmadığını gösteren bir değer alır.`Font` altı çizili. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Bunun için ölçü birimini alır`Font` . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Bunun tam bir derin kopyasını oluşturur`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Belirtilen nesnenin bir`Font` ve bununla aynı özellik değerlerine sahip`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Bunun için hash kodunu alır`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Bunun insan tarafından okunabilir bir dize temsilini döndürür`Font` . |

### Örnekler

Bu örnek, Image yüzeyinde dizeler çizmek için Font ve SolidBrush sınıfının kullanımını gösterir. Örnek, yeni bir Görüntü oluşturur ve Figures ve GraphicsPath kullanarak şekiller çizer.

```csharp
[C#]

//Görüntünün bir örneğini oluşturur
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluşturur ve başlatır
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizler
    graphics.Clear(Color.Wheat);

    // Font örneğini oluşturur
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Kırmızı Rengi olan bir SolidBrush örneği oluştur
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Bir Dizi Çiz
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // dışa aktarma seçeneklerini oluşturun.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // tüm değişiklikleri kaydet
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)



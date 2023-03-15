---
title: Class FileCreateSource
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Sources.FileCreateSource sınıf. Oluşturma için bir dosya kaynağını temsil eder.
type: docs
weight: 5590
url: /tr/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Oluşturma için bir dosya kaynağını temsil eder.

```csharp
public sealed class FileCreateSource : FileSource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Yeni bir örneğini başlatır.`FileCreateSource` sınıf. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Yeni bir örneğini başlatır.`FileCreateSource` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Oluşturulacak dosya yolunu alır. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Dosyanın geçici olup olmayacağını gösteren bir değer alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Akış kapsayıcısını alır. |

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

* class [FileSource](../filesource/)
* ad alanı [Aspose.PSD.Sources](../../aspose.psd.sources/)
* toplantı [Aspose.PSD](../../)



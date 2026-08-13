---
title: "Sınıf FileCreateSource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Sources.FileCreateSource sınıfı. Oluşturma için bir dosya kaynağını temsil eder"
type: docs
weight: 6120
url: /tr/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Oluşturma için bir dosya kaynağını temsil eder.

```csharp
public sealed class FileCreateSource : FileSource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | `FileCreateSource` sınıfının yeni bir örneğini başlatır. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | `FileCreateSource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Oluşturmak için dosya yolunu alır. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Dosyanın geçici olup olmayacağını gösteren bir değeri alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Akış kapsayıcısını alır. |

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

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)



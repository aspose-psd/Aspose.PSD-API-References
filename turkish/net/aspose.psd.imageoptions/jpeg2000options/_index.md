---
title: "Class Jpeg2000Options"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.Jpeg2000Options class. Jpeg2000 dosya formatı seçenekleri"
type: docs
weight: 5350
url: /tr/net/aspose.psd.imageoptions/jpeg2000options/
---
{{< psd/tize >}}
## Jpeg2000Options class

The Jpeg2000 dosya formatı seçenekleri.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | `Jpeg2000Options` sınıfının yeni bir örneğini başlatır. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | `Jpeg2000Options` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | JPEG2000 codec'ini alır veya ayarlar |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Jpeg yorum işaretçilerini alır veya ayarlar. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Sıkıştırma oranı Array'ini alır veya ayarlar. Ardışık katmanlar için farklı sıkıştırma oranları. Her kalite seviyesi için belirtilen oran, istenen sıkıştırma faktörüdür. Azalan oranlar gereklidir. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | Geri dönüşümsüz DWT 9-7 (true) kullanılacağını veya kayıpsız DWT 5-3 sıkıştırmanın (varsayılan) kullanılacağını gösteren bir değeri alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

## Örnekler

Bu örnek, dışa aktarma amaçları için SaveOptions ad alanındaki farklı sınıfların kullanımını gösterir. Psd türünde bir görüntü Image örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.

```csharp
[C#]

//Image sınıfının bir örneğine mevcut bir görüntüyü yükle
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Varsayılan seçenekleri kullanarak BMP dosya formatına dışa aktar
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına dışa aktar
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak JPEG 2000 dosya formatına dışa aktar
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına dışa aktar
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına dışa aktar
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



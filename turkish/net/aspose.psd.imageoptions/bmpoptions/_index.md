---
title: "Sınıf BmpOptions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.BmpOptions sınıfı. bmp dosya formatı oluşturma seçenekleri"
type: docs
weight: 5310
url: /tr/net/aspose.psd.imageoptions/bmpoptions/
---
{{< psd/tize >}}
## BmpOptions class

bmp dosya formatı oluşturma seçenekleri.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | `BmpOptions` sınıfının yeni bir örneğini başlatır. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | `BmpOptions` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | Görüntünün piksel başına bit sayısını alır veya ayarlar. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | Sıkıştırmayı alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

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



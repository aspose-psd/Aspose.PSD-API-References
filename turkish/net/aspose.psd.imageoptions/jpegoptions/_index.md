---
title: "JpegOptions sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.JpegOptions sınıfı. JPEG dosya formatı oluşturma seçenekleri"
type: docs
weight: 5360
url: /tr/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

The jpeg dosya formatı oluşturma seçenekleri.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Yeni bir `JpegOptions` sınıfı örneği başlatır. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Yeni bir `JpegOptions` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Kayıpsız JPEG görüntüsü için kanal başına bit sayısını alır veya ayarlar. Şu anda kanal başına 2 ile 8 bit arasında desteklenmektedir. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK JPEG görüntüleri için hedef CMYK renk profili. Görüntüleri kaydederken kullanılır. Doğru renk dönüşümü için RGBColorProfile ile eşleşmelidir. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | JPEG görüntüsü için renk tipini alır veya ayarlar. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | JPEG dosya yorumunu alır veya ayarlar. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Sıkıştırma tipini alır veya ayarlar. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Exif veri konteynerini al veya ayarla |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Her bileşen için yatay alt örneklemeleri alır veya ayarlar. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | JFIF'i alır veya ayarlar. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | JPEG-LS yakın kayıpsız kodlama için fark sınırını (JPEG-LS spesifikasyonundaki NEAR parametresi) alır veya ayarlar. |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS ara katman (interleave) modunu alır veya ayarlar. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS ön ayar parametrelerini alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Alfa kanalı mevcutsa, kırmızı, yeşil ve mavi bileşenlerin arka plan rengiyle karıştırılıp karıştırılmayacağını belirten bir değeri alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Resim kalitesini alır veya ayarlar. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD optimizasyon ayarlarını alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Çözünürlük birimini alır veya ayarlar. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg görüntüleri için hedef RGB renk profili. Görüntüleri kaydetmek için kullanılır. Doğru renk dönüşümü için CMYKColorProfile ile eşleşmelidir. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8-bit değeri n-bit değere sığdırmak için örnek yuvarlama modunu alır veya ayarlar. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Ölçeklenmiş kalite. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Her bileşen için dikey alt örneklemeleri alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

## Örnekler

Bu örnek, Aspose.PSD for .Net API'sinin Görüntüleri Jpeg formatına dönüştürmek için kullanımını gösterir. Bu hedefe ulaşmak için örnek mevcut bir görüntüyü yükler ve ardından Jpeg dosya formatına dönüştürür.

```csharp
[C#]

//image sınıfının bir örneğini oluşturur ve Dosya yolu aracılığıyla mevcut bir dosyayla başlatır.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions sınıfının bir örneğini oluştur.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Çıktı görüntüsünün boyutunu azaltmak için kaliteyi %50'ye ayarla.
    jpegOptions.Quality = 50;

    //Exif yorumlarını ayarla.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Sağlanan JpegOptions ayarlarıyla görüntüyü disk konumuna kaydet.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Bu örnek, System.IO.Stream kullanarak yeni bir Image dosyası oluşturmayı gösterir.

```csharp
[C#]

//PsdOptions bir örnek oluşturur ve çeşitli özelliklerini ayarlar.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream bir örnek oluştur.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions örneği için source özelliğini tanımla.
//İkinci boolean parametre, Stream'in kapsam dışına çıktığında serbest bırakılıp bırakılmayacağını belirler.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image bir örnek oluşturur ve Image nesnesini başlatmak için PsdOptions parametresiyle Create metodunu çağırır.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap
}
```

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



---
title: Class JpegOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageOptions.JpegOptions sınıf. jpeg dosya biçimi oluşturma seçenekleri.
type: docs
weight: 4840
url: /tr/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

jpeg dosya biçimi oluşturma seçenekleri.

```csharp
public class JpegOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Yeni bir örneğini başlatır.`JpegOptions` sınıf. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Yeni bir örneğini başlatır.`JpegOptions` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Kayıpsız jpeg görüntüsü için kanal başına bit alır veya ayarlar. Artık kanal başına 2 ila 8 biti destekliyoruz. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg görüntüleri için hedef CMYK renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için RGBColorProfile ile birlikte olmalıdır. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | jpeg resmi için renk türünü alır veya ayarlar. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Jpeg dosyası yorumunu alır veya ayarlar. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Sıkıştırma türünü alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Exif veri kapsayıcısını alın veya ayarlayın |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [tam çerçeve]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Her bileşen için yatay alt örneklemeleri alır veya ayarlar. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | jfif. değerini alır veya ayarlar |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Neredeyse kayıpsız kodlama için JPEG-LS fark sınırını alır veya ayarlar (JPEG-LS spesifikasyonundan NEAR parametresi). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS serpiştirme modunu alır veya ayarlar. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS ön ayar parametrelerini alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Alfa kanalı varsa kırmızı, yeşil ve mavi bileşenlerin bir arka plan rengiyle karıştırılıp karıştırılmayacağını belirten bir değer alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Görüntü kalitesini alır veya ayarlar. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD iyileştirici ayarlarını alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Çözünürlük birimini alır veya ayarlar. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg görüntüleri için hedef RGB renk profili. Görüntüleri kaydetmek için kullanın. Doğru renk dönüşümü için CMYKColorProfile ile birlikte olmalıdır. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8 bitlik bir değeri n bitlik bir değere sığdırmak için örnek yuvarlama modunu alır veya ayarlar.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Ölçeklenmiş kalite. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | . içinde görüntü oluşturmak için kaynağı alır veya ayarlar |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör tarama seçeneklerini alır veya ayarlar. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Her bileşen için dikey alt örneklemeleri alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

### Örnekler

Bu örnek, Resimleri Jpeg formatına dönüştürmek için Aspose.PSD for .Net API kullanımını göstermektedir. Bu amaca ulaşmak için bu örnek, mevcut bir görüntüyü yükler ve ardından onu Jpeg dosya formatına dönüştürür.

```csharp
[C#]

//imaj sınıfının bir örneğini oluşturur ve onu Dosya yolu aracılığıyla mevcut bir dosyayla başlatır
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions sınıfının bir örneğini oluşturun
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Çıktı görüntüsünün boyutunu azaltmak için kaliteyi %50 olarak ayarlayın.
    jpegOptions.Quality = 50;

    //exif yorumlarını ayarlayın.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Verilen JpegOptions ayarlarıyla görüntüyü disk konumuna kaydedin
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Bu örnek, yeni bir Görüntü dosyası oluşturmak için System.IO.Stream'in kullanımını gösterir.

```csharp
[C#]

//PsdOptions'ın bir örneğini oluşturur ve çeşitli özelliklerini ayarlar
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream'in bir örneğini oluşturun
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions örneği için kaynak özelliğini tanımlayın
//İkinci boolean parametresi, Akışın kapsam dışına çıktıktan sonra atılıp atılmayacağını belirler
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Bir Image örneği oluşturur ve Image nesnesini başlatmak için parametre olarak PsdOptions ile Create yöntemini çağırır   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım
}
```

Bu örnek, dışa aktarma amacıyla SaveOptions Ad Alanından farklı sınıfların kullanımını gösterir. Psd türünde bir görüntü, Image örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.

```csharp
[C#]

//Mevcut bir görüntüyü Image sınıfının bir örneğine yükleyin
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Varsayılan seçenekleri kullanarak BMP dosya biçimine aktar
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya biçimine aktar
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak JPEG 2000 dosya biçimine aktarın
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Varsayılan seçenekleri kullanarak PNG dosya biçimine aktar
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya biçimine aktar
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ad alanı [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* toplantı [Aspose.PSD](../../)



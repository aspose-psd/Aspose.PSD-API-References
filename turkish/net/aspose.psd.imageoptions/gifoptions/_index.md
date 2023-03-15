---
title: Class GifOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageOptions.GifOptions sınıf. GIF dosyası biçimi oluşturma seçenekleri.
type: docs
weight: 4810
url: /tr/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

GIF dosyası biçimi oluşturma seçenekleri.

```csharp
public class GifOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Yeni bir örneğini başlatır.`GifOptions` sınıf. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Yeni bir örneğini başlatır.`GifOptions` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | GIF arka plan renk indeksini alır veya ayarlar. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | GIF renk çözünürlüğünü alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değer alır veya ayarlar. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [tam çerçeve]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | GIF'in fragmanı olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Görüntünün taramalı olması gerekiyorsa doğrudur. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değer alır veya ayarlar. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | İzin verilen maksimum piksel farkını alır veya ayarlar. Sıfırdan büyükse, kayıplı sıkıştırma kullanılacaktır. Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırmadır, 200 ise ağırdır. Yalnızca küçük bir kayıp söz konusu olduğunda ve sıkıştırma algoritmasının sınırlandırılması nedeniyle en iyi sonucu verir çok yüksek kayıp seviyeleri çok fazla kazanç sağlamaz. İzin verilen değer aralığı [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | GIF piksel en boy oranını alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | . içinde görüntü oluşturmak için kaynağı alır veya ayarlar |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör tarama seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

### Örnekler

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



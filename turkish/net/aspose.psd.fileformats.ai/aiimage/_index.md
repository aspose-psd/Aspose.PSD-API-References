---
title: "Sınıf AiImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Ai.AiImage sınıf. Adobe Illustrator AI Görüntüsü"
type: docs
weight: 1270
url: /tr/net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

Adobe Illustrator (AI) Görüntüsü.

```csharp
public sealed class AiImage : Image
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [AiImage](aiimage/)() | Yeni bir `AiImage` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | Etkin sayfanın dizinini alır veya ayarlar. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan renginin değerini alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Görüntünün piksel başına bit sayısını alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntünün sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.psd/image/container/) { get; } | `[`Image`](../../aspose.psd/image/)` kapsayıcısını alır. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Veri bölümünü alır. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Dosya formatının değerini alır. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Tamamlama bölümünü alır. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Resmin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Başlığı alır. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Resmin yüksekliğini alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesinti izleyicisini alır veya ayarlar. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekmediğini gösteren bir değeri alır. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Katman bölümlerini alır. |
| [PageCount](../../aspose.psd.fileformats.ai/aiimage/pagecount/) { get; } | Sayfa sayısı. Eski AI formatı görüntüleri için her zaman 0'dır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Kurulum bölümünü alır. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Adobe Illustrator formatının sürümünü alır. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Görüntü genişliğini alır. |
| [XmpData](../../aspose.psd.fileformats.ai/aiimage/xmpdata/) { get; } | XMP üst verilerini alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | AI katman bölümünü ekler. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Verileri önbelleğe alır ve temel [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için yararlı olabilir. Örneğin, 1 bit/piksel siyah-beyaz bir PNG görüntüsünü yükleyip [`Save`](../../aspose.psd/datastreamsupporter/save/) yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [`Save`](../../aspose.psd/image/save/) yöntemine geçirin. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan NearestNeighbourResample kullanılır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini temel akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |

## Örnekler

Aşağıdaki örnek, Adobe Illustrator dosyalarını Aspose.PSD içinde PDF formatına nasıl dışa aktarabileceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Aşağıdaki örnek, Aspose.PSD içinde AI dosyasını PSD ve PNG formatına nasıl dışa aktarabileceğinizi gösterir.

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Aşağıdaki örnek, Ai formatının PSD, PNG, JPG, GIF ve TIF formatlarına dışa aktarım desteğini gösterir.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Ayrıca Bakınız

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



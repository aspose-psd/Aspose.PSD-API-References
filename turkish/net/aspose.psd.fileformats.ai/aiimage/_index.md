---
title: Class AiImage
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Ai.AiImage sınıf. Adobe Illustrator AI Görüntüsü
type: docs
weight: 1260
url: /tr/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

Adobe Illustrator (AI) Görüntüsü

```csharp
public sealed class AiImage : Image
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AiImage](aiimage/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Paletin otomatik olarak ayarlanıp ayarlanmadığını gösteren bir değer alır veya ayarlar. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Arka plan rengi için bir değer alır veya ayarlar. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Piksel sayısı başına görüntü bitlerini alır. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Görüntü sınırlarını alır. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [Container](../../aspose.psd/image/container/) { get; } | Şunu alır:[`Image`](../../aspose.psd/image/) konteyner. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Veri bölümünü alır. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Nesnenin veri akışını alır. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | dosya formatı değerini alır |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Sonlandırma bölümünü alır. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Başlığı alır. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Görüntü yüksekliğini alır. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Kesme monitörünü alır veya ayarlar. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Nesnenin verilerinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değer alır. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Katman bölümlerini alır. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Renk paletini alır veya ayarlar. Pikseller doğrudan temsil edildiğinde renk paleti kullanılmaz. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Kurulum bölümünü alır. |
| [Size](../../aspose.psd/image/size/) { get; } | Görüntü boyutunu alır. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Adobe Illustrator format sürümünü alır |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Görüntü genişliğini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | AI katmanı bölümünü ekler. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Verileri önbelleğe alır ve temelden ek veri yüklemesi yapılmamasını sağlar[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Görüntünün, geçirilen kaydetme seçenekleri tarafından temsil edilen belirtilen dosya biçiminde kaydedilip kaydedilemeyeceğini belirler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Varsayılan seçenekleri alır. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Orijinal dosya ayarlarına göre seçenekleri alır. Bu, orijinal görüntünün bit derinliğini ve diğer parametrelerini değiştirmeden tutmak için yardımcı olabilir. Örneğin, piksel başına 1 bit olacak şekilde siyah-beyaz bir PNG görüntüsü yüklersek ve ardından the kullanarak kaydedin[`Save`](../../aspose.psd/datastreamsupporter/save/) yöntemiyle, piksel başına 8 bitlik çıktı PNG görüntüsü üretilir. Bundan kaçınmak ve PNG görüntüsünü piksel başına 1 bit ile kaydetmek için, karşılık gelen kaydetme seçeneklerini almak için bu yöntemi kullanın ve onları öğesini[`Save`](../../aspose.psd/image/save/)ikinci parametre olarak yöntem. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Görüntüyü yeniden boyutlandırır. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Görüntüyü yeniden boyutlandırır. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Genişliği orantılı olarak yeniden boyutlandırır. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Genişliği orantılı olarak yeniden boyutlandırır. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Görüntüyü döndürür, çevirir veya döndürür ve çevirir. |
| [Save](../../aspose.psd/image/save/)() | Görüntü verilerini alttaki akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Görüntü paletini ayarlar. |

### Örnekler

Aşağıdaki örnek, Adobe Illustrator dosyalarını Aspose.PSD'de PDF formatına nasıl aktarabileceğinizi göstermektedir.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Aşağıdaki örnek, AI dosyasını Aspose.PSD'de PSD ve PNG formatına nasıl aktarabileceğinizi göstermektedir.

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

Aşağıdaki örnek, Ai formatının PSD, PNG, JPG, GIF ve TIF formatlarına dışa aktarılmasının desteğini göstermektedir.

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

### Ayrıca bakınız

* class [Image](../../aspose.psd/image/)
* ad alanı [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* toplantı [Aspose.PSD](../../)



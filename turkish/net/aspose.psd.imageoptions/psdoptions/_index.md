---
title: "PsdOptions sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.ImageOptions.PsdOptions sınıfı. psd dosya formatı oluşturma seçenekleri"
type: docs
weight: 5420
url: /tr/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

The psd dosya formatı oluşturma seçenekleri.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | `PsdOptions` sınıfının yeni bir örneğini başlatır. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | `PsdOptions` sınıfının yeni bir örneğini başlatır. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | `PsdOptions` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | Arka plan rengini alır veya ayarlar. Şeffaf nesnelerin altında görülebilir. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Renk kanal başına bit sayısını alır veya ayarlar. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Renk kanalı sayısını alır veya ayarlar. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | PSD renk modunu alır veya ayarlar. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | PSD sıkıştırma yöntemini alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedekleme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizerken kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa). Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Görüntü önizleme verilerini [refresh image preview data] yenileme seçeneğini gösteren bir değeri alır veya ayarlar - bu seçenek başka PSD görüntüleyicileriyle uyumluluğu en üst düzeye çıkarmak için kullanılır. Lütfen, metin katmanlarının son düzene çizilmesinin Compact Framework platformu için desteklenmediğini unutmayın. |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Kaldırma işlemini gösteren bir değeri alır veya ayarlar - Global metin motoru kaynağını kaldır - Bazı metin katmanlı PSD dosyaları için kullanılır; yalnızca işleme sonrasında Adobe Photoshop'ta açılamadığında (çoğunlukla eksik fontlarla ilgili metin katmanları). Bu seçeneği kullandıktan sonra, kullanıcı Photoshop'ta açılan dosyada şu adımları izlemelidir: Menü \"Text\" -> \"Process absent fonts\". Bu işlemden sonra tüm metin tekrar görünecektir. Lütfen, bu işlemin bazı son düzen değişikliklerine neden olabileceğini unutmayın. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | PSD kaynaklarını alır veya ayarlar. Değer: NULL - orijinal ImageResources kaydedilir (varsayılan davranış) Boş değil - bu özelliğe geçirilen kaynaklar + [required resources] kaydedilir. Boş - yalnızca [required resources] kaydedilir. Gerekli kaynaklar: ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | Metadataları [update metadata] güncelleme seçeneğini gösteren bir değeri alır veya ayarlar. Değer true ise, görüntü kaydedilirken metadata güncellenir. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | PSD dosya sürümünü alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | XMP veri kapsayıcısını al veya ayarla |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |

## Örnekler

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

Bu örnek, PsdOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için birkaç özellik ayarlanır. Özellikle bu durumda gerçek disk konumunu belirten Source özelliği.

```csharp
[C#]

//PsdOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource bir örneği oluşturun ve bunu PsdOptions örneği için Source olarak atayın.
//İkinci Boolean parametre, oluşturulacak dosyanın geçici (IsTemporal) olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image bir örneği oluşturun ve Create metodunu çağırarak PsdOptions örneğiyle başlatın.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap

    // tüm değişiklikleri kaydet
    image.Save();
}
```

Aşağıdaki örnek, Grayscale 16 bit PSD dosyalarını kanal başına 16 bit RGB'ye okumanın ve kaydetmenin doğru çalıştığını ve istisna oluşmadığını gösterir.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Burada istisna olmamalıdır.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Aşağıdaki örnek, Grayscale 16 bit PSD dosyalarını kanal başına 8 bit Grayscale'e okumanın ve kaydetmenin doğru çalıştığını ve istisna oluşmadığını gösterir.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Burada istisna olmamalıdır.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Aşağıdaki örnek, Aspose.PSD içinde PassThrough katman karıştırma modunu nasıl kullanabileceğinizi gösterir.

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Aşağıdaki örnek, belge dönüştürme ilerlemesinin doğru ve istisna olmadan çalıştığını gösterir.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

Bu örnek, Pixel bilgilerini Color tipinde bir diziye nasıl yükleneceğini, diziyi nasıl manipüle edeceğini ve tekrar görüntüye nasıl ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için örnek, MemoryStream nesnesi kullanarak yeni bir Image dosyası (PSD formatında) oluşturur.

```csharp
[C#]

//MemoryStream bir örneği oluşturun.
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions bir örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın.
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image bir örneği oluşturun.
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Görüntünün piksellerini, alanı görüntü sınırı olarak belirterek alın
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Diziyi döngüye al ve alternatif indeksli pikselin rengini ayarlar
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //İndeksli pikselin rengini sarıya ayarla
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //İndeksli pikselin rengini maviye ayarla
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    //MemoryStream'i dosyaya yaz
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

Aşağıdaki örnek, Grayscale 16 bit PSD dosyalarının okunup kaydedilmesinin doğru bir şekilde ve istisna olmadan çalıştığını gösterir.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // Burada istisna olmamalıdır.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



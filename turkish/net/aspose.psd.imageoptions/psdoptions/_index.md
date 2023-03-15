---
title: Class PsdOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageOptions.PsdOptions sınıf. psd dosya biçimi oluşturma seçenekleri.
type: docs
weight: 4900
url: /tr/net/aspose.psd.imageoptions/psdoptions/
---
## PsdOptions class

psd dosya biçimi oluşturma seçenekleri.

```csharp
public class PsdOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Yeni bir örneğini başlatır.`PsdOptions` sınıf. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Yeni bir örneğini başlatır.`PsdOptions` sınıf. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Yeni bir örneğini başlatır.`PsdOptions` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Renk kanalı başına bit sayısını alır veya ayarlar. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Renk kanalı sayısını alır veya ayarlar. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | psd renk modunu alır veya ayarlar. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | psd sıkıştırma yöntemini alır veya ayarlar. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [tam çerçeve]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Dosya biçimi sürümünü alır veya ayarlar. PSD veya PSB. olabilir |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Başka bir PSD resim görüntüleyiciyle uyumluluğu en üst düzeye çıkarmak için kullanılan [resim önizleme verilerini yenile] seçeneğinin kullanılıp kullanılmadığını belirten bir değer alır veya ayarlar. Lütfen unutmayın, son düzene çizilen metin katmanları Compact Framework platformu için desteklenmez |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Şunu belirten bir değer alır veya ayarlar: - Genel metin motoru kaynağını kaldır - Bazı metin katmanlı psd dosyaları için kullanılır, yalnızca işlendikten sonra Adobe Photoshop'ta açılamadıkları durumlarda (çoğunlukla ilgili metin katmanları olmayan yazı tipleri için). Bu seçeneği kullandıktan sonra, kullanıcının Photoshop dosyasında açılan sonraki öğeyi yapması gerekir: Menü "Metin" -&gt; "Olmayan yazı tiplerini işle". Bu işlemden sonra tüm metin yeniden görünecektir. Bu işlemin bazı son düzen değişikliklerine neden olabileceğini lütfen unutmayın. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | psd kaynaklarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | . içinde görüntü oluşturmak için kaynağı alır veya ayarlar |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör tarama seçeneklerini alır veya ayarlar. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | psd dosya sürümünü alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | XMP veri kapsayıcısını alın veya ayarlayın |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

### Örnekler

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

Bu örnek, PsdOptions örneğinin Source özelliği tarafından belirtildiği gibi bazı disk konumlarında yeni bir Görüntü dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için çeşitli özellikler ayarlanır. Özellikle bu durumda gerçek disk konumuna atıfta bulunan Source özelliği.

```csharp
[C#]

//PsdOptions'ın bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Bir FileCreateSource örneği oluşturun ve bunu PsdOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Bir Image örneği oluşturun ve Create yöntemini çağırarak onu PsdOptions örneğiyle başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım

    // tüm değişiklikleri kaydet
    image.Save();
}
```

Aşağıdaki örnek, Gri Tonlamalı 16 bit PSD dosyalarını okumanın ve kanal başına 16 bit RGB'ye kaydetmenin doğru ve istisnasız çalıştığını göstermektedir.

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
    // Burada bir istisna olmamalıdır.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Aşağıdaki örnek, Gri Tonlamalı 16 bit PSD dosyalarını kanal başına 8 bit olarak okumanın ve kaydetmenin düzgün ve istisnasız çalıştığını göstermektedir.

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
    // Burada bir istisna olmamalıdır.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Aşağıdaki örnek, Aspose.PSD'de PassThrough katman karıştırma modunu nasıl kullanabileceğinizi gösterir.

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

Aşağıdaki örnek, belge dönüştürme ilerlemesinin doğru ve istisnasız çalıştığını göstermektedir.

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

Bu örnek, Piksel bilgilerinin bir Renk Türü Dizisinde nasıl Yükleneceğini, diziyi nasıl değiştireceğini ve tekrar görüntüye nasıl ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için bu örnek, MemoryStream nesnesini kullanarak yeni bir Görüntü dosyası (PSD formatında) oluşturur.

```csharp
[C#]

// Bir MemoryStream örneği oluştur
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Bir PsdOptions örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Görüntünün bir örneğini oluştur
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Görüntü sınırı olarak alanı belirleyerek görüntünün piksellerini alın
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Dizi üzerinde döngü yapın ve alternatif dizinlenmiş pikselin rengini ayarlar
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Dizinlenen piksel rengini sarı olarak ayarla
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Dizinlenmiş piksel rengini mavi olarak ayarla
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    //MemoryStream'i Dosyaya Yaz
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

Aşağıdaki örnek, Gri Tonlamalı 16 bit PSD dosyalarını okumanın ve kaydetmenin doğru ve istisnasız çalıştığını göstermektedir.

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
        // Burada bir istisna olmamalıdır.
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

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ad alanı [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* toplantı [Aspose.PSD](../../)



---
title: Class PngOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.ImageOptions.PngOptions sınıf. png dosya biçimi oluşturma seçenekleri.
type: docs
weight: 4880
url: /tr/net/aspose.psd.imageoptions/pngoptions/
---
## PngOptions class

png dosya biçimi oluşturma seçenekleri.

```csharp
public class PngOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | Yeni bir örneğini başlatır.`PngOptions` sınıf. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | Yeni bir örneğini başlatır.`PngOptions` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | Bit derinliği. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyutu tanımlayan arabellek boyutu ipucunu alır veya ayarlar. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | Rengin türünü alır veya ayarlar. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | 9'un maksimum sıkıştırma ve 0'ın depolama modu olduğu 0-9 aralığında png görüntü sıkıştırma düzeyi. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Varsayılan yedek yazı tipini alır veya ayarlar (PSD dosyasındaki mevcut katman yazı tipi sistemde sunulmuyorsa, taramaya dışa aktarırken metin çizmek için kullanılacak yazı tipi). Varsayılan yazı tipinin uygun adını almak için bir sonraki kod parçacığı kullanılabilir : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familys = col.Families; string defaultFontName = familys[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | PNG dosyası kaydetme işlemi sırasında kullanılan filtre türünü alır veya ayarlar. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [tam çerçeve]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Çok sayfalı seçenekler |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Renk paletini alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | İlerleme olay işleyicisini alır veya ayarlar. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | Bunun olup olmadığını gösteren bir değer alır veya ayarlar.`PngOptions` aşamalıdır. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | . içinde görüntü oluşturmak için kaynağı alır veya ayarlar |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Vektör tarama seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Bu örneği klonlar. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | Varsayılan sıkıştırma düzeyi. |

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

Bu örnek, Image yüzeyinde ilkel şekiller oluşturmak için Graphics sınıfını kullanır. İşlemi göstermek için örnek, PSD biçiminde yeni bir Görüntü oluşturur ve Graphics sınıfı tarafından sunulan Draw yöntemlerini kullanarak Görüntü yüzeyinde ilkel şekiller çizer ve ardından bunu PSD dosya biçimine dışa aktarır.

```csharp
[C#]

//Görüntünün bir örneğini oluştur 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics sınıfının bir örneğini oluştur ve başlat
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Grafik yüzeyini temizle
    graphics.Clear(Color.Wheat);

    //Siyah renkli Kalem nesnesini belirterek bir Yay çizin, 
    //Yay, Başlangıç Açısı ve Tarama Açısını çevreleyen bir Dikdörtgen
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Mavi renk ve koordinat Noktalarına sahip Kalem nesnesini belirterek bir Bezier çizin.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Yeşil renge ve bir Nokta dizisine sahip Kalem nesnesini belirterek bir Eğri çizin
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Kalem nesnesini ve çevreleyen Dikdörtgeni kullanarak bir Elips çizin
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Bir çizgi çiz 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Pasta parçası çiz
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Kırmızı renge ve Nokta dizisine sahip Kalem nesnesini belirterek bir Çokgen çizin
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dikdörtgen Çiz
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Bir SolidBrush nesnesi oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Belirli Noktada SolidBrush nesnesini ve Fontu kullanarak bir String çizin
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions örneğini oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // tüm değişiklikleri kaydet.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ad alanı [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* toplantı [Aspose.PSD](../../)



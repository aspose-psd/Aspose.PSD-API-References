---
title: Image.Save
second_title: Aspose.PSD for .NET API Referansı
description: Image yöntem. Görüntü verilerini alttaki akışa kaydeder.
type: docs
weight: 230
url: /tr/net/aspose.psd/image/save/
---
## Save() {#save}

Görüntü verilerini alttaki akışa kaydeder.

```csharp
public void Save()
```

### Ayrıca bakınız

* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| options | ImageOptionsBase | Seçenekler. |

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

Aşağıdaki örnek, AsposePSD'nin PSB dosyalarının bir PSD formatına dışa aktarılmasını desteklediğini göstermektedir.

```csharp
[C#]

// PSB'yi PDF olarak kaydetme desteği
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Aşağıdaki kod, PsdImage'ı seçilebilir metinle PDF belgesi olarak kaydediyor.

```csharp
[C#]

// PSD'yi PDF'ye kaydetmek, seçilebilir metin sağlamaz
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
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

Aşağıdaki örnek, sağdan sola yazılan diller için ITextPortion aracılığıyla Metin Hizalamanın doğru çalıştığını gösterir.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

Bu örnek, bir Görüntüyü Kaydetmek için basit adımları gösterir. Bu işlemi göstermek için, bir disk konumundan varolan bir dosyayı yüklüyoruz, görüntü üzerinde Döndürme işlemini gerçekleştiriyoruz ve Dosya Yolunu kullanarak görüntüyü Jpeg dosya formatında kaydediyoruz.

```csharp
[C#]

//imaj sınıfının bir örneğini oluşturun ve onu Dosya yolu aracılığıyla mevcut bir dosyayla başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Görüntüyü X ekseni etrafında 180 derece döndürün
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Görüntüyü, varsayılan JpegOptions ayarlarıyla Dosya Yoluna Jpeg olarak kaydedin
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Aşağıdaki örnek, Aspose.PSD'de LayerGroup görünürlüğünü nasıl değiştirebileceğinizi göstermektedir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// katman adlarında değişiklikler yapın ve kaydedin
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Grup içindeki her şeyi kapat
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Aşağıdaki örnek, Aspose.PSD'de basit kurucu sürümü kullanılıyorsa yeni oluşturulmuş bir katman üzerinde nasıl çizim yapabileceğinizi gösterir.

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // Kalem aracıyla bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Düz Fırça ile Mavi renkte başka bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| options | ImageOptionsBase | Seçenekler. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | seçenekler |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Görüntü kaydedilemedi. |

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | ImageOptionsBase | Kaydetme seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | seçeneklerTemel |
| ArgumentException | Şu anda desteklenmediği için belirtilen biçimde kaydedilemiyor.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Resim dışa aktarma başarısız oldu. |

### Örnekler

Bu örnek, bir Görüntüyü MemoryStream'e Kaydetme işlemini gösterir. Bu işlemi göstermek için, örnek bir disk konumundan varolan bir dosyayı yükler, görüntü üzerinde Döndürme işlemini gerçekleştirir ve görüntüyü Gif formatında kaydeder.

```csharp
[C#]

// Bir MemoryStream örneği oluştur
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //imaj sınıfının bir örneğini oluşturun ve onu Dosya yolu aracılığıyla mevcut bir dosyayla başlatın
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Görüntüyü X ekseni etrafında 180 derece döndürün
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Görüntüyü varsayılan GifOptions ayarlarıyla PSD olarak MemoryStream'e kaydedin
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | ImageOptionsBase | Kaydetme seçenekleri. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | seçeneklerTemel |
| ArgumentException | Şu anda desteklenmediği için belirtilen biçimde kaydedilemiyor.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Resim dışa aktarma başarısız oldu. |

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)



---
title: "Image.Save"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Image method. Görüntü verilerini temel akışa kaydeder"
type: docs
weight: 240
url: /tr/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

Görüntü verilerini temel akışa kaydeder.

```csharp
public void Save()
```

### Ayrıca Bakınız

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| seçenekler | ImageOptionsBase | Seçenekler. |

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

Aşağıdaki örnek, AsposePSD'nin PSB dosyalarını PSD formatına dışa aktarmayı desteklediğini gösterir.

```csharp
[C#]

// PSB'yi PDF olarak kaydetmeyi destekle
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Aşağıdaki kod, PsdImage'ı seçilebilir metin içeren PDF belgesi olarak kaydeder.

```csharp
[C#]

// PSD'yi PDF olarak kaydetmek seçilebilir metin sağlamaz
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
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

Aşağıdaki örnek, ITextPortion aracılığıyla metin hizalamasının sağdan sola dillerde doğru çalıştığını gösterir.

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

Bu örnek, bir Image'i Save etmek için basit adımları gösterir. Bu işlemi göstermek için, bir disk konumundan mevcut bir dosya yüklüyor, görüntü üzerinde Rotate işlemi gerçekleştiriyor ve File Path kullanarak görüntüyü Jpeg dosya formatında Save ediyor.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturun ve Dosya yolu aracılığıyla mevcut bir dosyayla başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Görüntüyü X ekseni etrafında 180 derece döndürün.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Image'i Jpeg olarak Dosya Yolu'na, varsayılan JpegOptions ayarlarıyla kaydedin
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Aşağıdaki örnek, Aspose.PSD içinde LayerGroup görünürlüğünü nasıl değiştirebileceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// katman adlarında değişiklik yapın ve kaydedin
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Bir grup içindeki her şeyi kapat
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Aşağıdaki örnek, Aspose.PSD içinde basit yapıcı sürümü kullanılırsa yeni oluşturulan bir katmanda nasıl çizebileceğinizi gösterir.

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

    // Pen aracıyla bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Mavi renkte Solid Brush ile başka bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| seçenekler | ImageOptionsBase | Seçenekler. |
| boundsRectangle | Rectangle | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırları için boş dikdörtgeni ayarlayın. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | seçenekler |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Image kaydetme başarısız oldu. |

### Ayrıca Bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | ImageOptionsBase | Kaydetme seçenekleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Belirtilen formata kaydedilemiyor çünkü şu anda desteklenmiyor.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Image dışa aktarma başarısız oldu. |

## Örnekler

Bu örnek, bir Image'i MemoryStream'e Saving işleminin sürecini gösterir. Bu işlemi göstermek için, örnek bir disk konumundan mevcut bir dosya yükler, görüntü üzerinde Rotate işlemi gerçekleştirir ve görüntüyü Gif formatında Save eder.

```csharp
[C#]

//MemoryStream bir örneği oluşturun.
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Image sınıfının bir örneğini oluşturun ve Dosya yolu aracılığıyla mevcut bir dosyayla başlatın
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //Görüntüyü X ekseni etrafında 180 derece döndürün.
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Image'i PSD olarak MemoryStream'e, varsayılan GifOptions ayarlarıyla kaydedin
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Görüntünün verilerini kaydetmek için akış. |
| optionsBase | ImageOptionsBase | Kaydetme seçenekleri. |
| boundsRectangle | Rectangle | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Belirtilen formata kaydedilemiyor çünkü şu anda desteklenmiyor.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Image dışa aktarma başarısız oldu. |

### Ayrıca Bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



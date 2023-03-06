---
title: Image.Load
second_title: Aspose.PSD for .NET API Referansı
description: Image yöntem. Belirtilen dosyadan yeni bir resim yükler.
type: docs
weight: 20
url: /tr/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

Belirtilen dosyadan yeni bir resim yükler.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Görüntünün yükleneceği dosya yolu. |
| loadOptions | LoadOptions | Yükleme seçenekleri. |

### Geri dönüş değeri

Yüklenen görüntü.

### Ayrıca bakınız

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

Belirtilen dosyadan yeni bir resim yükler.

```csharp
public static Image Load(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | . 'den görüntünün yükleneceği dosya yolu |

### Geri dönüş değeri

Yüklenen görüntü.

### Örnekler

Bu örnek, belirtilen dosya yolu kullanılarak mevcut bir Görüntü dosyasının bir Aspose.PSD.Image örneğine yüklenmesini gösterir.

```csharp
[C#]

//Görüntü örneği oluşturun ve onu disk konumundan mevcut bir görüntü dosyasıyla başlatın
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    // biraz görüntü işleme yapalım
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

* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Belirtilen akıştan yeni bir resim yükler.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntünün yükleneceği akış. |
| loadOptions | LoadOptions | Yükleme seçenekleri. |

### Geri dönüş değeri

Yüklenen görüntü.

### Ayrıca bakınız

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

Belirtilen akıştan yeni bir resim yükler.

```csharp
public static Image Load(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntünün yükleneceği akış. |

### Geri dönüş değeri

Yüklenen görüntü.

### Örnekler

Bu örnek, mevcut bir Görüntü dosyasını yüklemek için System.IO.Stream nesnelerinin kullanımını gösterir.

```csharp
[C#]

//FileStream'in bir örneğini oluşturun
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Image sınıfının bir örneğini oluşturun ve Load yöntemini çağırarak FileStream nesnesi aracılığıyla mevcut bir dosyayı yükleyin
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //biraz görüntü işleme yapalım.
    }
}
```

### Ayrıca bakınız

* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)



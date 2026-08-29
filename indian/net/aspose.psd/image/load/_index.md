---
title: "Image.Load"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Image मेथड। निर्दिष्ट फ़ाइल से नई इमेज लोड करता है।"
type: docs
weight: 20
url: /hi/net/aspose.psd/image/load/
---
{{< psd/tize >}}
## Load(string, LoadOptions) {#load_3}

निर्दिष्ट फ़ाइल से नई इमेज लोड करता है।

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | इमेज लोड करने के लिए फ़ाइल पाथ। |
| loadOptions | LoadOptions | लोड विकल्प। |

### रिटर्न वैल्यू

लोड की गई इमेज।

### देखें भी

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

निर्दिष्ट फ़ाइल से नई इमेज लोड करता है।

```csharp
public static Image Load(string filePath)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | इमेज लोड करने के लिए फ़ाइल पाथ। |

### रिटर्न वैल्यू

लोड की गई इमेज।

## उदाहरण

यह उदाहरण निर्दिष्ट फ़ाइल पाथ का उपयोग करके Aspose.PSD.Image की एक इंस्टेंस में मौजूदा इमेज फ़ाइल को लोड करने को दर्शाता है।

```csharp
[C#]

//इमेज इंस्टेंस बनाएं और डिस्क लोकेशन से मौजूदा इमेज फ़ाइल के साथ इसे इनिशियलाइज़ करें।
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    //कुछ छवि प्रसंस्करण करें।
}
```

निम्न उदाहरण दर्शाता है कि दाएँ‑से‑बाएँ भाषाओं के लिए ITextPortion के माध्यम से टेक्स्ट अलाइनमेंट सही ढंग से काम करता है।

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

निम्न उदाहरण दर्शाता है कि Grayscale 16 बिट PSD फ़ाइलों को पढ़ना और 16 बिट प्रति चैनल RGB में सहेजना सही ढंग से और बिना किसी अपवाद के काम करता है।

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
    // यहाँ कोई अपवाद नहीं होना चाहिए।
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

निम्न उदाहरण दर्शाता है कि Grayscale 16 बिट PSD फ़ाइलों को पढ़ना और 8 बिट प्रति चैनल Grayscale में सहेजना सही ढंग से और बिना किसी अपवाद के काम करता है।

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
    // यहाँ कोई अपवाद नहीं होना चाहिए।
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

निम्न उदाहरण दर्शाता है कि दस्तावेज़ रूपांतरण प्रगति सही ढंग से और बिना किसी अपवाद के काम करती है।

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

निम्न उदाहरण दर्शाता है कि ग्रेस्केल 16 बिट PSD फ़ाइलों को पढ़ना और सहेजना सही ढंग से और बिना किसी अपवाद के काम करता है।

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
        // यहाँ कोई अपवाद नहीं होना चाहिए।
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

### देखें भी

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

निर्दिष्ट स्ट्रीम से नई इमेज लोड करता है।

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इमेज लोड करने के लिए स्ट्रीम। |
| loadOptions | LoadOptions | लोड विकल्प। |

### रिटर्न वैल्यू

लोड की गई इमेज।

### देखें भी

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

निर्दिष्ट स्ट्रीम से नई इमेज लोड करता है।

```csharp
public static Image Load(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इमेज लोड करने के लिए स्ट्रीम। |

### रिटर्न वैल्यू

लोड की गई इमेज।

## उदाहरण

यह उदाहरण मौजूदा इमेज फ़ाइल को लोड करने के लिए System.IO.Stream ऑब्जेक्ट्स के उपयोग को दर्शाता है।

```csharp
[C#]

//FileStream की एक इंस्टेंस बनाएं
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Image क्लास की एक इंस्टेंस बनाएं और Load मेथड को कॉल करके FileStream ऑब्जेक्ट के माध्यम से मौजूदा फ़ाइल लोड करें
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //कुछ इमेज प्रोसेसिंग करें।
    }
}
```

### देखें भी

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



---
title: "Image.Save"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Image मेथड। छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है।"
type: docs
weight: 240
url: /hi/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

इमेज डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

```csharp
public void Save()
```

### देखें भी

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| विकल्प | ImageOptionsBase | विकल्प। |

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि आप Adobe Illustrator फ़ाइलों को Aspose.PSD में PDF फ़ॉर्मेट में कैसे निर्यात कर सकते हैं।

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

निम्नलिखित उदाहरण दर्शाता है कि AsposePSD PSB फ़ाइलों को PSD फ़ॉर्मेट में निर्यात करने का समर्थन करता है।

```csharp
[C#]

// PSB को PDF के रूप में सहेजने का समर्थन
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

निम्नलिखित कोड PsdImage को चयन योग्य टेक्स्ट के साथ PDF दस्तावेज़ के रूप में सहेजता है।

```csharp
[C#]

// PSD को PDF में सहेजने से चयन योग्य टेक्स्ट उपलब्ध नहीं होता है
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में AI फ़ाइल को PSD और PNG फ़ॉर्मेट में कैसे निर्यात कर सकते हैं।

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

यह उदाहरण एक Image को Save करने के सरल चरण दिखाता है। इस ऑपरेशन को प्रदर्शित करने के लिए, हम किसी डिस्क स्थान से मौजूदा फ़ाइल लोड करते हैं, Image पर Rotate ऑपरेशन करते हैं और File Path का उपयोग करके JPEG फ़ाइल फ़ॉर्मेट में Image को Save करते हैं।

```csharp
[C#]

//Image क्लास की एक इंस्टेंस बनाएं और इसे File path के माध्यम से मौजूदा फ़ाइल से इनिशियलाइज़ करें।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //इमेज को X अक्ष के बारे में 180 डिग्री घुमाएँ
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Image को Jpeg के रूप में File Path पर डिफ़ॉल्ट JpegOptions सेटिंग्स के साथ Save करें।
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में LayerGroup की दृश्यता को कैसे बदल सकते हैं।

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// लेयर नामों में परिवर्तन करें और इसे सहेजें
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // समूह के भीतर सभी चीज़ों को बंद करें
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में सरल कंस्ट्रक्टर संस्करण का उपयोग करने पर नए बनाए गए लेयर पर कैसे ड्रॉ कर सकते हैं

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

    // Pen टूल से एक आयत बनाएं
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // नीले रंग में Solid Brush से एक और आयत बनाएं
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में PassThrough लेयर ब्लेंड मोड का उपयोग कैसे कर सकते हैं।

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| विकल्प | ImageOptionsBase | विकल्प। |
| boundsRectangle | Rectangle | गंतव्य छवि सीमाओं का आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | विकल्प |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | छवि सहेजना विफल रहा। |

### देखें भी

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इमेज डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | ImageOptionsBase | सेव विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | वर्तमान में यह समर्थित नहीं होने के कारण निर्दिष्ट प्रारूप में सहेज नहीं सकता।;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | छवि निर्यात विफल रहा। |

## उदाहरण

यह उदाहरण छवि को MemoryStream में सहेजने की प्रक्रिया दिखाता है। इस ऑपरेशन को प्रदर्शित करने के लिए, उदाहरण किसी डिस्क स्थान से मौजूदा फ़ाइल लोड करता है, छवि पर Rotate ऑपरेशन करता है और छवि को Gif प्रारूप में सहेजता है।

```csharp
[C#]

//MemoryStream का एक इंस्टेंस बनाएँ।
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Image क्लास की एक इंस्टेंस बनाएं और इसे File path के माध्यम से मौजूदा फ़ाइल से इनिशियलाइज़ करें।
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //इमेज को X अक्ष के बारे में 180 डिग्री घुमाएँ
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //डिफ़ॉल्ट GifOptions सेटिंग्स के साथ छवि को PSD के रूप में MemoryStream में सहेजें
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### देखें भी

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इमेज डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | ImageOptionsBase | सेव विकल्प। |
| boundsRectangle | Rectangle | गंतव्य इमेज बाउंड्स आयत। स्रोत बाउंड्स के उपयोग के लिए खाली आयत सेट करें। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | वर्तमान में यह समर्थित नहीं होने के कारण निर्दिष्ट प्रारूप में सहेज नहीं सकता।;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | छवि निर्यात विफल रहा। |

### देखें भी

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



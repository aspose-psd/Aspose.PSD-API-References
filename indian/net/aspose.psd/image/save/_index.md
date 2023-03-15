---
title: Image.Save
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Image तरक. छव डेट क अंतर्नहत स्ट्रम में सहेजत है
type: docs
weight: 230
url: /hi/net/aspose.psd/image/save/
---
## Save() {#save}

छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

```csharp
public void Save()
```

### यह सभी देखें

* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है।

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ. |
| options | ImageOptionsBase | विकल्प। |

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि कैसे आप Adobe Illustrator फ़ाइलों को Aspose.PSD में PDF स्वरूप में निर्यात कर सकते हैं

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

निम्न उदाहरण दर्शाता है कि AsposePSD PSB फ़ाइलों को PSD प्रारूप में निर्यात करने का समर्थन करता है।

```csharp
[C#]

// पीएसबी को पीडीएफ के रूप में सहेजने का समर्थन करें
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

चयन योग्य पाठ के साथ PsdImage को PDF दस्तावेज़ के रूप में सहेजने वाला निम्न कोड।

```csharp
[C#]

// PSD को PDF में सहेजना चयन करने योग्य पाठ प्रदान नहीं करता है
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

निम्न उदाहरण दर्शाता है कि कैसे आप AI फ़ाइल को Aspose.PSD में PSD और PNG प्रारूप में निर्यात कर सकते हैं

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

निम्न उदाहरण दर्शाता है कि दाएँ-से-बाएँ भाषाओं के लिए ITextPortion के माध्यम से पाठ संरेखण ठीक से काम करता है।

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

यह उदाहरण एक छवि को बचाने के सरल चरणों को दिखाता है। इस ऑपरेशन को प्रदर्शित करने के लिए, हम किसी डिस्क स्थान से एक मौजूदा फ़ाइल को लोड करते हैं, छवि पर रोटेट ऑपरेशन करते हैं और फ़ाइल पथ का उपयोग करके जेपीईजी फ़ाइल प्रारूप में छवि को सहेजते हैं।

```csharp
[C#]

// छवि वर्ग का एक उदाहरण बनाएं और इसे फ़ाइल पथ के माध्यम से मौजूदा फ़ाइल के साथ प्रारंभ करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // एक्स अक्ष के बारे में छवि को 180 डिग्री पर घुमाएं
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // छवि को Jpeg के रूप में फ़ाइल पथ में डिफ़ॉल्ट JpegOptions सेटिंग्स के साथ सहेजें
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में LayerGroup दृश्यता को कैसे बदल सकते हैं

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// लेयर के नाम में बदलाव करें और इसे सेव करें
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // एक समूह के अंदर सब कुछ बंद कर दें
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

निम्न उदाहरण प्रदर्शित करता है कि यदि Aspose.PSD में सरल कन्स्ट्रक्टर संस्करण का उपयोग किया जाता है तो आप नई बनाई गई परत पर कैसे आकर्षित कर सकते हैं

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

    // पेन टूल के साथ एक आयत बनाएं
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // सॉलिड ब्रश के साथ नीले रंग में एक और आयत बनाएं
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

निम्न उदाहरण दर्शाता है कि ग्रेस्केल 16 बिट PSD फ़ाइलों को 16 बिट प्रति चैनल आरजीबी में पढ़ना और सहेजना सही ढंग से और बिना किसी अपवाद के काम करता है।

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

निम्न उदाहरण दर्शाता है कि ग्रेस्केल 16 बिट PSD फ़ाइलों को 8 बिट प्रति चैनल ग्रेस्केल में पढ़ना और सहेजना सही ढंग से और बिना किसी अपवाद के काम करता है।

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

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में PassThrough लेयर ब्लेंड मोड का उपयोग कैसे कर सकते हैं

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

### यह सभी देखें

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है।

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| options | ImageOptionsBase | विकल्प। |
| boundsRectangle | Rectangle | गंतव्य छवि आयत को सीमित करती है। स्रोत सीमा का उपयोग करने के लिए खाली आयत सेट करें। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | विकल्प |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | छवि सहेजना विफल रहा. |

### यह सभी देखें

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | ImageOptionsBase | सेव विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | निर्दिष्ट प्रारूप में सहेजा नहीं जा सकता क्योंकि यह इस समय समर्थित नहीं है। विकल्पबेस |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | छवि निर्यात विफल रहा। |

### उदाहरण

यह उदाहरण इमेज को मेमोरीस्ट्रीम में सेव करने की प्रक्रिया को दिखाता है। इस ऑपरेशन को प्रदर्शित करने के लिए, उदाहरण किसी डिस्क स्थान से मौजूदा फ़ाइल को लोड करता है, इमेज पर रोटेट ऑपरेशन करता है और इमेज को Gif फॉर्मेट में सेव करता है

```csharp
[C#]

// मेमोरीस्ट्रीम का एक उदाहरण बनाएं
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // छवि वर्ग का एक उदाहरण बनाएं और इसे फ़ाइल पथ के माध्यम से मौजूदा फ़ाइल के साथ प्रारंभ करें
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // एक्स अक्ष के बारे में छवि को 180 डिग्री पर घुमाएं
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        // छवि को डिफ़ॉल्ट GifOptions सेटिंग्स के साथ PSD के रूप में मेमोरीस्ट्रीम में सहेजें
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### यह सभी देखें

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| optionsBase | ImageOptionsBase | सेव विकल्प। |
| boundsRectangle | Rectangle | गंतव्य छवि आयत को सीमित करती है। स्रोत सीमा का उपयोग करने के लिए खाली आयत सेट करें। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | निर्दिष्ट प्रारूप में सहेजा नहीं जा सकता क्योंकि यह इस समय समर्थित नहीं है। विकल्पबेस |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | छवि निर्यात विफल रहा। |

### यह सभी देखें

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)



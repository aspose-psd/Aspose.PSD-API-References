---
title: "क्लास PsdOptions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageOptions.PsdOptions क्लास। PSD फ़ाइल प्रारूप निर्माण विकल्प।"
type: docs
weight: 5390
url: /hi/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

psd फ़ाइल फ़ॉर्मेट निर्माण विकल्प।

```csharp
public class PsdOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | `PsdOptions` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | `PsdOptions` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | `PsdOptions` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। यह पारदर्शी वस्तुओं के नीचे देखा जा सकता है। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | रंग चैनल प्रति बिट्स की संख्या प्राप्त करता है या सेट करता है। |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | रंग चैनलों की संख्या प्राप्त करता है या सेट करता है। |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | psd रंग मोड प्राप्त करता है या सेट करता है। |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | psd संपीड़न विधि प्राप्त करता है या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: `System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });` |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [full frame] है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | रंग पैलेट प्राप्त करता है या सेट करता है। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है या सेट करता है। यह PSD या PSB हो सकता है। |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या [refresh image preview data] - विकल्प का उपयोग अन्य PSD इमेज व्यूअर्स के साथ संगतता अधिकतम करने के लिए किया जाता है। कृपया ध्यान दें, कॉम्पैक्ट फ्रेमवर्क प्लेटफ़ॉर्म के लिए अंतिम लेआउट में टेक्स्ट लेयर्स का ड्रॉ करना समर्थित नहीं है। |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या - ग्लोबल टेक्स्ट इंजन रिसोर्स हटाएँ - कुछ टेक्स्ट-लेयर वाले psd फ़ाइलों के लिए उपयोग किया जाता है, केवल तभी जब प्रोसेसिंग के बाद उन्हें Adobe Photoshop में नहीं खोला जा सकता (मुख्यतः अनुपलब्ध फ़ॉन्ट्स वाले टेक्स्ट लेयर्स के कारण)। इस विकल्प का उपयोग करने के बाद, उपयोगकर्ता को Photoshop में खुले फ़ाइल में निम्न करना होगा: मेनू \"Text\" -> \"Process absent fonts\"। उस ऑपरेशन के बाद सभी टेक्स्ट फिर से दिखाई देंगे। कृपया ध्यान दें, यह ऑपरेशन अंतिम लेआउट में कुछ परिवर्तन कर सकता है। |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | psd संसाधनों को प्राप्त करता है या सेट करता है। यदि मान: NULL - तो मूल ImageResources सहेजें (डिफ़ॉल्ट व्यवहार) Not Empty - तो इस प्रॉपर्टी में पास किए गए संसाधनों + [required resources] सहेजें। Empty - तो केवल [required resources] सहेजे जाएँ। आवश्यक संसाधन: ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या [update metadata]। यदि मान true है, तो इमेज सहेजते समय मेटाडेटा अपडेट हो जाएगा। |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रास्टराइज़ेशन विकल्प प्राप्त करता है या सेट करता है। |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | psd फ़ाइल संस्करण प्राप्त करता है या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | XMP डेटा कंटेनर प्राप्त करें या सेट करें |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस इंस्टेंस की क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |

## उदाहरण

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

यह उदाहरण PsdOptions इंस्टेंस की Source प्रॉपर्टी द्वारा निर्दिष्ट डिस्क स्थान पर एक नई Image फ़ाइल बनाता है। वास्तविक इमेज बनाने से पहले PsdOptions इंस्टेंस की कई प्रॉपर्टी सेट की जाती हैं। विशेष रूप से Source प्रॉपर्टी, जो इस मामले में वास्तविक डिस्क स्थान को दर्शाती है।

```csharp
[C#]

//PsdOptions का एक इंस्टेंस बनाएँ और उसकी विभिन्न प्रॉपर्टी सेट करें।
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource का एक इंस्टेंस बनाएँ और उसे PsdOptions इंस्टेंस के लिए Source के रूप में असाइन करें।
//दूसरा Boolean पैरामीटर निर्धारित करता है कि बनाई जाने वाली फ़ाइल अस्थायी है या नहीं।
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image का एक इंस्टेंस बनाएँ और Create मेथड को कॉल करके उसे PsdOptions के इंस्टेंस से इनिशियलाइज़ करें।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //कुछ छवि प्रसंस्करण करें।

    // सभी परिवर्तन सहेजें।
    image.Save();
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

यह उदाहरण दिखाता है कि कैसे पिक्सेल जानकारी को Color प्रकार की एरे में लोड किया जाता है, एरे को संशोधित किया जाता है और उसे इमेज में वापस सेट किया जाता है। इन ऑपरेशनों को करने के लिए, यह उदाहरण MemoryStream ऑब्जेक्ट का उपयोग करके एक नई Image फ़ाइल (PSD फ़ॉर्मेट में) बनाता है।

```csharp
[C#]

//MemoryStream का एक इंस्टेंस बनाएँ।
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions का एक इंस्टेंस बनाएँ और उसकी विभिन्न प्रॉपर्टी, जिसमें Source प्रॉपर्टी भी शामिल है, सेट करें।
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image का एक इंस्टेंस बनाएँ।
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //छवि की सीमा को निर्दिष्ट करके छवि के पिक्सेल प्राप्त करें
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //ऐरे पर लूप करें और वैकल्पिक अनुक्रमित पिक्सेल का रंग सेट करें
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //अनुक्रमित पिक्सेल का रंग पीला सेट करें
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //अनुक्रमित पिक्सेल का रंग नीला सेट करें
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //पिक्सेल परिवर्तन को छवि पर लागू करें
        image.SavePixels(image.Bounds, pixels);

        // सभी परिवर्तन सहेजें।
        image.Save();
    }

    //MemoryStream को फ़ाइल में लिखें
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



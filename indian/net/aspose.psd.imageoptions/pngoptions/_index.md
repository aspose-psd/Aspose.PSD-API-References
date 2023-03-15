---
title: Class PngOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ImageOptions.PngOptions कक्ष. पएनज फ़इल प्ररूप वकल्प बनत है
type: docs
weight: 4880
url: /hi/net/aspose.psd.imageoptions/pngoptions/
---
## PngOptions class

पीएनजी फ़ाइल प्रारूप विकल्प बनाता है।

```csharp
public class PngOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`PngOptions` वर्ग. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | का एक नया उदाहरण प्रारंभ करता है`PngOptions` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | थोड़ी गहराई। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | रंग के प्रकार को प्राप्त या सेट करता है। |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | 0-9 रेंज में पीएनजी छवि संपीड़न स्तर, जहां 9 अधिकतम संपीड़न है और 0 स्टोर मोड है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रेखापुंज में निर्यात करते समय पाठ को आकर्षित करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा परत फ़ॉन्ट सिस्टम में प्रस्तुत नहीं किया गया है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम लेने के लिए अगले कोड स्निपेट का उपयोग किया जा सकता है : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | पीएनजी फ़ाइल सहेजने की प्रक्रिया के दौरान उपयोग किए जाने वाले फ़िल्टर प्रकार को प्राप्त या सेट करता है। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [पूर्ण फ्रेम] . इंगित करने वाला मान प्राप्त करता है या सेट करता है |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रगति ईवेंट हैंडलर प्राप्त या सेट करता है। |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह`PngOptions` प्रगतिशील है. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त या सेट करता है। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के लिए स्रोत प्राप्त करता है या सेट करता है. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रेखांकन विकल्प प्राप्त या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा कंटेनर प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस उदाहरण को क्लोन करता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | डिफ़ॉल्ट संपीड़न स्तर। |

### उदाहरण

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

यह उदाहरण निर्यात उद्देश्यों के लिए SaveOptions Namespace से विभिन्न वर्गों के उपयोग को प्रदर्शित करता है। Psd प्रकार की छवि को छवि के उदाहरण में लोड किया जाता है और फिर कई स्वरूपों में निर्यात किया जाता है।

```csharp
[C#]

// छवि वर्ग के एक उदाहरण में एक मौजूदा छवि लोड करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // डिफ़ॉल्ट विकल्पों का उपयोग करके BMP फ़ाइल स्वरूप में निर्यात करें
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    // डिफ़ॉल्ट विकल्पों का उपयोग करके JPEG फ़ाइल स्वरूप में निर्यात करें
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    // डिफ़ॉल्ट विकल्पों का उपयोग करके JPEG 2000 फ़ाइल स्वरूप में निर्यात करें
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    // डिफ़ॉल्ट विकल्पों का उपयोग करके PNG फ़ाइल स्वरूप में निर्यात करें
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    // डिफ़ॉल्ट विकल्पों का उपयोग करके TIFF फ़ाइल स्वरूप में निर्यात करें
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
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

यह उदाहरण छवि सतह पर आदिम आकार बनाने के लिए ग्राफिक्स वर्ग का उपयोग करता है। ऑपरेशन को प्रदर्शित करने के लिए, उदाहरण PSD प्रारूप में एक नई छवि बनाता है और ग्राफिक्स वर्ग द्वारा प्रदर्शित ड्रा विधियों का उपयोग करके छवि सतह पर आदिम आकृतियों को खींचता है और फिर इसे PSD फ़ाइल प्रारूप में निर्यात करता है।

```csharp
[C#]

// छवि का एक उदाहरण बनाएं 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स क्लास का एक उदाहरण बनाएं और आरंभ करें
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // स्पष्ट ग्राफिक्स सतह
    graphics.Clear(Color.Wheat);

    // ब्लैक कलर वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक आर्क बनाएं, 
    // आर्क के चारों ओर एक आयत, स्टार्ट एंगल और स्वीप एंगल
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // ब्लू कलर और को-ऑर्डिनेट पॉइंट वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक बेज़ियर ड्रा करें।
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // हरे रंग और बिंदुओं की एक सरणी वाले पेन ऑब्जेक्ट को निर्दिष्ट करके एक वक्र बनाएं
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // पेन ऑब्जेक्ट और आसपास के आयत का उपयोग करके एक दीर्घवृत्त बनाएं
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //एक रेखा खींचो 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // पाई सेगमेंट ड्रा करें
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // पेन ऑब्जेक्ट को लाल रंग और बिंदुओं की एक सरणी निर्दिष्ट करके एक बहुभुज बनाएं
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // एक आयत बनाएं
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    // एक सॉलिडब्रश ऑब्जेक्ट बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // विशिष्ट बिंदु पर सॉलिडब्रश ऑब्जेक्ट और फ़ॉन्ट का उपयोग करके एक स्ट्रिंग बनाएं
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // सभी परिवर्तनों को सहेजें।
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### यह सभी देखें

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* नाम स्थान [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* सभा [Aspose.PSD](../../)



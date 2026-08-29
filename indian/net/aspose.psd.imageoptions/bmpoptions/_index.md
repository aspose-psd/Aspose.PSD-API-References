---
title: "क्लास BmpOptions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageOptions.BmpOptions क्लास। BMP फ़ाइल फ़ॉर्मेट निर्माण विकल्प।"
type: docs
weight: 5280
url: /hi/net/aspose.psd.imageoptions/bmpoptions/
---
{{< psd/tize >}}
## BmpOptions class

BMP फ़ाइल फ़ॉर्मेट निर्माण विकल्प।

```csharp
public class BmpOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | `BmpOptions` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | `BmpOptions` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | इमेज बिट्स प्रति पिक्सेल की संख्या को प्राप्त करता है या सेट करता है। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | कम्प्रेशन को प्राप्त करता है या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: `System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });` |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [full frame] है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | रंग पैलेट प्राप्त करता है या सेट करता है। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रास्टराइज़ेशन विकल्प प्राप्त करता है या सेट करता है। |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस इंस्टेंस की क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |

## उदाहरण

यह उदाहरण निर्यात उद्देश्यों के लिए SaveOptions नेमस्पेस की विभिन्न क्लासों के उपयोग को दर्शाता है। Psd प्रकार की एक इमेज को Image के इंस्टेंस में लोड किया जाता है और फिर कई फ़ॉर्मेट में निर्यात किया जाता है।

```csharp
[C#]

//Image क्लास के एक इंस्टेंस में मौजूदा इमेज लोड करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //डिफ़ॉल्ट विकल्पों का उपयोग करके BMP फ़ाइल फ़ॉर्मेट में निर्यात करें
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //डिफ़ॉल्ट विकल्पों का उपयोग करके JPEG फ़ाइल फ़ॉर्मेट में निर्यात करें
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //डिफ़ॉल्ट विकल्पों का उपयोग करके JPEG 2000 फ़ाइल फ़ॉर्मेट में निर्यात करें
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //डिफ़ॉल्ट विकल्पों का उपयोग करके PNG फ़ाइल फ़ॉर्मेट में निर्यात करें
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //डिफ़ॉल्ट विकल्पों का उपयोग करके TIFF फ़ाइल फ़ॉर्मेट में निर्यात करें
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### देखें भी

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



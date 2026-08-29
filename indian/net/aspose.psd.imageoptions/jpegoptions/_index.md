---
title: "JpegOptions क्लास"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageOptions.JpegOptions क्लास। JPEG फ़ाइल फ़ॉर्मेट निर्माण विकल्प"
type: docs
weight: 5330
url: /hi/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

jpeg फ़ाइल फ़ॉर्मेट निर्माण विकल्प।

```csharp
public class JpegOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | `JpegOptions` क्लास का नया उदाहरण आरंभ करता है। |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | `JpegOptions` क्लास का नया उदाहरण आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | लॉसलेस JPEG छवि के लिए प्रति चैनल बिट्स को प्राप्त करता है या सेट करता है। अब हम 2 से 8 बिट्स प्रति चैनल का समर्थन करते हैं। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK JPEG छवियों के लिए गंतव्य CMYK रंग प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे RGBColorProfile के साथ जोड़े में होना चाहिए। |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | JPEG छवि के लिए रंग प्रकार को प्राप्त करता है या सेट करता है। |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | JPEG फ़ाइल टिप्पणी को प्राप्त करता है या सेट करता है। |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | संपीड़न प्रकार को प्राप्त करता है या सेट करता है। |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | डिफ़ॉल्ट मेमोरी आवंटन सीमा को प्राप्त करता है या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: `System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });` |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | EXIF डेटा कंटेनर को प्राप्त करें या सेट करें |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [full frame] है। |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | प्रत्येक घटक के लिए क्षैतिज सबसैंपलिंग को प्राप्त करता है या सेट करता है। |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | JFIF को प्राप्त करता है या सेट करता है। |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | नियर-लॉसलेस कोडिंग के लिए JPEG-LS अंतर सीमा को प्राप्त करता है या सेट करता है (JPEG-LS विनिर्देशन से NEAR पैरामीटर)। |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS इंटरलीव मोड को प्राप्त करता है या सेट करता है। |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS प्रीसेट पैरामीटर को प्राप्त करता है या सेट करता है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | रंग पैलेट प्राप्त करता है या सेट करता है। |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | लाल, हरे और नीले घटकों को पृष्ठभूमि रंग के साथ मिलाया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है, यदि अल्फा चैनल मौजूद हो। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | छवि गुणवत्ता प्राप्त करता है या सेट करता है। |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD ऑप्टिमाइज़र सेटिंग्स प्राप्त करता है या सेट करता है। |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है। |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK JPEG छवियों के लिए गंतव्य RGB रंग प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे CMYKColorProfile के साथ जोड़ा जाना चाहिए। |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड प्राप्त करता है या सेट करता है। BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | स्केल्ड गुणवत्ता। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रास्टराइज़ेशन विकल्प प्राप्त करता है या सेट करता है। |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | प्रत्येक घटक के लिए लंबवत सबसैंपलिंग प्राप्त करता है या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस इंस्टेंस की क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |

## उदाहरण

यह उदाहरण Aspose.PSD for .Net API के उपयोग को दिखाता है जिससे छवियों को JPEG प्रारूप में परिवर्तित किया जाता है। इस लक्ष्य को प्राप्त करने के लिए यह उदाहरण एक मौजूदा छवि लोड करता है और फिर उसे JPEG फ़ाइल प्रारूप में बदलता है।

```csharp
[C#]

//छवि क्लास का एक इंस्टेंस बनाता है और फ़ाइल पथ के माध्यम से मौजूदा फ़ाइल से इसे प्रारंभ करता है।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //आउटपुट छवि का आकार कम करने के लिए गुणवत्ता को 50% पर सेट करें।
    jpegOptions.Quality = 50;

    //EXIF टिप्पणियों को सेट करें।
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //प्रदान किए गए JpegOptions सेटिंग्स के साथ छवि को डिस्क स्थान पर सहेजें।
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

यह उदाहरण System.IO.Stream के उपयोग को दर्शाता है जिससे नई छवि फ़ाइल बनाई जाती है।

```csharp
[C#]

//PsdOptions का एक इंस्टेंस बनाता है और उसकी विभिन्न प्रॉपर्टीज़ सेट करता है।
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream का एक इंस्टेंस बनाएं।
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions के इंस्टेंस के लिए स्रोत प्रॉपर्टी को परिभाषित करें।
//दूसरा बूलियन पैरामीटर निर्धारित करता है कि क्या Stream को स्कोप से बाहर निकलते ही डिस्पोज़ किया जाता है।
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image का एक इंस्टेंस बनाता है और Image ऑब्जेक्ट को प्रारंभ करने के लिए PsdOptions को पैरामीटर के रूप में देकर Create मेथड को कॉल करता है।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //कुछ छवि प्रसंस्करण करें।
}
```

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



---
title: Class JpegOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ImageOptions.JpegOptions कक्ष. जेपईज फ़इल प्ररूप वकल्प बनते हैं
type: docs
weight: 4840
url: /hi/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

जेपीईजी फ़ाइल प्रारूप विकल्प बनाते हैं।

```csharp
public class JpegOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`JpegOptions` वर्ग. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | का एक नया उदाहरण प्रारंभ करता है`JpegOptions` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | दोषरहित जेपीईजी छवि के लिए प्रति चैनल बिट प्राप्त या सेट करता है। अब हम प्रति चैनल 2 से 8 बिट्स का समर्थन करते हैं. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg छवियों के लिए गंतव्य CMYK रंग प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए RGBColorProfile के साथ जोड़ा जाना चाहिए। |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | जेपीईजी छवि के लिए रंग प्रकार प्राप्त या सेट करता है। |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | जेपीईजी फ़ाइल टिप्पणी प्राप्त या सेट करता है। |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | संपीड़न प्रकार प्राप्त या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रेखापुंज में निर्यात करते समय पाठ को आकर्षित करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा परत फ़ॉन्ट सिस्टम में प्रस्तुत नहीं किया गया है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम लेने के लिए अगले कोड स्निपेट का उपयोग किया जा सकता है : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | एक्सिफ डेटा कंटेनर प्राप्त करें या सेट करें |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [पूर्ण फ्रेम] . इंगित करने वाला मान प्राप्त करता है या सेट करता है |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | प्रत्येक घटक के लिए क्षैतिज सबसैम्पलिंग प्राप्त या सेट करता है। |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | jfif. प्राप्त या सेट करता है |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | निकट-दोषरहित कोडिंग (जेपीईजी-एलएस विनिर्देश से NEAR पैरामीटर) के लिए JPEG-LS अंतर को प्राप्त या सेट करता है। |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | जेपीईजी-एलएस इंटरलीव मोड प्राप्त या सेट करता है। |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | जेपीईजी-एलएस प्रीसेट पैरामीटर प्राप्त या सेट करता है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि अल्फा चैनल मौजूद होने पर लाल, हरे और नीले घटकों को पृष्ठभूमि रंग के साथ मिश्रित किया जाना चाहिए या नहीं। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रगति ईवेंट हैंडलर प्राप्त या सेट करता है। |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | छवि गुणवत्ता प्राप्त या सेट करता है। |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | आरडी ऑप्टिमाइज़र सेटिंग प्राप्त या सेट करता है. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त या सेट करता है। |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | रिज़ॉल्यूशन यूनिट प्राप्त या सेट करता है। |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg छवियों के लिए गंतव्य RGB रंग प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए CMYKColorProfile के साथ जोड़ा जाना चाहिए। |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8-बिट मान को n-बिट मान में फ़िट करने के लिए सैंपल राउंडिंग मोड प्राप्त या सेट करता है।BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | मापी गई गुणवत्ता. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के लिए स्रोत प्राप्त करता है या सेट करता है. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रेखांकन विकल्प प्राप्त या सेट करता है। |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | प्रत्येक घटक के लिए वर्टिकल सबसैम्पलिंग प्राप्त या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा कंटेनर प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस उदाहरण को क्लोन करता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |

### उदाहरण

यह उदाहरण छवियों को जेपीईजी प्रारूप में कनवर्ट करने के लिए .NET API के लिए Aspose.PSD के उपयोग को प्रदर्शित करता है। इस लक्ष्य को प्राप्त करने के लिए यह उदाहरण एक मौजूदा छवि को लोड करता है और फिर इसे जेपीईजी फ़ाइल स्वरूप में परिवर्तित करता है।

```csharp
[C#]

// छवि वर्ग का एक उदाहरण बनाता है और इसे फ़ाइल पथ के माध्यम से मौजूदा फ़ाइल के साथ प्रारंभ करता है
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // PsdOptions वर्ग का एक उदाहरण बनाएँ
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    // आउटपुट छवि के आकार को कम करने के लिए गुणवत्ता को 50% पर सेट करें।
    jpegOptions.Quality = 50;

    // एक्सिफ कमेंट सेट करें।
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    // आपूर्ति की गई JpegOptions सेटिंग्स के साथ छवि को डिस्क स्थान पर सहेजें
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

यह उदाहरण एक नई छवि फ़ाइल बनाने के लिए System.IO.Stream के उपयोग को प्रदर्शित करता है

```csharp
[C#]

// PsdOptions का एक उदाहरण बनाता है और इसके विभिन्न गुणों को सेट करता है
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// System.IO.Stream का एक उदाहरण बनाएँ
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

// PsdOptions के उदाहरण के लिए स्रोत संपत्ति को परिभाषित करें
// दूसरा बूलियन पैरामीटर निर्धारित करता है कि क्या एक बार दायरे से बाहर हो जाने पर स्ट्रीम का निपटान किया जाता है
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

// इमेज का एक उदाहरण बनाता है और इमेज ऑब्जेक्ट को इनिशियलाइज़ करने के लिए पैरामीटर के रूप में PsdOptions के साथ क्रिएट मेथड को कॉल करता है   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // कुछ इमेज प्रोसेसिंग करें
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

### यह सभी देखें

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* नाम स्थान [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* सभा [Aspose.PSD](../../)



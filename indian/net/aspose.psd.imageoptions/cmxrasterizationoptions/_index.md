---
title: Class CmxRasterizationOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ImageOptions.CmxRasterizationOptions कक्ष. सएमएक्स नर्यतक वकल्प
type: docs
weight: 4800
url: /hi/net/aspose.psd.imageoptions/cmxrasterizationoptions/
---
## CmxRasterizationOptions class

सीएमएक्स निर्यातक विकल्प।

```csharp
public class CmxRasterizationOptions : VectorRasterizationOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CmxRasterizationOptions](cmxrasterizationoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | एक पृष्ठभूमि रंग प्राप्त या सेट करता है। |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | सीमा X. प्राप्त या सेट करता है |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | सीमा Y. प्राप्त या सेट करता है |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि केंद्र आरेखण है या नहीं। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रेखापुंज में निर्यात करते समय पाठ को आकर्षित करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा परत फ़ॉन्ट सिस्टम में प्रस्तुत नहीं किया गया है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम लेने के लिए अगले कोड स्निपेट का उपयोग किया जा सकता है : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | एक अग्रभूमि रंग प्राप्त या सेट करता है। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [पूर्ण फ्रेम] . इंगित करने वाला मान प्राप्त करता है या सेट करता है |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | पृष्ठ ऊंचाई प्राप्त या सेट करता है। |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | पृष्ठ आकार प्राप्त या सेट करता है। |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | पृष्ठ की चौड़ाई प्राप्त या सेट करता है। |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। |
| [Positioning](../../aspose.psd.imageoptions/cmxrasterizationoptions/positioning/) { get; set; } | स्थिति प्राप्त करता है या सेट करता है। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रगति ईवेंट हैंडलर प्राप्त या सेट करता है। |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त या सेट करता है। |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | स्मूथिंग मोड प्राप्त या सेट करता है। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के लिए स्रोत प्राप्त करता है या सेट करता है. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | टेक्स्ट रेंडरिंग संकेत प्राप्त या सेट करता है। |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रेखांकन विकल्प प्राप्त या सेट करता है। |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा कंटेनर प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस उदाहरण को क्लोन करता है। |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | इसकी प्रतिलिपि बनाता है. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |

### यह सभी देखें

* class [VectorRasterizationOptions](../vectorrasterizationoptions/)
* नाम स्थान [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* सभा [Aspose.PSD](../../)



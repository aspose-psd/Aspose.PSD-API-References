---
title: "Class PdfOptions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageOptions.PdfOptions class. PDF विकल्प।"
type: docs
weight: 5360
url: /hi/net/aspose.psd.imageoptions/pdfoptions/
---
{{< psd/tize >}}
## PdfOptions class

PDF विकल्प।

```csharp
public class PdfOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfOptions](pdfoptions/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: `System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });` |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [full frame] है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | पृष्ठ का आकार प्राप्त करता है या सेट करता है। |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | रंग पैलेट प्राप्त करता है या सेट करता है। |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF कोर विकल्प |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | दस्तावेज़ के लिए मेटाडेटा प्राप्त करता है या सेट करता है। |
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

निम्नलिखित उदाहरण PsdImage को PDF फ़ॉर्मेट में निर्यात करने के समर्थन को दर्शाता है।

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### देखें भी

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



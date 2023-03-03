---
title: Class GifOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ImageOptions.GifOptions कक्ष. जआईएफ फ़इल प्ररूप नर्मण वकल्प
type: docs
weight: 4810
url: /hi/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

जीआईएफ फ़ाइल प्रारूप निर्माण विकल्प।

```csharp
public class GifOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`GifOptions` वर्ग. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | का एक नया उदाहरण प्रारंभ करता है`GifOptions` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | GIF बैकग्राउंड कलर इंडेक्स प्राप्त या सेट करता है। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | GIF रंग रिज़ॉल्यूशन प्राप्त या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रेखापुंज में निर्यात करते समय पाठ को आकर्षित करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा परत फ़ॉन्ट सिस्टम में प्रस्तुत नहीं किया गया है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम लेने के लिए अगले कोड स्निपेट का उपयोग किया जा सकता है : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | पैलेट सुधार लागू किया गया है या नहीं यह इंगित करने वाला मान प्राप्त या सेट करता है। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [पूर्ण फ्रेम] . इंगित करने वाला मान प्राप्त करता है या सेट करता है |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि GIF में ट्रेलर है या नहीं। |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | सच है अगर छवि इंटरलेस्ड होनी चाहिए। |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | पैलेट प्रविष्टियों को सॉर्ट किया गया है या नहीं यह इंगित करने वाला मान प्राप्त या सेट करता है। |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | अधिकतम अनुमत पिक्सेल अंतर प्राप्त या सेट करता है। यदि शून्य से अधिक है, हानिकारक संपीड़न का उपयोग किया जाएगा। इष्टतम हानिकारक संपीड़न के लिए अनुशंसित मूल्य 80 है। 30 बहुत हल्का संपीड़न है, 200 भारी है। यह सबसे अच्छा काम करता है जब केवल थोड़ा नुकसान पेश किया जाता है, और संपीड़न एल्गोरिदम की सीमा के कारण बहुत अधिक नुकसान का स्तर उतना लाभ नहीं देगा। अनुमत मानों की सीमा [0, 1000] है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | GIF पिक्सेल पहलू अनुपात प्राप्त या सेट करता है। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रगति ईवेंट हैंडलर प्राप्त या सेट करता है। |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त या सेट करता है। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के लिए स्रोत प्राप्त करता है या सेट करता है. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रेखांकन विकल्प प्राप्त या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा कंटेनर प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस उदाहरण को क्लोन करता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |

### उदाहरण

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



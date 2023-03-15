---
title: Class TiffOptions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.ImageOptions.TiffOptions कक्ष. टफ फ़इल प्ररूप वकल्प ध्यन दें क चड़ई और ऊंचई टैग चड़ई और ऊंचई पैरमटर द्वर छव नर्मण पर अधलेखत ह जएंगे इसलए उन्हें सधे नर्दष्ट करने क कई आवश्यकत नहं है ध्यन दें क कई वकल्प डफ़ल्ट मन लटते हैं लेकन इसक मतलब यह नहं है यह वकल्प स्पष्ट रूप से टैग मन के रूप में सेट कय गय है यह सत्यपत करने के लए क टैग मजूद है टैग गुण य संबंधत IsTagPresent पद्धत क उपयग करें.
type: docs
weight: 4940
url: /hi/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

टिफ फ़ाइल प्रारूप विकल्प। ध्यान दें कि चौड़ाई और ऊंचाई टैग चौड़ाई और ऊंचाई पैरामीटर द्वारा छवि निर्माण पर अधिलेखित हो जाएंगे, इसलिए उन्हें सीधे निर्दिष्ट करने की कोई आवश्यकता नहीं है। ध्यान दें कि कई विकल्प डिफ़ॉल्ट मान लौटाते हैं लेकिन इसका मतलब यह नहीं है यह विकल्प स्पष्ट रूप से टैग मान के रूप में सेट किया गया है। यह सत्यापित करने के लिए कि टैग मौजूद है, टैग गुण या संबंधित IsTagPresent पद्धति का उपयोग करें.

```csharp
public class TiffOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | का एक नया उदाहरण प्रारंभ करता है`TiffOptions` वर्ग. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | का एक नया उदाहरण प्रारंभ करता है`TiffOptions` कक्षा। डिफ़ॉल्ट रूप से छोटे एंडियन कन्वेंशन का उपयोग किया जाता है। |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | का एक नया उदाहरण प्रारंभ करता है`TiffOptions` वर्ग. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | का एक नया उदाहरण प्रारंभ करता है`TiffOptions` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | अल्फा स्टोरेज विकल्प प्राप्त या सेट करता है। के अलावा अन्य विकल्पUnspecified का उपयोग तब किया जाता है जब 3 से अधिक हों[`SamplesPerPixel`](./samplesperpixel/) परिभाषित. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | कलाकार को प्राप्त या सेट करता है। |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | बिट्स प्रति पिक्सेल प्राप्त करता है। |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | प्रति नमूना बिट्स प्राप्त या सेट करता है। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | टिफ बाइट ऑर्डर को इंगित करने वाला मान प्राप्त या सेट करता है। |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | कलर मैप प्राप्त या सेट करता है। |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | संकुचित छवि गुणवत्ता प्राप्त या सेट करता है। जेपीईजी संपीड़न के साथ प्रयोग किया जाता है। |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | संपीड़न प्राप्त या सेट करता है। |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | कॉपीराइट प्राप्त करता है या सेट करता है। |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | दिनांक और समय प्राप्त या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रेखापुंज में निर्यात करते समय पाठ को आकर्षित करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा परत फ़ॉन्ट सिस्टम में प्रस्तुत नहीं किया गया है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम लेने के लिए अगले कोड स्निपेट का उपयोग किया जा सकता है : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] family = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | दस्तावेज़ का नाम प्राप्त या सेट करता है। |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | पॉइंटर को EXIF IFD. पर ले जाता है या सेट करता है |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | फ़ैक्स t4 विकल्प प्राप्त या सेट करता है. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF फ़ाइल मानक प्राप्त या सेट करता है। |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | बाइट बिट्स भरण क्रम प्राप्त या सेट करता है। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [पूर्ण फ्रेम] . इंगित करने वाला मान प्राप्त करता है या सेट करता है |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | हाफ़टोन संकेत प्राप्त या सेट करता है। |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Icc प्रोफ़ाइल स्ट्रीम प्राप्त या सेट करता है. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | छवि विवरण प्राप्त या सेट करता है। |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | छवि की लंबाई प्राप्त या सेट करता है। |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | छवि चौड़ाई प्राप्त या सेट करता है। |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | स्याही के नाम प्राप्त या सेट करता है। |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि अतिरिक्त नमूने मौजूद हैं या नहीं। |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि छवि टाइल की गई है या नहीं। |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या`TiffOptions` ठीक से कॉन्फ़िगर किया गया है। विफलता का कारण खोजने के लिए वैलिडेट विधि का उपयोग करें। |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | अधिकतम नमूना मान प्राप्त या सेट करता है। |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | न्यूनतम नमूना मान प्राप्त या सेट करता है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | ओरिएंटेशन प्राप्त या सेट करता है। |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | पृष्ठ का नाम प्राप्त या सेट करता है। |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | पेज नंबर टैग प्राप्त या सेट करता है। |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | फोटोमेट्रिक प्राप्त या सेट करता है। |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | प्लानर कॉन्फ़िगरेशन प्राप्त या सेट करता है। |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW संपीड़न के लिए भविष्यवक्ता प्राप्त करता है या सेट करता है। |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि घटकों को पूर्व-गुणा किया जाना चाहिए। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रगति ईवेंट हैंडलर प्राप्त या सेट करता है। |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त या सेट करता है। |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | रिज़ॉल्यूशन यूनिट प्राप्त या सेट करता है। |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | प्रति पट्टी पंक्तियों को प्राप्त या सेट करता है। |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | नमूना प्रारूप प्राप्त या सेट करता है। |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | प्रति पिक्सेल नमूने प्राप्त करता है। इस संपत्ति मूल्य को बदलने के लिए उपयोग करें[`BitsPerSample`](./bitspersample/) संपत्ति सेटर. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | स्कैनर निर्माता को प्राप्त या सेट करता है। |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | स्कैनर मॉडल प्राप्त या सेट करता है। |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | अधिकतम नमूना मान प्राप्त या सेट करता है। मान में एक फ़ील्ड प्रकार होता है जो नमूना डेटा (बाइट, छोटा या लंबा प्रकार) से सबसे अच्छा मेल खाता है. |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | न्यूनतम नमूना मान प्राप्त या सेट करता है। मान में एक फ़ील्ड प्रकार होता है जो नमूना डेटा (बाइट, छोटा या लंबा प्रकार) से सबसे अच्छा मेल खाता है. |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | सॉफ़्टवेयर प्रकार प्राप्त या सेट करता है। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के लिए स्रोत प्राप्त करता है या सेट करता है. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | स्ट्रिप बाइट काउंट प्राप्त या सेट करता है। |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | स्ट्रिप ऑफ़सेट प्राप्त या सेट करता है। |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | इस सबफाइल में निहित डेटा के प्रकार का सामान्य संकेत देता है या सेट करता है। |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | टैग प्राप्त या सेट करता है। |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | लक्ष्य प्रिंटर को प्राप्त या सेट करता है। |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | थ्रेसहोल्डिंग प्राप्त या सेट करता है। |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | टाइल बाइट की गणना करता है या सेट करता है। |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | टाइल की लंबाई निर्धारित करता है। |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | टाइल ऑफ़सेट प्राप्त या सेट करता है. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | टाइल की चौड़ाई निर्धारित करता है। |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | कुल पृष्ठ प्राप्त करता है। |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | मान्य टैग संख्या प्राप्त करता है। यह कुल टैग्स की संख्या नहीं है बल्कि उन टैग्स की संख्या है जिन्हें संरक्षित किया जा सकता है। |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रेखांकन विकल्प प्राप्त या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा कंटेनर प्राप्त या सेट करता है। |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | छवि लेखक को प्राप्त या सेट करता है, जिसका उपयोग विंडोज एक्सप्लोरर द्वारा किया जाता है। |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | छवि पर टिप्पणी प्राप्त या सेट करता है, जिसका उपयोग विंडोज एक्सप्लोरर द्वारा किया जाता है। |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | सब्जेक्ट इमेज प्राप्त या सेट करता है, जिसका उपयोग विंडोज एक्सप्लोरर द्वारा किया जाता है। |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | x स्थिति प्राप्त या सेट करता है। |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | छवि के बारे में जानकारी प्राप्त या सेट करता है, जिसका उपयोग विंडोज एक्सप्लोरर द्वारा किया जाता है। |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | छवि के बारे में जानकारी प्राप्त या सेट करता है, जिसका उपयोग विंडोज एक्सप्लोरर द्वारा किया जाता है। |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | x रिज़ॉल्यूशन प्राप्त या सेट करता है। |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | वाईसीबीसीआर गुणांक प्राप्त या सेट करता है। |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | वाईसीबीसीआर फोटोमेट्रिक के लिए सबसैंपलिंग कारक प्राप्त या सेट करता है। |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | वाई स्थिति प्राप्त या सेट करता है। |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | वाई रिज़ॉल्यूशन प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | एक नया टैग जोड़ता है। |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | टैग जोड़ता है। |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस उदाहरण को क्लोन करता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | प्रकार द्वारा टैग का उदाहरण प्राप्त करता है। |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | निर्धारित करता है कि टैग विकल्पों में मौजूद है या नहीं। |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | टैग निकालता है. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | मान्य करता है कि विकल्पों में टैग्स का मान्य संयोजन है |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | मान्य टैग संख्या प्राप्त करता है। |

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

यह उदाहरण एक छवि सतह पर आंकड़े बनाने और हेरफेर करने के लिए ग्राफ़िक्सपाथ और ग्राफ़िक्स वर्ग का उपयोग करते हैं। उदाहरण एक नई छवि बनाता है और ग्राफिक्सपाथ वर्ग की मदद से पथ बनाता है। अंत में ग्राफिक्स वर्ग द्वारा प्रदर्शित ड्रॉपाथ विधि को सतह पर पथ प्रस्तुत करने के लिए बुलाया जाता है। अंत में छवि को टिफ़ फ़ाइल स्वरूप में निर्यात किया जाता है।

```csharp
[C#]

// छवि का एक उदाहरण बनाएं 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // ग्राफिक्स क्लास का एक उदाहरण बनाएं और आरंभ करें
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // स्पष्ट ग्राफिक्स सतह
    graphics.Clear(Color.Wheat);

    // ग्राफिक्सपाथ क्लास का एक उदाहरण बनाएं
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // चित्र वर्ग का एक उदाहरण बनाएँ
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // चित्र वस्तु में आकृतियाँ जोड़ें
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // ग्राफिक्सपाथ में फिगर ऑब्जेक्ट जोड़ें
    graphicspath.AddFigure(figure);

    // काले रंग के पेन ऑब्जेक्ट के साथ पथ बनाएं
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // TiffOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // सभी परिवर्तनों को सहेजें।
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### यह सभी देखें

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* नाम स्थान [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* सभा [Aspose.PSD](../../)



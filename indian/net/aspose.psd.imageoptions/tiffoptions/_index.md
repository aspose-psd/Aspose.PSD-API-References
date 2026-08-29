---
title: "क्लास TiffOptions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageOptions.TiffOptions क्लास। tiff फ़ाइल फ़ॉर्मेट विकल्प। ध्यान दें कि चौड़ाई और ऊँचाई टैग्स को इमेज निर्माण के समय चौड़ाई और ऊँचाई पैरामीटर द्वारा ओवरराइट किया जाएगा, इसलिए उन्हें सीधे निर्दिष्ट करने की आवश्यकता नहीं है। ध्यान दें कि कई विकल्प डिफ़ॉल्ट मान लौटाते हैं, लेकिन इसका अर्थ यह नहीं है कि यह विकल्प टैग मान के रूप में स्पष्ट रूप से सेट किया गया है। टैग मौजूद है यह सत्यापित करने के लिए Tags property या संबंधित IsTagPresent method का उपयोग करें"
type: docs
weight: 5430
url: /hi/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

tiff फ़ाइल फ़ॉर्मेट विकल्प। ध्यान दें कि चौड़ाई और ऊँचाई टैग छवि निर्माण के दौरान चौड़ाई और ऊँचाई पैरामीटर द्वारा ओवरराइट हो जाएंगे, इसलिए उन्हें सीधे निर्दिष्ट करने की आवश्यकता नहीं है। ध्यान दें कि कई विकल्प डिफ़ॉल्ट मान लौटाते हैं, लेकिन इसका अर्थ यह नहीं है कि यह विकल्प टैग मान के रूप में स्पष्ट रूप से सेट किया गया है। यह जांचने के लिए कि टैग मौजूद है, Tags प्रॉपर्टी या संबंधित IsTagPresent मेथड का उपयोग करें।

```csharp
public class TiffOptions : ImageOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | `TiffOptions` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | `TiffOptions` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट रूप से लिटिल एंडियन कन्वेंशन उपयोग किया जाता है। |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | `TiffOptions` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | `TiffOptions` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | अल्फा स्टोरेज विकल्प प्राप्त करता है या सेट करता है। Unspecified के अलावा विकल्प तब उपयोग किए जाते हैं जब 3 से अधिक [`SamplesPerPixel`](./samplesperpixel/) परिभाषित हों। |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | कलाकार प्राप्त करता है या सेट करता है। |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | पिक्सेल प्रति बिट्स प्राप्त करता है। |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | सैंपल प्रति बिट्स प्राप्त करता है या सेट करता है। |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | tiff बाइट ऑर्डर को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | रंग मानचित्र को प्राप्त या सेट करता है। |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | संपीड़ित छवि गुणवत्ता को प्राप्त या सेट करता है। Jpeg संपीड़न के साथ उपयोग किया जाता है। |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | कम्प्रेशन को प्राप्त करता है या सेट करता है। |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | कॉपीराइट को प्राप्त या सेट करता है। |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | तारीख और समय को प्राप्त या सेट करता है। |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | डिफ़ॉल्ट मेमोरी आवंटन सीमा को प्राप्त करता है या सेट करता है। |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जो रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए उपयोग किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का उचित नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: `System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });` |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | दस्तावेज़ का नाम प्राप्त या सेट करता है। |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है। |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | फ़ैक्स t4 विकल्पों को प्राप्त या सेट करता है। |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF फ़ाइल मानक को प्राप्त या सेट करता है। |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | बाइट बिट्स भरने का क्रम प्राप्त या सेट करता है। |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [full frame] है। |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | हाफ़टोन संकेतों को प्राप्त या सेट करता है। |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Icc प्रोफ़ाइल स्ट्रीम को प्राप्त या सेट करता है। |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | छवि विवरण को प्राप्त या सेट करता है। |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | छवि लंबाई को प्राप्त या सेट करता है। |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | छवि चौड़ाई को प्राप्त या सेट करता है। |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | स्याही नामों को प्राप्त या सेट करता है। |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि अतिरिक्त नमूने मौजूद हैं या नहीं। |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि छवि टाइल्ड है या नहीं। |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि `TiffOptions` सही ढंग से कॉन्फ़िगर किए गए हैं या नहीं। विफलता कारण खोजने के लिए Validate मेथड का उपयोग करें। |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | अधिकतम नमूना मान को प्राप्त या सेट करता है। |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | न्यूनतम नमूना मान को प्राप्त या सेट करता है। |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | मल्टीपेज विकल्प |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | ओरिएंटेशन को प्राप्त या सेट करता है। |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | पृष्ठ नाम को प्राप्त या सेट करता है। |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | पृष्ठ संख्या टैग को प्राप्त या सेट करता है। |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | रंग पैलेट प्राप्त करता है या सेट करता है। |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | फोटोमेट्रिक को प्राप्त या सेट करता है। |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | प्लैनेर कॉन्फ़िगरेशन को प्राप्त या सेट करता है। |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW संपीड़न के लिए प्रेडिक्टर को प्राप्त या सेट करता है। |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | किसी मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए या नहीं। |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | रिज़ॉल्यूशन सेटिंग्स प्राप्त करता है या सेट करता है। |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | रिज़ॉल्यूशन इकाई प्राप्त करता है या सेट करता है। |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | प्रति स्ट्रिप पंक्तियों को प्राप्त करता है या सेट करता है। |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | सैंपल फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | प्रति पिक्सेल सैंपल प्राप्त करता है। इस प्रॉपर्टी मान को बदलने के लिए [`BitsPerSample`](./bitspersample/) प्रॉपर्टी सेट्टर का उपयोग करें। |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | स्कैनर निर्माता को प्राप्त करता है या सेट करता है। |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | स्कैनर मॉडल को प्राप्त करता है या सेट करता है। |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | अधिकतम सैंपल मान को प्राप्त करता है या सेट करता है। इस मान का फ़ील्ड प्रकार सैंपल डेटा (बाइट, शॉर्ट या लॉन्ग प्रकार) के साथ सबसे उपयुक्त मेल खाता है। |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | न्यूनतम सैंपल मान को प्राप्त करता है या सेट करता है। इस मान का फ़ील्ड प्रकार सैंपल डेटा (बाइट, शॉर्ट या लॉन्ग प्रकार) के साथ सबसे उपयुक्त मेल खाता है। |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | सॉफ़्टवेयर प्रकार को प्राप्त करता है या सेट करता है। |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | छवि बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | स्ट्रिप बाइट काउंट को प्राप्त करता है या सेट करता है। |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | स्ट्रिप ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | इस सबफ़ाइल में मौजूद डेटा के प्रकार का सामान्य संकेत प्राप्त करता है या सेट करता है। |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | टैग्स को प्राप्त करता है या सेट करता है। |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | लक्ष्य प्रिंटर को प्राप्त करता है या सेट करता है। |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | थ्रेशहोल्डिंग को प्राप्त करता है या सेट करता है। |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | टाइल बाइट काउंट को प्राप्त करता है या सेट करता है। |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | टाइल लंबाई को प्राप्त करता है या सेट करता है। |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | टाइल ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | टाइल चौड़ाई को प्राप्त करता है या सेट करता है। |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | कुल पृष्ठों को प्राप्त करता है। |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | वैध टैग गिनती को प्राप्त करता है। यह कुल टैग गिनती नहीं है बल्कि उन टैगों की संख्या है जिन्हें संरक्षित किया जा सकता है। |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | वेक्टर रास्टराइज़ेशन विकल्प प्राप्त करता है या सेट करता है। |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | इमेज लेखक को प्राप्त करता है या सेट करता है, जिसे विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | इमेज पर टिप्पणी को प्राप्त करता है या सेट करता है, जिसे विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | विषय इमेज को प्राप्त करता है या सेट करता है, जिसे विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | x स्थिति को प्राप्त करता है या सेट करता है। |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | इमेज के बारे में जानकारी प्राप्त करता है या सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | इमेज के बारे में जानकारी प्राप्त करता है या सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | x रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | YCbCrCoefficients प्राप्त करता है या सेट करता है। |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग फैक्टर्स प्राप्त करता है या सेट करता है। |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | y स्थिति प्राप्त करता है या सेट करता है। |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | y रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | एक नया टैग जोड़ता है। |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | टैग्स जोड़ता है। |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | इस इंस्टेंस की क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | टैग का इंस्टेंस प्रकार द्वारा प्राप्त करता है। |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | निर्धारित करता है कि टैग विकल्पों में मौजूद है या नहीं। |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | टैग को हटाता है। |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | जाँचता है कि विकल्पों में टैग्स का वैध संयोजन है या नहीं। |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | वैध टैग्स की गिनती प्राप्त करता है। |

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

यह उदाहरण GraphicsPath और Graphics क्लास का उपयोग करके Image सतह पर फ़िगर्स बनाता और संशोधित करता है। उदाहरण एक नया Image बनाता है और GraphicsPath क्लास की मदद से पाथ्स ड्रॉ करता है। अंत में Graphics क्लास द्वारा प्रदान किया गया DrawPath मेथड कॉल किया जाता है ताकि पाथ्स को सतह पर रेंडर किया जा सके। अंत में इमेज को Tiff फ़ाइल फ़ॉर्मेट में निर्यात किया जाता है।

```csharp
[C#]

//Image का एक इंस्टेंस बनाएं।
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics क्लास का एक इंस्टेंस बनाएं और प्रारंभ करें।
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics सतह को साफ़ करें।
    graphics.Clear(Color.Wheat);

    //GraphicsPath क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure क्लास का एक इंस्टेंस बनाएं।
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure ऑब्जेक्ट में शेप्स जोड़ें।
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //GraphicsPath में Figure ऑब्जेक्ट जोड़ें।
    graphicspath.AddFigure(figure);

    //काली रंग की Pen ऑब्जेक्ट से पाथ ड्रॉ करें।
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions का एक इंस्टेंस बनाएं और उसकी विभिन्न प्रॉपर्टीज़ सेट करें।
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // सभी परिवर्तन सहेजें।
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### देखें भी

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



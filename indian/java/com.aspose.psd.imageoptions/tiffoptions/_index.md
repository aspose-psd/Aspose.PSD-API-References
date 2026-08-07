---
title: "TiffOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "TIFF फ़ाइल फ़ॉर्मेट विकल्प।"
type: docs
weight: 25
url: /hi/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

tiff फ़ाइल फ़ॉर्मेट विकल्प। ध्यान दें कि चौड़ाई और ऊँचाई टैग्स को छवि निर्माण के दौरान चौड़ाई और ऊँचाई पैरामीटर द्वारा ओवरराइट किया जाएगा, इसलिए उन्हें सीधे निर्दिष्ट करने की आवश्यकता नहीं है। ध्यान दें कि कई विकल्प डिफ़ॉल्ट मान लौटाते हैं, लेकिन इसका अर्थ यह नहीं है कि यह विकल्प टैग मान के रूप में स्पष्ट रूप से सेट किया गया है। टैग मौजूद है यह सत्यापित करने के लिए Tags प्रॉपर्टी या संबंधित IsTagPresent मेथड का उपयोग करें।

WARNING! सहेजते समय tiff विकल्पों को कभी न बदलें क्योंकि इससे साइड इफ़ेक्ट्स और खोजने में कठिन बग्स हो सकते हैं। निम्न पंक्ति को विशेष रूप से टिप्पणी किया गया था क्योंकि इससे डेटा की शुरुआत का गलत निर्धारण हुआ। पास किए गए विकल्पों में spp नहीं था (हालांकि ऐसे मामले में विकल्प सही नहीं हैं लेकिन फिर भी यह स्थिति त्रुटियों का कारण बनती है) और अगली पंक्ति ने +spp टैग +bpp टैग जोड़े, और जब विकल्प डेटा पूरी तरह लिखे जाने के बाद लिखे गए तो उन्होंने अनकम्प्रेस्ड कोडेक के लिए डेटा की शुरुआत को ओवरराइट कर दिया!!! देखें TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | एक नया टैग जोड़ता है। |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | टैग्स जोड़ता है। |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | अल्फा स्टोरेज विकल्प प्राप्त करता है या सेट करता है। |
| [getArtist()](#getArtist--) | कलाकार को प्राप्त करता है या सेट करता है। |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। |
| [getBitsPerPixel()](#getBitsPerPixel--) | प्रति पिक्सेल बिट्स प्राप्त करता है। |
| [getBitsPerSample()](#getBitsPerSample--) | प्रति सैंपल बिट्स प्राप्त करता है। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [getByteOrder()](#getByteOrder--) | tiff बाइट ऑर्डर दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | कैश प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | रंग मानचित्र को प्राप्त करता है या सेट करता है। |
| [getCompressedQuality()](#getCompressedQuality--) | संपीड़ित छवि की गुणवत्ता प्राप्त करता है। |
| [getCompression()](#getCompression--) | संपीड़न प्राप्त करता है। |
| [getCopyright()](#getCopyright--) | कॉपीराइट प्राप्त करता है। |
| [getDateTime()](#getDateTime--) | तारीख और समय को प्राप्त करता है या सेट करता है। |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | डिफ़ॉल्ट मेमोरी आवंटन सीमा को प्राप्त करता है या सेट करता है। |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getDocumentName()](#getDocumentName--) | दस्तावेज़ का नाम प्राप्त करता है या सेट करता है। |
| [getExifIfd()](#getExifIfd--) | EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है। |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | अतिरिक्त नमूना गिनती प्राप्त करता है। |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | अतिरिक्त नमूनों के मान प्राप्त करता है। |
| [getFaxT4Options()](#getFaxT4Options--) | फ़ैक्स T4 विकल्पों को प्राप्त करता है या सेट करता है। |
| [getFileStandard()](#getFileStandard--) | TIFF फ़ाइल मानक को प्राप्त करता है या सेट करता है। |
| [getFillOrder()](#getFillOrder--) | बाइट बिट्स भरने का क्रम प्राप्त करता है या सेट करता है। |
| [getFullFrame()](#getFullFrame--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]। |
| [getHalfToneHints()](#getHalfToneHints--) | हाफटोन संकेत प्राप्त करता है या सेट करता है। |
| [getIccProfile()](#getIccProfile--) | ICC प्रोफ़ाइल स्ट्रीम प्राप्त करता है। |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [getImageDescription()](#getImageDescription--) | छवि विवरण को प्राप्त करता है या सेट करता है। |
| [getImageLength()](#getImageLength--) | छवि लंबाई को प्राप्त करता है या सेट करता है। |
| [getImageWidth()](#getImageWidth--) | छवि चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getInkNames()](#getInkNames--) | इंक नामों को प्राप्त करता है या सेट करता है। |
| [getMaxSampleValue()](#getMaxSampleValue--) | अधिकतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [getMinSampleValue()](#getMinSampleValue--) | न्यूनतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [getMultiPageOptions()](#getMultiPageOptions--) | मल्टीपेज विकल्प |
| [getOrientation()](#getOrientation--) | ओरिएंटेशन को प्राप्त करता है या सेट करता है। |
| [getPageName()](#getPageName--) | पृष्ठ नाम को प्राप्त करता है या सेट करता है। |
| [getPageNumber()](#getPageNumber--) | पृष्ठ संख्या टैग को प्राप्त करता है या सेट करता है। |
| [getPalette()](#getPalette--) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getPhotometric()](#getPhotometric--) | फोटोमेट्रिक को प्राप्त करता है या सेट करता है। |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | प्लेनर कॉन्फ़िगरेशन को प्राप्त करता है या सेट करता है। |
| [getPredictor()](#getPredictor--) | LZW संपीड़न के लिए प्रेडिक्टर को प्राप्त करता है या सेट करता है। |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [getResolutionSettings()](#getResolutionSettings--) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getResolutionUnit()](#getResolutionUnit--) | रिज़ॉल्यूशन यूनिट को प्राप्त करता है या सेट करता है। |
| [getRowsPerStrip()](#getRowsPerStrip--) | प्रति स्ट्रिप पंक्तियों को प्राप्त करता है या सेट करता है। |
| [getSampleFormat()](#getSampleFormat--) | नमूना प्रारूप को प्राप्त करता है या सेट करता है। |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | पिक्सेल प्रति नमूने प्राप्त करता है। |
| [getScannerManufacturer()](#getScannerManufacturer--) | स्कैनर निर्माता प्राप्त करता है या सेट करता है। |
| [getScannerModel()](#getScannerModel--) | स्कैनर मॉडल प्राप्त करता है या सेट करता है। |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | अधिकतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [getSminSampleValue()](#getSminSampleValue--) | न्यूनतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [getSoftwareType()](#getSoftwareType--) | सॉफ़्टवेयर प्रकार प्राप्त करता है या सेट करता है। |
| [getSource()](#getSource--) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [getStripByteCounts()](#getStripByteCounts--) | स्ट्रिप बाइट गणना प्राप्त करता है या सेट करता है। |
| [getStripOffsets()](#getStripOffsets--) | स्ट्रिप ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [getSubFileType()](#getSubFileType--) | इस सबफ़ाइल में मौजूद डेटा के प्रकार का सामान्य संकेत प्राप्त करता है या सेट करता है। |
| [getTagByType(int tagKey)](#getTagByType-int-) | प्रकार द्वारा टैग का उदाहरण प्राप्त करता है। |
| [getTags()](#getTags--) | टैग प्राप्त करता है या सेट करता है। |
| [getTargetPrinter()](#getTargetPrinter--) | लक्ष्य प्रिंटर प्राप्त करता है या सेट करता है। |
| [getThreshholding()](#getThreshholding--) | थ्रेशहोल्डिंग प्राप्त करता है या सेट करता है। |
| [getTileByteCounts()](#getTileByteCounts--) | टाइल बाइट गणना प्राप्त करता है या सेट करता है। |
| [getTileLength()](#getTileLength--) | टाइल लंबाई प्राप्त करता है या सेट करता है। |
| [getTileOffsets()](#getTileOffsets--) | टाइल ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [getTileWidth()](#getTileWidth--) | टाइल चौड़ाई प्राप्त करता है या सेट करता है। |
| [getTotalPages()](#getTotalPages--) | कुल पृष्ठ प्राप्त करता है। |
| [getValidTagCount()](#getValidTagCount--) | वैध टैग गणना प्राप्त करता है। |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | मान्य टैग्स की गिनती प्राप्त करता है। |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [getXPAuthor()](#getXPAuthor--) | छवि लेखक प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [getXPComment()](#getXPComment--) | छवि पर टिप्पणी प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [getXPKeywords()](#getXPKeywords--) | विषय छवि प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [getXPSubject()](#getXPSubject--) | छवि के बारे में जानकारी प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [getXPTitle()](#getXPTitle--) | छवि के बारे में जानकारी प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है। |
| [getXmpData()](#getXmpData--) | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [getXposition()](#getXposition--) | x स्थिति प्राप्त करता है या सेट करता है। |
| [getXresolution()](#getXresolution--) | X रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | YCbCrCoefficients प्राप्त करता है या सेट करता है। |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग कारक प्राप्त करता है या सेट करता है। |
| [getYposition()](#getYposition--) | y स्थिति प्राप्त करता है या सेट करता है। |
| [getYresolution()](#getYresolution--) | y रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | एक मान प्राप्त करता है जो यह दर्शाता है कि अतिरिक्त नमूने मौजूद हैं या नहीं। |
| [isTagPresent(int tag)](#isTagPresent-int-) | निर्धारित करता है कि टैग विकल्पों में मौजूद है या नहीं। |
| [isTiled()](#isTiled--) | एक मान प्राप्त करता है जो यह दर्शाता है कि छवि टाइल्ड है या नहीं। |
| [isValid()](#isValid--) | एक मान प्राप्त करता है जो यह दर्शाता है कि TiffOptions सही ढंग से कॉन्फ़िगर किए गए हैं या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | टैग को हटाता है। |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | अल्फा स्टोरेज विकल्प प्राप्त करता है या सेट करता है। |
| [setArtist(String value)](#setArtist-java.lang.String-) | कलाकार को प्राप्त करता है या सेट करता है। |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | प्रति नमूना बिट्स सेट करता है। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setByteOrder(int value)](#setByteOrder-int-) | tiff बाइट ऑर्डर दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setColorMap(int[] value)](#setColorMap-int---) | रंग मानचित्र को प्राप्त करता है या सेट करता है। |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | संपीड़ित छवि गुणवत्ता सेट करता है। |
| [setCompression(int value)](#setCompression-int-) | संपीड़न सेट करता है। |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | कॉपीराइट सेट करता है। |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | तारीख और समय को प्राप्त करता है या सेट करता है। |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | डिफ़ॉल्ट मेमोरी आवंटन सीमा को प्राप्त करता है या सेट करता है। |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | दस्तावेज़ का नाम प्राप्त करता है या सेट करता है। |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | अतिरिक्त नमूनों के मान सेट करता है। |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | फ़ैक्स T4 विकल्पों को प्राप्त करता है या सेट करता है। |
| [setFileStandard(int value)](#setFileStandard-int-) | TIFF फ़ाइल मानक को प्राप्त करता है या सेट करता है। |
| [setFillOrder(int value)](#setFillOrder-int-) | बाइट बिट्स भरने का क्रम प्राप्त करता है या सेट करता है। |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | एक मान सेट करता है जो यह दर्शाता है कि [full frame]। |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | हाफटोन संकेत प्राप्त करता है या सेट करता है। |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | ICC प्रोफ़ाइल स्ट्रीम सेट करता है। |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | छवि विवरण को प्राप्त करता है या सेट करता है। |
| [setImageLength(long value)](#setImageLength-long-) | छवि लंबाई को प्राप्त करता है या सेट करता है। |
| [setImageWidth(long value)](#setImageWidth-long-) | छवि चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | इंक नामों को प्राप्त करता है या सेट करता है। |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | अधिकतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | न्यूनतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | मल्टीपेज विकल्प |
| [setOrientation(int value)](#setOrientation-int-) | ओरिएंटेशन को प्राप्त करता है या सेट करता है। |
| [setPageName(String value)](#setPageName-java.lang.String-) | पृष्ठ नाम को प्राप्त करता है या सेट करता है। |
| [setPageNumber(int[] value)](#setPageNumber-int---) | पृष्ठ संख्या टैग को प्राप्त करता है या सेट करता है। |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setPhotometric(int value)](#setPhotometric-int-) | फोटोमेट्रिक को प्राप्त करता है या सेट करता है। |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | प्लेनर कॉन्फ़िगरेशन को प्राप्त करता है या सेट करता है। |
| [setPredictor(int value)](#setPredictor-int-) | LZW संपीड़न के लिए प्रेडिक्टर को प्राप्त करता है या सेट करता है। |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | रिज़ॉल्यूशन यूनिट को प्राप्त करता है या सेट करता है। |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | प्रति स्ट्रिप पंक्तियों को प्राप्त करता है या सेट करता है। |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | नमूना प्रारूप को प्राप्त करता है या सेट करता है। |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | स्कैनर निर्माता प्राप्त करता है या सेट करता है। |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | स्कैनर मॉडल प्राप्त करता है या सेट करता है। |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | अधिकतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | न्यूनतम नमूना मान को प्राप्त करता है या सेट करता है। |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | सॉफ़्टवेयर प्रकार प्राप्त करता है या सेट करता है। |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | स्ट्रिप बाइट गणना प्राप्त करता है या सेट करता है। |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | स्ट्रिप ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [setSubFileType(long value)](#setSubFileType-long-) | इस सबफ़ाइल में मौजूद डेटा के प्रकार का सामान्य संकेत प्राप्त करता है या सेट करता है। |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | टैग प्राप्त करता है या सेट करता है। |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | लक्ष्य प्रिंटर प्राप्त करता है या सेट करता है। |
| [setThreshholding(int value)](#setThreshholding-int-) | थ्रेशहोल्डिंग प्राप्त करता है या सेट करता है। |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | टाइल बाइट गणना प्राप्त करता है या सेट करता है। |
| [setTileLength(long value)](#setTileLength-long-) | टाइल लंबाई प्राप्त करता है या सेट करता है। |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | टाइल ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [setTileWidth(long value)](#setTileWidth-long-) | टाइल चौड़ाई प्राप्त करता है या सेट करता है। |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | छवि लेखक सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | छवि पर टिप्पणी सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | विषय छवि सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | छवि के बारे में जानकारी सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | छवि के बारे में जानकारी सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है। |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | x स्थिति प्राप्त करता है या सेट करता है। |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | X रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | YCbCrCoefficients प्राप्त करता है या सेट करता है। |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग कारक प्राप्त करता है या सेट करता है। |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | y स्थिति प्राप्त करता है या सेट करता है। |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | y रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [validate()](#validate--) | वैलिडेट करता है कि विकल्पों में टैग्स का वैध संयोजन है या नहीं। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expectedFormat | int | अपेक्षित tiff फ़ाइल फ़ॉर्मेट। |
| byteOrder | int | उपयोग करने के लिए TIFF फ़ाइल फ़ॉर्मेट बाइट ऑर्डर। |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। डिफ़ॉल्ट रूप से लिटिल एंडियन कन्वेंशन उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| expectedFormat | int | अपेक्षित tiff फ़ाइल फ़ॉर्मेट। |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | कॉपी करने के लिए विकल्प। |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


TiffOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | विकल्पों को इनिशियलाइज़ करने के लिए टैग्स। |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


एक नया टैग जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | जोड़ने के लिए टैग। |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


टैग्स जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | जोड़ने के लिए टैग्स। |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


इस उदाहरण को क्लोन करता है।

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


इस उदाहरण को क्लोन करता है।

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


अल्फा स्टोरेज विकल्प प्राप्त करता है या सेट करता है। TiffAlphaStorage.Unspecified के अलावा विकल्प तब उपयोग किए जाते हैं जब 3 से अधिक SamplesPerPixel परिभाषित हों।

**Returns:**
int - अल्फा संग्रह विकल्प।
### getArtist() {#getArtist--}
```
public String getArtist()
```


कलाकार को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - कलाकार।
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। आंतरिक प्रयोजनों के लिए छवि की पृष्ठभूमि रंग संग्रहीत करने हेतु उपयोग किया जाता है।

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


प्रति पिक्सेल बिट्स प्राप्त करता है।

**Returns:**
int - प्रति पिक्सेल बिट।
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


प्रति सैंपल बिट्स प्राप्त करता है।

**Returns:**
int[] - प्रति नमूना बिट्स मान।

जब इस मान को सेट किया जाए तो ध्यान रखें कि यह SamplesPerPixel मान को भी एरे की लंबाई पर सेट करेगा। ये दो गुण बहुत घनिष्ठ रूप से जुड़े हुए हैं इसलिए केवल साथ में ही सेट किए जा सकते हैं।
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


tiff बाइट ऑर्डर दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


कैश प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| टैग | int | टैग (जो एक एरे प्रकार है)। |

**Returns:**
long[] - टैग मान।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


रंग मानचित्र को प्राप्त करता है या सेट करता है।

**Returns:**
int[] - रंग मानचित्र।
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


संपीड़ित छवि गुणवत्ता प्राप्त करता है। Jpeg संपीड़न के साथ उपयोग किया जाता है।

**Returns:**
int - संपीड़ित छवि गुणवत्ता।
### getCompression() {#getCompression--}
```
public int getCompression()
```


संपीड़न प्राप्त करता है।

**Returns:**
int - संपीड़न।
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


कॉपीराइट प्राप्त करता है।

**Returns:**
java.lang.String - कॉपीराइट।
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


तारीख और समय को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - तिथि और समय।
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


डिफ़ॉल्ट मेमोरी आवंटन सीमा को प्राप्त करता है या सेट करता है।

**Returns:**
int - डिफ़ॉल्ट मेमोरी आवंटन सीमा।
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग टेक्स्ट को रास्टर में निर्यात करते समय किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

मान: डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट।

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


दस्तावेज़ का नाम प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - दस्तावेज़ का नाम।
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है।

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


अतिरिक्त नमूना गिनती प्राप्त करता है।

मान: अतिरिक्त नमूना गणना।

**Returns:**
long - अतिरिक्त नमूना गणना।
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


अतिरिक्त नमूनों के मान प्राप्त करता है।

मान: अतिरिक्त नमूनों का मान।

**Returns:**
int[] - अतिरिक्त नमूनों के मान।
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


फ़ैक्स T4 विकल्पों को प्राप्त करता है या सेट करता है।

**Returns:**
long - फ़ैक्स t4 विकल्प।
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


TIFF फ़ाइल मानक को प्राप्त करता है या सेट करता है।

**Returns:**
int - TIFF फ़ाइल मानक।
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


बाइट बिट्स भरने का क्रम प्राप्त करता है या सेट करता है।

**Returns:**
int - बाइट बिट्स भरने का क्रम।
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]।

मान:  true  यदि [full frame]; अन्यथा,  false .

**Returns:**
बूलियन - एक मान जो यह दर्शाता है कि [full frame]।
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


हाफटोन संकेत प्राप्त करता है या सेट करता है।

**Returns:**
int[] - हाफटोन संकेत।
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


ICC प्रोफ़ाइल स्ट्रीम प्राप्त करता है।

**Returns:**
byte[] - icc प्रोफ़ाइल।
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं।

मान:  true  यदि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए; अन्यथा,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


छवि विवरण को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - छवि विवरण।
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


छवि लंबाई को प्राप्त करता है या सेट करता है।

**Returns:**
long - छवि की लंबाई।
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


छवि चौड़ाई को प्राप्त करता है या सेट करता है।

**Returns:**
long - छवि की चौड़ाई।
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


इंक नामों को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - इंक के नाम।
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


अधिकतम नमूना मान को प्राप्त करता है या सेट करता है।

**Returns:**
int[] - अधिकतम सैंपल मान।
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


न्यूनतम नमूना मान को प्राप्त करता है या सेट करता है।

**Returns:**
int[] - न्यूनतम सैंपल मान।
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


मल्टीपेज विकल्प

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


ओरिएंटेशन को प्राप्त करता है या सेट करता है।

**Returns:**
int - अभिविन्यास।
### getPageName() {#getPageName--}
```
public String getPageName()
```


पृष्ठ नाम को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - पृष्ठ का नाम।
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


पृष्ठ संख्या टैग को प्राप्त करता है या सेट करता है।

**Returns:**
int[] - पृष्ठ संख्या टैग।
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


रंग पैलेट को प्राप्त करता है या सेट करता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


फोटोमेट्रिक को प्राप्त करता है या सेट करता है।

**Returns:**
int - फोटोमेट्रिक।
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


प्लेनर कॉन्फ़िगरेशन को प्राप्त करता है या सेट करता है।

**Returns:**
int - प्लेनर कॉन्फ़िगरेशन।
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


LZW संपीड़न के लिए प्रेडिक्टर को प्राप्त करता है या सेट करता है।

**Returns:**
int - प्रेडिक्टर प्रकार।
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं।

**Returns:**
boolean -  true  यदि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए; अन्यथा,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है।

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


रिज़ॉल्यूशन यूनिट को प्राप्त करता है या सेट करता है।

**Returns:**
int - रिज़ॉल्यूशन इकाई।
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


प्रति स्ट्रिप पंक्तियों को प्राप्त करता है या सेट करता है।

**Returns:**
long - स्ट्रिप प्रति पंक्तियाँ।
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


नमूना प्रारूप को प्राप्त करता है या सेट करता है।

**Returns:**
int[] - सैंपल फ़ॉर्मेट।
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


प्रति पिक्सेल सैंपल प्राप्त करता है। इस प्रॉपर्टी मान को बदलने के लिए  BitsPerSample  प्रॉपर्टी सेट्टर का उपयोग करें।

**Returns:**
int - प्रति पिक्सेल सैंपल।
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


स्कैनर निर्माता प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - स्कैनर निर्माता।
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


स्कैनर मॉडल प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - स्कैनर मॉडल।
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


अधिकतम सैंपल मान प्राप्त करता है या सेट करता है। मान में एक फ़ील्ड प्रकार होता है जो सैंपल डेटा (Byte, Short या Long प्रकार) के साथ सबसे अच्छा मेल खाता है।

**Returns:**
long[] - अधिकतम सैंपल मान।
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


न्यूनतम सैंपल मान प्राप्त करता है या सेट करता है। मान में एक फ़ील्ड प्रकार होता है जो सैंपल डेटा (Byte, Short या Long प्रकार) के साथ सबसे अच्छा मेल खाता है।

**Returns:**
long[] - न्यूनतम सैंपल मान।
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


सॉफ़्टवेयर प्रकार प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - सॉफ़्टवेयर प्रकार।
### getSource() {#getSource--}
```
public final Source getSource()
```


इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है।

मान: इमेज बनाने का स्रोत।

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


स्ट्रिप बाइट गणना प्राप्त करता है या सेट करता है।

**Returns:**
long[] - स्ट्रिप बाइट काउंट।
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


स्ट्रिप ऑफ़सेट प्राप्त करता है या सेट करता है।

**Returns:**
long[] - स्ट्रिप ऑफ़सेट्स।
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


इस सबफ़ाइल में मौजूद डेटा के प्रकार का सामान्य संकेत प्राप्त करता है या सेट करता है।

**Returns:**
long - इस सबफ़ाइल में सम्मिलित डेटा के प्रकार का सामान्य संकेत।
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


प्रकार द्वारा टैग का उदाहरण प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tagKey | int | टैग कुंजी। |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


टैग प्राप्त करता है या सेट करता है।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - टैग्स।
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


लक्ष्य प्रिंटर प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - लक्ष्य प्रिंटर।
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


थ्रेशहोल्डिंग प्राप्त करता है या सेट करता है।

**Returns:**
int - थ्रेशहोल्डिंग।
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


टाइल बाइट गणना प्राप्त करता है या सेट करता है।

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


टाइल लंबाई प्राप्त करता है या सेट करता है।

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


टाइल ऑफ़सेट प्राप्त करता है या सेट करता है।

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


टाइल चौड़ाई प्राप्त करता है या सेट करता है।

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


कुल पृष्ठ प्राप्त करता है।

**Returns:**
int - कुल पृष्ठ।
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


वैध टैग गिनती प्राप्त करता है। यह कुल टैग गिनती नहीं है बल्कि उन टैगों की संख्या है जिन्हें संरक्षित किया जा सकता है।

**Returns:**
int - वैध टैग गिनती।
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


मान्य टैग्स की गिनती प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | वैलिडेट करने के लिए टैग्स। |

**Returns:**
int - मान्य टैग्स की गिनती।
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


छवि लेखक प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है।

मान: Image Author, Windows Explorer द्वारा उपयोग किया जाता है। XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) को Windows Explorer द्वारा अनदेखा किया जाता है यदि Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) टैग मौजूद है।

**Returns:**
java.lang.String - इमेज ऑथर, जो Windows Explorer द्वारा उपयोग किया जाता है।
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


छवि पर टिप्पणी प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है।

मान: इमेज पर टिप्पणी, Windows Explorer द्वारा उपयोग किया जाता है।

**Returns:**
java.lang.String - इमेज पर टिप्पणी, जो Windows Explorer द्वारा उपयोग किया जाता है।
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


विषय छवि प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है।

मान: इमेज विषय, Windows Explorer द्वारा उपयोग किया जाता है।

**Returns:**
java.lang.String - इमेज विषय, जो Windows Explorer द्वारा उपयोग किया जाता है।
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


छवि के बारे में जानकारी प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है।

मान: इमेज के बारे में जानकारी, Windows Explorer द्वारा उपयोग किया जाता है।

**Returns:**
java.lang.String - इमेज के बारे में जानकारी, जो Windows Explorer द्वारा उपयोग किया जाता है।
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


छवि के बारे में जानकारी प्राप्त करता है, जो विंडोज़ एक्सप्लोरर द्वारा उपयोग किया जाता है।

मान: इमेज के बारे में जानकारी, Windows Explorer द्वारा उपयोग किया जाता है। XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) को Windows Explorer द्वारा अनदेखा किया जाता है यदि ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) टैग मौजूद है।

**Returns:**
java.lang.String - इमेज के बारे में जानकारी, जो Windows Explorer द्वारा उपयोग किया जाता है।
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है।

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


x स्थिति प्राप्त करता है या सेट करता है।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


X रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


YCbCrCoefficients प्राप्त करता है या सेट करता है।

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - YCbCr गुणांक।
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग कारक प्राप्त करता है या सेट करता है।

**Returns:**
int[] - YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग फैक्टर्स।
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


y स्थिति प्राप्त करता है या सेट करता है।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


y रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है।

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि अतिरिक्त नमूने मौजूद हैं या नहीं।

**Returns:**
boolean - यदि अतिरिक्त सैंपल मौजूद है तो true; अन्यथा false।
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


निर्धारित करता है कि टैग विकल्पों में मौजूद है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| टैग | int | जाँचने के लिए टैग आईडी। |

**Returns:**
boolean - यदि टैग मौजूद है तो true; अन्यथा false।
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि छवि टाइल्ड है या नहीं।

**Returns:**
boolean - यदि इमेज टाइल्ड है तो true; अन्यथा false।
### isValid() {#isValid--}
```
public boolean isValid()
```


एक मान प्राप्त करता है जो दर्शाता है कि TiffOptions सही तरीके से कॉन्फ़िगर किए गए हैं या नहीं। विफलता कारण खोजने के लिए Validate मेथड का उपयोग करें।

**Returns:**
boolean - यदि TiffOptions सही तरीके से कॉन्फ़िगर किए गए हैं तो true; अन्यथा false।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


टैग को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| टैग | int | हटाने के लिए टैग। |

**Returns:**
boolean - यदि सफलतापूर्वक हटाया गया हो तो true
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


अल्फा स्टोरेज विकल्प प्राप्त करता है या सेट करता है। TiffAlphaStorage.Unspecified के अलावा विकल्प तब उपयोग किए जाते हैं जब 3 से अधिक SamplesPerPixel परिभाषित हों।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | अल्फा स्टोरेज विकल्प। |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


कलाकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | कलाकार। |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। आंतरिक प्रयोजनों के लिए छवि की पृष्ठभूमि रंग संग्रहीत करने हेतु उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | पृष्ठभूमि का रंग। |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


प्रति नमूना बिट्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int[] | प्रति सैंपल बिट्स मान। |

इस मान को सेट करते समय ध्यान रखें कि यह SamplesPerPixel मान को भी एरे की लंबाई पर सेट करेगा। ये दो प्रॉपर्टी बहुत घनिष्ठ रूप से जुड़ी हुई हैं, इसलिए इन्हें केवल साथ में ही सेट किया जा सकता है। |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


tiff बाइट ऑर्डर दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


रंग मानचित्र को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | रंग मानचित्र। |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


संपीड़ित छवि गुणवत्ता सेट करता है। Jpeg संपीड़न के साथ उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | संपीड़ित छवि गुणवत्ता। |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


संपीड़न सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | संपीड़न। |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


कॉपीराइट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | कॉपीराइट। |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


तारीख और समय को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | तारीख और समय। |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


डिफ़ॉल्ट मेमोरी आवंटन सीमा को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | डिफ़ॉल्ट मेमोरी आवंटन सीमा। |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट को प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग टेक्स्ट को रास्टर में निर्यात करते समय किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। डिफ़ॉल्ट फ़ॉन्ट का सही नाम प्राप्त करने के लिए निम्न कोड स्निपेट का उपयोग किया जा सकता है: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

मान: डिफ़ॉल्ट रिप्लेसमेंट फ़ॉन्ट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


दस्तावेज़ का नाम प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | दस्तावेज़ का नाम। |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


अतिरिक्त नमूनों के मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | अतिरिक्त सैंपल मान। |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


फ़ैक्स T4 विकल्पों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | फ़ैक्स t4 विकल्प। |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


TIFF फ़ाइल मानक को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | TIFF फ़ाइल मानक। |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


बाइट बिट्स भरने का क्रम प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | बाइट बिट्स भरने का क्रम। |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


एक मान सेट करता है जो यह दर्शाता है कि [full frame]।

मान:  true  यदि [full frame]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो यह दर्शाता है कि [full frame]। |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


हाफटोन संकेत प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | हाफटोन संकेत। |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


ICC प्रोफ़ाइल स्ट्रीम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] | icc प्रोफ़ाइल। |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं।

मान:  true  यदि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


छवि विवरण को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | छवि विवरण। |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


छवि लंबाई को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | छवि लंबाई। |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


छवि चौड़ाई को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | छवि की चौड़ाई। |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


इंक नामों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | इंक नाम। |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


अधिकतम नमूना मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | अधिकतम सैंपल मान। |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


न्यूनतम नमूना मान को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | न्यूनतम सैंपल मान। |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


मल्टीपेज विकल्प

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


ओरिएंटेशन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | दिशा। |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


पृष्ठ नाम को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | पृष्ठ नाम। |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


पृष्ठ संख्या टैग को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | पृष्ठ संख्या टैग। |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


रंग पैलेट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


फोटोमेट्रिक को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | फ़ोटोमैट्रिक। |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


प्लेनर कॉन्फ़िगरेशन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | समतलीय विन्यास। |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


LZW संपीड़न के लिए प्रेडिक्टर को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | प्रेडिक्टर प्रकार। |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | यदि घटकों को प्रीमल्टिप्लाई किया जाना चाहिए तो true; अन्यथा false। |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


रिज़ॉल्यूशन यूनिट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | रिज़ॉल्यूशन इकाई। |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


प्रति स्ट्रिप पंक्तियों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | प्रति स्ट्रिप पंक्तियाँ। |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


नमूना प्रारूप को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | सैंपल फ़ॉर्मेट। |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


स्कैनर निर्माता प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | स्कैनर निर्माता। |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


स्कैनर मॉडल प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | स्कैनर मॉडल। |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


अधिकतम सैंपल मान प्राप्त करता है या सेट करता है। मान में एक फ़ील्ड प्रकार होता है जो सैंपल डेटा (Byte, Short या Long प्रकार) के साथ सबसे अच्छा मेल खाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long[] | अधिकतम सैंपल मान। |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


न्यूनतम सैंपल मान प्राप्त करता है या सेट करता है। मान में एक फ़ील्ड प्रकार होता है जो सैंपल डेटा (Byte, Short या Long प्रकार) के साथ सबसे अच्छा मेल खाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long[] | न्यूनतम सैंपल मान। |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


सॉफ़्टवेयर प्रकार प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | सॉफ़्टवेयर प्रकार। |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है।

मान: इमेज बनाने का स्रोत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


स्ट्रिप बाइट गणना प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long[] | स्ट्रिप बाइट गणना। |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


स्ट्रिप ऑफ़सेट प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long[] | स्ट्रिप ऑफ़सेट। |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


इस सबफ़ाइल में मौजूद डेटा के प्रकार का सामान्य संकेत प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | इस सबफ़ाइल में सम्मिलित डेटा के प्रकार का सामान्य संकेत। |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


टैग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | टैग। |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


लक्ष्य प्रिंटर प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | लक्षित प्रिंटर। |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


थ्रेशहोल्डिंग प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | थ्रेशहोल्डिंग। |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


टाइल बाइट गणना प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


टाइल लंबाई प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


टाइल ऑफ़सेट प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


टाइल चौड़ाई प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


छवि लेखक सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है।

मान: Image Author, Windows Explorer द्वारा उपयोग किया जाता है। XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) को Windows Explorer द्वारा अनदेखा किया जाता है यदि Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) टैग मौजूद है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | image author, जो Windows Explorer द्वारा उपयोग किया जाता है। |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


छवि पर टिप्पणी सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है।

मान: इमेज पर टिप्पणी, Windows Explorer द्वारा उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | comment on image, जो Windows Explorer द्वारा उपयोग किया जाता है। |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


विषय छवि सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है।

मान: इमेज विषय, Windows Explorer द्वारा उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | subject image, जो Windows Explorer द्वारा उपयोग किया जाता है। |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


छवि के बारे में जानकारी सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है।

मान: इमेज के बारे में जानकारी, Windows Explorer द्वारा उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | information about image, जो Windows Explorer द्वारा उपयोग किया जाता है। |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


छवि के बारे में जानकारी सेट करता है, जिसका उपयोग Windows Explorer द्वारा किया जाता है।

मान: Information about image, Windows Explorer द्वारा उपयोग किया जाता है। XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) को Windows Explorer द्वारा अनदेखा किया जाता है यदि ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) टैग मौजूद है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | information about image, जो Windows Explorer द्वारा उपयोग किया जाता है। |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP डेटा कंटेनर। |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


x स्थिति प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x स्थिति। |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


X रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | x रिज़ॉल्यूशन। |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


YCbCrCoefficients प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | YCbCrCoefficients। |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग कारक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] | YCbCr फोटोमेट्रिक के लिए सबसैंपलिंग कारक। |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


y स्थिति प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y स्थिति। |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


y रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | y रिज़ॉल्यूशन। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


वैलिडेट करता है कि विकल्पों में टैग्स का वैध संयोजन है या नहीं।

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


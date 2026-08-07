---
title: "JpegOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "JPEG फ़ाइल फ़ॉर्मेट निर्माण विकल्प।"
type: docs
weight: 15
url: /hi/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

JPEG फ़ाइल फ़ॉर्मेट निर्माण विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | JpegOptions वर्ग का नया उदाहरण प्रारंभ करता है। |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | JpegOptions वर्ग का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | lossless jpeg छवि के लिए प्रति चैनल बिट्स प्राप्त करता है। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK jpeg छवियों के लिए गंतव्य CMYK रंग प्रोफ़ाइल। |
| [getColorType()](#getColorType--) | jpeg छवि के लिए रंग प्रकार प्राप्त करता है। |
| [getComment()](#getComment--) | jpeg फ़ाइल टिप्पणी प्राप्त करता है। |
| [getCompressionType()](#getCompressionType--) | संपीड़न प्रकार प्राप्त करता है। |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | डिफ़ॉल्ट मेमोरी आवंटन सीमा प्राप्त करता है। |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getExifData()](#getExifData--) | exif डेटा कंटेनर प्राप्त करें या सेट करें |
| [getFullFrame()](#getFullFrame--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]। |
| [getHorizontalSampling()](#getHorizontalSampling--) | प्रत्येक घटक के लिए क्षैतिज सबसैंपलिंग प्राप्त करता है। |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [getJfif()](#getJfif--) | jfif प्राप्त करता है। |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | नज़दीकी-लॉसलेस कोडिंग के लिए JPEG-LS अंतर सीमा प्राप्त करता है (JPEG-LS विनिर्देशन से NEAR पैरामीटर)। |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | JPEG-LS इंटरलीव मोड प्राप्त करता है। |
| [getJpegLsPreset()](#getJpegLsPreset--) | JPEG-LS प्रीसेट पैरामीटर प्राप्त करता है। |
| [getMultiPageOptions()](#getMultiPageOptions--) | मल्टीपेज विकल्प |
| [getPalette()](#getPalette--) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | यदि अल्फा चैनल मौजूद है, तो लाल, हरा और नीला घटक पृष्ठभूमि रंग के साथ मिश्रित किए जाने चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [getQuality()](#getQuality--) | छवि गुणवत्ता प्राप्त करता है। |
| [getRdOptSettings()](#getRdOptSettings--) | RD ऑप्टिमाइज़र सेटिंग्स प्राप्त करता है। |
| [getResolutionSettings()](#getResolutionSettings--) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getResolutionUnit()](#getResolutionUnit--) | रिज़ॉल्यूशन इकाई प्राप्त करता है। |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK jpeg छवियों के लिए गंतव्य RGB रंग प्रोफ़ाइल। |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड प्राप्त करता है। |
| [getScaledQuality()](#getScaledQuality--) | स्केल्ड गुणवत्ता। |
| [getSource()](#getSource--) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [getVerticalSampling()](#getVerticalSampling--) | प्रत्येक घटक के लिए लंबवत सबसैंपलिंग प्राप्त करता है। |
| [getXmpData()](#getXmpData--) | XMP मेटाडेटा कंटेनर प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | लॉसलेस jpeg छवि के लिए प्रति चैनल बिट्स सेट करता है। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK jpeg छवियों के लिए गंतव्य CMYK रंग प्रोफ़ाइल। |
| [setColorType(int value)](#setColorType-int-) | jpeg छवि के लिए रंग प्रकार सेट करता है। |
| [setComment(String value)](#setComment-java.lang.String-) | jpeg फ़ाइल टिप्पणी सेट करता है। |
| [setCompressionType(int value)](#setCompressionType-int-) | संपीड़न प्रकार सेट करता है। |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | डिफ़ॉल्ट मेमोरी आवंटन सीमा सेट करता है। |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | exif डेटा कंटेनर प्राप्त करें या सेट करें |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | एक मान सेट करता है जो यह दर्शाता है कि [full frame]। |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | प्रत्येक घटक के लिए क्षैतिज सबसैंपलिंग सेट करता है। |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | jfif को सेट करता है। |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | निकट-निरुपयोगी कोडिंग के लिए JPEG-LS अंतर सीमा सेट करता है (JPEG-LS विनिर्देशन से NEAR पैरामीटर)। |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | JPEG-LS इंटरलीव मोड सेट करता है। |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | JPEG-LS प्रीसेट पैरामीटर सेट करता है। |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | मल्टीपेज विकल्प |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | यदि अल्फा चैनल मौजूद है, तो लाल, हरा और नीला घटक पृष्ठभूमि रंग के साथ मिश्रित होने चाहिए या नहीं, यह दर्शाने वाला मान सेट करता है। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [setQuality(int value)](#setQuality-int-) | छवि गुणवत्ता सेट करता है। |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | RD ऑप्टिमाइज़र सेटिंग्स सेट करता है। |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | रिज़ॉल्यूशन इकाई सेट करता है। |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | CMYK jpeg छवियों के लिए गंतव्य RGB रंग प्रोफ़ाइल। |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड सेट करता है। |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | प्रत्येक घटक के लिए वर्टिकल सबसैंपलिंग सेट करता है। |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP मेटाडेटा कंटेनर सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


JpegOptions वर्ग का नया उदाहरण प्रारंभ करता है।

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


JpegOptions वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | JPEG विकल्प। |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


लॉसलेस JPEG छवि के लिए प्रति चैनल बिट्स प्राप्त करता है। अब हम 2 से 8 बिट्स प्रति चैनल का समर्थन करते हैं।

**Returns:**
byte
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


CMYK JPEG छवियों के लिए गंतव्य CMYK कलर प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे RGBColorProfile के साथ जोड़ा होना चाहिए।

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg छवि के लिए रंग प्रकार प्राप्त करता है।

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


jpeg फ़ाइल टिप्पणी प्राप्त करता है।

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


संपीड़न प्रकार प्राप्त करता है।

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


डिफ़ॉल्ट मेमोरी आवंटन सीमा प्राप्त करता है।

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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


exif डेटा कंटेनर प्राप्त करें या सेट करें

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]।

मान:  true  यदि [full frame]; अन्यथा,  false .

**Returns:**
बूलियन - एक मान जो यह दर्शाता है कि [full frame]।
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


प्रत्येक घटक के लिए क्षैतिज सबसैंपलिंग प्राप्त करता है।

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं।

मान:  true  यदि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए; अन्यथा,  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


jfif प्राप्त करता है।

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


नज़दीकी-लॉसलेस कोडिंग के लिए JPEG-LS अंतर सीमा प्राप्त करता है (JPEG-LS विनिर्देशन से NEAR पैरामीटर)।

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


JPEG-LS इंटरलीव मोड प्राप्त करता है।

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


JPEG-LS प्रीसेट पैरामीटर प्राप्त करता है।

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


मल्टीपेज विकल्प

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


रंग पैलेट को प्राप्त करता है या सेट करता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


यदि अल्फा चैनल मौजूद है, तो लाल, हरा और नीला घटक पृष्ठभूमि रंग के साथ मिश्रित किए जाने चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


छवि गुणवत्ता प्राप्त करता है।

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


RD ऑप्टिमाइज़र सेटिंग्स प्राप्त करता है।

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है।

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


रिज़ॉल्यूशन इकाई प्राप्त करता है।

**Returns:**
byte - रिज़ॉल्यूशन इकाई।
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


CMYK JPEG छवियों के लिए गंतव्य RGB कलर प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे CMYKColorProfile के साथ जोड़ा होना चाहिए।

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड प्राप्त करता है।  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


स्केल्ड गुणवत्ता।

**Returns:**
int
### getSource() {#getSource--}
```
public final Source getSource()
```


इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है।

मान: इमेज बनाने का स्रोत।

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


प्रत्येक घटक के लिए लंबवत सबसैंपलिंग प्राप्त करता है।

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP मेटाडेटा कंटेनर प्राप्त करता है।

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


लॉसलेस JPEG छवि के लिए प्रति चैनल बिट्स सेट करता है। अब हम 2 से 8 बिट्स प्रति चैनल का समर्थन करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK JPEG छवियों के लिए गंतव्य CMYK कलर प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे RGBColorProfile के साथ जोड़ा होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg छवि के लिए रंग प्रकार सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpeg फ़ाइल टिप्पणी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


संपीड़न प्रकार सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


डिफ़ॉल्ट मेमोरी आवंटन सीमा सेट करता है।

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


exif डेटा कंटेनर प्राप्त करें या सेट करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


प्रत्येक घटक के लिए क्षैतिज सबसैंपलिंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


jfif को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


निकट-निरुपयोगी कोडिंग के लिए JPEG-LS अंतर सीमा सेट करता है (JPEG-LS विनिर्देशन से NEAR पैरामीटर)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


JPEG-LS इंटरलीव मोड सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


JPEG-LS प्रीसेट पैरामीटर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


मल्टीपेज विकल्प

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


रंग पैलेट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


यदि अल्फा चैनल मौजूद है, तो लाल, हरा और नीला घटक पृष्ठभूमि रंग के साथ मिश्रित होने चाहिए या नहीं, यह दर्शाने वाला मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


छवि गुणवत्ता सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


RD ऑप्टिमाइज़र सेटिंग्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | RD ऑप्टिमाइज़र सेटिंग्स। |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


रिज़ॉल्यूशन इकाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte | रिज़ॉल्यूशन इकाई। |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


CMYK JPEG छवियों के लिए गंतव्य RGB कलर प्रोफ़ाइल। छवियों को सहेजने के लिए उपयोग करें। सही रंग रूपांतरण के लिए इसे CMYKColorProfile के साथ जोड़ा होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8-बिट मान को n-बिट मान में फिट करने के लिए सैंपल राउंडिंग मोड सेट करता है।  P:JpegOptions.BitsPerChannel

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


प्रत्येक घटक के लिए वर्टिकल सबसैंपलिंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP मेटाडेटा कंटेनर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | XMP डेटा कंटेनर। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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


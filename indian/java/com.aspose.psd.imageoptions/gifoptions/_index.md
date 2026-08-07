---
title: "GifOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "GIF फ़ाइल फ़ॉर्मेट निर्माण विकल्प।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

GIF फ़ाइल फ़ॉर्मेट निर्माण विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions क्लास की एक नई इंस्टेंस को इनिशियलाइज़ करता है. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | GifOptions क्लास की एक नई इंस्टेंस को इनिशियलाइज़ करता है. |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF पृष्ठभूमि रंग इंडेक्स को प्राप्त करता है या सेट करता है. |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है. |
| [getFullFrame()](#getFullFrame--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]। |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [getInterlaced()](#getInterlaced--) | यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य. |
| [getMaxDiff()](#getMaxDiff--) | अधिकतम अनुमत पिक्सेल अंतर को प्राप्त करता है या सेट करता है. |
| [getMultiPageOptions()](#getMultiPageOptions--) | मल्टीपेज विकल्प |
| [getPalette()](#getPalette--) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF पिक्सेल आस्पेक्ट अनुपात को प्राप्त करता है या सेट करता है. |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [getResolutionSettings()](#getResolutionSettings--) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getSource()](#getSource--) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [getXmpData()](#getXmpData--) | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [hasTrailer()](#hasTrailer--) | GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | पैलेट एंट्रीज़ क्रमबद्ध हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF पृष्ठभूमि रंग इंडेक्स को प्राप्त करता है या सेट करता है. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setColorResolution(byte value)](#setColorResolution-byte-) | GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | एक मान सेट करता है जो यह दर्शाता है कि [full frame]। |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | अधिकतम अनुमत पिक्सेल अंतर को प्राप्त करता है या सेट करता है. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | मल्टीपेज विकल्प |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | पैलेट एंट्रीज़ क्रमबद्ध हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF पिक्सेल आस्पेक्ट अनुपात को प्राप्त करता है या सेट करता है. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [setTrailer(boolean value)](#setTrailer-boolean-) | GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions क्लास की एक नई इंस्टेंस को इनिशियलाइज़ करता है.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


GifOptions क्लास की एक नई इंस्टेंस को इनिशियलाइज़ करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | GIF विकल्प. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF पृष्ठभूमि रंग इंडेक्स को प्राप्त करता है या सेट करता है.

**Returns:**
byte - GIF पृष्ठभूमि रंग सूचकांक।
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है.

**Returns:**
byte - रंग रिज़ॉल्यूशन।

Color Resolution - मूल छवि में प्रत्येक प्राथमिक रंग के लिए उपलब्ध बिट्स की संख्या, माइनस 1। यह मान ग्राफिक में चयनित रंगों के पूरे पैलेट का आकार दर्शाता है, न कि ग्राफिक में वास्तविक उपयोग किए गए रंगों की संख्या। उदाहरण के लिए, यदि इस फ़ील्ड में मान 3 है, तो मूल छवि के पैलेट में प्रत्येक प्राथमिक रंग के लिए 4 बिट्स उपलब्ध थे जो छवि बनाने के लिए उपयोग किए गए। इस मान को मूल पैलेट की समृद्धि दर्शाने के लिए सेट किया जाना चाहिए, भले ही स्रोत मशीन पर पूरे पैलेट के सभी रंग उपलब्ध न हों।
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है.

**Returns:**
boolean - यदि पैलेट सुधार लागू किया गया हो तो true; अन्यथा false।

Palette correction का अर्थ है कि जब भी छवि को GIF में निर्यात किया जाता है, स्रोत छवि के रंगों का विश्लेषण किया जाएगा ताकि सबसे उपयुक्त पैलेट बनाया जा सके (यदि छवि का Palette मौजूद नहीं है या विकल्पों में निर्दिष्ट नहीं है)। विश्लेषण प्रक्रिया में कुछ समय लगता है, लेकिन आउटपुट छवि में सबसे उपयुक्त रंग पैलेट होगा और परिणाम दृश्य रूप से बेहतर होगा।
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]।

मान:  true  यदि [full frame]; अन्यथा,  false .

**Returns:**
बूलियन - एक मान जो यह दर्शाता है कि [full frame]।
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं।

मान:  true  यदि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए; अन्यथा,  false .

**Returns:**
boolean
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


अधिकतम अनुमत पिक्सेल अंतर को प्राप्त करता है या सेट करता है। यदि शून्य से अधिक है, तो लॉसी संपीड़न उपयोग किया जाएगा। इष्टतम लॉसी संपीड़न के लिए अनुशंसित मान 80 है। 30 बहुत हल्का संपीड़न है, 200 भारी है। यह तब सबसे अच्छा काम करता है जब केवल थोड़ा ही नुकसान प्रस्तुत किया जाता है, और संपीड़न एल्गोरिदम की सीमा के कारण बहुत उच्च नुकसान स्तर पर्याप्त लाभ नहीं देते। अनुमत मानों की सीमा [0, 1000] है।

**Returns:**
int - अनुमत मानों की सीमा।
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF पिक्सेल आस्पेक्ट अनुपात को प्राप्त करता है या सेट करता है.

Pixel Aspect Ratio - मूल छवि में पिक्सेल के अनुपात का अनुमान लगाने के लिए उपयोग किया जाने वाला कारक। यदि फ़ील्ड का मान 0 नहीं है, तो इस अनुपात का अनुमान निम्न सूत्र के आधार पर गणना किया जाता है: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64। Pixel Aspect Ratio को पिक्सेल की चौड़ाई को उसकी ऊँचाई से भाग देने के रूप में परिभाषित किया गया है। इस फ़ील्ड में मानों की सीमा 4:1 (सबसे चौड़ा पिक्सेल) से 1:4 (सबसे ऊँचा पिक्सेल) तक 1/64 के चरणों में निर्दिष्ट करने की अनुमति देती है। मान: 0 - कोई अनुपात जानकारी नहीं दी गई। 1..255 - गणना में उपयोग किया गया मान।

**Returns:**
byte - GIF पिक्सेल अनुपात।
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
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है।

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है.

**Returns:**
boolean - यदि GIF में ट्रेलर है तो true; अन्यथा false।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


पैलेट एंट्रीज़ क्रमबद्ध हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है.

**Returns:**
boolean - यदि पैलेट प्रविष्टियाँ क्रमबद्ध हैं तो true; अन्यथा false।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF पृष्ठभूमि रंग इंडेक्स को प्राप्त करता है या सेट करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte | GIF पृष्ठभूमि रंग सूचकांक। |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF रंग रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | byte | रंग रिज़ॉल्यूशन। |

Color Resolution - मूल छवि में प्रत्येक प्राथमिक रंग के लिए उपलब्ध बिट्स की संख्या, माइनस 1। यह मान ग्राफिक में चयनित रंगों के पूरे पैलेट का आकार दर्शाता है, न कि ग्राफिक में वास्तविक उपयोग किए गए रंगों की संख्या। उदाहरण के लिए, यदि इस फ़ील्ड में मान 3 है, तो मूल छवि के पैलेट में प्रत्येक प्राथमिक रंग के लिए 4 बिट्स उपलब्ध थे जो छवि बनाने के लिए उपयोग किए गए। इस मान को मूल पैलेट की समृद्धि दर्शाने के लिए सेट किया जाना चाहिए, भले ही स्रोत मशीन पर पूरे पैलेट के सभी रंग उपलब्ध न हों। |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


पैलेट सुधार लागू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि पैलेट सुधार लागू किया गया हो तो true; अन्यथा false। |

Palette correction का अर्थ है कि जब भी छवि को GIF में निर्यात किया जाता है, स्रोत छवि के रंगों का विश्लेषण किया जाएगा ताकि सबसे उपयुक्त पैलेट बनाया जा सके (यदि छवि का Palette मौजूद नहीं है या विकल्पों में निर्दिष्ट नहीं है)। विश्लेषण प्रक्रिया में कुछ समय लगता है, लेकिन आउटपुट छवि में सबसे उपयुक्त रंग पैलेट होगा और परिणाम दृश्य रूप से बेहतर होगा। |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


यदि छवि को इंटरलेस किया जाना चाहिए तो सत्य.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


अधिकतम अनुमत पिक्सेल अंतर को प्राप्त करता है या सेट करता है। यदि शून्य से अधिक है, तो लॉसी संपीड़न उपयोग किया जाएगा। इष्टतम लॉसी संपीड़न के लिए अनुशंसित मान 80 है। 30 बहुत हल्का संपीड़न है, 200 भारी है। यह तब सबसे अच्छा काम करता है जब केवल थोड़ा ही नुकसान प्रस्तुत किया जाता है, और संपीड़न एल्गोरिदम की सीमा के कारण बहुत उच्च नुकसान स्तर पर्याप्त लाभ नहीं देते। अनुमत मानों की सीमा [0, 1000] है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | अनुमत मानों की सीमा। |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


पैलेट एंट्रीज़ क्रमबद्ध हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | boolean - यदि पैलेट प्रविष्टियाँ क्रमबद्ध हैं तो true; अन्यथा false। |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF पिक्सेल आस्पेक्ट अनुपात को प्राप्त करता है या सेट करता है.

Pixel Aspect Ratio - मूल छवि में पिक्सेल के अनुपात का अनुमान लगाने के लिए उपयोग किया जाने वाला कारक। यदि फ़ील्ड का मान 0 नहीं है, तो इस अनुपात का अनुमान निम्न सूत्र के आधार पर गणना किया जाता है: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64। Pixel Aspect Ratio को पिक्सेल की चौड़ाई को उसकी ऊँचाई से भाग देने के रूप में परिभाषित किया गया है। इस फ़ील्ड में मानों की सीमा 4:1 (सबसे चौड़ा पिक्सेल) से 1:4 (सबसे ऊँचा पिक्सेल) तक 1/64 के चरणों में निर्दिष्ट करने की अनुमति देती है। मान: 0 - कोई अनुपात जानकारी नहीं दी गई। 1..255 - गणना में उपयोग किया गया मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte | GIF पिक्सेल अनुपात। |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF में ट्रेलर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | boolean - यदि GIF में ट्रेलर है तो true; अन्यथा false। |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है।

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


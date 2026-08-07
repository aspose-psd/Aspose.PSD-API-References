---
title: "PsdOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "PSD फ़ाइल फ़ॉर्मेट निर्माण विकल्प।"
type: docs
weight: 21
url: /hi/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

PSD फ़ाइल फ़ॉर्मेट निर्माण विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) क्लास का नया उदाहरण प्रारंभ करता है। |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) क्लास का नया उदाहरण प्रारंभ करता है। |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | बैकग्राउंड का रंग प्राप्त करता है या सेट करता है। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [getChannelBitsCount()](#getChannelBitsCount--) | रंग चैनल प्रति बिट्स की संख्या प्राप्त करता है या सेट करता है। |
| [getChannelsCount()](#getChannelsCount--) | रंग चैनलों की संख्या प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | psd रंग मोड प्राप्त करता है या सेट करता है। |
| [getCompressionMethod()](#getCompressionMethod--) | psd संपीड़न विधि प्राप्त करता है या सेट करता है। |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getFullFrame()](#getFullFrame--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]। |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [getMultiPageOptions()](#getMultiPageOptions--) | मल्टीपेज विकल्प |
| [getPalette()](#getPalette--) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [getPsdVersion()](#getPsdVersion--) | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है या सेट करता है। |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [refresh image preview data] - विकल्प का उपयोग अन्य PSD इमेज व्यूअर्स के साथ संगतता अधिकतम करने के लिए किया जाता है। |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि - ग्लोबल टेक्स्ट इंजन रिसोर्स हटाएँ - कुछ टेक्स्ट-लेयर वाले psd फ़ाइलों के लिए उपयोग किया जाता है, केवल उस स्थिति में जब प्रोसेसिंग के बाद उन्हें Adobe Photoshop में नहीं खोला जा सकता (मुख्यतः अनुपलब्ध फ़ॉन्ट्स वाले टेक्स्ट लेयर्स से संबंधित)। |
| [getResolutionSettings()](#getResolutionSettings--) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getResources()](#getResources--) | psd संसाधनों को प्राप्त करता है या सेट करता है। |
| [getSource()](#getSource--) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [getUpdateMetadata()](#getUpdateMetadata--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [update metadata]। |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [getVersion()](#getVersion--) | psd फ़ाइल संस्करण प्राप्त करता है या सेट करता है। |
| [getXmpData()](#getXmpData--) | XMP डेटा कंटेनर प्राप्त करें या सेट करें |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | दिखाता है कि ColorMode प्रॉपर्टी असाइन की गई है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | बैकग्राउंड का रंग प्राप्त करता है या सेट करता है। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | रंग चैनल प्रति बिट्स की संख्या प्राप्त करता है या सेट करता है। |
| [setChannelsCount(short value)](#setChannelsCount-short-) | रंग चैनलों की संख्या प्राप्त करता है या सेट करता है। |
| [setColorMode(short value)](#setColorMode-short-) | psd रंग मोड प्राप्त करता है या सेट करता है। |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | psd संपीड़न विधि प्राप्त करता है या सेट करता है। |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | एक मान सेट करता है जो यह दर्शाता है कि [full frame]। |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | मल्टीपेज विकल्प |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है या सेट करता है। |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [refresh image preview data] - विकल्प का उपयोग अन्य PSD इमेज व्यूअर्स के साथ संगतता अधिकतम करने के लिए किया जाता है। |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि - ग्लोबल टेक्स्ट इंजन रिसोर्स हटाएँ - कुछ टेक्स्ट-लेयर वाले psd फ़ाइलों के लिए उपयोग किया जाता है, केवल उस स्थिति में जब प्रोसेसिंग के बाद उन्हें Adobe Photoshop में नहीं खोला जा सकता (मुख्यतः अनुपलब्ध फ़ॉन्ट्स वाले टेक्स्ट लेयर्स से संबंधित)। |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | psd संसाधनों को प्राप्त करता है या सेट करता है। |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [update metadata]। |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [setVersion(int value)](#setVersion-int-) | psd फ़ाइल संस्करण प्राप्त करता है या सेट करता है। |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP डेटा कंटेनर प्राप्त करें या सेट करें |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) क्लास का नया उदाहरण प्रारंभ करता है।

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | विकल्प। |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | छवि। |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। इसे पारदर्शी वस्तुओं के नीचे देखा जा सकता है।

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


रंग चैनल प्रति बिट्स की संख्या प्राप्त करता है या सेट करता है।

मान: रंग चैनल प्रति बिट्स की संख्या।

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


रंग चैनलों की संख्या प्राप्त करता है या सेट करता है।

मान: रंग चैनलों की संख्या।

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


psd रंग मोड प्राप्त करता है या सेट करता है।

मान: रंग मोड।

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


psd संपीड़न विधि प्राप्त करता है या सेट करता है।

मान: संपीड़न विधि।

**Returns:**
short
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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है या सेट करता है। यह PSD या PSB हो सकता है।

मान: फ़ाइल फ़ॉर्मेट संस्करण।

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [refresh image preview data] - विकल्प का उपयोग अन्य PSD इमेज व्यूअर्स के साथ संगतता अधिकतम करने के लिए किया जाता है। कृपया ध्यान दें, कॉम्पैक्ट फ़्रेमवर्क प्लेटफ़ॉर्म के लिए अंतिम लेआउट में टेक्स्ट लेयर ड्रॉइंग समर्थित नहीं है।

मान:  true  यदि [refresh image preview data]; अन्यथा,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि - ग्लोबल टेक्स्ट इंजन रिसोर्स हटाएँ - कुछ टेक्स्ट-लेयर वाले psd फ़ाइलों के लिए उपयोग किया जाता है, केवल तब जब प्रोसेसिंग के बाद उन्हें Adobe Photoshop में नहीं खोला जा सकता (मुख्यतः अनुपलब्ध फ़ॉन्ट्स वाले टेक्स्ट लेयर्स से संबंधित)। इस विकल्प का उपयोग करने के बाद, उपयोगकर्ता को Photoshop में खुले फ़ाइल में निम्न करना होगा: मेन्यू "Text" -> "Process absent fonts"। इसके बाद सभी टेक्स्ट फिर से दिखाई देंगे। कृपया ध्यान दें, इस ऑपरेशन से अंतिम लेआउट में कुछ परिवर्तन हो सकते हैं।

मान:  true  यदि [remove global text engine resource]; अन्यथा,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है।

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


psd संसाधनों को प्राप्त करता है या सेट करता है। यदि मान: NULL - तो मूल ImageResources सहेजें (डिफ़ॉल्ट व्यवहार) Not Empty - तो इस प्रॉपर्टी में पास किए गए संसाधनों + [required resources] को सहेजें। Empty - तो केवल [required resources] सहेजे जाएँ। आवश्यक संसाधन: ResolutionInfoResource, XmpResource

मान: psd संसाधन।

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है।

मान: इमेज बनाने का स्रोत।

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [update metadata]। यदि मान true है, तो इमेज सहेजते समय मेटाडेटा अपडेट किया जाएगा।

मान:  true  यदि [update metadata]; अन्यथा,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


psd फ़ाइल संस्करण प्राप्त करता है या सेट करता है।

मान: psd फ़ाइल संस्करण।

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


XMP डेटा कंटेनर प्राप्त करें या सेट करें

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


दिखाता है कि ColorMode प्रॉपर्टी असाइन की गई है या नहीं।

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


पृष्ठभूमि का रंग प्राप्त करता है या सेट करता है। इसे पारदर्शी वस्तुओं के नीचे देखा जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


रंग चैनल प्रति बिट्स की संख्या प्राप्त करता है या सेट करता है।

मान: रंग चैनल प्रति बिट्स की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


रंग चैनलों की संख्या प्राप्त करता है या सेट करता है।

मान: रंग चैनलों की संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


psd रंग मोड प्राप्त करता है या सेट करता है।

मान: रंग मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


psd संपीड़न विधि प्राप्त करता है या सेट करता है।

मान: संपीड़न विधि।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है या सेट करता है। यह PSD या PSB हो सकता है।

मान: फ़ाइल फ़ॉर्मेट संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [refresh image preview data] - विकल्प का उपयोग अन्य PSD इमेज व्यूअर्स के साथ संगतता अधिकतम करने के लिए किया जाता है। कृपया ध्यान दें, कॉम्पैक्ट फ़्रेमवर्क प्लेटफ़ॉर्म के लिए अंतिम लेआउट में टेक्स्ट लेयर ड्रॉइंग समर्थित नहीं है।

मान:  true  यदि [refresh image preview data]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि - ग्लोबल टेक्स्ट इंजन रिसोर्स हटाएँ - कुछ टेक्स्ट-लेयर वाले psd फ़ाइलों के लिए उपयोग किया जाता है, केवल तब जब प्रोसेसिंग के बाद उन्हें Adobe Photoshop में नहीं खोला जा सकता (मुख्यतः अनुपलब्ध फ़ॉन्ट्स वाले टेक्स्ट लेयर्स से संबंधित)। इस विकल्प का उपयोग करने के बाद, उपयोगकर्ता को Photoshop में खुले फ़ाइल में निम्न करना होगा: मेन्यू "Text" -> "Process absent fonts"। इसके बाद सभी टेक्स्ट फिर से दिखाई देंगे। कृपया ध्यान दें, इस ऑपरेशन से अंतिम लेआउट में कुछ परिवर्तन हो सकते हैं।

मान:  true  यदि [remove global text engine resource]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


psd संसाधनों को प्राप्त करता है या सेट करता है। यदि मान: NULL - तो मूल ImageResources सहेजें (डिफ़ॉल्ट व्यवहार) Not Empty - तो इस प्रॉपर्टी में पास किए गए संसाधनों + [required resources] को सहेजें। Empty - तो केवल [required resources] सहेजे जाएँ। आवश्यक संसाधन: ResolutionInfoResource, XmpResource

मान: psd संसाधन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [update metadata]। यदि मान true है, तो इमेज सहेजते समय मेटाडेटा अपडेट किया जाएगा।

मान:  true  यदि [update metadata]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


psd फ़ाइल संस्करण प्राप्त करता है या सेट करता है।

मान: psd फ़ाइल संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


XMP डेटा कंटेनर प्राप्त करें या सेट करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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


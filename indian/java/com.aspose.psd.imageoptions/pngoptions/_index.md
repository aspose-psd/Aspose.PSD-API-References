---
title: "PngOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "PNG फ़ाइल फ़ॉर्मेट निर्माण विकल्प।"
type: docs
weight: 19
url: /hi/java/com.aspose.psd.imageoptions/pngoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

PNG फ़ाइल फ़ॉर्मेट निर्माण विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PngOptions()](#PngOptions--) | PngOptions वर्ग की नई इंस्टेंस को प्रारंभ करता है। |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.psd.imageoptions.PngOptions-) | JpegOptions वर्ग का नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | डिफ़ॉल्ट संपीड़न स्तर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | इस उदाहरण को क्लोन करता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | बिट गहराई प्राप्त करता है। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | रंग के प्रकार को प्राप्त करता है या सेट करता है। |
| [getCompressionLevel()](#getCompressionLevel--) | 0-9 सीमा में png छवि संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न और 0 स्टोर मोड है। |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getFilterType()](#getFilterType--) | png फ़ाइल सहेजने प्रक्रिया के दौरान उपयोग किए जाने वाले फ़िल्टर प्रकार को प्राप्त करता है या सेट करता है। |
| [getFullFrame()](#getFullFrame--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या [full frame]। |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [getMultiPageOptions()](#getMultiPageOptions--) | मल्टीपेज विकल्प |
| [getPalette()](#getPalette--) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [getProgressive()](#getProgressive--) | यह PngOptions प्रोग्रेसिव है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getResolutionSettings()](#getResolutionSettings--) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getSource()](#getSource--) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [getXmpData()](#getXmpData--) | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitDepth(byte value)](#setBitDepth-byte-) | बिट गहराई सेट करता है। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setColorType(int value)](#setColorType-int-) | रंग के प्रकार को प्राप्त करता है या सेट करता है। |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 0-9 सीमा में png छवि संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न और 0 स्टोर मोड है। |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | डिफ़ॉल्ट प्रतिस्थापन फ़ॉन्ट प्राप्त करता है या सेट करता है (फ़ॉन्ट जिसका उपयोग रास्टर में निर्यात करते समय टेक्स्ट ड्रॉ करने के लिए किया जाएगा, यदि PSD फ़ाइल में मौजूदा लेयर फ़ॉन्ट सिस्टम में उपलब्ध नहीं है)। |
| [setFilterType(int value)](#setFilterType-int-) | png फ़ाइल सहेजने प्रक्रिया के दौरान उपयोग किए जाने वाले फ़िल्टर प्रकार को प्राप्त करता है या सेट करता है। |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | एक मान सेट करता है जो यह दर्शाता है कि [full frame]। |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | प्राप्त करता है या सेट करता है वह मान जो यह दर्शाता है कि निर्माण इवेंट के बाद उपेक्षा की जानी चाहिए या नहीं। |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | मल्टीपेज विकल्प |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | रंग पैलेट को प्राप्त करता है या सेट करता है। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| [setProgressive(boolean value)](#setProgressive-boolean-) | यह PngOptions प्रोग्रेसिव है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | रिज़ॉल्यूशन सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | इमेज बनाने के स्रोत को प्राप्त करता है या सेट करता है। |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | वेक्टर रास्टराइज़ेशन विकल्पों को प्राप्त करता है या सेट करता है। |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | XMP मेटाडेटा कंटेनर को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [validate_internalized()](#validate-internalized--) | विकल्प सत्यापन प्रक्रिया। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngOptions() {#PngOptions--}
```
public PngOptions()
```


PngOptions वर्ग की नई इंस्टेंस को प्रारंभ करता है।

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.psd.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


JpegOptions वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.psd.imageoptions/pngoptions) | PNG विकल्प। |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


डिफ़ॉल्ट संपीड़न स्तर।

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
### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


बिट गहराई प्राप्त करता है।

**Returns:**
byte - बिट गहराई।
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
### getColorType() {#getColorType--}
```
public int getColorType()
```


रंग के प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
int - रंग का प्रकार।
### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


0-9 सीमा में png छवि संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न और 0 स्टोर मोड है।

**Returns:**
int - 0-9 सीमा में संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न और 0 स्टोर मोड है।
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
### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


png फ़ाइल सहेजने प्रक्रिया के दौरान उपयोग किए जाने वाले फ़िल्टर प्रकार को प्राप्त करता है या सेट करता है।

**Returns:**
int - png फ़ाइल सहेजने प्रक्रिया के दौरान उपयोग किया गया फ़िल्टर प्रकार।
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
### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


यह PngOptions प्रोग्रेसिव है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
बूलियन - यदि प्रोग्रेसिव है तो true, अन्यथा false।
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

मान: XMP डेटा कंटेनर।

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


बिट गहराई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte | बिट गहराई। |

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

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


रंग के प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | रंग का प्रकार। |

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


0-9 सीमा में png छवि संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न और 0 स्टोर मोड है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | 0-9 सीमा में संपीड़न स्तर, जहाँ 9 अधिकतम संपीड़न है और 0 स्टोर मोड है। |

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

### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


png फ़ाइल सहेजने प्रक्रिया के दौरान उपयोग किए जाने वाले फ़िल्टर प्रकार को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | png फ़ाइल सहेजने की प्रक्रिया के दौरान उपयोग किया गया फ़िल्टर प्रकार। |

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

### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


यह PngOptions प्रोग्रेसिव है या नहीं दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | यदि प्रोग्रेसिव है तो true, अन्यथा false। |

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

मान: XMP डेटा कंटेनर।

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
### validate_internalized() {#validate-internalized--}
```
public void validate_internalized()
```


विकल्प सत्यापन प्रक्रिया।

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


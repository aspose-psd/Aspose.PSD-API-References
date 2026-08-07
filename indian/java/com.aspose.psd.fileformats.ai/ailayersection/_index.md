---
title: "AiLayerSection"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Ai फ़ॉर्मेट लेयर सेक्शन"
type: docs
weight: 15
url: /hi/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Ai फ़ॉर्मेट लेयर सेक्शन
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | रास्टर छवि जोड़ता है। |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | नीले रंग घटक को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | रंग के सूचकांक को प्राप्त करता है या सेट करता है। |
| [getColorNumber()](#getColorNumber--) | रंग संख्या को प्राप्त करता है या सेट करता है। |
| [getData()](#getData--) | स्ट्रिंग डेटा प्राप्त करता है। |
| [getDimValue()](#getDimValue--) | डिम मान को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getGreen()](#getGreen--) | ग्रीन रंग घटक को प्राप्त करता है या सेट करता है। |
| [getName()](#getName--) | लेयर नाम को प्राप्त करता है या सेट करता है। |
| [getRasterImages()](#getRasterImages--) | रास्टर छवियों को प्राप्त करता है। |
| [getRed()](#getRed--) | रेड रंग घटक को प्राप्त करता है या सेट करता है। |
| [getStream_internalized()](#getStream-internalized--) | आंतरिक स्ट्रीम प्राप्त करता है |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | इस इंस्टेंस में मल्टीलेयर मास्क हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | यह लेयर डिम्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [isLocked()](#isLocked--) | यह लेयर लॉक्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [isPreview()](#isPreview--) | यह लेयर प्रीव्यू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [isPrinted()](#isPrinted--) | यह लेयर प्रिंटेड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [isShown()](#isShown--) | यह लेयर दिखाया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [isTemplate()](#isTemplate--) | यह लेयर टेम्पलेट लेयर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | नीले रंग घटक को प्राप्त करता है या सेट करता है। |
| [setColorIndex(int value)](#setColorIndex-int-) | रंग के सूचकांक को प्राप्त करता है या सेट करता है। |
| [setColorNumber(int value)](#setColorNumber-int-) | रंग संख्या को प्राप्त करता है या सेट करता है। |
| [setDimValue(int value)](#setDimValue-int-) | डिम मान को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [setGreen(int value)](#setGreen-int-) | ग्रीन रंग घटक को प्राप्त करता है या सेट करता है। |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | यह लेयर डिम्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setLocked(boolean value)](#setLocked-boolean-) | यह लेयर लॉक्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | इस इंस्टेंस में मल्टीलेयर मास्क हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | लेयर नाम को प्राप्त करता है या सेट करता है। |
| [setPreview(boolean value)](#setPreview-boolean-) | यह लेयर प्रीव्यू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setPrinted(boolean value)](#setPrinted-boolean-) | यह लेयर प्रिंटेड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setRed(int value)](#setRed-int-) | रेड रंग घटक को प्राप्त करता है या सेट करता है। |
| [setShown(boolean value)](#setShown-boolean-) | यह लेयर दिखाया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setTemplate(boolean value)](#setTemplate-boolean-) | यह लेयर टेम्पलेट लेयर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


रास्टर छवि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | रास्टर छवि। |

### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |
| गुणधर्म | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


नीले रंग घटक को प्राप्त करता है या सेट करता है।

मान: ब्लू रंग घटक।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


रंग का इंडेक्स प्राप्त करता है या सेट करता है। यह आर्ग्यूमेंट \\u20131 और 26 के बीच मान ले सकता है। प्रत्येक पूर्णांक एक ऐसे रंग को दर्शाता है जिसे उपयोगकर्ता पहचान उद्देश्यों के लिए लेयर को असाइन किया जा सकता है।

मान: रंग का इंडेक्स।

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


रंग संख्या प्राप्त करता है या सेट करता है। -1 रेड, ग्रीन, ब्लू प्रॉपर्टीज़ से कस्टम रंग मान है। लेयर\\u2019 की रंग सेटिंग निर्दिष्ट करता है।

मान: रंग संख्या।

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


स्ट्रिंग डेटा प्राप्त करता है।

**Returns:**
java.lang.String - सेक्शन का स्ट्रिंग डेटा
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


डिम वैल्यू को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। लेयर में मौजूद लिंक्ड इमेजेज और बिटमैप इमेजेज की तीव्रता को निर्दिष्ट प्रतिशत तक घटाता है।

मान: डिम वैल्यू प्रतिशत के रूप में।

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getGreen() {#getGreen--}
```
public final int getGreen()
```


ग्रीन रंग घटक को प्राप्त करता है या सेट करता है।

मान: ग्रीन रंग घटक।

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


लेयर नाम प्राप्त करता है या सेट करता है। लेयर्स पैनल में दिखाई देने वाले आइटम का नाम निर्दिष्ट करता है।

मान: लेयर का नाम।

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


रास्टर छवियों को प्राप्त करता है।

मान: रास्टर छवियां।

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


रेड रंग घटक को प्राप्त करता है या सेट करता है।

मान: रेड रंग घटक।

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


आंतरिक स्ट्रीम प्राप्त करता है

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


इस इंस्टेंस में मल्टीलेयर मास्क हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि इस इंस्टेंस में मल्टीलेयर मास्क हैं; अन्यथा,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


यह लेयर डिम्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। लेयर में मौजूद लिंक्ड इमेजेज और बिटमैप इमेजेज की तीव्रता को घटाता है।

मान:  true  यदि यह लेयर डिम्ड है; अन्यथा,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


इस लेयर को लॉक किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। आइटम में परिवर्तन को रोकता है।

मान: यदि यह लेयर लॉक है तो true; अन्यथा false।

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


इस लेयर का प्रीव्यू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। लेयर में मौजूद कलाकृति को रूपरेखा के बजाय रंग में प्रदर्शित करता है।

मान: यदि यह लेयर प्रीव्यू है तो true; अन्यथा false।

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


इस लेयर प्रिंट किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true हो तो लेयर में मौजूद कलाकृति को प्रिंट योग्य बनाता है।

मान: यदि यह लेयर प्रिंट किया गया है तो true; अन्यथा false।

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


इस लेयर दिखाया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true हो तो लेयर में मौजूद सभी कलाकृति को आर्टबोर्ड पर प्रदर्शित करता है।

मान: यदि यह लेयर दिखाया गया है तो true; अन्यथा false।

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


यह लेयर टेम्पलेट लेयर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि यह लेयर एक टेम्पलेट है तो true; अन्यथा false।

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


नीले रंग घटक को प्राप्त करता है या सेट करता है।

मान: ब्लू रंग घटक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


रंग का इंडेक्स प्राप्त करता है या सेट करता है। यह आर्ग्यूमेंट \\u20131 और 26 के बीच मान ले सकता है। प्रत्येक पूर्णांक एक ऐसे रंग को दर्शाता है जिसे उपयोगकर्ता पहचान उद्देश्यों के लिए लेयर को असाइन किया जा सकता है।

मान: रंग का इंडेक्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


रंग संख्या प्राप्त करता है या सेट करता है। -1 रेड, ग्रीन, ब्लू प्रॉपर्टीज़ से कस्टम रंग मान है। लेयर\\u2019 की रंग सेटिंग निर्दिष्ट करता है।

मान: रंग संख्या।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


डिम वैल्यू को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। लेयर में मौजूद लिंक्ड इमेजेज और बिटमैप इमेजेज की तीव्रता को निर्दिष्ट प्रतिशत तक घटाता है।

मान: डिम वैल्यू प्रतिशत के रूप में।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


ग्रीन रंग घटक को प्राप्त करता है या सेट करता है।

मान: ग्रीन रंग घटक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


यह लेयर डिम्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। लेयर में मौजूद लिंक्ड इमेजेज और बिटमैप इमेजेज की तीव्रता को घटाता है।

मान:  true  यदि यह लेयर डिम्ड है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


इस लेयर को लॉक किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। आइटम में परिवर्तन को रोकता है।

मान: यदि यह लेयर लॉक है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


इस इंस्टेंस में मल्टीलेयर मास्क हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि इस इंस्टेंस में मल्टीलेयर मास्क हैं; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


लेयर नाम प्राप्त करता है या सेट करता है। लेयर्स पैनल में दिखाई देने वाले आइटम का नाम निर्दिष्ट करता है।

मान: लेयर का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


इस लेयर का प्रीव्यू है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। लेयर में मौजूद कलाकृति को रूपरेखा के बजाय रंग में प्रदर्शित करता है।

मान: यदि यह लेयर प्रीव्यू है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


इस लेयर प्रिंट किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true हो तो लेयर में मौजूद कलाकृति को प्रिंट योग्य बनाता है।

मान: यदि यह लेयर प्रिंट किया गया है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


रेड रंग घटक को प्राप्त करता है या सेट करता है।

मान: रेड रंग घटक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


इस लेयर दिखाया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि true हो तो लेयर में मौजूद सभी कलाकृति को आर्टबोर्ड पर प्रदर्शित करता है।

मान: यदि यह लेयर दिखाया गया है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


यह लेयर टेम्पलेट लेयर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि यह लेयर एक टेम्पलेट है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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


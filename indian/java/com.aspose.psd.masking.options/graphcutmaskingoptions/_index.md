---
title: "GraphCutMaskingOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्राफकट ऑटो मास्किंग विकल्प।"
type: docs
weight: 14
url: /hi/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

ग्राफकट ऑटो मास्किंग विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | पृष्ठभूमि वस्तु संख्या |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | सेगमेंटेशन एल्गोरिदम के तर्कों को प्राप्त करता है। |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | पृष्ठभूमि प्रतिस्थापन रंग को प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | प्राप्त करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है। |
| [getExportOptions()](#getExportOptions--) | छवि निर्यात विकल्पों को प्राप्त करता है। |
| [getFeatheringRadius()](#getFeatheringRadius--) | फेदरिंग त्रिज्या प्राप्त करता है। |
| [getMaskingArea()](#getMaskingArea--) | मास्किंग क्षेत्र को प्राप्त करता है। |
| [getMethod()](#getMethod--) | सेगमेंटेशन विधि को प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | सेगमेंटेशन एल्गोरिदम के तर्कों को निर्धारित करता है। |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | पृष्ठभूमि प्रतिस्थापन रंग को निर्धारित करता है। |
| [setDecompose(boolean value)](#setDecompose-boolean-) | सेट करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है। |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | छवि निर्यात विकल्पों को निर्धारित करता है। |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | फ़ेदरिंग त्रिज्या सेट करता है। |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | मास्किंग क्षेत्र को निर्धारित करता है। |
| [setMethod(int value)](#setMethod-int-) | सेगमेंटेशन विधि को निर्धारित करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


पृष्ठभूमि वस्तु संख्या

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


सेगमेंटेशन एल्गोरिदम के तर्कों को प्राप्त करता है।

मान: सेगमेंटेशन एल्गोरिदम के तर्क।

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


पृष्ठभूमि प्रतिस्थापन रंग को प्राप्त करता है।

मान: पृष्ठभूमि प्रतिस्थापन रंग। यह रंग परिणामस्वरूप छवियों में पृष्ठभूमि रंग के रूप में उपयोग किया जाएगा।

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


प्राप्त करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है।

मान: यदि विघटित किया जाए तो true; अन्यथा false।

**Returns:**
बूलियन - वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है।
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


छवि निर्यात विकल्पों को प्राप्त करता है।

मान: छवि निर्यात विकल्प जो परिणामस्वरूप छवियों को बनाने के लिए उपयोग किए जाएंगे।

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


फेदरिंग त्रिज्या प्राप्त करता है।

**Returns:**
int - फ़ेदरिंग त्रिज्या।
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


मास्किंग क्षेत्र को प्राप्त करता है।

मान: मास्किंग क्षेत्र जो स्रोत छवि का एक आंशिक भाग है। Rectangle.Empty मान का अर्थ पूर्ण स्रोत छवि क्षेत्र है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


सेगमेंटेशन विधि को प्राप्त करता है।

मान: विभाजन विधि।

**Returns:**
int - विभाजन विधि।
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


सेगमेंटेशन एल्गोरिदम के तर्कों को निर्धारित करता है।

मान: सेगमेंटेशन एल्गोरिदम के तर्क।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | विभाजन एल्गोरिदम के तर्क। |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


पृष्ठभूमि प्रतिस्थापन रंग को निर्धारित करता है।

मान: पृष्ठभूमि प्रतिस्थापन रंग। यह रंग परिणामस्वरूप छवियों में पृष्ठभूमि रंग के रूप में उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | पृष्ठभूमि प्रतिस्थापन रंग। |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


सेट करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है।

मान: यदि विघटित किया जाए तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो संकेत करता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में अलग करना अनावश्यक है या पृष्ठभूमि से अलग किए गए mask से संयुक्त वस्तु के रूप में। |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


छवि निर्यात विकल्पों को निर्धारित करता है।

मान: छवि निर्यात विकल्प जो परिणामस्वरूप छवियों को बनाने के लिए उपयोग किए जाएंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | छवि निर्यात विकल्प। |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


फ़ेदरिंग त्रिज्या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | फ़ेदरिंग त्रिज्या। |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


मास्किंग क्षेत्र को निर्धारित करता है।

मान: मास्किंग क्षेत्र जो स्रोत छवि का एक आंशिक भाग है। Rectangle.Empty मान का अर्थ पूर्ण स्रोत छवि क्षेत्र है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | मास्किंग क्षेत्र। |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


सेगमेंटेशन विधि को निर्धारित करता है।

मान: विभाजन विधि।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | विभाजन विधि। |

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


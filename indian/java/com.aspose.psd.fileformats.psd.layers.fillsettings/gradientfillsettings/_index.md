---
title: "GradientFillSettings"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्रेडिएंट फ़िल इफ़ेक्ट सेटिंग्स।"
type: docs
weight: 14
url: /hi/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

ग्रेडिएंट फ़िल इफ़ेक्ट सेटिंग्स।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | निम्नलिखित [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) क्लास का नया उदाहरण आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getAngle()](#getAngle--) | कोण प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | ग्रेडिएंट की स्थिति को सही ढंग से गणना करने के लिए लेयर कंटेनर की सीमाएँ प्राप्त करता है या सेट करता है। |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | वर्तमान Scale मान के अनुरूप **denormalized** ग्रेडिएंट स्केल (UI Scale) की गणना करता है और लौटाता है ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) मान। |
| [getDither()](#getDither--) | इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getFillType()](#getFillType--) | फ़िल प्रकार। |
| [getGradient()](#getGradient--) | विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है। |
| [getGradientType()](#getGradientType--) | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| [getHorizontalOffset()](#getHorizontalOffset--) | प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [getInterpolationMethod()](#getInterpolationMethod--) | ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है। |
| [getReverse()](#getReverse--) | इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getScale()](#getScale--) | **normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है |
| [getVerticalOffset()](#getVerticalOffset--) | प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | मान परिवर्तन को ट्रिगर करता है। |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setAngle(double value)](#setAngle-double-) | कोण प्राप्त करता है या सेट करता है। |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | ग्रेडिएंट की स्थिति को सही ढंग से गणना करने के लिए लेयर कंटेनर की सीमाएँ प्राप्त करता है या सेट करता है। |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | निर्दिष्ट denormalized स्केल (UI) मान को उसके **normalized** समतुल्य में बदलता है और इसे Scale को असाइन करता है ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है। |
| [setGradientType(int value)](#setGradientType-int-) | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है। |
| [setReverse(boolean value)](#setReverse-boolean-) | इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setScale(int value)](#setScale-int-) | **normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


निम्नलिखित [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) क्लास का नया उदाहरण आरंभ करता है।

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि [align with layer]; अन्यथा,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


कोण प्राप्त करता है या सेट करता है।

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


ग्रेडिएंट की स्थिति को सही ढंग से गणना करने के लिए लेयर कंटेनर की सीमाएँ प्राप्त करता है या सेट करता है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


वर्तमान Scale मान के अनुरूप **denormalized** ग्रेडिएंट स्केल (UI Scale) की गणना करता है और लौटाता है ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | ग्रेडिएंट की सीमाएँ। |

**Returns:**
int - Photoshop में प्रदर्शित denormalized (UI) स्केल प्रतिशत में।
### getDither() {#getDither--}
```
public final boolean getDither()
```


इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि डिथर है तो true; अन्यथा false।

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


फ़िल प्रकार।

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है।

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

मान: ग्रेडिएंट का प्रकार।

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है।

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि रिवर्स है तो true; अन्यथा false।

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


**normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


मान परिवर्तन को ट्रिगर करता है।

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि [align with layer]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


कोण प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


ग्रेडिएंट की स्थिति को सही ढंग से गणना करने के लिए लेयर कंटेनर की सीमाएँ प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


निर्दिष्ट denormalized स्केल (UI) मान को उसके **normalized** समतुल्य में बदलता है और इसे Scale को असाइन करता है ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). परिवर्तन ग्रेडिएंट\\u2019s वर्तमान Angle ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) और प्रदान किए गए fillArea को लागू करके सामान्यीकरण कारक की गणना करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | Photoshop द्वारा प्रदर्शित denormalized स्केल, UI Scale प्रतिशत में; |
| fillArea | [Size](../../com.aspose.psd/size) | ग्रेडिएंट की सीमाएँ। |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का डिथर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि डिथर है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

मान: ग्रेडिएंट का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


प्रतिशत में क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


इस [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) का रिवर्स है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि रिवर्स है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


**normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


प्रतिशत में लंबवत ऑफ़सेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

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


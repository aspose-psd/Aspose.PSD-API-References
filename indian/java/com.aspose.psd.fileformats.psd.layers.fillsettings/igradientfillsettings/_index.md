---
title: "IGradientFillSettings"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्रेडिएंट फ़िल सेटिंग्स के लिए बेस इंटरफ़ेस।"
type: docs
weight: 23
url: /hi/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

ग्रेडिएंट फ़िल सेटिंग्स के लिए बेस इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getAngle()](#getAngle--) | कोण प्राप्त करता है या सेट करता है। |
| [getDither()](#getDither--) | इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का डिथर होना दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getGradient()](#getGradient--) | विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है। |
| [getGradientType()](#getGradientType--) | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| [getHorizontalOffset()](#getHorizontalOffset--) | क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है। |
| [getInterpolationMethod()](#getInterpolationMethod--) | ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है। |
| [getReverse()](#getReverse--) | इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का रिवर्स होना दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getScale()](#getScale--) | **normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है। |
| [getVerticalOffset()](#getVerticalOffset--) | ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है। |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setAngle(double value)](#setAngle-double-) | कोण प्राप्त करता है या सेट करता है। |
| [setDither(boolean value)](#setDither-boolean-) | इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का डिथर होना दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है। |
| [setGradientType(int value)](#setGradientType-int-) | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है। |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है। |
| [setReverse(boolean value)](#setReverse-boolean-) | इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का रिवर्स होना दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setScale(int value)](#setScale-int-) | **normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है। |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है। |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि [align with layer]; अन्यथा,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


कोण प्राप्त करता है या सेट करता है।

मान: कोण।

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का डिथर होना दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि डिथर है तो true; अन्यथा false।

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है।

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

मान: ग्रेडिएंट का प्रकार।

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है।

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का रिवर्स होना दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि रिवर्स है तो true; अन्यथा false।

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


**normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है।

मान: स्केल।

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


लेयर के साथ [align with layer] है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि [align with layer]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


कोण प्राप्त करता है या सेट करता है।

मान: कोण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का डिथर होना दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि डिथर है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


विशिष्ट ग्रेडिएंट परिभाषा उदाहरण (Solid/Noise) प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है।

मान: ग्रेडिएंट का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है।

मान: क्षैतिज ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


इस [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) का रिवर्स होना दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: यदि रिवर्स है तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


**normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है।

मान: स्केल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


ऊर्ध्वाधर ऑफसेट प्राप्त करता है या सेट करता है।

मान: लंबवत ऑफ़सेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |


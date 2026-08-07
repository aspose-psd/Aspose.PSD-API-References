---
title: "ILayerEffect"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लेयर इफ़ेक्ट्स के लिए इंटरफ़ेस"
type: docs
weight: 20
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

लेयर इफ़ेक्ट्स के लिए इंटरफ़ेस
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है। |
| [getEffectType()](#getEffectType--) | इफ़ेक्ट का प्रकार प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | अपेक्षिता को प्राप्त करता है या सेट करता है जहाँ 255 = 100%। |
| [isVisible()](#isVisible--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [setBlendMode(long value)](#setBlendMode-long-) | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [setOpacity(byte value)](#setOpacity-byte-) | अपेक्षिता को प्राप्त करता है या सेट करता है जहाँ 255 = 100%। |
| [setVisible(boolean value)](#setVisible-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


ब्लेंड मोड को प्राप्त करता है या सेट करता है।

मान: ब्लेंड मोड।

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | लेयर पिक्सेल सीमाएँ। |
| globalAngle | int | वैश्विक प्रकाश कोण की गणना के लिए वैश्विक कोण। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


इफ़ेक्ट का प्रकार प्राप्त करता है।

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


अपेक्षिता को प्राप्त करता है या सेट करता है जहाँ 255 = 100%।

मान: अपारदर्शिता।

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं।

मान:  true  यदि यह इंस्टेंस दृश्यमान है; अन्यथा,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


ब्लेंड मोड को प्राप्त करता है या सेट करता है।

मान: ब्लेंड मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


अपेक्षिता को प्राप्त करता है या सेट करता है जहाँ 255 = 100%।

मान: अपारदर्शिता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं।

मान:  true  यदि यह इंस्टेंस दृश्यमान है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |


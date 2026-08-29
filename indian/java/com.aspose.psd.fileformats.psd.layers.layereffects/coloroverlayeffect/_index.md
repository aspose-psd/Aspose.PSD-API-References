---
title: "ColorOverlayEffect"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "कलर ओवरले लेयर इफ़ेक्ट"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class ColorOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

कलर ओवरले लेयर इफ़ेक्ट
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | रंग प्राप्त करता है या सेट करता है। |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है। |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | इकाई प्राप्त करता है। |
| [getEffectType()](#getEffectType--) | इफ़ेक्ट का प्रकार प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | अपारदर्शिता को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | रंग प्राप्त करता है या सेट करता है। |
| [setOpacity(byte value)](#setOpacity-byte-) | अपारदर्शिता को प्राप्त करता है या सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static ColorOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


ब्लेंड मोड को प्राप्त करता है या सेट करता है।

मान: ब्लेंड मोड।

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


रंग प्राप्त करता है या सेट करता है।

मान: रंग।

**Returns:**
[Color](../../com.aspose.psd/color)
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | लेयर पिक्सेल सीमाएँ। |
| globalAngle | int | वैश्विक प्रकाश कोण की गणना के लिए वैश्विक कोण। |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


इकाई प्राप्त करता है।

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


इफ़ेक्ट का प्रकार प्राप्त करता है।

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


अपारदर्शिता को प्राप्त करता है या सेट करता है।

मान: अपारदर्शिता।

**Returns:**
byte
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं।

मान:  true  यदि यह इंस्टेंस दृश्यमान है; अन्यथा,  false .

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


ब्लेंड मोड को प्राप्त करता है या सेट करता है।

मान: ब्लेंड मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


रंग प्राप्त करता है या सेट करता है।

मान: रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


अपारदर्शिता को प्राप्त करता है या सेट करता है।

मान: अपारदर्शिता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं।

मान:  true  यदि यह इंस्टेंस दृश्यमान है; अन्यथा,  false .

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


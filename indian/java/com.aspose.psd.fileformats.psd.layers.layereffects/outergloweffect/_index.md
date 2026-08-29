---
title: "OuterGlowEffect"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "आउटर ग्लो लेयर इफ़ेक्ट"
type: docs
weight: 15
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

आउटर ग्लो लेयर इफ़ेक्ट
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | इनपुट लेयर पिक्सेल सीमाओं के आधार पर इफ़ेक्ट पिक्सेल की सीमाओं की गणना करता है और प्राप्त करता है। |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | इकाई प्राप्त करता है। |
| [getEffectType()](#getEffectType--) | इफ़ेक्ट प्रकार प्राप्त करता है |
| [getFillColor()](#getFillColor--) | रंग प्राप्त करता है या सेट करता है। |
| [getIntensity()](#getIntensity--) | डिग्री में कोण प्राप्त करता है या सेट करता है। |
| [getJitter()](#getJitter--) | शोर प्राप्त करता है या सेट करता है। |
| [getNoise()](#getNoise--) | शोर प्राप्त करता है या सेट करता है। |
| [getOpacity()](#getOpacity--) | अपारदर्शिता को प्राप्त करता है या सेट करता है। |
| [getRange()](#getRange--) | शोर प्राप्त करता है या सेट करता है। |
| [getSize()](#getSize--) | पिक्सेल में ब्लर मान प्राप्त करता है। |
| [getSpread()](#getSpread--) | प्रतिशत के रूप में तीव्रता प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | सक्षम AntiAliasing इफ़ेक्ट को प्राप्त करता है या सेट करता है |
| [isSoftBlend()](#isSoftBlend--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [knocks out]। |
| [isVisible()](#isVisible--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | सक्षम AntiAliasing इफ़ेक्ट को प्राप्त करता है या सेट करता है |
| [setBlendMode(long value)](#setBlendMode-long-) | ब्लेंड मोड को प्राप्त करता है या सेट करता है। |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | रंग प्राप्त करता है या सेट करता है। |
| [setIntensity(int value)](#setIntensity-int-) | डिग्री में कोण प्राप्त करता है या सेट करता है। |
| [setJitter(int value)](#setJitter-int-) | शोर प्राप्त करता है या सेट करता है। |
| [setNoise(int value)](#setNoise-int-) | शोर प्राप्त करता है या सेट करता है। |
| [setOpacity(byte value)](#setOpacity-byte-) | अपारदर्शिता को प्राप्त करता है या सेट करता है। |
| [setRange(int value)](#setRange-int-) | शोर प्राप्त करता है या सेट करता है। |
| [setSize(int value)](#setSize-int-) | पिक्सेल में ब्लर मान प्राप्त करता है। |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [knocks out]। |
| [setSpread(int value)](#setSpread-int-) | प्रतिशत के रूप में तीव्रता प्राप्त करता है या सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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


इफ़ेक्ट प्रकार प्राप्त करता है

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


रंग प्राप्त करता है या सेट करता है।

मान: रंग।

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


डिग्री में कोण प्राप्त करता है या सेट करता है।

मान: कोण।

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


शोर प्राप्त करता है या सेट करता है।

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


शोर प्राप्त करता है या सेट करता है।

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
### getRange() {#getRange--}
```
public final int getRange()
```


शोर प्राप्त करता है या सेट करता है।

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


पिक्सेल में ब्लर मान प्राप्त करता है।

मान: आकार।

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


प्रतिशत के रूप में तीव्रता प्राप्त करता है या सेट करता है।

मान: प्रसार।

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


सक्षम AntiAliasing इफ़ेक्ट को प्राप्त करता है या सेट करता है

मान: दूरी।

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [knocks out]।

मान:  true  यदि [नॉक आउट करता है]; अन्यथा,  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


सक्षम AntiAliasing इफ़ेक्ट को प्राप्त करता है या सेट करता है

मान: दूरी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


रंग प्राप्त करता है या सेट करता है।

मान: रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


डिग्री में कोण प्राप्त करता है या सेट करता है।

मान: कोण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


शोर प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


शोर प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


शोर प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


पिक्सेल में ब्लर मान प्राप्त करता है।

मान: आकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [knocks out]।

मान:  true  यदि [नॉक आउट करता है]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


प्रतिशत के रूप में तीव्रता प्राप्त करता है या सेट करता है।

मान: प्रसार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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


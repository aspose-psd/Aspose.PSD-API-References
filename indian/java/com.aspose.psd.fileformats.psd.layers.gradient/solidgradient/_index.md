---
title: "SolidGradient"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्रेडिएंट फ़िल इफ़ेक्ट सेटिंग्स।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

ग्रेडिएंट फ़िल इफ़ेक्ट सेटिंग्स।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | एक नया उदाहरण प्रारंभ करता है [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) वर्ग का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | रंग बिंदु जोड़ता है। |
| [addTransparencyPoint()](#addTransparencyPoint--) | रंग बिंदु जोड़ता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | LFX2 संसाधन नोड्स उत्पन्न करता है। |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | रंग बिंदुओं को प्राप्त करता है या सेट करता है। |
| [getGradientMode()](#getGradientMode--) | इस ग्रेडिएंट के लिए मोड प्राप्त करता है। |
| [getGradientName()](#getGradientName--) | ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है। |
| [getInterpolation()](#getInterpolation--) | इंटरपोलेशन को प्राप्त करता है या सेट करता है। |
| [getTransparencyPoints()](#getTransparencyPoints--) | पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | रंग बिंदु हटाता है। |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | पारदर्शिता बिंदु हटाता है। |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | रंग बिंदुओं को प्राप्त करता है या सेट करता है। |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है। |
| [setInterpolation(short value)](#setInterpolation-short-) | इंटरपोलेशन को प्राप्त करता है या सेट करता है। |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


एक नया उदाहरण प्रारंभ करता है [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) वर्ग का।

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


रंग बिंदु जोड़ता है।

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


रंग बिंदु जोड़ता है।

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


LFX2 संसाधन नोड्स उत्पन्न करता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - उत्पन्न सूची [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


रंग बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रंग बिंदु।

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


इस ग्रेडिएंट के लिए मोड प्राप्त करता है। निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)।

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है।

Value: ग्रेडिएंट का नाम।

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


इंटरपोलेशन को प्राप्त करता है या सेट करता है। जब 'Gradient Type' = 'Solid' हो तो स्मूदनेस निर्धारित करता है। मान सीमा: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है।

मान: पारदर्शिता बिंदु।

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


रंग बिंदु हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | बिंदु। |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


पारदर्शिता बिंदु हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | बिंदु। |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


रंग बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रंग बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है।

Value: ग्रेडिएंट का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


इंटरपोलेशन को प्राप्त करता है या सेट करता है। जब 'Gradient Type' = 'Solid' हो तो स्मूदनेस निर्धारित करता है। मान सीमा: 0-4096.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है।

मान: पारदर्शिता बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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


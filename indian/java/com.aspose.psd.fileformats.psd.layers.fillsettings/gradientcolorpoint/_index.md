---
title: "GradientColorPoint"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्रेडिएंट रंग बिंदु।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint)
```
public class GradientColorPoint implements IGradientColorPoint
```

ग्रेडिएंट रंग बिंदु।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GradientColorPoint()](#GradientColorPoint--) | एक नया उदाहरण प्रारंभ करता है [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) क्लास का। |
| [GradientColorPoint(Color color, int location, int medianPointLocation)](#GradientColorPoint-com.aspose.psd.Color-int-int-) | एक नया उदाहरण प्रारंभ करता है [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(GradientColorPointEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | रंग को अनुसरण करने के लिए Mode |
| [getLocation()](#getLocation--) | प्राप्त करता है या सेट करता है point location on gradient. |
| [getMedianPointLocation()](#getMedianPointLocation--) | प्राप्त करता है या सेट करता है median gradient point location. |
| [getRawColor()](#getRawColor--) | कच्चे का रंग प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorMode(short value)](#setColorMode-short-) | रंग को अनुसरण करने के लिए Mode |
| [setLocation(int value)](#setLocation-int-) | प्राप्त करता है या सेट करता है point location on gradient. |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | प्राप्त करता है या सेट करता है median gradient point location. |
| [setRawColor(RawColor value)](#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | कच्चे का रंग प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientColorPoint() {#GradientColorPoint--}
```
public GradientColorPoint()
```


एक नया उदाहरण प्रारंभ करता है [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) क्लास का।

### GradientColorPoint(Color color, int location, int medianPointLocation) {#GradientColorPoint-com.aspose.psd.Color-int-int-}
```
public GradientColorPoint(Color color, int location, int medianPointLocation)
```


एक नया उदाहरण प्रारंभ करता है [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Gradient पर Color point. |
| location | int | Gradient पर color point का स्थान. |
| medianPointLocation | int | median gradient point का स्थान. |

### create_internalized(GradientColorPointEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-}
```
public static GradientColorPoint create_internalized(GradientColorPointEntity entity)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity |  |

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint)
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


रंग को अनुसरण करने के लिए Mode

**Returns:**
short
### getLocation() {#getLocation--}
```
public final int getLocation()
```


प्राप्त करता है या सेट करता है point location on gradient.

मान: स्थान।

**Returns:**
int
### getMedianPointLocation() {#getMedianPointLocation--}
```
public final int getMedianPointLocation()
```


प्राप्त करता है या सेट करता है median gradient point location.

मान: मध्य बिंदु स्थान।

**Returns:**
int
### getRawColor() {#getRawColor--}
```
public final RawColor getRawColor()
```


कच्चे का रंग प्राप्त करता है या सेट करता है।

मान: कच्चे का रंग।

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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




### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


रंग को अनुसरण करने के लिए Mode

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setLocation(int value) {#setLocation-int-}
```
public final void setLocation(int value)
```


प्राप्त करता है या सेट करता है point location on gradient.

मान: स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMedianPointLocation(int value) {#setMedianPointLocation-int-}
```
public final void setMedianPointLocation(int value)
```


प्राप्त करता है या सेट करता है median gradient point location.

मान: मध्य बिंदु स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRawColor(RawColor value) {#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setRawColor(RawColor value)
```


कच्चे का रंग प्राप्त करता है या सेट करता है।

मान: कच्चे का रंग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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


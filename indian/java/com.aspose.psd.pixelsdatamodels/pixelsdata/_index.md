---
title: "PixelsData"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इमेज पिक्सेल डेटा और उसके बाउंड्स को स्टोर करने के लिए क्लास।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

इमेज पिक्सेल डेटा और उसके बाउंड्स को स्टोर करने के लिए क्लास।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PixelsData()](#PixelsData--) | नए [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | नए [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | वर्तमान [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) उदाहरण के लिए PixelsDataLoader इंस्टेंस बनाता है। |
| [createSaver_internalized()](#createSaver-internalized--) | वर्तमान [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) उदाहरण के लिए PixelsDataSaver इंस्टेंस बनाता है। |
| [deepClone()](#deepClone--) | यह उदाहरण की पूरी कॉपी बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | पिक्सेल डेटा की सीमाओं को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | पिक्सेल डेटा को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | पिक्सेल डेटा की सीमाओं को प्राप्त करता है या सेट करता है। |
| [setPixels(int[] value)](#setPixels-int---) | पिक्सेल डेटा को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


नए [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) क्लास का एक नया उदाहरण प्रारंभ करता है।

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


नए [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पिक्सेल | int[] | पिक्सेल डेटा। |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | पिक्सेल सीमाओं का आयत। |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


वर्तमान [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) उदाहरण के लिए PixelsDataLoader इंस्टेंस बनाता है।

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


वर्तमान [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) उदाहरण के लिए PixelsDataSaver इंस्टेंस बनाता है।

**Returns:**
com.aspose.internal.IPixelsSaver - वर्तमान [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) उदाहरण के आधार पर PixelsDataSaver का नया इंस्टेंस।
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


यह उदाहरण की पूरी कॉपी बनाता है।

**Returns:**
java.lang.Object - उदाहरण की कॉपी।
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


पिक्सेल डेटा की सीमाओं को प्राप्त करता है या सेट करता है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


पिक्सेल डेटा को प्राप्त करता है या सेट करता है।

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


पिक्सेल डेटा की सीमाओं को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


पिक्सेल डेटा को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

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


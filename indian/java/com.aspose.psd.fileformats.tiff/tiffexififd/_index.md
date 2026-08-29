---
title: "TiffExifIfd"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "TIFF Exif इमेज फ़ाइल डायरेक्टरी क्लास।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif इमेज फ़ाइल डायरेक्टरी क्लास।

Exif IFD के एक पॉइंटर को संलग्न करता है। Interoperability, Exif IFD का वही संरचना है जैसा कि TIFF में निर्दिष्ट IFD की है। सामान्यतः, हालांकि, इसमें TIFF के मामले की तरह इमेज डेटा नहीं होता। अधिक विवरण के लिए http://www.exiv2.org/tags.html और http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html देखें।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | TiffExifIfd क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | TiffExifIfd क्लास का नया इंस्टेंस प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है। |
| [hasValue()](#hasValue--) | यह संकेत करने वाला मान प्राप्त करता है कि इस इंस्टेंस में मान है या नहीं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


TiffExifIfd क्लास का नया इंस्टेंस प्रारंभ करता है।

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


TiffExifIfd क्लास का नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | ifdOffset | long | Exif IFD की एक पॉइंटर। |

Interoperability, Exif IFD का वही संरचना है जैसा कि TIFF में निर्दिष्ट IFD की है। सामान्यतः, हालांकि, इसमें TIFF के मामले की तरह इमेज डेटा नहीं होता। |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है।

**Returns:**
long - EXIF IFD के पॉइंटर।
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


यह संकेत करने वाला मान प्राप्त करता है कि इस इंस्टेंस में मान है या नहीं।

**Returns:**
boolean - true यदि इस इंस्टेंस में मान है; अन्यथा, false।
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




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


EXIF IFD के पॉइंटर को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | EXIF IFD का पॉइंटर। |

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


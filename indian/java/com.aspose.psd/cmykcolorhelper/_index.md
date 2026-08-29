---
title: "CmykColorHelper"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "साइन किए गए 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग के साथ काम करने के लिए सहायक विधियाँ।"
type: docs
weight: 18
url: /hi/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

CMYK रंग के साथ काम करने के लिए सहायक विधियाँ, जो एक साइन किए गए 32-बिट पूर्णांक मान के रूप में प्रस्तुत की गई हैं। यह com.aspose.psd.CmykColor स्ट्रक्ट के समान API प्रदान करती है। यह अधिक हल्की है क्योंकि CMYK रंग को केवल Int32 के रूप में प्रस्तुत किया जाता है, न कि आंतरिक फ़ील्ड वाले स्ट्रक्ट के रूप में। कृपया संभव हो तो इस क्लास की स्थैतिक विधियों का उपयोग करें, बजाय डिप्रिकेटेड com.aspose.psd.CmykColor स्ट्रक्ट के।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से CMYK बनाता है। |
| [getC(int cmyk)](#getC-int-) | सियान घटक का मान प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | ब्लैक घटक का मान प्राप्त करता है। |
| [getM(int cmyk)](#getM-int-) | मैजेंटा घटक का मान प्राप्त करता है। |
| [getY(int cmyk)](#getY-int-) | येलो घटक का मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | CMYK रंग से ARGB रंग में रूपांतरण। |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | CMYK color से ARGB Color में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | CMYK color से ARGB color में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | CMYK रंगों से ARGB रंगों में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | CMYK रंगों से ARGB रंगों में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | ARGB रंग से CMYK रंग में रूपांतरण। |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [toCmyk(int argbPixel)](#toCmyk-int-) | ARGB रंग से CMYK रंग में रूपांतरण। |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | RGB को CMYK में परिवर्तित करता है। |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | ARGB रंग से CMYK रंग में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | ARGB रंग से CMYK रंग में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | ARGB रंगों से CMYK रंगों में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | ARGB रंगों से CMYK रंगों में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण। |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | RGB को CMYK में कस्टम ICC प्रोफ़ाइल का उपयोग करके परिवर्तित करता है। |
| [toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से CMYK बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सियान | int | सियान घटक। मान्य मान 0 से 255 तक हैं। |
| मैजेंटा | int | मैजेंटा घटक। मान्य मान 0 से 255 तक हैं। |
| पीला | int | पीला घटक। मान्य मान 0 से 255 तक हैं। |
| ब्लैक | int | ब्लैक घटक। मान्य मान 0 से 255 तक हैं। |

**Returns:**
int - 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग।
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


सियान घटक का मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmyk | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
int - सियान घटक मान।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


ब्लैक घटक का मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmyk | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
int - ब्लैक घटक मान।
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


मैजेंटा घटक का मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmyk | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
int - मैजेंटा घटक मान।
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


येलो घटक का मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmyk | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
int - पीला घटक मान।
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




### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


CMYK रंग से ARGB रंग में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
com.aspose.psd.Color[] - ARGB रंग।
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
int[] - 32-बिट पूर्णांक मानों के रूप में प्रस्तुत ARGB रंग।
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


CMYK color से ARGB Color में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYK color से ARGB color में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग। |
| cmykIccStream | java.io.InputStream | CMYK Icc प्रोफ़ाइल युक्त स्ट्रीम। |
| rgbIccStream | java.io.InputStream | RGB Icc प्रोफ़ाइल युक्त स्ट्रीम। |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


CMYK रंगों से ARGB रंगों में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK पिक्सेल। |

**Returns:**
com.aspose.psd.Color[] - ARGB रंग।
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


CMYK रंगों से ARGB रंगों में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग। |
| cmykIccStream | java.io.InputStream | CMYK Icc प्रोफ़ाइल युक्त स्ट्रीम। |
| rgbIccStream | java.io.InputStream | RGB Icc प्रोफ़ाइल युक्त स्ट्रीम। |

**Returns:**
com.aspose.psd.Color[] - ARGB रंग।
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


ARGB रंग से CMYK रंग में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB रंग। |

**Returns:**
int - 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग।
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB रंग। |

**Returns:**
int[] - 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग।
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


ARGB रंग से CMYK रंग में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argbPixel | int | 32-बिट पूर्णांक मान के रूप में प्रस्तुत ARGB रंग। |

**Returns:**
int - 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग।
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argbPixels | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत ARGB रंग। |

**Returns:**
int[] - 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग।
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


RGB को CMYK में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argbPixels | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत RGB रंग। |
| startIndex | int | RGB रंग का प्रारंभिक सूचकांक। |
| लंबाई | int | परिवर्तित करने के लिए RGB पिक्सेल की संख्या। |

**Returns:**
byte[] - बाइट एरे के रूप में प्रस्तुत CMYK रंग।
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


ARGB रंग से CMYK रंग में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB रंग। |

**Returns:**
int - 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग।
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB रंग से CMYK रंग में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB रंग। |
| rgbIccStream | java.io.InputStream | RGB Icc प्रोफ़ाइल युक्त स्ट्रीम। |
| cmykIccStream | java.io.InputStream | CMYK Icc प्रोफ़ाइल युक्त स्ट्रीम। |

**Returns:**
int - 32-बिट पूर्णांक मान के रूप में प्रस्तुत CMYK रंग।
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


ARGB रंगों से CMYK रंगों में Icc रूपांतरण के साथ डिफ़ॉल्ट प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB रंग। |

**Returns:**
int[] - 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग।
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


ARGB रंगों से CMYK रंगों में Icc रूपांतरण के साथ कस्टम प्रोफ़ाइल का उपयोग करके रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB रंग। |
| rgbIccStream | java.io.InputStream | RGB Icc प्रोफ़ाइल युक्त स्ट्रीम। |
| cmykIccStream | java.io.InputStream | CMYK Icc प्रोफ़ाइल युक्त स्ट्रीम। |

**Returns:**
int[] - 32-बिट पूर्णांक मानों के रूप में प्रस्तुत CMYK रंग।
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


RGB को CMYK में कस्टम ICC प्रोफ़ाइल का उपयोग करके परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पिक्सेल | int[] | 32-बिट पूर्णांक मानों के रूप में प्रस्तुत RGB रंग। |
| startIndex | int | RGB रंग का प्रारंभिक सूचकांक। |
| लंबाई | int | परिवर्तित करने के लिए RGB पिक्सेल की संख्या। |
| rgbIccStream | java.io.InputStream | RGB प्रोफ़ाइल स्ट्रीम। |
| cmykIccStream | java.io.InputStream | CMYK प्रोफ़ाइल स्ट्रीम। |

**Returns:**
byte[] - बाइट एरे के रूप में प्रस्तुत CMYK रंग।
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पिक्सेल | int[] |  |
| startIndex | int |  |
| लंबाई | int |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
byte[]
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


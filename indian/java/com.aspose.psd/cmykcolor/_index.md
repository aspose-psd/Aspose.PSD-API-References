---
title: "CmykColor"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "पिक्सेल का CMYK रंग।"
type: docs
weight: 17
url: /hi/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

पिक्सेल का CMYK रंग।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | एक  CmykColor  संरचना बनाता है 32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से। |
| [getC()](#getC--) | इस  com.aspose.psd.Color  संरचना का स्यान घटक मान प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | खाली प्राप्त करता है। |
| [getK()](#getK--) | इस  com.aspose.psd.Color  संरचना का काला घटक मान प्राप्त करता है। |
| [getM()](#getM--) | इस  com.aspose.psd.Color  संरचना का मैजेंटा घटक मान प्राप्त करता है। |
| [getY()](#getY--) | इस  com.aspose.psd.Color  संरचना का पीला घटक मान प्राप्त करता है। |
| [hashCode()](#hashCode--) | हैश कोड प्राप्त करता है। |
| [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि यह  com.aspose.psd.Color  संरचना अपरिभाषित है या नहीं। |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ icc रूपांतरण का उपयोग करके CMYKColor से 32-बिट ARGB Color में रूपांतरण। |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 32-बिट ARGB से CMYKColor में रूपांतरण। |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 32-बिट ARGB रंग से CMYKColor में रूपांतरण। |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | CMYKColor से Color में रूपांतरण। |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | to मान। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


एक  CmykColor  संरचना 32-बिट स्यान, मैजेंटा, पीला और काला मानों से बनाता है। यह विधि अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper\#fromComponents(int, int, int, int) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सियान | int | सियान घटक। मान्य मान 0 से 255 तक हैं। |
| मैजेंटा | int | मैजेंटा घटक। मान्य मान 0 से 255 तक हैं। |
| पीला | int | पीला घटक। मान्य मान 0 से 255 तक हैं। |
| ब्लैक | int | ब्लैक घटक। मान्य मान 0 से 255 तक हैं। |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


इस  com.aspose.psd.Color  संरचना का स्यान घटक मान प्राप्त करता है।

**Returns:**
byte - इस  com.aspose.psd.Color  का स्यान घटक मान।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


खाली प्राप्त करता है।

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


इस  com.aspose.psd.Color  संरचना का काला घटक मान प्राप्त करता है।

मान: इस  com.aspose.psd.Color  का काला घटक मान।

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


इस  com.aspose.psd.Color  संरचना का मैजेंटा घटक मान प्राप्त करता है।

**Returns:**
byte - इस  com.aspose.psd.Color  का मैजेंटा घटक मान।
### getY() {#getY--}
```
public byte getY()
```


इस  com.aspose.psd.Color  संरचना का पीला घटक मान प्राप्त करता है।

**Returns:**
byte - इस  com.aspose.psd.Color  का पीला घटक मान।
### hashCode() {#hashCode--}
```
public int hashCode()
```


हैश कोड प्राप्त करता है।

**Returns:**
int - यह  int .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह  com.aspose.psd.Color  संरचना अपरिभाषित है या नहीं।

**Returns:**
boolean - यह प्रॉपर्टी true लौटाती है यदि यह रंग प्रारंभ नहीं किया गया है; अन्यथा false।
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

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




### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.psd.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


डिफ़ॉल्ट प्रोफ़ाइलों के साथ icc रूपांतरण का उपयोग करके CMYKColor से 32-बिट ARGB Color में रूपांतरण। यह विधि अप्रचलित है। कृपया अधिक प्रभावी  CmykColorHelper.toArgb32(int[]) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार के पिक्सेल। |

**Returns:**
int[] - 32-बिट ARGB रंग की सरणी।
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


32-बिट ARGB से CMYKColor में रूपांतरण। यह विधि अप्रचलित है। कृपया अधिक प्रभावी  CmykColorHelper.toCmyk(int) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argbPixel | int | 32-बिट ARGB फ़ॉर्मेट का पिक्सेल। |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


32-बिट ARGB रंग से CMYKColor में रूपांतरण। यह विधि अप्रचलित है। कृपया अधिक प्रभावी  CmykColorHelper.toCmyk(int[]) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argbPixels | int[] | 32-बिट ARGB फ़ॉर्मेट के पिक्सेल। |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[]।
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


CMYKColor से Color में रूपांतरण। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper.toArgb(int) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार के पिक्सेल। |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper.toArgb(int[]) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार के पिक्सेल। |

**Returns:**
com.aspose.psd.Color[] - ARGB रंगों की एरे।
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper.toArgbIcc(int) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार का पिक्सेल। |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper.toArgbIcc(int, Stream, Stream) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार का पिक्सेल। |
| cmykIccStream | java.io.InputStream | icc cmyk प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| rgbIccStream | java.io.InputStream | icc rgb प्रोफ़ाइल को शामिल करने वाला स्ट्रीम। |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper\\#toArgbIcc(int[]) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार के पिक्सेल। |

**Returns:**
com.aspose.psd.Color[] - com.aspose.psd.Color[]।
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार के पिक्सेल। |
| cmykIccStream | java.io.InputStream | icc cmyk प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| rgbIccStream | java.io.InputStream | icc rgb प्रोफ़ाइल को शामिल करने वाला स्ट्रीम। |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[]।
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार का पिक्सेल। |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb प्रोफ़ाइल को शामिल करने वाला स्ट्रीम। |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK फ़ॉर्मेट में CMYKColor प्रकार के पिक्सेल। |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb प्रोफ़ाइल को शामिल करने वाला स्ट्रीम। |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[]।
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toValue() {#toValue--}
```
public long toValue()
```


to मान।

**Returns:**
long - long।
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


---
title: "RawColorHelper"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Raw Color Helper Class तेज़ी से RawColor बनाने में मदद करता है, पूर्वनिर्धारित चैनल मेटाडेटा का उपयोग करके।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class तेज़ी से RawColor बनाने में मदद करता है, पूर्वनिर्धारित चैनल मेटाडाटा का उपयोग करके।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | प्रति चैनल 16-बिट ARGB रंग बनाता है। |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | प्रति चैनल 8-बिट ARGB रंग बनाता है। |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Drawing.Color से प्रति चैनल 8-बिट ARGB रंग बनाता है। |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | प्रति चैनल 16-बिट CMYK रंग बनाता है। |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | प्रति चैनल 8-बिट CMYK रंग बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


प्रति चैनल 16-बिट ARGB रंग बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| एक | int | अल्फा घटक मान (0-65535)। |
| r | int | लाल घटक मान (0-65535)। |
| g | int | हरा घटक मान (0-65535)। |
|  | बी | int | नीला घटक मान (0-65535)। |

--------------------

रंग घटकों को 64-बिट पूर्णांक में इस क्रम में पैक किया जाता है: अल्फा (बिट 48-63), लाल (बिट 32-47), हरा (बिट 16-31), और नीला (बिट 0-15)। |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


प्रति चैनल 8-बिट ARGB रंग बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| एक | byte | अल्फा घटक मान (0-255)। |
| r | byte | लाल घटक मान (0-255)। |
| g | byte | हरा घटक मान (0-255)। |
|  | बी | byte | नीला घटक मान (0-255)। |

--------------------

रंग घटकों को 32-बिट पूर्णांक में इस क्रम में पैक किया जाता है: अल्फा (बिट 24-31), लाल (बिट 16-23), हरा (बिट 8-15), और नीला (बिट 0-7)। |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Drawing.Color से प्रति चैनल 8-बिट ARGB रंग बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | यह System.Drawing Color |

--------------------

रंग घटकों को 32-बिट पूर्णांक में इस क्रम में पैक किया जाता है: अल्फा (बिट 24-31), लाल (बिट 16-23), हरा (बिट 8-15), और नीला (बिट 0-7)। |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


प्रति चैनल 16-बिट CMYK रंग बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | int | सियान घटक मान (0-65535)। |
| m | int | मैजेंटा घटक मान (0-65535). |
| y | int | पीला घटक मान (0-65535). |
|  | k | int | कुंजी (काला) घटक मान (0-65535). |

--------------------

रंग घटकों को 64-बिट पूर्णांक में निम्न क्रम में पैक किया जाता है: सियान (बिट 48-63), मैजेंटा (बिट 32-47), पीला (बिट 16-31), और कुंजी/काला (बिट 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


प्रति चैनल 8-बिट CMYK रंग बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | byte | सियान घटक मान (0-255). |
| m | byte | मैजेंटा घटक मान (0-255). |
| y | byte | पीला घटक मान (0-255). |
|  | k | byte | कुंजी (काला) घटक मान (0-255). |

--------------------

रंग घटकों को 32-बिट पूर्णांक में निम्न क्रम में पैक किया जाता है: सियान (बिट 24-31), मैजेंटा (बिट 16-23), पीला (बिट 8-15), और कुंजी/काला (बिट 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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


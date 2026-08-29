---
title: "RawColorHelper"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تساعد Raw Color Helper Class في إنشاء RawColor بشكل أسرع باستخدام بيانات تعريف القنوات المحددة مسبقًا"
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

فئة Raw Color Helper تساعد على إنشاء RawColor بسرعة أكبر، باستخدام بيانات تعريف القناة المحددة مسبقًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | ينشئ لون ARGB بعمق 16 بت لكل قناة. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | ينشئ لون ARGB بعمق 8 بت لكل قناة. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | ينشئ لون ARGB بعمق 8 بت لكل قناة من Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | ينشئ لون CMYK بعمق 16 بت لكل قناة. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | ينشئ لون CMYK بعمق 8 بت لكل قناة. |
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


ينشئ لون ARGB بعمق 16 بت لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | int | قيمة مكوّن ألفا (0-65535). |
| r | int | قيمة مكوّن الأحمر (0-65535). |
| g | int | قيمة مكوّن الأخضر (0-65535). |
|  | b | int | قيمة مكوّن الأزرق (0-65535). |

--------------------

مكوّنات اللون مُعبأة في عدد صحيح 64‑بت بالترتيب: ألفا (البتات 48-63)، أحمر (البتات 32-47)، أخضر (البتات 16-31)، وأزرق (البتات 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


ينشئ لون ARGB بعمق 8 بت لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | byte | قيمة مكوّن ألفا (0-255). |
| r | byte | قيمة مكوّن الأحمر (0-255). |
| g | byte | قيمة مكوّن الأخضر (0-255). |
|  | b | byte | قيمة مكوّن الأزرق (0-255). |

--------------------

مكوّنات اللون مُعبأة في عدد صحيح 32‑بت بالترتيب: ألفا (البتات 24-31)، أحمر (البتات 16-23)، أخضر (البتات 8-15)، وأزرق (البتات 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


ينشئ لون ARGB بعمق 8 بت لكل قناة من Drawing.Color

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | لون System.Drawing |

--------------------

مكوّنات اللون مُعبأة في عدد صحيح 32‑بت بالترتيب: ألفا (البتات 24-31)، أحمر (البتات 16-23)، أخضر (البتات 8-15)، وأزرق (البتات 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


ينشئ لون CMYK بعمق 16 بت لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | int | قيمة مكوّن السيان (0-65535). |
| m | int | قيمة مكوّن الماجنتا (0-65535). |
| ص | int | قيمة مكوّن الأصفر (0-65535). |
|  | k | int | قيمة المكوّن المفتاح (الأسود) (0-65535). |

--------------------

يتم تجميع مكوّنات اللون في عدد صحيح 64‑بت بالترتيب: cyan (bits 48-63), magenta (bits 32-47), yellow (bits 16-31), و key/black (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


ينشئ لون CMYK بعمق 8 بت لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c | byte | قيمة المكوّن cyan (0-255). |
| m | byte | قيمة المكوّن magenta (0-255). |
| ص | byte | قيمة المكوّن yellow (0-255). |
|  | k | byte | قيمة المكوّن المفتاح (الأسود) (0-255). |

--------------------

يتم تجميع مكوّنات اللون في عدد صحيح 32‑بت بالترتيب: cyan (bits 24-31), magenta (bits 16-23), yellow (bits 8-15), و key/black (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


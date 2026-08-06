---
title: "CmykColorHelper"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح 32-بت موقعة."
type: docs
weight: 18
url: /ar/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح موقعة 32‑بت. توفر واجهة برمجة تطبيقات مشابهة للهيكل com.aspose.psd.CmykColor. إنها أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الثابتة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل المهمل com.aspose.psd.CmykColor.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | ينشئ CMYK من قيم السيان، الماجنتا، الأصفر والأسود ذات 32‑بت. |
| [getC(int cmyk)](#getC-int-) | يحصل على قيمة المكوّن السيان. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | يحصل على قيمة المكوّن الأسود. |
| [getM(int cmyk)](#getM-int-) | يحصل على قيمة المكوّن الماجنتا. |
| [getY(int cmyk)](#getY-int-) | يحصل على قيمة المكوّن الأصفر. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | التحويل من لون CMYK إلى لون ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | التحويل من لون ARGB إلى لون CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | التحويل من لون ARGB إلى لون CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | يحوّل RGB إلى CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


ينشئ CMYK من قيم السيان، الماجنتا، الأصفر والأسود ذات 32‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| سيان | int | المكوّن السماوي. القيم الصالحة هي من 0 إلى 255. |
| ماجنتا | int | المكوّن الأرجواني. القيم الصالحة هي من 0 إلى 255. |
| أصفر | int | المكوّن الأصفر. القيم الصالحة هي من 0 إلى 255. |
| أسود | int | المكوّن الأسود. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
int - لون CMYK مقدم كقيمة عدد صحيح 32-بت.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


يحصل على قيمة المكوّن السيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة المكوّن السماوي.
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


يحصل على قيمة المكوّن الأسود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة المكوّن الأسود.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


يحصل على قيمة المكوّن الماجنتا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة المكوّن الأرجواني.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


يحصل على قيمة المكوّن الأصفر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmyk | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
int - قيمة المكوّن الأصفر.
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


التحويل من لون CMYK إلى لون ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK مقدمة كقيم أعداد صحيحة 32-بت. |

**Returns:**
com.aspose.psd.Color[] - ألوان ARGB.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


التحويل من ألوان CMYK إلى ألوان ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK مقدمة كقيم أعداد صحيحة 32-بت. |

**Returns:**
int[] - ألوان ARGB مقدمة كقيم أعداد صحيحة 32-بت.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixel | int | لون CMYK مقدم كقيمة عدد صحيح 32-بت. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | بكسلات CMYK المعروضة كقيم صحيحة 32-بت. |

**Returns:**
com.aspose.psd.Color[] - ألوان ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmykPixels | int[] | ألوان CMYK مقدمة كقيم أعداد صحيحة 32-بت. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |

**Returns:**
com.aspose.psd.Color[] - ألوان ARGB.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


التحويل من لون ARGB إلى لون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | لون ARGB. |

**Returns:**
int - لون CMYK مقدم كقيمة عدد صحيح 32-بت.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ألوان ARGB. |

**Returns:**
int[] - ألوان CMYK المعروضة كقيم صحيحة 32-بت.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


التحويل من لون ARGB إلى لون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixel | int | لون ARGB المعروض كقيمة صحيحة 32-بت. |

**Returns:**
int - لون CMYK مقدم كقيمة عدد صحيح 32-بت.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | int[] | ألوان ARGB المعروضة كقيم صحيحة 32-بت. |

**Returns:**
int[] - ألوان CMYK المعروضة كقيم صحيحة 32-بت.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


يحوّل RGB إلى CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argbPixels | int[] | ألوان RGB المعروضة كقيم صحيحة 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |

**Returns:**
byte[] - ألوان CMYK المعروضة كمصفوفة بايت.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | لون ARGB. |

**Returns:**
int - لون CMYK مقدم كقيمة عدد صحيح 32-بت.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | لون ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int - لون CMYK مقدم كقيمة عدد صحيح 32-بت.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ألوان ARGB. |

**Returns:**
int[] - ألوان CMYK المعروضة كقيم صحيحة 32-بت.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ألوان ARGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف RGB Icc. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف Icc لـ CMYK. |

**Returns:**
int[] - ألوان CMYK المعروضة كقيم صحيحة 32-بت.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


يحوّل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | ألوان RGB المعروضة كقيم صحيحة 32-بت. |
| startIndex | int | فهرس البداية للون RGB. |
| length | int | عدد بكسلات RGB للتحويل. |
| rgbIccStream | java.io.InputStream | دفق ملف تعريف RGB. |
| cmykIccStream | java.io.InputStream | دفق ملف تعريف CMYK. |

**Returns:**
byte[] - ألوان CMYK المعروضة كمصفوفة بايت.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] |  |
| startIndex | int |  |
| length | int |  |
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


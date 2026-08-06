---
title: "PsdColorPalette"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "لوحة ألوان PSD."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

لوحة ألوان PSD.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | ينسخ اللوحة. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | ينسخ اللوحة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [getArgb32Entries()](#getArgb32Entries--) | يحصل على مصفوفة من ألوان ARGB 32‑بت. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | يحصل على لون اللوحة حسب الفهرس. |
| [getEntries()](#getEntries--) | يحصل على مصفوفة من هياكل [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | يحصل على عدد الإدخالات. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | يحصل على فهرس أقرب لون. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | يحصل على فهرس أقرب لون. |
| [getRawEntries()](#getRawEntries--) | يحصل على بيانات إدخالات لوحة الألوان الخام. |
| [getRawEntriesCount()](#getRawEntriesCount--) | يحصل على عدد إدخالات لوحة الألوان الخام. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على اللون الشفاف. |
| [getTransparentIndex()](#getTransparentIndex--) | يحصل على فهرس اللون الشفاف. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كان اللون الشفاف موجودًا. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | يحصل على قيمة تشير إلى ما إذا كانت اللوحة مضغوطة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |
| transparentIndex | short | مؤشر اللون الشفاف. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rawEntriesData | byte[] | بيانات الإدخالات الخام. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rawEntriesData | byte[] | بيانات الإدخالات الخام. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rawEntriesData | byte[] | بيانات الإدخالات الخام. |
| transparentIndex | short | مؤشر اللون الشفاف. ملاحظة: المؤشر ليس مؤشر الإدخالات الخام بل هو للمصفوفة الملونة المحوّلة. |
| useCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rawEntriesData | byte[] | بيانات الإدخالات الخام. |
| transparentIndex | short | مؤشر اللون الشفاف. ملاحظة: المؤشر ليس مؤشر الإدخالات الخام بل هو للمصفوفة الملونة المحوّلة. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | إدخالات لوحة الألوان 32-بت ARGB. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | إدخالات لوحة الألوان. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | إدخالات لوحة الألوان. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | إدخالات لوحة الألوان. |
| transparentIndex | short | مؤشر اللون الشفاف. |
| useCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


ينشئ مثيلًا جديدًا من الفئة [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) وتكون IsCompactPalette خاطئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | إدخالات لوحة الألوان. |
| transparentIndex | short | مؤشر اللون الشفاف. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


ينسخ اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


ينسخ اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |
| useCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


يحصل على لون لوحة ARGB 32‑بت حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | مؤشر لون لوحة الألوان 32-بت ARGB. |

**Returns:**
int - إدخال لوحة الألوان المحدد بواسطة المؤشر.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


يحصل على مصفوفة من ألوان ARGB 32‑بت.

**Returns:**
int[] - المصفوفة التي تتكون من بنية 32-بت ARGB التي تشكل هذه [ColorPalette](../../com.aspose.psd/colorpalette). القيمة: الإدخالات.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
```


يحصل على لون اللوحة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | مؤشر لون اللوحة. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


يحصل على مصفوفة من هياكل [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - المصفوفة التي تتكون من بنية [Color](../../com.aspose.psd/color) التي تشكل هذه [ColorPalette](../../com.aspose.psd/colorpalette). القيمة: الإدخالات.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


يحصل على عدد الإدخالات.

القيمة: عدد الإدخالات.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


يحصل على فهرس أقرب لون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | اللون. |

**Returns:**
int - مؤشر أقرب لون.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


يحصل على فهرس أقرب لون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Color | int | لون 32-بت ARGB. |

**Returns:**
int - مؤشر أقرب لون.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


يحصل على بيانات إدخالات لوحة الألوان الخام.

القيمة: بيانات إدخالات لوحة الألوان الخام.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


يحصل على عدد إدخالات لوحة الألوان الخام.

القيمة: عدد إدخالات لوحة الألوان الخام.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


يحصل على اللون الشفاف.

القيمة: اللون الشفاف.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


يحصل على فهرس اللون الشفاف.

القيمة: مؤشر اللون الشفاف.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كان اللون الشفاف موجودًا.

القيمة:  true  إذا كان اللون الشفاف موجودًا؛ وإلا،  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


يحصل على قيمة تشير إلى ما إذا كانت اللوحة مضغوطة.

القيمة:  true  إذا كان اللوحة مضغوطة؛ وإلا،  false .

--------------------

اللوحة المضغوطة تعني أن الصورة ستحتوي فقط على مدخلات اللوحة المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر ضغطًا وتستهلك مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات اللوحة الممكنة. ضبط هذه القيمة إلى true وتغيير مدخلات اللوحة قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث لذا استخدمه بحذر.

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


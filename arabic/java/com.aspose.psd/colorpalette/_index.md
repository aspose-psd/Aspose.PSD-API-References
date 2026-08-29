---
title: "لوحة الألوان"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد مصفوفة من الألوان التي تشكل لوحة ألوان."
type: docs
weight: 27
url: /ar/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

يحدد مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32-بت. غير قابل للوراثة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | ينشئ مثيلًا جديدًا من الفئة  ColorPalette . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | ينشئ مثيلًا جديدًا من الفئة  ColorPalette  ويكون IsCompactPalette خاطئًا. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | ينشئ مثيلًا جديدًا من الفئة  ColorPalette . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | ينشئ مثيلًا جديدًا من الفئة  ColorPalette  ويكون IsCompactPalette خاطئًا. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | ينسخ اللوحة. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | ينسخ اللوحة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [getArgb32Entries()](#getArgb32Entries--) | يحصل على مصفوفة من هياكل ARGB 32-بت. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | يحصل على لون اللوحة حسب الفهرس. |
| [getEntries()](#getEntries--) | يحصل على مصفوفة من هياكل  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | يحصل على عدد الإدخالات. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | يحصل على فهرس أقرب لون. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | يحصل على فهرس أقرب لون. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة  ColorPalette .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Entries | int[] | مدخلات لوحة ألوان ARGB 32-بت. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


ينشئ مثيلًا جديدًا من الفئة  ColorPalette  ويكون IsCompactPalette خاطئًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Entries | int[] | مدخلات لوحة ألوان ARGB 32-بت. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


ينشئ مثيلًا جديدًا من الفئة  ColorPalette .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | إدخالات لوحة الألوان. |
| isCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


ينشئ مثيلًا جديدًا من الفئة  ColorPalette  ويكون IsCompactPalette خاطئًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | إدخالات لوحة الألوان. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


ينسخ اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


ينسخ اللوحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | لوحة الألوان. |
| useCompactPalette | boolean | يشير إلى ما إذا كانت اللوحة مضغوطة. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


يحصل على مصفوفة من هياكل ARGB 32-بت.

**Returns:**
int[] - المدخلات. مصفوفة من هياكل ARGB 32-بت التي تشكل هذه  Aspose.Imaging.ColorPalette .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


يحصل على مصفوفة من هياكل  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - الإدخالات. مصفوفة من بنية com.aspose.psd.Color التي تشكل هذه Aspose.Imaging.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


يحصل على عدد الإدخالات.

**Returns:**
int - عدد الإدخالات.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


يحصل على فهرس أقرب لون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Color | int | لون 32-بت ARGB. |

**Returns:**
int - مؤشر أقرب لون.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة.

**Returns:**
boolean -  true  إذا تم استخدام لوحة ألوان مدمجة؛ وإلا،  false .

اللوحة المضغوطة تعني أن الصورة ستحتوي فقط على مدخلات اللوحة المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر ضغطًا وتستهلك مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات اللوحة الممكنة. ضبط هذه القيمة إلى true وتغيير مدخلات اللوحة قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث لذا استخدمه بحذر.
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


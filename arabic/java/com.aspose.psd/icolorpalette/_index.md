---
title: "IColorPalette"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "واجهة لوحة الألوان."
type: docs
weight: 117
url: /ar/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

واجهة لوحة الألوان.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [getArgb32Entries()](#getArgb32Entries--) | يحصل على مصفوفة من هياكل ARGB 32-بت. |
| [getColor(int index)](#getColor-int-) | يحصل على لون اللوحة حسب الفهرس. |
| [getEntries()](#getEntries--) | يحصل على مصفوفة من هياكل  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | يحصل على عدد الإدخالات. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | يحصل على فهرس أقرب لون. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | يحصل على فهرس أقرب لون ARGB 32‑بت. |
| [isCompactPalette()](#isCompactPalette--) | يحصل على قيمة تشير إلى ما إذا تم استخدام لوحة ألوان مدمجة. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


يحصل على مصفوفة من هياكل ARGB 32-بت.

**Returns:**
int[] - مدخلات ARGB 32‑بت. المصفوفة من بنية ARGB 32‑بت التي تشكّل هذا com.aspose.psd.ColorPalette .
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


يحصل على مصفوفة من هياكل  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - المدخلات. المصفوفة من بنية com.aspose.psd.Color التي تشكّل هذا com.aspose.psd.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


يحصل على عدد الإدخالات.

**Returns:**
int - عدد الإدخالات.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


يحصل على فهرس أقرب لون ARGB 32‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb32Color | int | لون 32-بت ARGB. |

**Returns:**
int - مؤشر أقرب لون.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


يحصل على قيمة تشير إلى ما إذا تم استخدام لوحة ألوان مدمجة.

اللوحة المضغوطة تعني أن الصورة ستحتوي فقط على مدخلات اللوحة المحددة إذا كان ذلك ممكنًا أو بعبارة أخرى ستكون الصورة أكثر ضغطًا وتستهلك مساحة أقل؛ وإلا سيكون هناك 2^BitsPerPixel مدخلًا وستحجز الصورة مساحة أكبر لجميع مدخلات اللوحة الممكنة. ضبط هذه القيمة إلى true وتغيير مدخلات اللوحة قد يسبب عقوبة أداء لأن حركة البيانات قد تحدث لذا استخدمه بحذر.

**Returns:**
boolean -  true  إذا تم استخدام لوحة ألوان مدمجة؛ وإلا،  false .

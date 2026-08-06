---
title: "IPsdColorPalette"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "لوحة ألوان pasd"
type: docs
weight: 134
url: /ar/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

لوحة ألوان pasd
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | يحصل على بيانات إدخالات لوحة الألوان الخام. |
| [getRawEntriesCount()](#getRawEntriesCount--) | يحصل على عدد إدخالات لوحة الألوان الخام. |
| [getTransparentColor()](#getTransparentColor--) | يحصل على اللون الشفاف. |
| [getTransparentIndex()](#getTransparentIndex--) | يحصل على فهرس اللون الشفاف. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كان اللون الشفاف موجودًا. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


يحصل على بيانات إدخالات لوحة الألوان الخام.

القيمة: بيانات إدخالات لوحة الألوان الخام.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


يحصل على عدد إدخالات لوحة الألوان الخام.

القيمة: عدد إدخالات لوحة الألوان الخام.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


يحصل على اللون الشفاف.

القيمة: اللون الشفاف.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


يحصل على فهرس اللون الشفاف.

القيمة: مؤشر اللون الشفاف.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كان اللون الشفاف موجودًا.

القيمة:  true  إذا كان اللون الشفاف موجودًا؛ وإلا،  false .

**Returns:**
boolean

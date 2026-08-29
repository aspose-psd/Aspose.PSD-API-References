---
title: "ResolutionSetting"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "إعداد الدقة لخيارات حفظ الصورة."
type: docs
weight: 92
url: /ar/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

إعداد الدقة لخيارات حفظ الصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | ينشئ مثيلاً جديدًا لفئة  ResolutionSetting . |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | ينشئ مثيلاً جديدًا لفئة  ResolutionSetting . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | يحدد حجم صفحة PDF اعتمادًا على دقة DPI المأخوذة من PdfOptions.ResolutionSettings أو إذا كان لها قيم افتراضية؛ من الصورة نفسها |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | يحصل أو يضبط الدقة الأفقية. |
| [getVerticalResolution()](#getVerticalResolution--) | يحصل أو يضبط الدقة العمودية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | يحصل أو يضبط الدقة الأفقية. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | يحصل أو يضبط الدقة العمودية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


ينشئ مثيلاً جديدًا لفئة  ResolutionSetting .

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


ينشئ مثيلاً جديدًا لفئة  ResolutionSetting .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| horizontalResolution | double | الدقة الأفقية. |
| verticalResolution | double | دقة العمودية. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


يحدد حجم صفحة PDF اعتمادًا على دقة DPI المأخوذة من PdfOptions.ResolutionSettings أو إذا كان لها قيم افتراضية؛ من الصورة نفسها

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | حجم الصورة. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | الدقة الأصلية. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | الدقة الجديدة. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


يحصل أو يضبط الدقة الأفقية.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


يحصل أو يضبط الدقة العمودية.

**Returns:**
double
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




### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


يحصل أو يضبط الدقة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


يحصل أو يضبط الدقة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

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


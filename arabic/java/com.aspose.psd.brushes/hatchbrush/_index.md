---
title: "HatchBrush"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد فرشاة مستطيلة مع نمط تظليل لون أمامي ولون خلفي."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.brushes/hatchbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class HatchBrush extends Brush
```

يحدد فرشاة مستطيلة مع نمط تظليل، ولون أمامي، ولون خلفي. لا يمكن توريث هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | تنفذ واجهة Closable ويمكن استخدامها في عبارة try-with-resources منذ JDK 1.7. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة جديدة من الـ Brush الحالي. |
| [dispose()](#dispose--) | يحرر النسخة الحالية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الفراغات بين خطوط التظليل. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [getForegroundColor()](#getForegroundColor--) | يحصل على لون خطوط التظليل. |
| [getHatchStyle()](#getHatchStyle--) | يحصل على نمط التظليل لهذه الفرشاة. |
| [getOpacity()](#getOpacity--) | يحصل على شفافية الفرشاة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | يضبط لون الفراغات بين خطوط التظليل. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.psd.Color-) | يضبط لون خطوط التظليل. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | يضبط نمط التظليل لهذه الفرشاة. |
| [setOpacity(float value)](#setOpacity-float-) | يضبط شفافية الفرشاة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### close() {#close--}
```
public void close()
```


تنفيذ واجهة Closable ويمكن استخدامها في بيان try-with-resources منذ JDK 1.7. هذه الطريقة تستدعي ببساطة طريقة dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


ينشئ نسخة عميقة جديدة من الـ Brush الحالي.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


يحرر النسخة الحالية.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الفراغات بين خطوط التظليل.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of spaces between the hatch lines.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه.

**Returns:**
boolean -  true  إذا تم التخلص؛ وإلا،  false .
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


يحصل على لون خطوط التظليل.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of hatch lines.
### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


يحصل على نمط التظليل لهذه الفرشاة.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


يحصل على شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Returns:**
float - قيمة شفافية الفرشاة.
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط لون الفراغات بين خطوط التظليل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون الفراغات بين خطوط التظليل. |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.psd.Color-}
```
public void setForegroundColor(Color value)
```


يضبط لون خطوط التظليل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | لون خطوط التظليل. |

### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


يضبط نمط التظليل لهذه الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة غير شفافة تمامًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | قيمة شفافية الفرشاة. |

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


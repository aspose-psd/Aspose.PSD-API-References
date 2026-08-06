---
title: "ColorMatrix"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد مصفوفة 5 × 5 تحتوي على إحداثيات مساحة RGBA."
type: docs
weight: 25
url: /ar/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

يحدد مصفوفة 5 × 5 تحتوي على إحداثيات مساحة RGBA. عدة طرق في فئة com.aspose.psd.ImageAttributes تضبط ألوان الصورة باستخدام مصفوفة ألوان. لا يمكن توريث هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | ينشئ مثيلاً جديداً من فئة Aspose.Imaging.ColorMatrix. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | ينشئ مثيلاً جديداً من فئة Aspose.Imaging.ColorMatrix باستخدام العناصر في المصفوفة المحددة newColorMatrix. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | عدد العناصر في بُعد المصفوفة. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | عدد أبعاد المصفوفة. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | الإجمالي الكلي لعدد العناصر في المصفوفة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | يحصل على قيم المصفوفة. |
| [getMatrix00()](#getMatrix00--) | يحصل على العنصر في الصف 0 (صفر) والعمود 0 من هذه Aspose.Imaging.ColorMatrix. |
| [getMatrix01()](#getMatrix01--) | يحصل على العنصر في الصف 0 (صفر) والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix02()](#getMatrix02--) | يحصل على العنصر في الصف 0 (صفر) والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix03()](#getMatrix03--) | يحصل على العنصر في الصف 0 (صفر) والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix04()](#getMatrix04--) | يحصل على العنصر في الصف 0 (صفر) والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix10()](#getMatrix10--) | يحصل على العنصر في الصف الأول والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix11()](#getMatrix11--) | يحصل على العنصر في الصف الأول والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix12()](#getMatrix12--) | يحصل على العنصر في الصف الأول والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix13()](#getMatrix13--) | يحصل على العنصر في الصف الأول والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix14()](#getMatrix14--) | يحصل على العنصر في الصف الأول والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix20()](#getMatrix20--) | يحصل على العنصر في الصف الثاني والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix21()](#getMatrix21--) | يحصل على العنصر في الصف الثاني والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix22()](#getMatrix22--) | يحصل على العنصر في الصف الثاني والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix23()](#getMatrix23--) | يحصل على العنصر في الصف الثاني والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix24()](#getMatrix24--) | يحصل على العنصر في الصف الثاني والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix30()](#getMatrix30--) | يحصل على العنصر في الصف الثالث والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix31()](#getMatrix31--) | يحصل على العنصر في الصف الثالث والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix32()](#getMatrix32--) | يحصل على العنصر في الصف الثالث والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix33()](#getMatrix33--) | يحصل على العنصر في الصف الثالث والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix34()](#getMatrix34--) | يحصل على العنصر في الصف الثالث والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix40()](#getMatrix40--) | يحصل على العنصر في الصف الرابع والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix41()](#getMatrix41--) | يحصل على العنصر في الصف الرابع والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix42()](#getMatrix42--) | يحصل على العنصر في الصف الرابع والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix43()](#getMatrix43--) | يحصل على العنصر في الصف الرابع والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [getMatrix44()](#getMatrix44--) | يحصل على العنصر في الصف الرابع والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [get_Item(int row, int column)](#get-Item-int-int-) | يحصل على العنصر في الصف والعمود المحددين في  Aspose.Imaging.ColorMatrix . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | يضبط العنصر في الصف 0 (صفر) والعمود 0 من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix01(float value)](#setMatrix01-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix02(float value)](#setMatrix02-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix03(float value)](#setMatrix03-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix04(float value)](#setMatrix04-float-) | يضبط العنصر في الصف 0 (صفر) والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix10(float value)](#setMatrix10-float-) | يضبط العنصر في الصف الأول والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix11(float value)](#setMatrix11-float-) | يضبط العنصر في الصف الأول والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix12(float value)](#setMatrix12-float-) | يضبط العنصر في الصف الأول والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix13(float value)](#setMatrix13-float-) | يضبط العنصر في الصف الأول والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix14(float value)](#setMatrix14-float-) | يضبط العنصر في الصف الأول والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix20(float value)](#setMatrix20-float-) | يضبط العنصر في الصف الثاني والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix21(float value)](#setMatrix21-float-) | يضبط العنصر في الصف الثاني والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix22(float value)](#setMatrix22-float-) | يضبط العنصر في الصف الثاني والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix23(float value)](#setMatrix23-float-) | يضبط العنصر في الصف الثاني والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix24(float value)](#setMatrix24-float-) | يضبط العنصر في الصف الثاني والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix30(float value)](#setMatrix30-float-) | يضبط العنصر في الصف الثالث والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix31(float value)](#setMatrix31-float-) | يضبط العنصر في الصف الثالث والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix32(float value)](#setMatrix32-float-) | يضبط العنصر في الصف الثالث والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix33(float value)](#setMatrix33-float-) | يضبط العنصر في الصف الثالث والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix34(float value)](#setMatrix34-float-) | يضبط العنصر في الصف الثالث والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix40(float value)](#setMatrix40-float-) | يضبط العنصر في الصف الرابع والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix41(float value)](#setMatrix41-float-) | يضبط العنصر في الصف الرابع والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix42(float value)](#setMatrix42-float-) | يضبط العنصر في الصف الرابع والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix43(float value)](#setMatrix43-float-) | يضبط العنصر في الصف الرابع والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |
| [setMatrix44(float value)](#setMatrix44-float-) | يضبط العنصر في الصف الرابع والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | يضبط العنصر في الصف والعمود المحددين في Aspose.Imaging.ColorMatrix . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


ينشئ مثيلاً جديداً من فئة Aspose.Imaging.ColorMatrix.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


ينشئ مثيلاً جديداً من فئة Aspose.Imaging.ColorMatrix باستخدام العناصر في المصفوفة المحددة newColorMatrix.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorMatrix | float[][] | قيم العناصر للمصفوفة الجديدة Aspose.Imaging.ColorMatrix . |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


عدد العناصر في بُعد المصفوفة.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


عدد أبعاد المصفوفة.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


الإجمالي الكلي لعدد العناصر في المصفوفة.

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
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


يحصل على قيم المصفوفة.

**Returns:**
float[][] - مصفوفة قيم المصفوفة.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


يحصل على العنصر في الصف 0 (صفر) والعمود 0 من هذه Aspose.Imaging.ColorMatrix.

**Returns:**
float - العنصر في الصف 0 والعمود 0 من Aspose.Imaging.ColorMatrix هذا .
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف 0 والعمود الأول من Aspose.Imaging.ColorMatrix هذا .
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف 0 والعمود الثاني من Aspose.Imaging.ColorMatrix هذا .
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف 0 والعمود الثالث من Aspose.Imaging.ColorMatrix هذا .
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


يحصل على العنصر في الصف 0 (صفر) والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف 0 والعمود الرابع من Aspose.Imaging.ColorMatrix هذا .
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


يحصل على العنصر في الصف الأول والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الأول والعمود 0 من Aspose.Imaging.ColorMatrix هذا .
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


يحصل على العنصر في الصف الأول والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الأول والعمود الأول من Aspose.Imaging.ColorMatrix هذا .
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


يحصل على العنصر في الصف الأول والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الأول والعمود الثاني من Aspose.Imaging.ColorMatrix هذا .
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


يحصل على العنصر في الصف الأول والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الأول والعمود الثالث من Aspose.Imaging.ColorMatrix هذا .
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


يحصل على العنصر في الصف الأول والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الأول والعمود الرابع من Aspose.Imaging.ColorMatrix هذا .
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


يحصل على العنصر في الصف الثاني والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثاني والعمود 0 من Aspose.Imaging.ColorMatrix هذا .
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


يحصل على العنصر في الصف الثاني والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثاني والعمود الأول من Aspose.Imaging.ColorMatrix هذا .
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


يحصل على العنصر في الصف الثاني والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثاني والعمود الثاني من Aspose.Imaging.ColorMatrix هذا .
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


يحصل على العنصر في الصف الثاني والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثاني والعمود الثالث من Aspose.Imaging.ColorMatrix هذا .
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


يحصل على العنصر في الصف الثاني والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثاني والعمود الرابع من Aspose.Imaging.ColorMatrix هذا .
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


يحصل على العنصر في الصف الثالث والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثالث والعمود 0 من Aspose.Imaging.ColorMatrix هذا .
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


يحصل على العنصر في الصف الثالث والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثالث والعمود الأول من Aspose.Imaging.ColorMatrix هذا .
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


يحصل على العنصر في الصف الثالث والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثالث والعمود الثاني من Aspose.Imaging.ColorMatrix هذا .
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


يحصل على العنصر في الصف الثالث والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثالث والعمود الثالث من Aspose.Imaging.ColorMatrix هذا .
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


يحصل على العنصر في الصف الثالث والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الثالث والعمود الرابع من Aspose.Imaging.ColorMatrix هذا .
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


يحصل على العنصر في الصف الرابع والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الرابع والعمود 0 من هذا  Aspose.Imaging.ColorMatrix .
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


يحصل على العنصر في الصف الرابع والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الرابع والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


يحصل على العنصر في الصف الرابع والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الرابع والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


يحصل على العنصر في الصف الرابع والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الرابع والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


يحصل على العنصر في الصف الرابع والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Returns:**
float - العنصر في الصف الرابع والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


يحصل على العنصر في الصف والعمود المحددين في  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صف | int | رقم الصف. |
| عمود | int | رقم العمود. |

**Returns:**
float - العنصر في الصف والعمود المحددين.
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




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود 0 من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف 0 والعمود 0 من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف 0 والعمود الأول من هذا  Aspose.Imaging.ColorMatrix  . |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف 0 والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف 0 والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


يضبط العنصر في الصف 0 (صفر) والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف 0 والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


يضبط العنصر في الصف الأول والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الأول والعمود 0 من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


يضبط العنصر في الصف الأول والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الأول والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


يضبط العنصر في الصف الأول والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الأول والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


يضبط العنصر في الصف الأول والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الأول والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


يضبط العنصر في الصف الأول والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الأول والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


يضبط العنصر في الصف الثاني والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثاني والعمود 0 من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


يضبط العنصر في الصف الثاني والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثاني والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


يضبط العنصر في الصف الثاني والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثاني والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


يضبط العنصر في الصف الثاني والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثاني والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


يضبط العنصر في الصف الثاني والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثاني والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


يضبط العنصر في الصف الثالث والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثالث والعمود 0 من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


يضبط العنصر في الصف الثالث والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثالث والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


يضبط العنصر في الصف الثالث والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثالث والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


يضبط العنصر في الصف الثالث والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثالث والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


يضبط العنصر في الصف الثالث والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الثالث والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


يضبط العنصر في الصف الرابع والعمود 0 (صفر) من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الرابع والعمود 0 من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


يضبط العنصر في الصف الرابع والعمود الأول من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الرابع والعمود الأول من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


يضبط العنصر في الصف الرابع والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الرابع والعمود الثاني من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


يضبط العنصر في الصف الرابع والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الرابع والعمود الثالث من هذا  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


يضبط العنصر في الصف الرابع والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | العنصر في الصف الرابع والعمود الرابع من هذا  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


يضبط العنصر في الصف والعمود المحددين في Aspose.Imaging.ColorMatrix .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صف | int | رقم الصف. |
| عمود | int | رقم العمود. |
| القيمة | float | القيمة |

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


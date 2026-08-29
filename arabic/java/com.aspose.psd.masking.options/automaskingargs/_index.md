---
title: "AutoMaskingArgs"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل الوسائط المحددة لطرق القناع الآلية"
type: docs
weight: 11
url: /ar/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

يمثل الوسائط المحددة لطرق القناع الآلية
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | يعيد الحد الأقصى لعدد التكرارات. |
| [getNumberOfObjects()](#getNumberOfObjects--) | يعيد عدد الكائنات التي يجب فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية). |
| [getObjectsPoints()](#getObjectsPoints--) | يعيد النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. |
| [getObjectsRectangles()](#getObjectsRectangles--) | يعيد مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). |
| [getOrphanedPoints()](#getOrphanedPoints--) | يعيد النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). |
| [getPrecision()](#getPrecision--) | يعيد دقة طريقة التجزئة (اختياري). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | يضبط الحد الأقصى لعدد التكرارات. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | يضبط عدد الكائنات التي يجب فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | يضبط النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | يضبط مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | يضبط النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). |
| [setPrecision(double value)](#setPrecision-double-) | يضبط دقة طريقة التجزئة (اختياري). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


يعيد الحد الأقصى لعدد التكرارات.

القيمة: الحد الأقصى الأقصى لعدد التكرارات.

**Returns:**
int - الحد الأقصى لعدد التكرارات.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


يعيد عدد الكائنات التي يجب فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية).

القيمة: عدد الكائنات.

**Returns:**
int - عدد الكائنات التي يجب فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


يعيد النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: نقاط الكائنات.

**Returns:**
com.aspose.psd.Point[][] - النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


يعيد مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: مستطيلات الكائنات.

**Returns:**
com.aspose.psd.Rectangle[] - مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


يحصل على النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). يُستخدم هذا المعامل فقط في حالة إعادة التجزئة.

القيمة: النقاط اليتيمة.

**Returns:**
com.aspose.psd.Point[] - النقاط التي لم تعد تنتمي إلى أي كائن (اختياري).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


يعيد دقة طريقة التجزئة (اختياري).

القيمة: دقة طريقة التجزئة (اختياري).

**Returns:**
double - دقة طريقة التجزئة (اختياري).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


يضبط الحد الأقصى لعدد التكرارات.

القيمة: الحد الأقصى الأقصى لعدد التكرارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحد الأقصى لعدد التكرارات. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


يضبط عدد الكائنات التي يجب فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية).

القيمة: عدد الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | عدد الكائنات التي سيتم فصل الصورة الأولية إليها (اختياري)، القيمة الافتراضية هي 2 (كائن وخلفية). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


يضبط النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: نقاط الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | النقاط التي تنتمي إلى الكائنات المفصولة (اختياري) إحداثيات NumberOfObjects التي تنتمي إلى كائنات NumberOfObjects في الصورة الأولية. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


يضبط مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). يُستخدم هذا المعامل لزيادة دقة طريقة التجزئة.

القيمة: مستطيلات الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | مستطيلات الكائنات التي تنتمي إلى الكائنات المفصولة (اختياري). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


يضبط النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). يُستخدم هذا المعامل فقط في حالة إعادة التجزئة.

القيمة: النقاط اليتيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | النقاط التي لم تعد تنتمي إلى أي كائن (اختياري). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


يضبط دقة طريقة التجزئة (اختياري).

القيمة: دقة طريقة التجزئة (اختياري).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | دقة طريقة التجزئة (اختياري). |

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


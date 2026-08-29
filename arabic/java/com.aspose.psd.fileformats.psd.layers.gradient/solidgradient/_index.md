---
title: "SolidGradient"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "إعدادات تأثير تعبئة التدرج."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

إعدادات تأثير تعبئة التدرج.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | يُنشئ مثلاً جديداً من الفئة [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | يضيف نقطة اللون. |
| [addTransparencyPoint()](#addTransparencyPoint--) | يضيف نقطة اللون. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | يولد عقد موارد LFX2. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | يحصل أو يعيّن نقاط اللون. |
| [getGradientMode()](#getGradientMode--) | يحصل على الوضع لهذا التدرج. |
| [getGradientName()](#getGradientName--) | يحصل أو يعيّن اسم التدرج. |
| [getInterpolation()](#getInterpolation--) | يحصل أو يعيّن الاستيفاء. |
| [getTransparencyPoints()](#getTransparencyPoints--) | يحصل أو يضبط نقاط الشفافية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | يزيل نقطة اللون. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | يزيل نقطة الشفافية. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | يحصل أو يعيّن نقاط اللون. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | يحصل أو يعيّن اسم التدرج. |
| [setInterpolation(short value)](#setInterpolation-short-) | يحصل أو يعيّن الاستيفاء. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | يحصل أو يضبط نقاط الشفافية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


يُنشئ مثلاً جديداً من الفئة [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient).

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


يضيف نقطة اللون.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


يضيف نقطة اللون.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


يولد عقد موارد LFX2.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - قائمة مُولَّدة من [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


يحصل أو يعيّن نقاط اللون.

القيمة: نقاط اللون.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


يحصل على الوضع لهذا التدرج. يحدد 'نوع التدرج' = 'صلب/ضوضاء' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


يحصل أو يعيّن اسم التدرج.

القيمة: اسم التدرج.

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


يحصل أو يضبط Interpolation. يحدد Smoothness، عندما تكون 'Gradient Type' = 'Solid'. نطاق القيمة: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


يحصل أو يضبط نقاط الشفافية.

القيمة: نقاط الشفافية.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


يزيل نقطة اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | النقطة. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


يزيل نقطة الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | النقطة. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


يحصل أو يعيّن نقاط اللون.

القيمة: نقاط اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


يحصل أو يعيّن اسم التدرج.

القيمة: اسم التدرج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


يحصل أو يضبط Interpolation. يحدد Smoothness، عندما تكون 'Gradient Type' = 'Solid'. نطاق القيمة: 0-4096.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


يحصل أو يضبط نقاط الشفافية.

القيمة: نقاط الشفافية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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


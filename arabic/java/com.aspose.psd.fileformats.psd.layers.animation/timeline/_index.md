---
title: "الجدول الزمني"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "نموذج خيارات خط الزمن."
type: docs
weight: 14
url: /ar/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

نموذج خيارات خط الزمن.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Timeline()](#Timeline--) | يُنشئ مثلاً جديدًا من الفئة [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | تطبيق قيم الخط الزمني الحالية على PsdImage المدخل ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | يحصل أو يضبط قيمة AFSt. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | يحصل أو يضبط فهرس الإطار النشط. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | يحصل على الإطار حسب المعرف. |
| [getFrames()](#getFrames--) | يحصل على قائمة الإطارات. |
| [getFramesList()](#getFramesList--) | يحصل على قائمة الإطارات. |
| [getFsID()](#getFsID--) | يحصل أو يضبط قيمة FsID. |
| [getLoopesCount()](#getLoopesCount--) | يحصل أو يضبط عدد الحلقات. |
| [getPsdImage()](#getPsdImage--) | يحصل أو يضبط صورة PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) لهذا [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | يحفظ بيانات PsdImage والجدول الزمني إلى الدفق المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | يحفظ بيانات PsdImage والجدول الزمني إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ. |
| [setAFSt(int value)](#setAFSt-int-) | يحصل أو يضبط قيمة AFSt. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | يحصل أو يضبط فهرس الإطار النشط. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | يحصل على قائمة الإطارات. |
| [setFsID(int value)](#setFsID-int-) | يحصل أو يضبط قيمة FsID. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | يحصل أو يضبط عدد الحلقات. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | يحصل أو يضبط صورة PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) لهذا [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | يبدل الإطار النشط إلى الإطار المستهدف. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | تطبيق قيم الخط الزمني الحالية على PsdImage المدخل ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


يُنشئ مثلاً جديدًا من الفئة [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


تطبيق قيم الخط الزمني الحالية على PsdImage المدخل ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | صورة psd. |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


يحصل أو يضبط قيمة AFSt.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


يحصل أو يضبط فهرس الإطار النشط.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


يحصل على الإطار حسب المعرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frameId | int | معرف الإطار. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


يحصل على قائمة الإطارات.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


يحصل على قائمة الإطارات.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


يحصل أو يضبط قيمة FsID.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


يحصل أو يضبط عدد الحلقات.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


يحصل أو يضبط صورة PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) لهذا [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


يحفظ بيانات PsdImage والجدول الزمني إلى الدفق المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | دفق الإخراج. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


يحفظ بيانات PsdImage والجدول الزمني إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | الخيارات. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


يحصل أو يضبط قيمة AFSt.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


يحصل أو يضبط فهرس الإطار النشط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


يحصل على قائمة الإطارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


يحصل أو يضبط قيمة FsID.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


يحصل أو يضبط عدد الحلقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


يحصل أو يضبط صورة PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)) لهذا [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


يبدل الإطار النشط إلى الإطار المستهدف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| targetActiveFrameIndex | int | فهرس الإطار المستهدف. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


تطبيق قيم الخط الزمني الحالية على PsdImage المدخل ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| frameIndex | int | فهرس الإطار لتحديث حالات الطبقة. |

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


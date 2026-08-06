---
title: "ArtDResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "بيانات معلومات لوحة الرسم لـ PsdImage.GlobalLayerResources/."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtDResource extends BaseArtboardInfoResource
```

بيانات معلومات لوحة الرسم لـ  PsdImage.GlobalLayerResources ([PsdImage.getGlobalLayerResources](../../com.aspose.psd.fileformats.psd/psdimage\#getGlobalLayerResources)/[PsdImage.setGlobalLayerResources(LayerResource[])](../../com.aspose.psd.fileformats.psd/psdimage\#setGlobalLayerResources-LayerResource---)).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ArtDResource()](#ArtDResource--) | تهيئ نسخة جديدة من الفئة [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) . |
## الحقول

| حقل | الوصف |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | إصدار رأس PSB |
| [PsbResourceSignature](#PsbResourceSignature) | توقيع المورد الخاص بـ PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | إصدار رأس PSD |
| [ResourceSignature](#ResourceSignature) | توقيع المورد المشترك. |
| [TypeToolKey](#TypeToolKey) | مفتاح معلومات أداة النوع. |
| [ventureLicense_internalized](#ventureLicense-internalized) | رخصة المشروع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArtboardCount_internalized()](#getArtboardCount-internalized--) | يحصل أو يضبط عدد لوحات الرسم. |
| [getAutoExpandOffset_internalized()](#getAutoExpandOffset-internalized--) | يحصل أو يضبط إزاحة التوسيع التلقائي. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | يحصل أو يعيّن معرف فئة المورد. |
| [getClassName_internalized()](#getClassName-internalized--) | يحصل أو يعيّن اسم فئة المورد. |
| [getDocDefaultNewArtboardBackgroundColor_internalized()](#getDocDefaultNewArtboardBackgroundColor-internalized--) | يحصل أو يضبط  DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [getDocDefaultNewArtboardBackgroundType_internalized()](#getDocDefaultNewArtboardBackgroundType-internalized--) | يحصل أو يضبط  DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)). |
| [getHeader_internalized()](#getHeader-internalized--) | يحصل أو يضبط الرأس. |
| [getItems()](#getItems--) | يحصل أو يضبط العناصر [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [getKey()](#getKey--) | يحصل على مفتاح مورد الطبقة. |
| [getLength()](#getLength--) |    |
| [getOriginPoint_internalized()](#getOriginPoint-internalized--) | يحصل أو يضبط نقطة الأصل. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | يحصل على طول البادئة. |
| [getPsdVersion()](#getPsdVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. |
| [getSignature()](#getSignature--) | يحصل على توقيع مورد الطبقة. |
| [getVersion_internalized()](#getVersion-internalized--) | يحصل أو يضبط نسخة المورد. |
| [hashCode()](#hashCode--) |  |
| [isAutoExpandEnabled_internalized()](#isAutoExpandEnabled-internalized--) | الحصول أو الضبط للخاصية IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [isAutoNestEnabled_internalized()](#isAutoNestEnabled-internalized--) | الحصول أو الضبط للخاصية IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [isAutoPositionEnabled_internalized()](#isAutoPositionEnabled-internalized--) | الحصول أو الضبط للخاصية IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | يحدد ما إذا كان المورد خاصًا بـ PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB. |
| [isShrinkwrapOnSaveEnabled_internalized()](#isShrinkwrapOnSaveEnabled-internalized--) | الحصول أو الضبط للخاصية IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | يحفظ المورد إلى حاوية الدفق المحددة. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | يحفظ رأس المورد المخصص. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | يحفظ توقيع الرأس، المعرف والطول. |
| [setArtboardCount_internalized(int value)](#setArtboardCount-internalized-int-) | يحصل أو يضبط عدد لوحات الرسم. |
| [setAutoExpandEnabled_internalized(boolean value)](#setAutoExpandEnabled-internalized-boolean-) | الحصول أو الضبط للخاصية IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [setAutoExpandOffset_internalized(PointF value)](#setAutoExpandOffset-internalized-com.aspose.psd.PointF-) | يحصل أو يضبط إزاحة التوسيع التلقائي. |
| [setAutoNestEnabled_internalized(boolean value)](#setAutoNestEnabled-internalized-boolean-) | الحصول أو الضبط للخاصية IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [setAutoPositionEnabled_internalized(boolean value)](#setAutoPositionEnabled-internalized-boolean-) | الحصول أو الضبط للخاصية IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | يحصل أو يعيّن معرف فئة المورد. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | يحصل أو يعيّن اسم فئة المورد. |
| [setDocDefaultNewArtboardBackgroundColor_internalized(Color value)](#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-) | يحصل أو يضبط  DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)). |
| [setDocDefaultNewArtboardBackgroundType_internalized(int value)](#setDocDefaultNewArtboardBackgroundType-internalized-int-) | يحصل أو يضبط  DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)). |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | يحصل أو يضبط الرأس. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | يحصل أو يضبط العناصر [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [setOriginPoint_internalized(PointF value)](#setOriginPoint-internalized-com.aspose.psd.PointF-) | يحصل أو يضبط نقطة الأصل. |
| [setShrinkwrapOnSaveEnabled_internalized(boolean value)](#setShrinkwrapOnSaveEnabled-internalized-boolean-) | الحصول أو الضبط للخاصية IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | يحصل أو يضبط نسخة المورد. |
| [toString()](#toString--) | يرجع سلسلة تمثل هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtDResource() {#ArtDResource--}
```
public ArtDResource()
```


تهيئ نسخة جديدة من الفئة [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) .

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


إصدار رأس PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


توقيع المورد الخاص بـ PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


إصدار رأس PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


توقيع المورد المشترك.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


مفتاح معلومات أداة النوع.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


رخصة المشروع.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


يتحقق من ويضبط ما إذا كان المورد خاصًا بـ PSB. بعض الموارد غير معروفة حاليًا، لكن لدينا قائمة كاملة بالموارد الخاصة بـ PSB التي تغير سلوكها عند الحفظ. لذلك نحتاج إلى التحقق من ذلك في UnknownResource على الأقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | المفتاح. |

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
### getArtboardCount_internalized() {#getArtboardCount-internalized--}
```
public final int getArtboardCount_internalized()
```


يحصل أو يضبط عدد لوحات الرسم.

**Returns:**
int
### getAutoExpandOffset_internalized() {#getAutoExpandOffset-internalized--}
```
public final PointF getAutoExpandOffset_internalized()
```


يحصل أو يضبط إزاحة التوسيع التلقائي.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


يحصل أو يعيّن معرف فئة المورد.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


يحصل أو يعيّن اسم فئة المورد.

**Returns:**
java.lang.String
### getDocDefaultNewArtboardBackgroundColor_internalized() {#getDocDefaultNewArtboardBackgroundColor-internalized--}
```
public final Color getDocDefaultNewArtboardBackgroundColor_internalized()
```


يحصل أو يضبط  DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Returns:**
[Color](../../com.aspose.psd/color)
### getDocDefaultNewArtboardBackgroundType_internalized() {#getDocDefaultNewArtboardBackgroundType-internalized--}
```
public final int getDocDefaultNewArtboardBackgroundType_internalized()
```


يحصل أو يضبط  DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)).

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


يحصل أو يضبط العناصر [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


يحصل على مفتاح مورد الطبقة.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


  

**Returns:**
int
### getOriginPoint_internalized() {#getOriginPoint-internalized--}
```
public final PointF getOriginPoint_internalized()
```


يحصل أو يضبط نقطة الأصل.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


يحصل على طول البادئة. القيمة الافتراضية هي 12 لموارد 8BIM و 16 لموارد 8B64.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| psdVersion | int | إصدار PSD. |

**Returns:**
int - طول البادئة.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


يحصل على توقيع مورد الطبقة.

**Returns:**
int
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


يحصل أو يضبط نسخة المورد.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoExpandEnabled_internalized() {#isAutoExpandEnabled-internalized--}
```
public final boolean isAutoExpandEnabled_internalized()
```


الحصول أو الضبط للخاصية IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoNestEnabled_internalized() {#isAutoNestEnabled-internalized--}
```
public final boolean isAutoNestEnabled_internalized()
```


الحصول أو الضبط للخاصية IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoPositionEnabled_internalized() {#isAutoPositionEnabled-internalized--}
```
public final boolean isAutoPositionEnabled_internalized()
```


الحصول أو الضبط للخاصية IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


يحدد ما إذا كان المورد خاصًا بـ PSB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | int | مفتاح المورد. |

**Returns:**
boolean -  true  إذا كان المورد خاصًا بـ PSD؛ وإلا،  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن خاصًا بـ PSB.

القيمة:  true  إذا كان هذا الكائن خاصًا بـ PSB؛ وإلا،  false .

**Returns:**
boolean
### isShrinkwrapOnSaveEnabled_internalized() {#isShrinkwrapOnSaveEnabled-internalized--}
```
public final boolean isShrinkwrapOnSaveEnabled_internalized()
```


الحصول أو الضبط للخاصية IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


يحفظ المورد إلى حاوية الدفق المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ إليها. |
| psdVersion | int | إصدار PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


يحفظ رأس المورد المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


يحفظ توقيع الرأس، المعرف والطول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق. |
| التوقيع | int | التوقيع. |
| isLengthLong | boolean | إذا تم ضبطه على  true  يكون الطول طويلًا. |

### setArtboardCount_internalized(int value) {#setArtboardCount-internalized-int-}
```
public final void setArtboardCount_internalized(int value)
```


يحصل أو يضبط عدد لوحات الرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setAutoExpandEnabled_internalized(boolean value) {#setAutoExpandEnabled-internalized-boolean-}
```
public final void setAutoExpandEnabled_internalized(boolean value)
```


الحصول أو الضبط للخاصية IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAutoExpandOffset_internalized(PointF value) {#setAutoExpandOffset-internalized-com.aspose.psd.PointF-}
```
public final void setAutoExpandOffset_internalized(PointF value)
```


يحصل أو يضبط إزاحة التوسيع التلقائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setAutoNestEnabled_internalized(boolean value) {#setAutoNestEnabled-internalized-boolean-}
```
public final void setAutoNestEnabled_internalized(boolean value)
```


الحصول أو الضبط للخاصية IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAutoPositionEnabled_internalized(boolean value) {#setAutoPositionEnabled-internalized-boolean-}
```
public final void setAutoPositionEnabled_internalized(boolean value)
```


الحصول أو الضبط للخاصية IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


يحصل أو يعيّن معرف فئة المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


يحصل أو يعيّن اسم فئة المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDocDefaultNewArtboardBackgroundColor_internalized(Color value) {#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-}
```
public final void setDocDefaultNewArtboardBackgroundColor_internalized(Color value)
```


يحصل أو يضبط  DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDocDefaultNewArtboardBackgroundType_internalized(int value) {#setDocDefaultNewArtboardBackgroundType-internalized-int-}
```
public final void setDocDefaultNewArtboardBackgroundType_internalized(int value)
```


يحصل أو يضبط  DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


يحصل أو يضبط الرأس.

القيمة: الترويسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


يحصل أو يضبط العناصر [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setOriginPoint_internalized(PointF value) {#setOriginPoint-internalized-com.aspose.psd.PointF-}
```
public final void setOriginPoint_internalized(PointF value)
```


يحصل أو يضبط نقطة الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setShrinkwrapOnSaveEnabled_internalized(boolean value) {#setShrinkwrapOnSaveEnabled-internalized-boolean-}
```
public final void setShrinkwrapOnSaveEnabled_internalized(boolean value)
```


الحصول أو الضبط للخاصية IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


يحصل أو يضبط نسخة المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل هذا الكائن.

**Returns:**
java.lang.String - سلسلة تمثل هذه الحالة.
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


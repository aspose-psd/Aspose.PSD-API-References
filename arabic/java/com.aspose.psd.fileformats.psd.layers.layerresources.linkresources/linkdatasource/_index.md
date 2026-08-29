---
title: "LinkDataSource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يعرف فئة LinkDataSource التي تحتوي على معلومات حول ملف مرتبط أو أصل في ملف PSD."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource/
---

**Inheritance:**
java.lang.Object
```
public abstract class LinkDataSource
```

يعرف فئة LinkDataSource التي تحتوي على معلومات حول ملف مرتبط أو أصل في ملف PSD.
## الحقول

| حقل | الوصف |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | إصدار الوصف. |
| [LatestVersion_internalized](#LatestVersion-internalized) | أحدث إصدار متاح لمصدر بيانات الارتباط |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | قيمة غير متوقعة لنوع مصدر بيانات الارتباط |
| [ZeroChar_internalized](#ZeroChar-internalized) | حرف الصفر |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفلاً. |
| [getAssetModTime()](#getAssetModTime--) | يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبات Adobe® Photoshop® \u0421\u0421. |
| [getChildDocId()](#getChildDocId--) | يحصل أو يعيّن معرف المستند الفرعي في مصدر بيانات liFE أو liFD لمورد Adobe® Photoshop® Lnk2 / LnkE. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | يحصل أو يعيّن معرف فئة المورد. |
| [getClassName_internalized()](#getClassName-internalized--) | يحصل أو يعيّن اسم فئة المورد. |
| [getCompId()](#getCompId--) | يحصل أو يعيّن معرف المكوّن المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | يحصل أو يعيّن خاصية ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | يحصل على طول البيانات الإضافية. |
| [getDataLength_internalized()](#getDataLength-internalized--) | يحصل على طول بيانات مصدر الارتباط. |
| [getFileCreator()](#getFileCreator--) | يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2. |
| [getFileType()](#getFileType--) | يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE. |
| [getItems_internalized()](#getItems-internalized--) | يحصل أو يعيّن مصفوفة OSTypeStructure التي تحدد خصائص المورد. |
| [getLength()](#getLength--) | يحصل على طول مصدر بيانات الرابط بالبايت. |
| [getOriginalCompId()](#getOriginalCompId--) | يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [getOriginalFileName()](#getOriginalFileName--) | يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الربط العالمي Adobe® Photoshop®. |
| [getType()](#getType--) | يحصل على نوع مصدر البيانات للربط العالمي Adobe® Photoshop® والذي يمكن أن يكون أحد التالي أو لا شيء: ملف الربط المدمج liFD الذي يت对应 مع PSD Lnk2Resource، ملف الربط الخارجي liFE الذي يت对应 مع PSD LnkeResource، اسم مستعار ملف الربط liFA. |
| [getUniqueId()](#getUniqueId--) | يحصل على المعرف الفريد العالمي لمصدر البيانات في مورد ربط PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | يحصل أو يعيّن البيانات غير المعروفة التي تسبق خصائص Items OSTypeStructures. |
| [getVersion()](#getVersion--) | يحصل على إصدار مصدر البيانات في مورد PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات هذا الرابط يحتوي على واصف فتح الملف: CompId و OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD هذا يربط إلى عنصر مكتبة Adobe® Photoshop® \\u0421\\u0421. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | يحفظ بيانات كتلة مصدر البيانات للربط. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفلاً. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبات Adobe® Photoshop® \u0421\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | يحصل أو يعيّن معرف المستند الفرعي في مصدر بيانات liFE أو liFD لمورد Adobe® Photoshop® Lnk2 / LnkE. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | يحصل أو يعيّن معرف فئة المورد. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | يحصل أو يعيّن اسم فئة المورد. |
| [setCompId(int value)](#setCompId-int-) | يحصل أو يعيّن معرف المكوّن المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | يحصل أو يعيّن خاصية ContentID. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات هذا الرابط يحتوي على واصف فتح الملف: CompId و OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | يحصل أو يعيّن مصفوفة OSTypeStructure التي تحدد خصائص المورد. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD هذا يربط إلى عنصر مكتبة Adobe® Photoshop® \\u0421\\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الربط العالمي Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | يعيّن قيمة الخاصية وفقًا للهيكل النوعي. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | يحصل على المعرف الفريد العالمي لمصدر البيانات في مورد ربط PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | يحصل أو يعيّن البيانات غير المعروفة التي تسبق خصائص Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


إصدار الوصف.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


أحدث إصدار متاح لمصدر بيانات الارتباط

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


قيمة غير متوقعة لنوع مصدر بيانات الارتباط

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


حرف الصفر

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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفلًا. حالة القفل للأصل، لمكتبات Adobe® Photoshop® \u0421\u0421.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبات Adobe® Photoshop® \u0421\u0421.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


يحصل أو يعيّن معرف المستند الفرعي في مصدر بيانات liFE أو liFD لمورد Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
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
### getCompId() {#getCompId--}
```
public final int getCompId()
```


يحصل أو يعيّن معرف الـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ. الـ Comps هي تركيبات لتخطيط الصفحة يمكن للمصممين إنشاؤها. باستخدام Layer Comps، يمكنك إنشاء وإدارة وعرض إصدارات متعددة من التخطيط في ملف واحد من Adobe® Photoshop®. الـ Layer Comp هو لقطة لحالة لوحة Layers. تقوم Layer Comps بحفظ ثلاثة أنواع من خيارات الطبقة لكن هذه الخاصية تحصل على معرف اختيار Layer Comp للكائنات الذكية. Layer comps في Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


يحصل أو يعيّن خاصية ContentID. تُقرأ قيمة هذه الخاصية وتُحفظ فقط عندما يكون Version >= 8.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


يحصل على طول البيانات الإضافية.

القيمة: طول البيانات.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


يحصل على طول بيانات مصدر الارتباط.

**Returns:**
long - طول بيانات المصدر.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


يحصل أو يعيّن مصفوفة OSTypeStructure التي تحدد خصائص المورد.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


يحصل على طول مصدر بيانات الرابط بالبايت.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ. هذه الخاصية تحصل على معرف اختيار الـ layer Comp الأصلي للكائنات الذكية. Layer comps في Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الربط العالمي Adobe® Photoshop®.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


يحصل على نوع مصدر البيانات للربط العالمي Adobe® Photoshop® والذي يمكن أن يكون أحد التالي أو لا شيء: ملف الربط المدمج liFD الذي يت对应 مع PSD Lnk2Resource، ملف الربط الخارجي liFE الذي يت对应 مع PSD LnkeResource، اسم مستعار ملف الربط liFA.

القيمة: نوع مصدر بيانات رابط PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


يحصل على المعرف الفريد العالمي لمصدر البيانات في مورد ربط PSD.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


يحصل أو يعيّن البيانات غير المعروفة التي تسبق خصائص Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل على إصدار مصدر البيانات في مورد PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات هذا الرابط يحتوي على واصف فتح الملف: CompId و OriginalCompId.

القيمة:  true  إذا كان لهذا الكائن واصف ملف مفتوح؛ وإلا،  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD هذا يربط إلى عنصر مكتبة Adobe® Photoshop® \\u0421\\u0421.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


يحفظ بيانات كتلة مصدر البيانات للربط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ إليها. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفلًا. حالة القفل للأصل، لمكتبات Adobe® Photoshop® \u0421\u0421.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبات Adobe® Photoshop® \u0421\u0421.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


يحصل أو يعيّن معرف المستند الفرعي في مصدر بيانات liFE أو liFD لمورد Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


يحصل أو يعيّن معرف الـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ. الـ Comps هي تركيبات لتخطيط الصفحة يمكن للمصممين إنشاؤها. باستخدام Layer Comps، يمكنك إنشاء وإدارة وعرض إصدارات متعددة من التخطيط في ملف واحد من Adobe® Photoshop®. الـ Layer Comp هو لقطة لحالة لوحة Layers. تقوم Layer Comps بحفظ ثلاثة أنواع من خيارات الطبقة لكن هذه الخاصية تحصل على معرف اختيار Layer Comp للكائنات الذكية. Layer comps في Smart Objects

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


يحصل أو يعيّن خاصية ContentID. تُقرأ قيمة هذه الخاصية وتُحفظ فقط عندما يكون Version >= 8.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات هذا الرابط يحتوي على واصف فتح الملف: CompId و OriginalCompId.

القيمة:  true  إذا كان لهذا الكائن واصف ملف مفتوح؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


يحصل أو يعيّن مصفوفة OSTypeStructure التي تحدد خصائص المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD هذا يربط إلى عنصر مكتبة Adobe® Photoshop® \\u0421\\u0421.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ. هذه الخاصية تحصل على معرف اختيار الـ layer Comp الأصلي للكائنات الذكية. Layer comps في Smart Objects

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الربط العالمي Adobe® Photoshop®.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


يعيّن قيمة الخاصية وفقًا للهيكل النوعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | البنية. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


يحصل على المعرف الفريد العالمي لمصدر البيانات في مورد ربط PSD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


يحصل أو يعيّن البيانات غير المعروفة التي تسبق خصائص Items OSTypeStructures.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

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


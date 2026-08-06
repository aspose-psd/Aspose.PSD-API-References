---
title: "LiFeDataSource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يعرف فئة LnkeDataSource التي تحتوي على معلومات حول ملف مرتبط خارجي."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

يعرّف فئة LnkeDataSource التي تحتوي على معلومات حول الملف المرتبط الخارجي. هذا جزء من واجهة برمجة تطبيقات معالجة تنسيق ملفات PSD التي تساعد على تعديل ملفات Adobe® Photoshop®.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | ينشئ مثلاً جديداً من الفئة [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثلاً جديداً من الفئة [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
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
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | يحصل أو يعيّن معرف مكتبة الرسومات AdobeStockId، لمكتبات Adobe® Photoshop® CC. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | يحصل على حالة ترخيص Adobe Stock إذا كان متاحًا، لمكتبات Adobe® Photoshop® CC. |
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
| [getDate()](#getDate--) | يحصل أو يعيّن تاريخ ووقت الكتابة الأخير للملف الخارجي في مصدر بيانات LiFE لمورد PSD LnkE. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | يحصل أو يعيّن اسم عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC. |
| [getElementRef()](#getElementRef--) | يحصل أو يعيّن مرجع عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC. |
| [getFileCreator()](#getFileCreator--) | يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2. |
| [getFileName()](#getFileName--) | يحصل أو يعيّن اسم الملف الخارجي أو المدمج في مورد ربط PSD. |
| [getFileSize()](#getFileSize--) | يحصل أو يعيّن حجم الملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE. |
| [getFileType()](#getFileType--) | يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE. |
| [getFullPath()](#getFullPath--) | يحصل أو يعيّن المسار الكامل للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE. |
| [getItems_internalized()](#getItems-internalized--) | يحصل أو يعيّن مصفوفة OSTypeStructure التي تحدد خصائص المورد. |
| [getLength()](#getLength--) | يحصل على طول مصدر بيانات الرابط بالبايت. |
| [getOriginalCompId()](#getOriginalCompId--) | يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [getOriginalFileName()](#getOriginalFileName--) | يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الربط العالمي Adobe® Photoshop®. |
| [getRelativePath()](#getRelativePath--) | يحصل أو يعيّن المسار النسبي للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE. |
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
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | يحصل أو يعيّن معرف مكتبة الرسومات AdobeStockId، لمكتبات Adobe® Photoshop® CC. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفلاً. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبات Adobe® Photoshop® \u0421\u0421. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | يحصل أو يعيّن معرف المستند الفرعي في مصدر بيانات liFE أو liFD لمورد Adobe® Photoshop® Lnk2 / LnkE. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | يحصل أو يعيّن معرف فئة المورد. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | يحصل أو يعيّن اسم فئة المورد. |
| [setCompId(int value)](#setCompId-int-) | يحصل أو يعيّن معرف المكوّن المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | يحصل أو يعيّن خاصية ContentID. |
| [setDate(Date value)](#setDate-java.util.Date-) | يحصل أو يعيّن تاريخ ووقت الكتابة الأخير للملف الخارجي في مصدر بيانات LiFE لمورد PSD LnkE. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | يحصل أو يعيّن اسم عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | يحصل أو يعيّن مرجع عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2. |
| [setFileName(String value)](#setFileName-java.lang.String-) | يحصل أو يعيّن اسم الملف الخارجي أو المدمج في مورد ربط PSD. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات هذا الرابط يحتوي على واصف فتح الملف: CompId و OriginalCompId. |
| [setFileSize(long value)](#setFileSize-long-) | يحصل أو يعيّن حجم الملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE. |
| [setFileType(String value)](#setFileType-java.lang.String-) | يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | يحصل أو يعيّن المسار الكامل للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | يحصل أو يعيّن مصفوفة OSTypeStructure التي تحدد خصائص المورد. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD هذا يربط إلى عنصر مكتبة Adobe® Photoshop® \\u0421\\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الربط العالمي Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | يعيّن قيمة الخاصية وفقًا للهيكل النوعي. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | يحصل أو يعيّن المسار النسبي للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | يحصل على المعرف الفريد العالمي لمصدر البيانات في مورد ربط PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | يحصل أو يعيّن البيانات غير المعروفة التي تسبق خصائص Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


ينشئ مثلاً جديداً من الفئة [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


ينشئ مثلاً جديداً من الفئة [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| version | int | الإصدار. |
| uniqueId | java.util.UUID | المعرّف الفريد. |
| originalFileName | java.lang.String | اسم الملف الأصلي. |
| fileType | java.lang.String | نوع الملف. |
| fileCreator | java.lang.String | منشئ الملف. |

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

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| version | int |  |
| uniqueId | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)
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
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


يحصل أو يعيّن معرف مكتبة الرسومات AdobeStockId، لمكتبات Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


يحصل على حالة ترخيص Adobe Stock إذا كان متاحًا، لمكتبات Adobe® Photoshop® CC.

القيمة: حالة ترخيص Adobe Stock أو سلسلة فارغة إذا لم يتوفر.

**Returns:**
java.lang.String
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
### getDate() {#getDate--}
```
public final Date getDate()
```


يحصل أو يعيّن تاريخ ووقت الكتابة الأخير للملف الخارجي في مصدر بيانات LiFE لمورد PSD LnkE.

**Returns:**
java.util.Date
### getDate_internalized() {#getDate-internalized--}
```
public final System.DateTime getDate_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getElementName() {#getElementName--}
```
public final String getElementName()
```


يحصل أو يعيّن اسم عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


يحصل أو يعيّن مرجع عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


يحصل أو يعيّن اسم الملف الخارجي أو المدمج في مورد ربط PSD.

القيمة: اسم الملف الخارجي أو المدمج.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


يحصل أو يعيّن حجم الملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


يحصل أو يعيّن المسار الكامل للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE.

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
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


يحصل أو يعيّن المسار النسبي للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE.

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

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


يحصل أو يعيّن معرف مكتبة الرسومات AdobeStockId، لمكتبات Adobe® Photoshop® CC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


يحصل أو يعيّن تاريخ ووقت الكتابة الأخير للملف الخارجي في مصدر بيانات LiFE لمورد PSD LnkE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


يحصل أو يعيّن اسم عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


يحصل أو يعيّن مرجع عنصر مكتبة الرسومات، لمكتبات Adobe® Photoshop® CC.

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

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


يحصل أو يعيّن اسم الملف الخارجي أو المدمج في مورد ربط PSD.

القيمة: اسم الملف الخارجي أو المدمج.

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

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


يحصل أو يعيّن حجم الملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


يحصل أو يعيّن المسار الكامل للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE.

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

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


يحصل أو يعيّن المسار النسبي للملف الخارجي في مصدر البيانات LiFE لمورد PSD LnkE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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


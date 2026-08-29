---
title: "SmartObjectProvider"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يحدد موفر الكائن الذكي الذي يوفر الحصول على/تعيين مصادر البيانات من موارد الروابط العالمية لملف PSD ومحتوياتها."
type: docs
weight: 17
url: /ar/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

يحدد موفر الكائن الذكي الذي يوفر الحصول على/تعيين مصادر البيانات من موارد الروابط العالمية لملف PSD ومحتوياتها.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | يحوّل الطبقات إلى كائن ذكي مدمج. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | يحوّل الطبقات إلى كائن ذكي مدمج. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | يُنشئ مثيلًا جديدًا من الفئة [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | يضمّن جميع الكائنات الذكية المرتبطة في الصورة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | يحصل على نوع محتوى طبقة الكائن الذكي. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | يحصل على محتويات الملف المدمج أو المرتبط. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | يحصل على مصدر بيانات الرابط بواسطة المعرف الفريد. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | يقوم بتحميل المحتويات. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | ينشئ طبقة كائن ذكي جديدة عن طريق نسخ الطبقة المصدر. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | يزيل مصادر البيانات من الموارد المدمجة والخارجية التي لا توجد في القائمة المقدمة من GUIDs الصالحة. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | يستبدل مصدر البيانات في الموارد العامة بالمحتويات المقدمة للدمج. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | يستبدل مصدر البيانات في موارد LinkResource العالمية بمصدر البيانات الجديد الذي تم إنشاؤه من ملف خارجي. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | يضبط محتويات الملف المدمج أو الخارجي. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | يضبط (يستبدل أو يضيف) مصدر بيانات الرابط في المورد العالمي للروابط. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | يحدّث محتوى جميع الكائنات الذكية المعدّلة في الصورة. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | يحدّث جميع طبقات الكائن الذكي داخل الحاوية التي يتطابق معرفها  UniqueId  مع  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


يحوّل الطبقات إلى كائن ذكي مدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقات. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


يحوّل الطبقات إلى كائن ذكي مدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerNumbers | int[] | أرقام الطبقات. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


يُنشئ مثيلًا جديدًا من الفئة [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | الحاوية. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


يضمّن جميع الكائنات الذكية المرتبطة في الصورة.

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


يحصل على نوع محتوى طبقة الكائن الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | المعرّف الفريد. |

**Returns:**
int - نوع محتوى طبقة الكائن الذكي.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


يحصل على محتويات الملف المدمج أو المرتبط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | المعرّف الفريد لمصدر بيانات الرابط. |

**Returns:**
byte[] - محتويات  byte[]  .
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


يحصل على مصدر بيانات الرابط بواسطة المعرف الفريد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | المعرّف الفريد. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


يقوم بتحميل المحتويات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | المعرّف الفريد. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


ينشئ طبقة كائن ذكي جديدة عن طريق نسخ الطبقة المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | طبقة المصدر. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


يزيل مصادر البيانات من الموارد المضمنة والخارجية التي لا توجد في القائمة المقدمة من GUIDs الصالحة. تقوم هذه الطريقة بتنظيف مصادر البيانات اليتيمة عن طريق المقارنة مع معرفات مصادر البيانات الصالحة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | قائمة GUIDs لمصادر البيانات الصالحة التي يجب الاحتفاظ بها. سيتم إزالة مصادر البيانات غير الموجودة في هذه القائمة. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


يستبدل مصدر البيانات في الموارد العامة بالمحتويات المقدمة للدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | المعرّف الفريد لمصدر البيانات الحالي. |
| contents | byte[] | البيانات لمصدر بيانات جديد. |

**Returns:**
com.aspose.ms.System.Guid - المعرف الفريد لمصدر البيانات المضمن الذي تم إنشاؤه.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


يستبدل مصدر البيانات في موارد LinkResource العالمية بمصدر البيانات الجديد الذي تم إنشاؤه من ملف خارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | المورد المرتبط. |
| linkedPath | java.lang.String | المسار المطلق للملف المرتبط. |
| isReplaceOnlyThis | boolean | إذا كان صحيحًا، فلا تقم بإزالة مصدر البيانات في الموارد العامة. |

**Returns:**
com.aspose.ms.System.Guid - المعرف الفريد Guid لمصدر البيانات المرتبط الذي تم إنشاؤه. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


يضبط محتويات الملف المدمج أو الخارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | المعرّف الفريد لمصدر بيانات الرابط. |
| بيانات | byte[] | البيانات. |
| fileType | java.lang.String | نوع ملف البيانات. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


يضبط (يستبدل أو يضيف) مصدر بيانات الرابط في المورد العالمي للروابط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | مصدر بيانات الارتباط. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


يحدّث محتوى جميع الكائنات الذكية المعدّلة في الصورة.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


يقوم بتحديث جميع طبقات الكائن الذكي داخل الحاوية التي يتطابق معرفها  UniqueId  مع  oldGuid . يتم إعادة تعيين معرف UniqueId للطبقات المتطابقة إلى  newGuid  ويتم تحديث محتواها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | المعرّف الفريد لمصدر بيانات الكائن الذكي الأصلي الذي سيتم استبداله. |
| newGuid | com.aspose.ms.System.Guid | المعرّف الفريد لمصدر بيانات الكائن الذكي الجديد لتعيينه. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | إعدادات الدقة التي يجب تطبيقها عند تحديث المحتوى. إذا كان null، يتم استخدام دقة الصورة. |

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


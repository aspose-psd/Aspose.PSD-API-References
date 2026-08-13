---
title: "فئة LiFdDataSource"
type: docs
weight: 510
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | يُنشئ مثالا جديدًا من الفئة [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | يُنشئ مثالا جديدًا من الفئة [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفلًا.<br/>            حالة القفل للأصل، لمكتبات Adobe® Photoshop® СС. |
| asset_mod_time | double | r/w | يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبة Adobe® Photoshop® СС. |
| child_doc_id | string | r/w | يحصل أو يعيّن معرف المستند الفرعي في مصدر البيانات liFE أو liFD لمورد Lnk2 / LnkE Adobe® Photoshop®. |
| comp_id | int | r/w | يحصل أو يعيّن معرف الـ comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ.<br/>            الـ comps هي تركيبات لتخطيط الصفحة يمكن للمصممين إنشاؤها. باستخدام الـ layer comps، يمكنك إنشاء وإدارة وعرض إصدارات متعددة<br/>            لتخطيط في ملف Adobe® Photoshop® واحد. الـ layer comp هو لقطة لحالة لوحة الـ Layers. الـ layer comps تحفظ ثلاثة أنواع من خيارات الطبقة لكن<br/>            هذه الخاصية تحصل على معرف اختيار الـ Layer Comp للكائنات الذكية.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| البيانات | byte | r/w | يحصل أو يعيّن بيانات الكائن الذكي المدمج في ملف PSD. |
| file_creator | string | r/w | يحصل أو يعيّن منشئ الملف في مورد PSD بصيغة LnkE / Lnk2. |
| file_type | string | r/w | يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE. |
| has_file_open_descriptor | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات الارتباط يحتوي على موصِّف فتح الملف: CompId و OriginalCompId. |
| is_library_link | bool | r | يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD يربط إلى عنصر مكتبة Adobe® Photoshop® СС. |
| الطول | long | r | يحصل على طول مصدر البيانات للارتباط بوحدة البايت. |
| original_comp_id | int | r | يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء.<br/>            هذه الخاصية تحصل على معرف اختيار طبقة الـ Comp الأصلي لكائنات Smart Objects.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">طبقات الـ Comp في كائنات Smart Objects</see> |
| original_file_name | string | r | يحصل على اسم الملف الأصلي لمصدر البيانات في مورد الارتباط العالمي لـ Adobe® Photoshop®. |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | يحصل على نوع مصدر البيانات للارتباط العالمي في Adobe® Photoshop® والذي يمكن أن يكون أحد التالي أو لا شيء:<br/>            ملف الارتباط المدمج liFD الذي يتطابق مع PSD Lnk2Resource<br/>            ملف الارتباط الخارجي liFE الذي يتطابق مع PSD LnkeResource<br/>            اسم ملف الارتباط liFA |
| unique_id | Guid | r | يحصل على المعرف الفريد العالمي لمصدر البيانات في مورد ارتباط PSD. |
| version | int | r | يحصل على إصدار مصدر البيانات في مورد PSD LnkE / Lnk2. |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

يُنشئ مثالا جديدًا من الفئة [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

يُنشئ مثالا جديدًا من الفئة [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| version | int | الإصدار. |
| unique_id | Guid | المعرف الفريد. |
| original_file_name | string | اسم الملف الأصلي. |
| file_type | string | نوع الملف. |
| file_creator | string | منشئ الملف. |


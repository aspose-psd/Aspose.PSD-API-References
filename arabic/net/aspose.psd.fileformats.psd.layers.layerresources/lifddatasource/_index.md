---
title: Class LiFdDataSource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource فصل. يحدد فئة مصدر بيانات liFD في ملف PSD الذي يحتوي على معلومات حول ملف مضمن. هذا جزء من PSD File Format Manipulation API الذي يساعد على تعديل ملفات Adobe Photoshop
type: docs
weight: 2670
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
## LiFdDataSource class

يحدد فئة مصدر بيانات liFD في ملف PSD الذي يحتوي على معلومات حول ملف مضمن. هذا جزء من PSD File Format Manipulation API الذي يساعد على تعديل ملفات Adobe® Photoshop®

```csharp
public class LiFdDataSource : LinkDataSource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | يقوم بتهيئة مثيل جديد لملف`LiFdDataSource` فئة . |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | يقوم بتهيئة مثيل جديد لملف`LiFdDataSource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان أصل PSD مؤمنًا. حالة تأمين الأصل ، لأصول مكتبات Adobe® Photoshop® СС . |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | الحصول على وقت تعديل الأصل أو تعيينه ، لأصول مكتبات Adobe® Photoshop® СС . |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | الحصول على أو تعيين معرف المستند الفرعي في مصدر بيانات liFE أو liFD لمورد Lnk2 / LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | الحصول على أو تعيين معرف التركيب المحدد حاليًا للمستند الفرعي ، والذي سيكون -1 إذا لم يتم تحديد أي منها . التركيبات هي تركيبات لتخطيط الصفحة والتي يمكن للمصممين إنشاؤها. باستخدام تركيبات الطبقة ، يمكنك إنشاء إصدارات متعددة من التخطيط وإدارتها وعرضها في ملف Adobe® Photoshop® واحد. تراكب الطبقة هو لقطة لحالة لوحة Layers. تقوم تركيبات الطبقة بحفظ ثلاثة أنواع من خيارات الطبقة ولكن تحصل هذه الخاصية على معرف تحديد تراكب الطبقة للكائنات الذكية.[تراكبات الطبقة في الكائنات الذكية](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | الحصول على أو تعيين بيانات الكائن الذكي المضمنة في ملف PSD. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | الحصول على أو تعيين منشئ الملف بتنسيق PSD LnkE / Lnk2 Resource. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | الحصول على أو تحديد نوع الملف المضمن أو الخارجي الذي يحتوي أو يرتبط مورد Adobe® Photoshop® Lnk2 / LnkE. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | الحصول على قيمة أو تعيينها للإشارة إلى ما إذا كان مصدر بيانات الارتباط هذا يحتوي على واصف فتح الملف: CompId و OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ارتباط PSD هذا يرتبط بعنصر مكتبة Adobe® Photoshop® СС. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | الحصول على طول مصدر بيانات الارتباط بالبايت. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | يحصل على المعرف الأصلي لـ Comp المحدد حاليًا للمستند الفرعي ، والذي سيكون -1 إذا لم يتم تحديد أي منها.[تراكبات الطبقة في الكائنات الذكية](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | الحصول على اسم الملف الأصلي لمصدر البيانات في مورد الارتباط العالمي Adobe® Photoshop® . |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | الحصول على نوع مصدر بيانات الارتباط العالمي Adobe® Photoshop® الذي يمكن أن يكون أحد الأنواع التالية أو لا شيء: liFD الملف المرتبط المضمن الذي يتوافق مع PSD Lnk2Resource ملف PSD المرتبط الخارجي liFE الذي يتوافق مع LnkeResource الاسم المستعار للملف المرتبط liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | الحصول على المعرف الفريد العام لمصدر البيانات في مورد ارتباط PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | يحصل على نسخة مصدر البيانات في مصدر PSD LnkE / Lnk2. |

### أنظر أيضا

* class [LinkDataSource](../linkdatasource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)



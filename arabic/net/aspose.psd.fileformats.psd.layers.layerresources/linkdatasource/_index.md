---
title: "الفئة LinkDataSource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource. يعرّف الفئة LinkDataSource التي تحتوي على معلومات حول ملف مرتبط أو أصل في ملف PSD."
type: docs
weight: 2990
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

يعرّف فئة LinkDataSource التي تحتوي على معلومات حول ملف مرتبط أو أصل في ملف PSD.

```csharp
public abstract class LinkDataSource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان أصل PSD مقفولًا. حالة القفل للأصل، لأصول مكتبات Adobe® Photoshop® СС. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | يحصل أو يعيّن وقت تعديل الأصل، لأصول مكتبات Adobe® Photoshop® СС. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | يحصل أو يعيّن معرف المستند الفرعي في مصدر البيانات liFE أو liFD الخاص بموارد Lnk2 / LnkE لـ Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | يحصل أو يعيّن معرف الـ comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ. الـ comps هي تركيبات لتخطيط الصفحة يمكن للمصممين إنشاؤها. باستخدام الـ layer comps، يمكنك إنشاء وإدارة وعرض إصدارات متعددة من التخطيط في ملف Adobe® Photoshop® واحد. الـ layer comp هو لقطة لحالة لوحة Layers. الـ layer comps تحفظ ثلاثة أنواع من خيارات الطبقة لكن هذه الخاصية تحصل على معرف اختيار الـ Layer Comp للكائنات الذكية. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | يحصل أو يعيّن مُنشئ الملف في مورد PSD بصيغة LnkE / Lnk2. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | يحصل أو يعيّن نوع الملف المدمج أو الخارجي الذي يحتويه أو يربطه مورد Adobe® Photoshop® Lnk2 / LnkE. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان مصدر بيانات الارتباط هذا يحتوي على واصف فتح الملف: CompId و OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | يحصل على قيمة تشير إلى ما إذا كان مصدر بيانات ربط PSD هذا يربط إلى عنصر مكتبة Adobe® Photoshop® СС. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | يحصل على طول مصدر بيانات الارتباط بالبايت. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | يحصل على المعرف الأصلي للـ Comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أيٍّ. هذه الخاصية تحصل على معرف اختيار الـ layer Comp الأصلي للكائنات الذكية. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | يحصل على اسم الملف الأصلي لمصدر البيانات في مورد ربط عالمي لـ Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | يحصل على نوع مصدر بيانات الارتباط العالمي لـ Adobe® Photoshop® والذي يمكن أن يكون أحد التالي أو لا شيء: ملف الارتباط المدمج liFD الذي يت对应 مع مورد PSD Lnk2Resource، ملف الارتباط الخارجي liFE الذي يت对应 مع مورد PSD LnkeResource، اسم مستعار ملف الارتباط liFA. |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | يحصل على المعرف العالمي الفريد لمصدر البيانات في مورد ربط PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | يحصل على إصدار مصدر البيانات في مورد PSD LnkE / Lnk2. |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



---
title: Class LinkResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource فصل. يحدد فئة LinkResource التي تحتوي على معلومات حول الملفات المرتبطة أو المضمنة في صورة بتنسيق PSD . قد يحتوي مورد الارتباط على عدةLinkDataSource المثيلات التي يمكن الوصول إليها من قبل المفهرسين في أي فئة مشتقة.
type: docs
weight: 2710
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

يحدد فئة LinkResource التي تحتوي على معلومات حول الملفات المرتبطة أو المضمنة في صورة بتنسيق PSD . قد يحتوي مورد الارتباط على عدة[`LinkDataSource`](../linkdatasource/) المثيلات التي يمكن الوصول إليها من قبل المفهرسين في أي فئة مشتقة.

```csharp
public abstract class LinkResource : LayerResource
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | الحصول على عدد مصادر بيانات الارتباط التي يمكن للمفهرس الوصول إليها. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان مثيل مورد الارتباط فارغًا. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | يحصل على ملف[`LinkDataSource`](../linkdatasource/) في الفهرس المحدد وهو المعرف الفريد لمصدر بيانات الارتباط .. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | الحصول على طول مورد الارتباط العام لـ PSD بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | الحصول على إصدار تنسيق PSD . |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | الحصول على توقيع مورد الارتباط العالمي لـ PSD . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | يحفظ بيانات كتلة المورد. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)



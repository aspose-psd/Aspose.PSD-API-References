---
title: "الفئة LinkResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource الفئة. يحدد فئة LinkResource التي تحتوي على معلومات حول الملفات المرتبطة أو المدمجة في صورة بصيغة PSD. قد يحتوي مورد الارتباط على عدة مثيلات LinkDataSource يمكن الوصول إليها عبر الفهارس في أي فئة مشتقة."
type: docs
weight: 3010
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

يحدد فئة LinkResource التي تحتوي على معلومات حول الملفات المرتبطة أو المدمجة في صورة بصيغة PSD. قد يحتوي مورد الارتباط على عدة مثيلات [`LinkDataSource`](../linkdatasource/) يمكن الوصول إليها عبر الفهارس في أي فئة مشتقة.

```csharp
public abstract class LinkResource : LayerResource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | يحصل على عدد مصادر بيانات الرابط التي يمكن الوصول إليها عبر الفهرس. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل من مورد الرابط فارغًا. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | يحصل على [`LinkDataSource`](../linkdatasource/) في الفهرس المحدد والذي هو المعرف الفريد لمصدر بيانات الارتباط. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | يحصل على طول مورد الرابط العام لملف PSD بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | يحفظ بيانات كتلة المورد. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



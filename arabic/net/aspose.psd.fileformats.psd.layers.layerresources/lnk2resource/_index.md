---
title: "الفئة Lnk2Resource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource. يحدد الفئة التي تحتوي على معلومات حول الملفات المدمجة في صورة بتنسيق PSD. قد يحتوي مورد الارتباط على عدة مثيلات LiFdDataSource يمكن الوصول إليها عبر الفهرس."
type: docs
weight: 3030
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

يحدد الفئة التي تحتوي على معلومات حول الملفات المدمجة في صورة بتنسيق PSD. قد يحتوي مورد الارتباط على عدة مثيلات [`LiFdDataSource`](../lifddatasource/) يمكن الوصول إليها عبر الفهرس.

```csharp
public class Lnk2Resource : LinkResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | ينشئ مثلاً جديداً من الفئة `Lnk2Resource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | يحصل على عدد مصادر بيانات الرابط التي يمكن الوصول إليها عبر الفهرس. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل من مورد الرابط فارغًا. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | يحصل على [`LiFdDataSource`](../lifddatasource/) عند الفهرس المحدد. (فهرسان) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | يحصل على طول مورد الرابط العام لملف PSD بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | يحفظ بيانات كتلة المورد. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



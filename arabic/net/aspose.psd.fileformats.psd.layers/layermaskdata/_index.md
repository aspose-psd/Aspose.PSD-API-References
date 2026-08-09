---
title: "الفئة LayerMaskData"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData class. يعرّف الفئة الأساسية LayerMaskData التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD. يمكنه المساعدة في تعديل ملفات Adobe Photoshop برمجيًا وأتمتة تحرير تنسيق PSD. إذا كان للطبقة قناع نقطي فقط فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كان للطبقة قناع متجه فقط فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسوم مسبقًا والمخزن مؤقتًا. إذا كانت الطبقة تحتوي على أقنعة طبقة وأقنعة متجه فإن ImageData يحتوي على القناع النقطي والقناع المتجه المرسوم مسبقًا معًا. يجب أن يكون طول بايتات ImageData مساويًا للعرض * الارتفاع لخصائص MaskRectangle. لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData ليس كافيًا للحفظ الصحيح لأن القنوات لا تُحدّث رغم أنه قد يوفر عرضًا صحيحًا. يجب استخدام طريقة AddLayerMask لذلك."
type: docs
weight: 2440
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

يعرّف الفئة الأساسية LayerMaskData التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD. يمكنه المساعدة في تعديل ملفات Adobe® Photoshop® برمجيًا وأتمتة تحرير تنسيق PSD. إذا كان للطبقة قناع نقطي فقط فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كان للطبقة قناع متجه فقط فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسوم (المخزن مؤقتًا). إذا كانت الطبقة تحتوي على أقنعة طبقة وأقنعة متجه فإن ImageData يحتوي على القناع النقطي والقناع المتجه المرسوم معًا. يجب أن يكون طول بايتات [`ImageData`](./imagedata/) مساويًا للعرض * الارتفاع لخصائص [`MaskRectangle`](./maskrectangle/). لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData ليس كافيًا للحفظ الصحيح لأن القنوات لا تُحدّث؛ رغم أنه قد يوفر عرضًا صحيحًا. يجب استخدام طريقة [`AddLayerMask`](../layer/addlayermask/) لذلك.

```csharp
public abstract class LayerMaskData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة السفلي. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | يحصل على حجم بيانات قناع الطبقة. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | يحصل أو يضبط اللون الافتراضي. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | يحصل أو يضبط أعلام قناع الطبقة. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة الأيسر. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | يحصل أو يضبط قناع [`Rectangle`](../../aspose.psd/rectangle/) لقناع الطبقة في ملف PSD. يأخذ الخصائص اليسار، اليمين، الأعلى والأسفل وينشئ [`Rectangle`](../../aspose.psd/rectangle/). |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة العلوي. |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)



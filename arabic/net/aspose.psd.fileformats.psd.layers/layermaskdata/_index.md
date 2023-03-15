---
title: Class LayerMaskData
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData فصل. يحدد فئة LayerMaskData الأساسية التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD . يمكن أن تساعد في تعديل ملفات Adobe Photoshop برمجيًا وأتمتة تحرير تنسيق PSD . إذا كانت الطبقة تحتوي فقط على قناع نقطي  فإن ImageData تحتوي على البيانات النقطية بايت بيانات القناع . إذا كانت الطبقة تحتوي على قناع متجه فقط  فإن ImageData تحتوي على بايت بيانات قناع متجه مخزنة مؤقتًا. الImageDataيجب أن يكون طول البايت متساويًا في العرض  الارتفاعMaskRectangle Properties. لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData ليس كافيًا لـ save الصحيح لأن القنوات لا يتم تحديثها  على الرغم من أنه قد يوفر العرض الصحيحAddLayerMask يجب استخدام الطريقة لذلك.
type: docs
weight: 2240
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

يحدد فئة LayerMaskData الأساسية التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD . يمكن أن تساعد في تعديل ملفات Adobe® Photoshop® برمجيًا وأتمتة تحرير تنسيق PSD . إذا كانت الطبقة تحتوي فقط على قناع نقطي ، فإن ImageData تحتوي على البيانات النقطية بايت بيانات القناع . إذا كانت الطبقة تحتوي على قناع متجه فقط ، فإن ImageData تحتوي على بايت بيانات قناع متجه (مخزنة مؤقتًا). ال[`ImageData`](./imagedata/)يجب أن يكون طول البايت متساويًا في العرض * الارتفاع[`MaskRectangle`](./maskrectangle/) Properties. لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData ليس كافيًا لـ save الصحيح لأن القنوات لا يتم تحديثها ؛ على الرغم من أنه قد يوفر العرض الصحيح[`AddLayerMask`](../layer/addlayermask/) يجب استخدام الطريقة لذلك.

```csharp
public abstract class LayerMaskData
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | الحصول على أو تحديد موضع قناع الطبقة السفلية. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | يحصل على حجم بيانات قناع الطبقة. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | الحصول على اللون الافتراضي أو تعيينه. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | الحصول على أو تعيين أعلام قناع الطبقة. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | الحصول على أو تعيين بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | الحصول على أو تحديد موضع قناع الطبقة الأيسر. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | الحصول على القناع أو تحديده[`Rectangle`](../../aspose.psd/rectangle/)قناع الطبقة في ملف PSD. يأخذ خصائص وينشئ اليسار واليمين والعلوي والسفلي[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | الحصول على أو تحديد موضع قناع الطبقة الصحيح. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | الحصول على أو تحديد موضع قناع الطبقة العليا. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* المجسم [Aspose.PSD](../../)



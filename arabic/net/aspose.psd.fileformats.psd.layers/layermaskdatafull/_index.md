---
title: "الفئة LayerMaskDataFull"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull class. يعرّف الفئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تحتوي الطبقة على كل من أقنعة الطبقة وأقنعة المتجه. وإلا يتم استخدام LayerMaskDataShort. يحتوي ImageData على القناع النقطي والقناع المتجه المرسوم معًا. يجب أن يكون طول بايتات ImageData مساويًا لخصائص MaskRectangle.Width  MaskRectangle.Height."
type: docs
weight: 2450
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

يعرّف الفئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تحتوي الطبقة على كل من أقنعة الطبقة وأقنعة المتجه. وإلا يتم استخدام [`LayerMaskDataShort`](../layermaskdatashort/). يحتوي ImageData على القناع النقطي والقناع المتجه المرسوم معًا. يجب أن يكون طول بايتات ImageData مساويًا لخصائص MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | يحصل أو يضبط لون الخلفية. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة السفلي. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | يحصل على حجم بيانات قناع الطبقة. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | يحصل أو يضبط اللون الافتراضي. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | يحصل أو يضبط موضع القناع النقطي السفلي المحيط في طبقة صورة PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | يحصل أو يضبط موضع القناع النقطي الأيسر المحيط في طبقة ملف PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | يحصل أو يضبط موضع القناع النقطي الأيمن المحيط في طبقة ملف PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | يحصل أو يضبط الموضع العلوي القائم للقناع النقطي في طبقة صورة PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | يحصل أو يضبط أعلام قناع الطبقة. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | يحصل أو يضبط بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة الأيسر. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | يحصل أو يضبط قناع [`Rectangle`](../../aspose.psd/rectangle/) لقناع الطبقة في ملف PSD. يأخذ الخصائص اليسار، اليمين، الأعلى والأسفل وينشئ [`Rectangle`](../../aspose.psd/rectangle/). |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | يحصل أو يضبط أعلام قناع الطبقة المستخدمة للقناع المستخدم / النقطي. بالنسبة لقناع المتجه تُستخدم خاصية Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة العلوي. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | يحصل أو يضبط بيانات القناع المستخدم (النقطي) لطبقة في ملف PSD. (هناك قناع متجه مرسوم في خاصية MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | يحصل أو يضبط مستطيل القناع المستخدم (المحيط) في طبقة صورة PSD.. |

### انظر أيضًا

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)



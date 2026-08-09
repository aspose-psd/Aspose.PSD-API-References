---
title: "الفئة LayerMaskDataShort"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort. تعرف فئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تكون الطبقة تحتوي فقط على قناع نقطي أو قناع متجه وليس كليهما. وإلا يتم استخدام LayerMaskDataFull. إذا كانت الطبقة تحتوي فقط على قناع نقطي فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كانت الطبقة تحتوي فقط على قناع متجه فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسومة مؤقتًا. يجب أن يكون طول بايتات ImageData مساويًا للعرض * الارتفاع لخصائص MaskRectangle."
type: docs
weight: 2460
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

تعرف فئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تكون الطبقة تحتوي فقط على قناع نقطي أو قناع متجه وليس كليهما. وإلا يتم استخدام [`LayerMaskDataFull`](../layermaskdatafull/). إذا كانت الطبقة تحتوي فقط على قناع نقطي فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كانت الطبقة تحتوي فقط على قناع متجه فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسومة (المخزنة مؤقتًا). يجب أن يكون طول بايتات [`ImageData`](../layermaskdata/imagedata/) مساويًا للعرض * الارتفاع لخصائص [`MaskRectangle`](../layermaskdata/maskrectangle/).

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | ينشئ مثيلًا جديدًا من فئة `LayerMaskDataShort`. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | يحصل أو يعيّن حشو قناع الطبقة. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة الأيمن. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | يحصل أو يضبط موضع قناع الطبقة العلوي. |

### انظر أيضًا

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)



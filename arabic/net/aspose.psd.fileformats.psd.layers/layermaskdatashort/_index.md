---
title: Class LayerMaskDataShort
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort فصل. يحدد فئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في ملف PSD layer عندما تحتوي الطبقة على قناع نقطي أو متجه فقط وليس كلاهما. خلاف ذلك  أLayerMaskDataFull . إذا كانت الطبقة تحتوي فقط على قناع نقطي  فإن ImageData تحتوي على بايت بيانات قناع نقطي.ImageDataيجب أن يكون طول البايت متساويًا في العرض  الارتفاعMaskRectangle الخصائص .
type: docs
weight: 2260
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

يحدد فئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في ملف PSD layer عندما تحتوي الطبقة على قناع نقطي أو متجه فقط وليس كلاهما. خلاف ذلك ، أ[`LayerMaskDataFull`](../layermaskdatafull/) . إذا كانت الطبقة تحتوي فقط على قناع نقطي ، فإن ImageData تحتوي على بايت بيانات قناع نقطي.[`ImageData`](../layermaskdata/imagedata/)يجب أن يكون طول البايت متساويًا في العرض * الارتفاع[`MaskRectangle`](../layermaskdata/maskrectangle/) الخصائص .

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Default_Constructor |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | الحصول على أو تعيين حشوة قناع الطبقة. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | الحصول على أو تحديد موضع قناع الطبقة الصحيح. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | الحصول على أو تحديد موضع قناع الطبقة العليا. |

### أنظر أيضا

* class [LayerMaskData](../layermaskdata/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* المجسم [Aspose.PSD](../../)



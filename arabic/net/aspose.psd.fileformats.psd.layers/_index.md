---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD لمرجع .NET API
description: تحتوي مساحة الاسم على طبقات تنسيق ملف PSD.
type: docs
weight: 210
url: /ar/net/aspose.psd.fileformats.psd.layers/
---
تحتوي مساحة الاسم على طبقات تنسيق ملف PSD.

## الطبقات

| فصل | وصف |
| --- | --- |
| [BlendRange](./blendrange/) | نطاق المزج . |
| [ChannelInformation](./channelinformation/) | معلومات القناة . |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | قسم قناع الطبقة العمومي . |
| [Layer](./layer/) | طبقة psd . |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | نطاقات مزج الطبقة . |
| [LayerGroup](./layergroup/) | فئة طبقة المجموعة |
| [LayerHashCalculator](./layerhashcalculator/) | حاسبة التجزئة لطبقات PSD. يمكن استخدامه لإيجاد طبقات متساوية أو مختلفة في ملفات PSD مختلفة |
| [LayerMaskData](./layermaskdata/) | يحدد فئة LayerMaskData الأساسية التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD . يمكن أن تساعد في تعديل ملفات Adobe® Photoshop® برمجيًا وأتمتة تحرير تنسيق PSD . إذا كانت الطبقة تحتوي فقط على قناع نقطي ، فإن ImageData تحتوي على البيانات النقطية بايت بيانات القناع . إذا كانت الطبقة تحتوي على قناع متجه فقط ، فإن ImageData تحتوي على بايت بيانات قناع متجه (مخزنة مؤقتًا). ال[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)يجب أن يكون طول البايت متساويًا في العرض * الارتفاع[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) Properties. لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData ليس كافيًا لـ save الصحيح لأن القنوات لا يتم تحديثها ؛ على الرغم من أنه قد يوفر العرض الصحيح[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) يجب استخدام الطريقة لذلك. |
| [LayerMaskDataFull](./layermaskdatafull/) | يحدد فئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في ملف PSD layer عندما تحتوي الطبقة على أقنعة طبقة وأقنعة متجهة. خلاف ذلك ، أ[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) . تحتوي ImageData على القناع النقطي وقناع المتجه النقطي معًا. |
| [LayerMaskDataShort](./layermaskdatashort/) | يحدد فئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في ملف PSD layer عندما تحتوي الطبقة على قناع نقطي أو متجه فقط وليس كلاهما. خلاف ذلك ، أ[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) . إذا كانت الطبقة تحتوي فقط على قناع نقطي ، فإن ImageData تحتوي على بايت بيانات قناع نقطي.[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)يجب أن يكون طول البايت متساويًا في العرض * الارتفاع[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) الخصائص . |
| [LayerResource](./layerresource/) | يمثل معلومات الطبقة . |
| [LayerResourcesRegistry](./layerresourcesregistry/) | تحديد سجل موارد الطبقة لتحميل ملفات PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | فئة مدير الطبقات المرتبطة . |
| [SectionDividerLayer](./sectiondividerlayer/) | طبقة مقسم القسم لتمييز حدود المجلد (مجموعة الطبقات) . |
| [TextLayer](./textlayer/) | طبقة النص class |
## واجهات

| واجهه المستخدم | وصف |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | الواجهة الأساسية لإعدادات التعبئة |
| [ILayerResourceLoader](./ilayerresourceloader/) | مُحمل موارد الطبقة . |
## تعداد

| تعداد | وصف |
| --- | --- |
| [LayerFlags](./layerflags/) | أعلام الطبقة |
| [LayerMaskFlags](./layermaskflags/) | أعلام قناع الطبقة |



---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "المجال يحتوي على طبقات تنسيق ملف PSD."
type: docs
weight: 230
url: /ar/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
تحتوي مساحة الاسم على طبقات تنسيق ملف PSD.

## الفئات

| فئة | الوصف |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | فئة طبقة لوحة الرسم. |
| [BlendRange](./blendrange/) | نطاق الدمج. |
| [ChannelInformation](./channelinformation/) | معلومات القناة. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | قسم قناع الطبقة العالمي. |
| [Layer](./layer/) | طبقة psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | بيانات نطاقات دمج الطبقة. |
| [LayerGroup](./layergroup/) | فئة طبقة المجموعة |
| [LayerHashCalculator](./layerhashcalculator/) | حاسبة التجزئة لطبقات PSD. يمكن استخدامها للعثور على طبقات متساوية أو مختلفة في ملفات PSD مختلفة. |
| [LayerMaskData](./layermaskdata/) | يعرّف الفئة الأساسية LayerMaskData التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD. يمكنه المساعدة في تعديل ملفات Adobe® Photoshop® برمجيًا وأتمتة تحرير تنسيق PSD. إذا كانت الطبقة تحتوي على قناع نقطي فقط، فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كانت الطبقة تحتوي على قناع متجه فقط، فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسوم (المخزن مؤقتًا). إذا كانت الطبقة تحتوي على كل من القناع النقطي والقناع المتجه، فإن ImageData يحتوي على القناع النقطي والقناع المتجه المرسوم معًا. يجب أن يكون طول بايتات [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) مساويًا لـ Width * Height لخصائص [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). لاحظ أن إزالة / إضافة / تحديث LayerMaskData وحدها لا تكفي للحفظ الصحيح لأن القنوات غير محدثة؛ رغم ذلك قد توفر عرضًا صحيحًا. يجب استخدام طريقة [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) لهذا. |
| [LayerMaskDataFull](./layermaskdatafull/) | يعرّف الفئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تكون الطبقة لديها كل من أقنعة الطبقة والقناع المتجه. وإلا، يتم استخدام [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/). يحتوي ImageData على القناع النقطي والقناع المتجه المرسوم معًا. يجب أن يكون طول بايتات ImageData مساويًا لخصائص MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | يعرّف الفئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD عندما تكون الطبقة لديها قناع نقطي أو قناع متجه فقط وليس كليهما. وإلا، يتم استخدام [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/). إذا كانت الطبقة تحتوي على قناع نقطي فقط، فإن ImageData يحتوي على بايتات بيانات القناع النقطي. إذا كانت الطبقة تحتوي على قناع متجه فقط، فإن ImageData يحتوي على بايتات بيانات القناع المتجه المرسوم (المخزن مؤقتًا). يجب أن يكون طول بايتات [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) مساويًا لـ Width * Height لخصائص [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | يمثل معلومات الطبقة. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | حدد سجل موارد الطبقة لتحميل ملفات PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | فئة مدير الطبقات المرتبطة. |
| [SectionDividerLayer](./sectiondividerlayer/) | طبقة فاصل القسم لتحديد حدود المجلد (مجموعة الطبقات). |
| [ShapeLayer](./shapelayer/) | طبقة الشكل. تغلف منطق العمل مع طبقة الشكل والموارد المرتبطة. |
| [TextLayer](./textlayer/) | فئة طبقة النص |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | الواجهة الأساسية لإعدادات التعبئة |
| [ILayerResourceLoader](./ilayerresourceloader/) | محمل موارد الطبقة. |
| [IShapeLayer](./ishapelayer/) | يصف خصائص طبقة الشكل. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [LayerFlags](./layerflags/) | علامات الطبقة |
| [LayerMaskFlags](./layermaskflags/) | علامات قناع الطبقة |



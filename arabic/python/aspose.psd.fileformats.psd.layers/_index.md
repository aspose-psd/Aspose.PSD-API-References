---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /ar/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **فئة** | **الوصف** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | فئة طبقة لوحة الرسم. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | نطاق الدمج. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | معلومات القناة. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | قسم قناع الطبقة العالمي. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | الواجهة الأساسية لإعدادات التعبئة |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | محمل موارد الطبقة. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | يصف خصائص طبقة الشكل. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | طبقة PSD. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | بيانات نطاقات دمج الطبقة. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | فئة طبقة المجموعة |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | حاسبة التجزئة لطبقات PSD. يمكن استخدامها للعثور على طبقات متساوية أو مختلفة في ملفات PSD مختلفة |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | يعرف الفئة الأساسية LayerMaskData التي تحتوي على معلومات حول بيانات قناع الطبقة في ملف PSD.<br/>            يمكن أن تساعد في تعديل ملفات Adobe® Photoshop® برمجياً وأتمتة تحرير تنسيق PSD.<br/>            إذا كان للطبقة قناع نقطي فقط، فإن ImageData يحتوي على بايتات بيانات القناع النقطي.<br/>            إذا كان للطبقة قناع متجهي فقط، فإن ImageData يحتوي على بايتات بيانات القناع المتجهي المرسوم (المخزن مؤقتاً).<br/>            إذا كانت الطبقة تحتوي على كل من القناع النقطي والقناع المتجهي، فإن ImageData يحتوي على القناع النقطي والقناع المتجهي المرسوم معاً.<br/>            يجب أن يكون طول بايتات [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) مساويًا لـ Width * Height من خصائص [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            لاحظ أن مجرد إزالة / إضافة / تحديث LayerMaskData لا يكفي للحفظ الصحيح<br/>            لأن القنوات غير محدثة؛ رغم أنه قد يوفر عرضًا صحيحًا.<br/>            يجب استخدام طريقة [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) لذلك. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | يعرف الفئة LayerMaskDataFull التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD<br/>            عندما تكون الطبقة تحتوي على كل من أقنعة الطبقة والقناع المتجهي. وإلا، يتم استخدام [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/).<br/>            يحتوي ImageData على القناع النقطي والقناع المتجهي المرسوم معاً.<br/>            يجب أن يكون طول بايتات ImageData مساويًا لخصائص MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | يعرف الفئة LayerMaskDataShort التي تحتوي على معلومات حول بيانات القناع في طبقة ملف PSD<br/>            عندما تكون الطبقة لديها قناع نقطي أو متجهي فقط وليس كليهما. وإلا، يتم استخدام [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/).<br/>            إذا كان للطبقة قناع نقطي فقط، فإن ImageData يحتوي على بايتات بيانات القناع النقطي.<br/>            إذا كان للطبقة قناع متجهي فقط، فإن ImageData يحتوي على بايتات بيانات القناع المتجهي المرسوم (المخزن مؤقتاً).<br/>            يجب أن يكون طول بايتات [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) مساويًا لـ Width * Height من خصائص [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | يمثل معلومات الطبقة. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | حدد سجل موارد الطبقة لتحميل ملفات PSD. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | فئة مدير الطبقات المرتبطة. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | طبقة فاصل القسم لتحديد حدود المجلد (مجموعة الطبقات). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | طبقة الشكل. تغلف منطق العمل مع طبقة الشكل والموارد المرتبطة. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | فئة طبقة النص |
## **Enumerations**
| **تعداد** | **الوصف** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | علامات الطبقة |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | علامات قناع الطبقة |

---
title: "فئة LayerMaskDataFull"
type: docs
weight: 980
url: /ar/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | يُهيئ نسخة جديدة من فئة LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | byte | r/w | يحصل أو يضبط لون الخلفية. |
| أسفل | int | r/w | يحصل أو يعيّن موضع قناع الطبقة السفلية. |
| data_size | int | r | يحصل على حجم بيانات قناع الطبقة. |
| default_color | byte | r/w | يحصل أو يعيّن اللون الافتراضي. |
| enclosing_bottom | int | r/w | يحصل أو يعيّن موضع القناع النقطي السفلي المغلق في طبقة صورة PSD. |
| enclosing_left | int | r/w | يحصل أو يعيّن موضع القناع النقطي الأيسر المغلق في طبقة ملف PSD. |
| enclosing_right | int | r/w | يحصل أو يعيّن موضع القناع النقطي الأيمن المغلق في طبقة ملف PSD. |
| enclosing_top | int | r/w | يحصل أو يعيّن موضع القناع النقطي العلوي المغلق في طبقة صورة PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | يحصل أو يعيّن علامات قناع الطبقة. |
| image_data | byte | r/w | يحصل أو يعيّن بيانات قناع الطبقة (أو القناع المدمج / النهائي إذا كان هناك قناع متجه) في ملف PSD. |
| left | int | r/w | يحصل أو يعيّن موضع قناع الطبقة الأيسر. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | يحصل أو يعيّن قناع [Rectangle](/psd/python-net/aspose.psd/rectangle/) لقناع الطبقة في ملف PSD.<br/>            يأخذ خصائص اليسار واليمين والأعلى والأسفل وينشئ [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | يحصل أو يضبط علامات قناع الطبقة المستخدمة لقناع المستخدم/القناع النقطي. لقناع المتجه تُستخدم خاصية Flags. |
| right | int | r/w | يحصل أو يعيّن موضع قناع الطبقة الأيمن. |
| أعلى | int | r/w | يحصل أو يعيّن موضع قناع الطبقة العلوي. |
| user_mask_data | byte | r/w | يحصل أو يضبط بيانات قناع المستخدم (النقطي) لطبقة في ملف PSD. (هناك قناع متجه مُرصّص في خاصية MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | يحصل أو يضبط مستطيل قناع المستخدم (المحيط) في طبقة صورة PSD. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

يُهيئ نسخة جديدة من فئة LayerMaskDataFull


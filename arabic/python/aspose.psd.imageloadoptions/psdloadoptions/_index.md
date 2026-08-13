---
title: "فئة PsdLoadOptions"
type: docs
weight: 30
url: /ar/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | ينشئ مثلاً جديداً من فئة PsdLoadOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | يحصل أو يعيّن ما إذا كان سيتم الحفظ مع الصورة المُعالجة، مع أو بدون تحويل التشويه. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يعيّن خلفية [Image](/psd/python-net/aspose.psd/image/) [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | يحصل أو يعيّن وضع استعادة البيانات. |
| ignore_alpha_channel | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان سيتم تجاهل عرض طبقة النص الثابت في PSD عند تنفيذ عملية UpdateText. |
| load_effects_resource | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [load effects resource] (بشكل افتراضي لا يتم تحميل المورد). عند ضبط هذا الخيار سيتم عرض التأثيرات المدعومة فقط على الصورة المدمجة النهائية. |
| read_only_mode | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use read only mode]. هذا وضع القراءة فقط، مدعوم لتوافق مماثل مع Adobe Photoshop.<br/>            عندما يتم ضبط هذا الخيار، لن يتم حفظ جميع التغييرات المطبقة على الطبقات في الصورة النهائية. يتم استخدام جميع البيانات من قسم ImageData، لذا فهو مماثل لـ Photoshop. <br/>            بشكل افتراضي جميع الصور المحملة ليست متوافقة تمامًا مع Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use disk for load effects resource] (بشكل افتراضي يُستخدم القرص لتحميل موارد التأثيرات، ولكن يمكن استخدام الذاكرة إذا كان ذلك كافيًا بضبط هذه القيمة إلى false). |
| use_icc_profile_conversion | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تطبيق تحويل ملف تعريف ICC. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

ينشئ مثلاً جديداً من فئة PsdLoadOptions


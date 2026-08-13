---
title: "فئة VstkResource"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | يُنشئ مثلاً جديدًا من الفئة VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| fill_enabled | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان ملء Stroke مفعَّلًا. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | يحصل أو يضبط إعدادات التعبئة للخط. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| stroke_enabled | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تأثير stroke مفعَّلًا. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | يحصل أو يعيّن وضع Blend الخاص بـ Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | يحصل أو يعيّن كيان Stroke. الخاصية تحدد إعدادات ملء الـstroke. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | يحصل أو يضبط محاذاة خط نمط الخط. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | يحصل أو يعيّن نوع غطاء خط نمط stroke. |
| stroke_style_line_cap_width | double | r/w | يحصل أو يعيّن عرض غطاء خط Stroke. |
| stroke_style_line_dash_offset | int | r/w | يحصل أو يعيّن إزاحة الخط المتقطع لنمط stroke. |
| stroke_style_line_dash_set | double | r/w | يحصل أو يضبط مصفوفة من الفواصل الخطية. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | يحصل أو يعيّن نوع وصل خط نمط Stroke. |
| stroke_style_line_width | double | r/w | يحصل أو يعيّن عرض خط Stroke. |
| stroke_style_miter_limit | double | r/w | يحصل أو يعيّن حد الميتر لنمط stroke. |
| stroke_style_opacity | int | r/w | يحصل أو يعيّن شفافية نمط Stroke (0-100%). |
| stroke_style_resolution | double | r/w | يحصل أو يضبط دقة نمط الخط. |
| stroke_style_scale_lock | bool | r/w | يحصل أو يضبط قفل مقياس نمط الخط. |
| stroke_style_stroke_adjust | bool | r/w | يحصل أو يضبط تعديل الخط. |
| stroke_style_version | int | r/w | يحصل أو يضبط نسخة نمط الخط. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

يُنشئ مثلاً جديدًا من الفئة VstkResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |


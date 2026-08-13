---
title: "الفئة TypeToolInfoResource"
type: docs
weight: 1000
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | ينشئ مثيلًا جديدًا من الفئة TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| a_component | short | r/w | يحصل أو يعيّن مكوّنًا. |
| b_component | short | r/w | يحصل أو يعيّن المكوّن b. |
| character_count | int | r/w | يحصل أو يعيّن عدد الأحرف. |
| color_space_value | short | r/w | يحصل أو يعيّن قيمة مساحة اللون. |
| font_version | short | r/w | يحصل أو يعيّن نسخة الخط. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | يحصل أو يعيّن الخطوط. |
| fonts_count | short | r | يحصل على عدد الخطوط. |
| g_component | short | r/w | يحصل أو يعيّن المكوّن g. |
| horizontal_placement | int | r/w | يحصل أو يعيّن الموضع الأفقي. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| line_count | short | r | يحصل على عدد الأسطر. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | يحصل أو يضبط الأسطر. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| r_component | short | r/w | يحصل أو يضبط مكوّن r. |
| scale_factor | int | r/w | يحصل أو يضبط عامل المقياس. |
| selection_end | int | r/w | يحصل أو يضبط نهاية التحديد. |
| selection_start | int | r/w | يحصل أو يضبط بداية التحديد. |
| signature | int | r | يحصل على التوقيع. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | يحصل أو يضبط أنماط الخط. |
| styles_count | short | r | يحصل على عدد الأنماط. |
| transform_matrix | double | r/w | يحصل أو يضبط مصفوفة التحويل. |
| type_value | short | r/w | يحصل أو يضبط قيمة النوع. |
| version | short | r/w | يحصل أو يعيّن الإصدار. |
| vertical_placement | int | r/w | يحصل أو يضبط الموضع العمودي. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ حاوية الدفق المحددة. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

ينشئ مثيلًا جديدًا من الفئة TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| psd_version | int | إصدار PSD. |


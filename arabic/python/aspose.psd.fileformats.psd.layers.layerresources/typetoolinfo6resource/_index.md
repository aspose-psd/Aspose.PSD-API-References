---
title: "فئة TypeToolInfo6Resource"
type: docs
weight: 990
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | يقوم بتهيئة نسخة جديدة من الفئة [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| أسفل | int | r/w | يحصل أو يضبط الموقع السفلي. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن معرف الفئة. |
| class_name | string | r/w | يحصل أو يعيّن اسم الفئة. |
| descriptor_version | int | r/w | يحصل أو يعيّن إصدار الوصف. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | يحصل أو يضبط العناصر. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| left | int | r/w | يحصل أو يضبط الموقع الأيسر. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| right | int | r/w | يحصل أو يضبط الموقع الأيمن. |
| signature | int | r | يحصل على التوقيع. |
| text_version | short | r/w | يحصل أو يضبط نسخة النص. |
| أعلى | int | r/w | يحصل أو يضبط الموقع العلوي. |
| transform_matrix | double | r/w | يحصل أو يضبط مصفوفة التحويل. |
| version | short | r/w | يحصل أو يضبط نسخة أداة النوع. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن معرف الفئة. |
| warp_class_name | string | r/w | يحصل أو يضبط اسم فئة التشويه. |
| warp_descriptor_version | int | r/w | يحصل أو يضبط نسخة موصّف التشويه. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | الحصول أو تعيين عناصر الالتواء. |
| warp_version | short | r/w | يحصل أو يضبط نسخة التشويه. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

يقوم بتهيئة نسخة جديدة من الفئة [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | معرّف الفئة. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | معرّف فئة التشويه. |

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


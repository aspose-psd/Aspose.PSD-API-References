---
title: "فئة PlacedResource"
type: docs
weight: 830
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| anti_alias_policy | int | r/w | يحصل أو يعيّن سياسة إلغاء التمويه للطبقة الموضوعة في صورة PSD. |
| أسفل | double | r/w | يحصل أو يعيّن الموقع السفلي للطبقة الموضوعة في صورة PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | يحصل أو يعيّن حدود الطبقة الموضوعة في ملف PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | الحصول أو تعيين وحدة القياس لنقاط الشبكة الأفقية. |
| horizontal_mesh_points | double | r/w | الحصول أو تعيين نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| is_custom | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان نمط الالتواء لهذا الكائن مخصصًا.<br/>            إذا كان true يحتوي على نقاط الشبكة. إذا تم تعيينه إلى false يمسح نقاط الشبكة. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | الحصول أو تعيين عناصر الالتواء. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| left | double | r/w | الحصول أو تعيين الموقع الأيسر للطبقة الموضوعة في ملف PSD. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| page_number | int | r/w | الحصول أو تعيين رقم الصفحة للطبقة الموضوعة في ملف PSD. |
| perspective | double | r/w | الحصول أو تعيين قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| perspective_other | double | r/w | الحصول أو تعيين قيمة المنظور الأخرى للطبقة الموضوعة في ملف PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | الحصول أو تعيين نوع الطبقة الموضوعة في ملف PSD. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| right | double | r/w | الحصول أو تعيين الموقع الأيمن للطبقة الموضوعة في ملف PSD. |
| signature | int | r | يحصل على التوقيع. |
| أعلى | double | r/w | الحصول أو تعيين الموقع العلوي للطبقة الموضوعة في صورة PSD. |
| total_pages | int | r/w | الحصول أو تعيين إجمالي الصفحات للطبقة الموضوعة في ملف PSD. |
| transform_matrix | double | r/w | الحصول أو تعيين مصفوفة التحويل للطبقة الموضوعة في ملف PSD. |
| u_order | int | r/w | الحصول أو تعيين قيمة ترتيب U للطبقة الموضوعة في ملف PSD. |
| unique_id | Guid | r/w | الحصول أو تعيين المعرف الفريد العالمي للطبقة الموضوعة في صورة PSD. |
| v_order | int | r/w | الحصول أو تعيين قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |
| قيمة | double | r/w | الحصول أو تعيين قيمة الالتواء للطبقة الموضوعة في صورة PSD. |
| version | int | r | الحصول على نسخة الطبقة الموضوعة في ملف PSD، عادةً 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | الحصول أو تعيين وحدة القياس لنقاط الشبكة العمودية. |
| vertical_mesh_points | double | r/w | الحصول أو تعيين نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


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


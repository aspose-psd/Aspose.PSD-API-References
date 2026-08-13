---
title: "فئة SmartObjectResource"
type: docs
weight: 900
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| anti_alias_policy | int | r/w | يحصل أو يعيّن سياسة إلغاء التعرّج لبيانات طبقة الكائن الذكي في صورة PSD. |
| أسفل | double | r/w | يحصل أو يعيّن الموقع السفلي للطبقة الموضوعة في صورة PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | يحصل أو يعيّن حدود الطبقة الموضوعة في ملف PSD. |
| comp | int | r/w | يحصل أو يعيّن قيمة الـ comp لبيانات طبقة الكائن الذكي في ملف PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">تراكيب الطبقات في الكائنات الذكية</see> |
| comp_id | int | r/w | يحصل أو يعيّن معرف الـ comp المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي منها.<br/>            الـ comps هي تراكيب لتخطيط الصفحة يمكن للمصممين إنشاؤها. باستخدام تراكيب الطبقات، يمكنك إنشاء وإدارة وعرض إصدارات متعددة<br/>            لتخطيط في ملف Adobe™ Photoshop™ واحد. الـ layer comp هو لقطة لحالة لوحة الطبقات. تحفظ تراكيب الطبقات ثلاثة أنواع من خيارات الطبقة ولكن<br/>            هذه الخاصية تحصل على معرف اختيار الـ Layer Comp لطبقة الكائن الذكي في ملف PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">تراكيب الطبقات في الكائنات الذكية</see> |
| crop | int | r/w | يحصل أو يعيّن اقتصاص طبقة الكائن الذكي في صورة PSD. |
| duration_denominator | int | r/w | يحصل أو يعيّن مقام المدة. |
| duration_numerator | int | r/w | يحصل أو يعيّن بسط المدة. |
| frame_count | int | r/w | يحصل أو يعيّن عدد الإطارات لبيانات طبقة الكائن الذكي في ملف PSD. |
| frame_step_denominator | int | r/w | يحصل أو يعيّن مقام خطوة الإطار. |
| frame_step_numerator | int | r/w | يحصل أو يعيّن بسط خطوة الإطار. |
| الارتفاع | double | r/w | يحصل أو يعيّن الارتفاع. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | الحصول أو تعيين وحدة القياس لنقاط الشبكة الأفقية. |
| horizontal_mesh_points | double | r/w | الحصول أو تعيين نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| is_custom | bool | r/w | الحصول أو تعيين قيمة تشير إلى ما إذا كان نمط الالتواء لهذا الكائن مخصصًا.<br/>            إذا كان true يحتوي على نقاط الشبكة. إذا تم تعيينه إلى false يمسح نقاط الشبكة. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | يحصل أو يعيّن عناصر الوصف لبيانات طبقة الكائن الذكي في ملف PSD. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| left | double | r/w | الحصول أو تعيين الموقع الأيسر للطبقة الموضوعة في ملف PSD. |
| الطول | int | r | يحصل على طول مورد الكائن الذكي بالبايت. |
| non_affine_transform_matrix | double | r/w | يحصل أو يعيّن مصفوفة التحويل غير المتجانسة لبيانات طبقة الكائن الذكي في ملف PSD. |
| original_comp_id | int | r | يحصل على المعرف الأصلي للمكوّن المحدد حاليًا للمستند الفرعي، والذي سيكون -1 إذا لم يتم اختيار أي شيء.<br/>            هذه الخاصية تحصل على معرف اختيار طبقة المكوّن الأصلي للطبقة الكائن الذكي في ملف PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| page_number | int | r/w | يحصل أو يعيّن رقم الصفحة لبيانات طبقة الكائن الذكي في ملف PSD. |
| perspective | double | r/w | الحصول أو تعيين قيمة المنظور للطبقة الموضوعة في ملف PSD. |
| perspective_other | double | r/w | الحصول أو تعيين قيمة المنظور الأخرى للطبقة الموضوعة في ملف PSD. |
| placed_id | Guid | r/w | يحصل أو يعيّن المعرف الفريد لهذه البيانات طبقة الكائن الذكي في صورة PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | يحصل أو يعيّن نوع بيانات طبقة الكائن الذكي في ملف PSD. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| resolution | double | r/w | يحصل أو يعيّن دقة بيانات طبقة الكائن الذكي في ملف PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | يحصل أو يعيّن وحدة قياس الدقة لبيانات طبقة الكائن الذكي في ملف PSD. |
| right | double | r/w | الحصول أو تعيين الموقع الأيمن للطبقة الموضوعة في ملف PSD. |
| signature | int | r | يحصل على التوقيع. |
| أعلى | double | r/w | الحصول أو تعيين الموقع العلوي للطبقة الموضوعة في صورة PSD. |
| total_pages | int | r/w | يحصل أو يعيّن العدد الإجمالي للصفحات لبيانات طبقة الكائن الذكي في ملف PSD. |
| transform_matrix | double | r/w | يحصل أو يعيّن مصفوفة التحويل لبيانات طبقة الكائن الذكي في ملف PSD. |
| u_order | int | r/w | الحصول أو تعيين قيمة ترتيب U للطبقة الموضوعة في ملف PSD. |
| unique_id | Guid | r/w | يحصل أو يعيّن المعرف الفريد العالمي لبيانات طبقة الكائن الذكي [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) في صورة PSD. |
| v_order | int | r/w | الحصول أو تعيين قيمة ترتيب V للطبقة الموضوعة في ملف PSD. |
| قيمة | double | r/w | الحصول أو تعيين قيمة الالتواء للطبقة الموضوعة في صورة PSD. |
| version | int | r | الحصول على نسخة الطبقة الموضوعة في ملف PSD، عادةً 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | الحصول أو تعيين وحدة القياس لنقاط الشبكة العمودية. |
| vertical_mesh_points | double | r/w | الحصول أو تعيين نقاط الشبكة الأفقية للطبقة الموضوعة في ملف PSD. |
| width | double | r/w | يحصل أو يعيّن العرض. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ مورد الكائن الذكي إلى حاوية الدفق المحددة. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ مورد الكائن الذكي إلى حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |


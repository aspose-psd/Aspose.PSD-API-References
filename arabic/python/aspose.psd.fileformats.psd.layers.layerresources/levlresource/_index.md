---
title: "فئة LevlResource"
type: docs
weight: 490
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | ينشئ مثلاً جديداً من الفئة [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | ينشئ مثلاً جديداً من الفئة [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            مدعوم في أوضاع اللون GrayScale، Duotone، RGB، CMYK، Lab<br/>            2 بايت - الإصدار (=2)<br/>            29 * 10 بايت - مجموعات سجلات المستوى مع 5 أعداد صحيحة قصيرة<br/>            4 بايت - رأس Lvls (يبدأ عند الفهرس 292)<br/>            2 بايت - الإصدار (=3)<br/>            2 بايت - عدد إجمالي سجلات المستوى<br/>            10 * (الإجمالي - 29)<br/>            يجب أن يكون إنهاء الصفر لمورد Lvls مطويًا لأربعة أيضًا |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| version | short | r | يحصل على الإصدار. الافتراضي هو 2 |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | يحصل على القناة. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

ينشئ مثلاً جديداً من الفئة [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

ينشئ مثلاً جديداً من الفئة [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            مدعوم في أوضاع اللون GrayScale، Duotone، RGB، CMYK، Lab<br/>            2 بايت - الإصدار (=2)<br/>            29 * 10 بايت - مجموعات سجلات المستوى مع 5 أعداد صحيحة قصيرة<br/>            4 بايت - رأس Lvls (يبدأ عند الفهرس 292)<br/>            2 بايت - الإصدار (=3)<br/>            2 بايت - عدد إجمالي سجلات المستوى<br/>            10 * (الإجمالي - 29)<br/>            يجب أن يكون إنهاء الصفر لمورد Lvls مطويًا لأربعة أيضًا

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | الـ بايت. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

يحصل على القناة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | بيانات المستوى للقناة |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |


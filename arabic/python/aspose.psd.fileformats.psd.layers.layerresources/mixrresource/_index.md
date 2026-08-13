---
title: "فئة MixrResource"
type: docs
weight: 680
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | يُنشئ مثيلًا جديدًا من الفئة [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            يحتوي مواصفات تنسيق PSD على الوصف التالي:<br/>            2 الإصدار ( = 1)<br/>            2 أحادي اللون<br/>            20 لون RGB أو CMYK بالإضافة إلى ثابت لإعدادات الخلاط. 4 * 2 بايت من اللون مع 2 بايت من الثابت. |
| [MixrResource(data)](#MixrResource_data_2) | يُنشئ مثيلًا جديدًا من الفئة [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            يحتوي مواصفات تنسيق PSD على الوصف التالي:<br/>            2 الإصدار ( = 1)<br/>            2 أحادي اللون<br/>            20 لون RGB أو CMYK بالإضافة إلى ثابت لإعدادات الخلاط. 4 * 2 بايت من اللون مع 2 بايت من الثابت. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| monochrome | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) أحادي اللون. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| version | short | r/w | يحصل أو يعيّن الإصدار. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | يحصل على البيانات الأولية لمعلومات القناة |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | يحفظ المورد في حاوية الدفق المحددة. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | يعيّن معلومات القناة. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

يُنشئ مثيلًا جديدًا من الفئة [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            يحتوي مواصفات تنسيق PSD على الوصف التالي:<br/>            2 الإصدار ( = 1)<br/>            2 أحادي اللون<br/>            20 لون RGB أو CMYK بالإضافة إلى ثابت لإعدادات الخلاط. 4 * 2 بايت من اللون مع 2 بايت من الثابت.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

يُنشئ مثيلًا جديدًا من الفئة [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            يحتوي مواصفات تنسيق PSD على الوصف التالي:<br/>            2 الإصدار ( = 1)<br/>            2 أحادي اللون<br/>            20 لون RGB أو CMYK بالإضافة إلى ثابت لإعدادات الخلاط. 4 * 2 بايت من اللون مع 2 بايت من الثابت.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات المورد. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

يحصل على البيانات الأولية لمعلومات القناة

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | مصفوفة بايت أولية لمعلومات القناة. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

يعيّن معلومات القناة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |
| قيمة | byte | القيمة. |


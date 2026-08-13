---
title: "فئة CurvResource"
type: docs
weight: 190
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | ينشئ مثلاً جديداً من الفئة [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | ينشئ مثلاً جديداً من الفئة [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| is_data_stored_discretely | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل يخزن البيانات بشكل منفصل. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | يحصل على المدير النشط. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | يجلب بيانات القناة. |
| [get_curve_manager()](#get_curve_manager__3) | يجلب مدير المنحنى. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

ينشئ مثلاً جديداً من الفئة [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | الـ بايت. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

ينشئ مثلاً جديداً من الفئة [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| max_channel_count | int | الحد الأقصى لعدد القنوات. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

يحصل على المدير النشط.

**Returns**

| النوع | الوصف |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | المدير النشط |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

يجلب بيانات القناة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| channel_index | int | فهرس القناة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| byte | بيانات القناة |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

يجلب مدير المنحنى.

**Returns**

| النوع | الوصف |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) أو [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |


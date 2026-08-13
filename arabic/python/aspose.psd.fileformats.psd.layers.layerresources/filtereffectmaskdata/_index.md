---
title: "فئة FilterEffectMaskData"
type: docs
weight: 310
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | ينشئ مثلاً جديداً من الفئة [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | يحصل على القنوات. |
| guid | string | r | يحصل على GUID. |
| الطول | int | r | يحصل على طول بيانات قناع الفلتر بالبايتات. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على مستطيل قناع الورقة. |
| max_channels | int | r | يحصل على الحد الأقصى لعدد القنوات. |
| pixels_depth | int | r | يحصل على عمق البكسلات. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على مستطيل القنوات. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | يحصل على قناع الورقة. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | يحصل على قناع المستخدم. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

ينشئ مثلاً جديداً من الفئة [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| guid | string | معرف المورد guid. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل القنوات. |
| pixels_depth | int | عمق البكسلات. |
| max_channels | int | قيمة الحد الأقصى للقنوات. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | القنوات. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | قناع المستخدم. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل قناع الورقة. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | قناع الورقة. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |


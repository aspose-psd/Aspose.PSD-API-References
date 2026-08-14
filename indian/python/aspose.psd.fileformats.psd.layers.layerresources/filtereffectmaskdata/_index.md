---
title: "FilterEffectMaskData क्लास"
type: docs
weight: 310
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | एक नया उदाहरण प्रारंभ करता है [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) क्लास। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | चैनलों को प्राप्त करता है। |
| guid | string | r | GUID प्राप्त करता है। |
| लंबाई | int | r | फ़िल्टर मास्क डेटा की लंबाई बाइट्स में प्राप्त करता है। |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | शीट मास्क आयत प्राप्त करता है। |
| max_channels | int | r | चैनलों की गिनती का अधिकतम प्राप्त करता है। |
| pixels_depth | int | r | पिक्सेल गहराई प्राप्त करता है। |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | चैनलों का आयत प्राप्त करता है। |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | शीट मास्क प्राप्त करता है। |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | उपयोगकर्ता मास्क प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

एक नया उदाहरण प्रारंभ करता है [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| guid | string | संसाधन guid। |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | चैनलों का आयत। |
| pixels_depth | int | पिक्सेल गहराई। |
| max_channels | int | अधिकतम चैनलों का मान। |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | चैनल। |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | उपयोगकर्ता मास्क। |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | शीट मास्क आयत। |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | शीट मास्क। |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |


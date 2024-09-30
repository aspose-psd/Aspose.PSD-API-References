---
title: AnimatedDataSectionResource Class
type: docs
weight: 10
url: /python-net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---

**Summary:** The Animated Data Section Plug-In resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.AnimatedDataSectionResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.8.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | The resource signature of ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | The regular Photoshop resource signature. |
| animated_data_section | [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | r | Gets or sets the animated data section structure. |
| data_size | int | r | Gets the resource data size in bytes. |
| id | short | r/w | Gets or sets the unique identifier for the resource. |
| key_name | string | r | The resource key name. |
| minimal_version | int | r | Gets the minimal required PSD version. |
| name | string | r/w | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| signature | int | r | Gets the resource signature. Should be always '8BIM'. |
| size | int | r | Gets the resource block size in bytes including its data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the resource block data. |
| validate_values() | Validates the resource values. |


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the resource block data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |


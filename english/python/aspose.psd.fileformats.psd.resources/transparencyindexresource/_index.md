---
title: TransparencyIndexResource Class
type: docs
weight: 260
url: /python-net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---

**Summary:** The transparency index resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.TransparencyIndexResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TransparencyIndexResource()](#TransparencyIndexResource__1) | Initializes a new instance of the TransparencyIndexResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | The resource signature of ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | The regular Photoshop resource signature. |
| data_size | int | r | Gets the resource data size in bytes. |
| id | short | r/w | Gets or sets the unique identifier for the resource. |
| minimal_version | int | r | Gets the minimal required psd version. |
| name | string | r/w | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| signature | int | r | Gets the resource signature. Should be always '8BIM'. |
| size | int | r | Gets the resource block size in bytes including its data. |
| transparency_index | short | r/w | Gets or sets the transparency color index. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the resource block to the specified stream. |
| validate_values() | Validates the resource values. |


### Constructor: TransparencyIndexResource() {#TransparencyIndexResource__1}


```
 TransparencyIndexResource() 
```

Initializes a new instance of the TransparencyIndexResource class

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the resource block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream to save the resource block to. |


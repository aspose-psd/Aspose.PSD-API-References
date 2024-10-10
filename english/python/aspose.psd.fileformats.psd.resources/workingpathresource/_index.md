---
title: WorkingPathResource Class
type: docs
weight: 320
url: /python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Initializes a new instance of the [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | The resource signature of ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | The regular Photoshop resource signature. |
| data_size | int | r | Gets the resource data size in bytes. |
| id | short | r/w | Gets or sets the unique identifier for the resource. |
| is_disabled | bool | r/w | Gets or sets a value indicating whether this instance is disabled. |
| is_inverted | bool | r/w | Gets or sets a value indicating whether this instance is inverted. |
| is_not_linked | bool | r/w | Gets or sets a value indicating whether this instance is not linked. |
| minimal_version | int | r | Gets the minimal required PSD version. |
| name | string | r/w | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Gets or sets the path records. |
| signature | int | r | Gets the resource signature. Should be always '8BIM'. |
| size | int | r | Gets the resource block size in bytes including its data. |
| version | int | r/w | Gets or sets the version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the resource block to the specified stream. |
| validate_values() | Validates the resource values. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Initializes a new instance of the [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data_bytes | byte | The data of the vector path. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the resource block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream to save the resource block to. |


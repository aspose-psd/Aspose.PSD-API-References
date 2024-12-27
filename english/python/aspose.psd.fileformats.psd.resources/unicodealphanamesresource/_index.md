---
title: UnicodeAlphaNamesResource Class
type: docs
weight: 270
url: /python-net/aspose.psd.fileformats.psd.resources/unicodealphanamesresource/
---

**Summary:** Unicode alpha names resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.UnicodeAlphaNamesResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [UnicodeAlphaNamesResource()](#UnicodeAlphaNamesResource__1) | Initializes a new instance of the UnicodeAlphaNamesResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | The resource signature of ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | The regular Photoshop resource signature. |
| alpha_names | string | r/w | Gets or sets the alpha names. |
| data_size | int | r | Gets the resource data size in bytes. |
| id | short | r/w | Gets or sets the unique identifier for the resource. |
| minimal_version | int | r | Gets the minimal required PSD version. |
| name | string | r/w | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| signature | int | r | Gets the resource signature. Should be always '8BIM'. |
| size | int | r | Gets the resource block size in bytes including its data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the resource block to the specified stream. |
| validate_values() | Validates the resource values. |


### Constructor: UnicodeAlphaNamesResource() {#UnicodeAlphaNamesResource__1}


```
 UnicodeAlphaNamesResource() 
```

Initializes a new instance of the UnicodeAlphaNamesResource class

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the resource block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream to save the resource block to. |


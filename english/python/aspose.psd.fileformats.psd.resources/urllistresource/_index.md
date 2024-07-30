---
title: UrlListResource Class
type: docs
weight: 290
url: /python-net/aspose.psd.fileformats.psd.resources/urllistresource/
---

**Summary:** Url list resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.UrlListResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [UrlListResource()](#UrlListResource__1) | Initializes a new instance of the UrlListResource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | The resource signature of ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | The regular Photoshop resource signature. |
| count | int | r/w | Gets or sets the count. |
| data_size | int | r | Gets the resource data size in bytes. |
| id | short | r/w | Gets or sets the unique identifier for the resource. |
| ids | int | r/w | Gets or sets the ids. |
| longs | int | r/w | Gets or sets the longs. |
| minimal_version | int | r | Gets the minimal required PSD version. |
| name | string | r/w | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| signature | int | r | Gets the resource signature. Should be always '8BIM'. |
| size | int | r | Gets the resource block size in bytes including its data. |
| texts | string | r/w | Gets or sets the texts. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | Saves the resource block to the specified stream. |
| validate_values() | Validates the resource values. |


### Constructor: UrlListResource() {#UrlListResource__1}


```
 UrlListResource() 
```

Initializes a new instance of the UrlListResource class

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Saves the resource block to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream to save the resource block to. |


---
title: Lnk3Resource Class
type: docs
weight: 540
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---

**Summary:** Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk3Resource

**Inheritance:** Lnk2Resource

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Lnk3Resource()](#Lnk3Resource__1) | Initializes a new instance of the [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| data_source_count | int | r | Gets the count of link data sources which can be accessed by the indexer. |
| is_empty | bool | r | Gets a value indicating whether this link resource instance is empty. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the PSD global link resource length in bytes. |
| psd_version | int | r | Gets the PSD format version. |
| signature | int | r | Gets the PSD global link resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource block data. |


### Constructor: Lnk3Resource() {#Lnk3Resource__1}


```
 Lnk3Resource() 
```

Initializes a new instance of the [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) class.

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the resource block data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |


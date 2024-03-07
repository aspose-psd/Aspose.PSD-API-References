---
title: Txt2Resource Class
type: docs
weight: 920
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Initializes a new instance of the Txt2Resource class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| data | byte | r/w | Gets or sets the data. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Adds the text record to Resource and returns id of text record. |
| [get_text_data()](#get_text_data__2) | Gets the text record from resource data. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Saves the specified stream container. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Initializes a new instance of the Txt2Resource class

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Adds the text record to Resource and returns id of text record.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| text | string | The record text. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The bounds. |

**Returns**

| Type | Description |
| :- | :- |
| int | Returns Id of text record for resource |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Gets the text record from resource data.

**Returns**

| Type | Description |
| :- | :- |
| string | Array of text record |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Saves the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| psd_version | int | The PSD version. |


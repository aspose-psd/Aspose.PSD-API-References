---
title: LmskResource Class
type: docs
weight: 560
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | Initializes a new instance of the [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| color_component1 | ushort | r/w | Gets the color component 1. |
| color_component2 | ushort | r/w | Gets the color component 2. |
| color_component3 | ushort | r/w | Gets the color component 3. |
| color_component4 | ushort | r/w | Gets the color component 4. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | Gets the color space. |
| flag | byte | r | Gets the flag. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| opacity | short | r/w | Gets the opacity. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

Initializes a new instance of the [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) class.

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |


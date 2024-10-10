---
title: ColorComponent Class
type: docs
weight: 10
url: /python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Initializes a new instance of the [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) class.<br/>            Please check |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_depth | byte | r | Gets the bit depth of Color Component/Channel |
| description | string | r | Gets the description of Color Component |
| full_name | string | r | Gets the full name of color component with name and space-separated description |
| name | string | r | Gets the name of color component. |
| permitted_full_names [static] | string | r | Gets the permitted full names. |
| value | ulong | r/w | Gets or sets the value. <br/>            Please note, if you try to set value that is more than <br/>            possible stored in current bit depth, you'll get an exception |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Initializes a new instance of the [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/) class.<br/>            Please check

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bit_depth | byte | The bit depth. |
| full_name | string | The full name. |


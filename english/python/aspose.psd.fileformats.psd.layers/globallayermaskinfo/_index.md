---
title: GlobalLayerMaskInfo Class
type: docs
weight: 570
url: /python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/
---

**Summary:** The global layer mask section.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.GlobalLayerMaskInfo

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GlobalLayerMaskInfo()](#GlobalLayerMaskInfo__1) | Initializes a new instance of the GlobalLayerMaskInfo class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_mask | short | r/w | Gets or sets the alpha mask. |
| blue_mask | short | r/w | Gets or sets the blue mask. |
| green_mask | short | r/w | Gets or sets the green mask. |
| kind | byte | r/w | Gets or sets the kind.<br/>            0 = Color selected--i.e. inverted;<br/>            1 = Color protected;<br/>            128 = use value stored per layer. This value is preferred.<br/>            The others are for backward compatibility with beta versions. |
| length | int | r | Gets the global layer mask section length in bytes. |
| opacity | short | r/w | Gets or sets global layers opacity. 0 = transparent, 100 = opaque. |
| overlay_color_space | short | r/w | Gets or sets the overlay color space (undocumented value). |
| red_mask | short | r/w | Gets or sets the red mask. |


### Constructor: GlobalLayerMaskInfo() {#GlobalLayerMaskInfo__1}


```
 GlobalLayerMaskInfo() 
```

Initializes a new instance of the GlobalLayerMaskInfo class


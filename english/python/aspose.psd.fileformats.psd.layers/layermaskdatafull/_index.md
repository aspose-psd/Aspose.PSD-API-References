---
title: LayerMaskDataFull Class
type: docs
weight: 920
url: /python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Initializes a new instance of the LayerMaskDataFull class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Gets or sets the background color. |
| bottom | int | r/w | Gets or sets the bottom layer mask position. |
| data_size | int | r | Gets the size of the layer mask mask data. |
| default_color | byte | r/w | Gets or sets the default color. |
| enclosing_bottom | int | r/w | Gets or sets the enclosing bottom raster mask position in the PSD image layer. |
| enclosing_left | int | r/w | Gets or sets the enclosing left raster mask position in the PSD file layer. |
| enclosing_right | int | r/w | Gets or sets the enclosing right raster mask position in the PSD file layer. |
| enclosing_top | int | r/w | Gets or sets the enclosing top position of the raster mask in the PSD image layer. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Gets or sets the layer mask flags. |
| image_data | byte | r/w | Gets or sets the layer mask data (or combined / final mask if there is a vector mask) in the PSD file. |
| left | int | r/w | Gets or sets the left layer mask position. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Gets or sets the mask [Rectangle](/psd/python-net/aspose.psd/rectangle/) of the layer mask in the PSD file.<br/>            It takes left, right, top and bottom properties and creates [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Gets or sets the layer mask flags that is used for user / raster mask. For vector mask the Flags property is used. |
| right | int | r/w | Gets or sets the right layer mask position. |
| top | int | r/w | Gets or sets the top layer mask position. |
| user_mask_data | byte | r/w | Gets or sets the user (raster) mask data of a layer in the PSD file. (There is a raterized vector mask in the MaskData property). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Gets or sets the user mask (enclosing) rectangle in the PSD image layer.. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Initializes a new instance of the LayerMaskDataFull class


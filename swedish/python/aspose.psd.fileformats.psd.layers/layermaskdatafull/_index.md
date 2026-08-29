---
title: "LayerMaskDataFull-klass"
type: docs
weight: 980
url: /sv/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Initierar en ny instans av klassen LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Hämtar eller anger bakgrundsfärgen. |
| nedre | int | r/w | Hämtar eller anger den nedre lagermaskens position. |
| data_size | int | r | Hämtar storleken på lagermaskens maskdata. |
| default_color | byte | r/w | Hämtar eller anger standardfärgen. |
| enclosing_bottom | int | r/w | Hämtar eller anger den omgivande nedre rastermaskens position i PSD-bildlagret. |
| enclosing_left | int | r/w | Hämtar eller anger den omgivande vänstra rastermaskens position i PSD-filens lager. |
| enclosing_right | int | r/w | Hämtar eller anger den omgivande högra rastermaskens position i PSD-filens lager. |
| enclosing_top | int | r/w | Hämtar eller anger den omgivande övre positionen för rastermasken i PSD-bildlagret. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Hämtar eller anger lagermaskens flaggor. |
| image_data | byte | r/w | Hämtar eller anger lagermaskens data (eller kombinerad / slutmask om det finns en vektormask) i PSD-filen. |
| vänster | int | r/w | Hämtar eller anger den vänstra lagermaskens position. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Hämtar eller anger maskens [Rectangle](/psd/python-net/aspose.psd/rectangle/) för lagermasken i PSD-filen.<br/>            Den tar vänster-, höger-, topp- och bottenegenskaper och skapar [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Hämtar eller anger lagermaskens flaggor som används för användar‑/rastermask. För vektormask används egenskapen Flags. |
| höger | int | r/w | Hämtar eller anger den högra lagermaskens position. |
| övre | int | r/w | Hämtar eller anger den övre lagermaskens position. |
| user_mask_data | byte | r/w | Hämtar eller anger användar‑(raster)maskdata för ett lager i PSD-filen. (Det finns en rasteriserad vektormask i egenskapen MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Hämtar eller anger användarmaskens (omgivande) rektangel i PSD-bildlagret.. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Initierar en ny instans av klassen LayerMaskDataFull


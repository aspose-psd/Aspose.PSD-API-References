---
title: "LayerMaskDataShort klass"
type: docs
weight: 990
url: /sv/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Initierar en ny instans av klassen LayerMaskDataShort. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| nedre | int | r/w | Hämtar eller anger den nedre lagermaskens position. |
| data_size | int | r | Hämtar storleken på lagermaskens maskdata. |
| default_color | byte | r/w | Hämtar eller anger standardfärgen. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Hämtar eller anger lagermaskens flaggor. |
| image_data | byte | r/w | Hämtar eller anger lagermaskens data (eller kombinerad / slutmask om det finns en vektormask) i PSD-filen. |
| vänster | int | r/w | Hämtar eller anger den vänstra lagermaskens position. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Hämtar eller anger maskens [Rectangle](/psd/python-net/aspose.psd/rectangle/) för lagermasken i PSD-filen.<br/>            Den tar vänster-, höger-, topp- och bottenegenskaper och skapar [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| padding | short | r/w | Hämtar eller anger lagermaskens utfyllnad. |
| höger | int | r/w | Hämtar eller anger den högra lagermaskens position. |
| övre | int | r/w | Hämtar eller anger den övre lagermaskens position. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Initierar en ny instans av klassen LayerMaskDataShort.


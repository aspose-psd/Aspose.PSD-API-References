---
title: "LayerMaskDataShort Klasse"
type: docs
weight: 990
url: /nl/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Initialiseert een nieuw exemplaar van de LayerMaskDataShort klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bottom | int | r/w | Haalt of stelt de positie van het onderste laagmasker in. |
| data_size | int | r | Haalt de grootte van de laagmaskergegevens op. |
| default_color | byte | r/w | Haalt of stelt de standaardkleur in. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Haalt of stelt de vlaggen van het laagmasker in. |
| image_data | byte | r/w | Haalt of stelt de laagmaskergegevens (of gecombineerde/eindmasker als er een vectormasker is) in het PSD‑bestand in. |
| left | int | r/w | Haalt of stelt de positie van het linker laagmasker in. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Haalt of stelt het masker [Rectangle](/psd/python-net/aspose.psd/rectangle/) van het laagmasker in het PSD‑bestand.<br/>            Het neemt de eigenschappen left, right, top en bottom en maakt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| padding | short | r/w | Geeft of stelt de laagmasker‑opvulling in. |
| right | int | r/w | Haalt of stelt de positie van het rechter laagmasker in. |
| boven | int | r/w | Haalt of stelt de positie van het bovenste laagmasker in. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Initialiseert een nieuw exemplaar van de LayerMaskDataShort klasse


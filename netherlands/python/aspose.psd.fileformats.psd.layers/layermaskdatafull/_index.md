---
title: "LayerMaskDataFull Klasse"
type: docs
weight: 980
url: /nl/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Initialiseert een nieuw exemplaar van de LayerMaskDataFull klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Haalt de achtergrondkleur op of stelt deze in. |
| bottom | int | r/w | Haalt of stelt de positie van het onderste laagmasker in. |
| data_size | int | r | Haalt de grootte van de laagmaskergegevens op. |
| default_color | byte | r/w | Haalt of stelt de standaardkleur in. |
| enclosing_bottom | int | r/w | Haalt of stelt de omsluitende onderste rastermaskerpositie in de PSD‑afbeeldingslaag in. |
| enclosing_left | int | r/w | Haalt of stelt de omsluitende linker rastermaskerpositie in de PSD‑bestandslaag in. |
| enclosing_right | int | r/w | Haalt of stelt de omsluitende rechter rastermaskerpositie in de PSD‑bestandslaag in. |
| enclosing_top | int | r/w | Haalt of stelt de omsluitende bovenste positie van het rastermasker in de PSD‑afbeeldingslaag in. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Haalt of stelt de vlaggen van het laagmasker in. |
| image_data | byte | r/w | Haalt of stelt de laagmaskergegevens (of gecombineerde/eindmasker als er een vectormasker is) in het PSD‑bestand in. |
| left | int | r/w | Haalt of stelt de positie van het linker laagmasker in. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Haalt of stelt het masker [Rectangle](/psd/python-net/aspose.psd/rectangle/) van het laagmasker in het PSD‑bestand.<br/>            Het neemt de eigenschappen left, right, top en bottom en maakt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Geeft of stelt de laagmasker‑vlaggen in die worden gebruikt voor gebruikers‑/rastermasker. Voor vectormasker wordt de eigenschap Flags gebruikt. |
| right | int | r/w | Haalt of stelt de positie van het rechter laagmasker in. |
| boven | int | r/w | Haalt of stelt de positie van het bovenste laagmasker in. |
| user_mask_data | byte | r/w | Geeft of stelt de gebruikers‑(raster)maskergegevens van een laag in het PSD‑bestand in. (Er is een gerasteriseerd vectormasker in de eigenschap MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Geeft of stelt de gebruikersmasker (omvattende) rechthoek in de PSD‑afbeeldingslaag in.. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Initialiseert een nieuw exemplaar van de LayerMaskDataFull klasse


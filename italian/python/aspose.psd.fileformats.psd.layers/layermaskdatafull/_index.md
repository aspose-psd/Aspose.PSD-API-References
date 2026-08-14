---
title: "LayerMaskDataFull Classe"
type: docs
weight: 980
url: /it/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Inizializza una nuova istanza della classe LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Ottiene o imposta il colore di sfondo. |
| bottom | int | r/w | Ottiene o imposta la posizione inferiore della maschera del livello. |
| data_size | int | r | Ottiene la dimensione dei dati della maschera del livello. |
| default_color | byte | r/w | Ottiene o imposta il colore predefinito. |
| enclosing_bottom | int | r/w | Ottiene o imposta la posizione inferiore della maschera raster di contenimento nel livello immagine PSD. |
| enclosing_left | int | r/w | Ottiene o imposta la posizione sinistra della maschera raster di contenimento nel livello del file PSD. |
| enclosing_right | int | r/w | Ottiene o imposta la posizione destra della maschera raster di contenimento nel livello del file PSD. |
| enclosing_top | int | r/w | Ottiene o imposta la posizione superiore della maschera raster di contenimento nel livello immagine PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Ottiene o imposta i flag della maschera del livello. |
| image_data | byte | r/w | Ottiene o imposta i dati della maschera del livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD. |
| sinistra | int | r/w | Ottiene o imposta la posizione sinistra della maschera del livello. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Ottiene o imposta la [Rectangle](/psd/python-net/aspose.psd/rectangle/) della maschera del livello nel file PSD.<br/>            Prende le proprietà left, right, top e bottom e crea una [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Ottiene o imposta i flag della maschera di livello utilizzati per la maschera utente / raster. Per la maschera vettoriale viene utilizzata la proprietà Flags. |
| destra | int | r/w | Ottiene o imposta la posizione destra della maschera del livello. |
| superiore | int | r/w | Ottiene o imposta la posizione superiore della maschera del livello. |
| user_mask_data | byte | r/w | Ottiene o imposta i dati della maschera utente (raster) di un livello nel file PSD. (Esiste una maschera vettoriale rasterizzata nella proprietà MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Ottiene o imposta il rettangolo di contenimento della maschera utente nel livello immagine PSD. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Inizializza una nuova istanza della classe LayerMaskDataFull


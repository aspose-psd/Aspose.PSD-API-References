---
title: "Klasse LayerMaskDataFull"
type: docs
weight: 980
url: /de/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Initialisiert eine neue Instanz der Klasse LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Ruft die Hintergrundfarbe ab oder legt sie fest. |
| bottom | int | r/w | Liest oder setzt die Position der unteren Ebenenmaske. |
| data_size | int | r | Liest die Größe der Maskendaten der Ebenenmaske. |
| default_color | byte | r/w | Liest oder setzt die Standardfarbe. |
| enclosing_bottom | int | r/w | Liest oder setzt die Position der umgebenden unteren Rastermaske im PSD‑Bildebene. |
| enclosing_left | int | r/w | Liest oder setzt die Position der umgebenden linken Rastermaske in der PSD‑Dateiebenene. |
| enclosing_right | int | r/w | Liest oder setzt die umschließende rechte Rastermaskenposition in der PSD-Dateiebene. |
| enclosing_top | int | r/w | Liest oder setzt die umschließende obere Position der Rastermaske in der PSD-Bildebene. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Liest oder setzt die Flags der Ebenenmaske. |
| image_data | byte | r/w | Liest oder setzt die Maskendaten der Ebenenmaske (oder die kombinierte / endgültige Maske, falls ein Vektormaske vorhanden ist) in der PSD‑Datei. |
| left | int | r/w | Liest oder setzt die Position der linken Ebenenmaske. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt das Masken-[Rectangle](/psd/python-net/aspose.psd/rectangle/) der Ebenenmaske in der PSD‑Datei.<br/>            Es verwendet die Eigenschaften left, right, top und bottom und erstellt ein [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Liest oder setzt die Ebenenmasken‑Flags, die für die Benutzer‑/Rastermaske verwendet werden. Für Vektormasken wird die Eigenschaft Flags verwendet. |
| rechts | int | r/w | Liest oder setzt die Position der rechten Ebenenmaske. |
| oben | int | r/w | Liest oder setzt die Position der oberen Ebenenmaske. |
| user_mask_data | byte | r/w | Liest oder setzt die Benutzer‑(Raster‑)Maskendaten einer Ebene in der PSD‑Datei. (Im MaskData‑Eigenschaft befindet sich eine gerasterte Vektormaske). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt das Benutzer‑Masken‑(umschließende) Rechteck in der PSD‑Bildebene. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Initialisiert eine neue Instanz der Klasse LayerMaskDataFull


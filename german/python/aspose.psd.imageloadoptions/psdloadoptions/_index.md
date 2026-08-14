---
title: "PsdLoadOptions Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Initialisiert eine neue Instanz der Klasse PsdLoadOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Liest oder setzt, ob mit dem gerenderten Bild gespeichert werden soll, mit oder ohne Warp-Transformation. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt das Hintergrund-[Image](/psd/python-net/aspose.psd/image/) [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Liest oder setzt den Datenwiederherstellungsmodus. |
| ignore_alpha_channel | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die feste Breite der PSD-Textschicht bei der Ausführung der UpdateText-Operation ignoriert wird. |
| load_effects_resource | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [load effects resource] (standardmäßig ist die Ressource nicht geladen). Wenn diese Option gesetzt ist, werden nur unterstützte Effekte in das endgültige zusammengeführte Bild gerendert. |
| read_only_mode | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [use read only mode]. Dies ist der Nur-Lese-Modus, der für eine identische Kompatibilität mit Adobe Photoshop unterstützt wird.<br/>            Wenn diese Option gesetzt ist, werden alle Änderungen an den Ebenen nicht im endgültigen Bild gespeichert. Alle Daten werden aus dem ImageData‑Abschnitt verwendet, sodass es identisch zu Photoshop ist. <br/>            Standardmäßig sind alle geladenen Bilder nicht identisch zu Adobe Photoshop kompatibel. |
| use_disk_for_load_effects_resource | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [use disk for load effects resource] (standardmäßig wird die Festplatte zum Laden der Effektressourcen verwendet, kann aber Speicher verwendet werden, wenn es ausreichend ist, indem dieser Wert auf false gesetzt wird). |
| use_icc_profile_conversion | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die ICC-Profilkonvertierung angewendet werden soll. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Initialisiert eine neue Instanz der Klasse PsdLoadOptions


---
title: "PsdLoadOptions Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Initialiseert een nieuw exemplaar van de PsdLoadOptions klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Haalt op of stelt in of er moet worden opgeslagen met de gerenderde afbeelding, met of zonder een warp-transformatie. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt de [Image](/psd/python-net/aspose.psd/image/) achtergrond [Color](/psd/python-net/aspose.psd/color/) in. |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Haalt op of stelt de gegevensherstelmodus in. |
| ignore_alpha_channel | bool | r/w | Haalt of stelt een waarde in die aangeeft of [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Haalt of stelt een waarde in die aangeeft of de vaste breedte van de PSD-tekstlaag wordt genegeerd bij de uitvoering van de UpdateText‑bewerking. |
| load_effects_resource | bool | r/w | Haalt of stelt een waarde in die aangeeft of [load effects resource] (standaard is de bron niet geladen). Wanneer deze optie is ingesteld, worden alleen ondersteunde effecten gerenderd naar de uiteindelijke samengevoegde afbeelding. |
| read_only_mode | bool | r/w | Haalt of stelt een waarde in die aangeeft of [use read only mode]. Dit is de alleen-lezen modus, ondersteund voor identieke compatibiliteit met Adobe Photoshop.<br/>            Wanneer deze optie is ingesteld, worden alle wijzigingen die op lagen zijn toegepast niet opgeslagen in de uiteindelijke afbeelding. Alle gegevens worden gebruikt uit de ImageData‑sectie, dus het is identiek aan Photoshop. <br/>            Standaard zijn alle geladen afbeeldingen niet identiek compatibel met Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | Haalt of stelt een waarde in die aangeeft of [use disk for load effects resource] (standaard wordt de schijf gebruikt om effectbronnen te laden, maar er kan geheugen worden gebruikt als dit voldoende is door deze waarde op false te zetten). |
| use_icc_profile_conversion | bool | r/w | Haalt op of stelt een waarde in die aangeeft of ICC-profielconversie moet worden toegepast. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Initialiseert een nieuw exemplaar van de PsdLoadOptions klasse


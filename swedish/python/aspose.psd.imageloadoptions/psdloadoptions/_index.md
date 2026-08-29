---
title: "PsdLoadOptions-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Initierar en ny instans av PsdLoadOptions-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Hämtar eller anger om sparning ska ske med den renderade bilden, med eller utan en warp‑transformering. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger [Image](/psd/python-net/aspose.psd/image/) bakgrunds[Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Hämtar eller anger dataåterställningsläget. |
| ignore_alpha_channel | bool | r/w | Hämtar eller anger ett värde som indikerar om [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Hämtar eller anger ett värde som indikerar om PSD‑textlagrets fasta bredd ska ignoreras vid körning av UpdateText‑operationen. |
| load_effects_resource | bool | r/w | Hämtar eller anger ett värde som indikerar om [load effects resource] (standard är att resursen inte laddas). När detta alternativ är satt kommer endast stödda effekter att renderas till den slutliga sammanslagna bilden. |
| read_only_mode | bool | r/w | Hämtar eller anger ett värde som indikerar om [use read only mode]. Detta är skrivskyddat läge, som stöds för identisk kompatibilitet med Adobe Photoshop.<br/>            När detta alternativ är satt kommer alla ändringar som gjorts på lager inte att sparas till den slutliga bilden. All data hämtas från ImageData‑sektionen, så den är identisk med Photoshop. <br/>            Som standard är alla inlästa bilder inte identiska med Adobe Photoshop‑kompatibla. |
| use_disk_for_load_effects_resource | bool | r/w | Hämtar eller anger ett värde som indikerar om [use disk for load effects resource] (standard är att använda disk för att ladda effektresursen, men minne kan användas om det är tillräckligt genom att sätta detta värde till false). |
| use_icc_profile_conversion | bool | r/w | Hämtar eller anger ett värde som indikerar om ICC-profilkonvertering ska tillämpas. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Initierar en ny instans av PsdLoadOptions-klassen


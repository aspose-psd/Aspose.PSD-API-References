---
title: "BlncResource-klass"
type: docs
weight: 80
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Initierar en ny instans av klassen [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| highlights_cyan_red_balance | short | r/w | Hämtar eller anger Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Hämtar eller anger Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Hämtar eller anger Highlights Yellow Blue Balance. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| midtones_cyan_red_balance | short | r/w | Hämtar eller anger Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Hämtar eller anger Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Hämtar eller anger Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) bevarar luminans. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| shadows_cyan_red_balance | short | r/w | Hämtar eller anger Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Hämtar eller anger Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Hämtar eller anger Shadows Yellow Blue Balance. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Initierar en ny instans av klassen [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |


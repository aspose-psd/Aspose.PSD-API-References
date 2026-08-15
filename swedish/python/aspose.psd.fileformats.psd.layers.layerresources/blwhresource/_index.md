---
title: "BlwhResource-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Initierar en ny instans av klassen BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| black_and_white_preset_file_name | string | r/w | Hämtar eller anger filnamnet för svart‑vitt förinställning. |
| blåa | int | r/w | Hämtar eller anger värdet för blåa. |
| bw_preset_kind | int | r/w | Hämtar eller anger värdet för svart‑vita förinställningstyp. |
| cian | int | r/w | Hämtar eller anger värdet för cian. |
| gröna | int | r/w | Hämtar eller anger värdet för gröna. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| magenta | int | r/w | Hämtar eller anger värdet för magenta. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| röda | int | r/w | Hämtar eller anger värdet för röda. |
| signatur | int | r | Hämtar signaturen. |
| tint_color | int | r/w | Hämtar eller anger Tint Color ARGB-värdet. |
| use_tint | bool | r/w | Hämtar eller anger ett värde som indikerar om [tint color] används. |
| gula | int | r/w | Hämtar eller anger värdet för gula. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Initierar en ny instans av klassen BlwhResource

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


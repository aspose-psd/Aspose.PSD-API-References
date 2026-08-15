---
title: "Hue2Resource‑klass"
type: docs
weight: 350
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Initierar en ny instans av klassen [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/). |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Initierar en ny instans av klassen [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| colorize | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) är färgad. |
| nyans | short | r/w | Hämtar eller anger huvudnyansen. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| ljushet | short | r/w | Hämtar eller anger huvudljusheten. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Hämtar intervallen för Hue/Saturation‑justeringslagret.<br/>            Intervall i PS kan byta namn om intervallet ändras, så vi bör arbeta efter index |
| mättnad | short | r/w | Hämtar eller anger huvudmättnaden. |
| signatur | int | r | Hämtar signaturen. |
| version | short | r | Hämtar versionen. Standard är 2 |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Initierar en ny instans av klassen [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/).

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Initierar en ny instans av klassen [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Data för resursen. |

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


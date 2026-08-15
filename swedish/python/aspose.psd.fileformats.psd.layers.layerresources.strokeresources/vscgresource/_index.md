---
title: "VscgResource‑klass"
type: docs
weight: 30
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Initierar en ny instans av VscgResource‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Hämtar eller anger arrayen av strukturelement.<br/>            **Warning:** Värdena i `Items`-arrayen måste matcha `KeyForData`-egenskapen, som bestämmer typen av fyllningsinställningar som lagras i strukturerna inom `Items`. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| key_for_data | int | r | Hämtar heltalsnyckeln som definierar vilken typ av fyllningsinställningar som lagras i resursen:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradient - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Pattern - 0x5074466c - PtFlResource.TypeToolKey<br/>            Warning! Värdet på egenskapen KeyForData bör matcha typen av fyllningsinställningar som lagras i Items-strukturer. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Initierar en ny instans av VscgResource‑klassen

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


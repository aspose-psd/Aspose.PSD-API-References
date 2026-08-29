---
title: "AbddResource-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/
---

**Summary:** The Artboard info data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.AbddResource

**Inheritance:** BaseArtboardInfoResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [AbddResource()](#AbddResource__1) | Initierar en ny instans av AbddResource-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Hämtar eller anger [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)‑objekten. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | <inheritdoc /> |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: AbddResource() {#AbddResource__1}


```
 AbddResource() 
```

Initierar en ny instans av AbddResource-klassen

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


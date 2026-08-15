---
title: "IopaResource-klass"
type: docs
weight: 440
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Initierar en ny instans av klassen [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
| [IopaResource(data)](#IopaResource_data_2) | Initierar en ny instans av klassen [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| fill_opacity | byte | r/w | Hämtar eller anger fyllnadens opacitet. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Initierar en ny instans av klassen [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Initierar en ny instans av klassen [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Den rå byte-datan. |

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


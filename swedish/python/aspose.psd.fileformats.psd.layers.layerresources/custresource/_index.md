---
title: "CustResource-klass"
type: docs
weight: 230
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [CustResource()](#CustResource__1) | Initierar en ny instans av klassen [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
| [CustResource(data)](#CustResource_data_2) | Initierar en ny instans av klassen [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| layer_created_date_time | datetime | r/w | Hämtar eller anger lagrets skapelsedatum. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Initierar en ny instans av klassen [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Initierar en ny instans av klassen [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

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


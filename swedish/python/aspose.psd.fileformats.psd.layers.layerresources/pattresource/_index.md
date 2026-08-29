---
title: "PattResource-klass"
type: docs
weight: 770
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PattResource()](#PattResource__1) | Initierar en ny instans av klassen [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Initierar en ny instans av klassen [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Den 'Patt'-typens verktygsinformationsnyckel för 8‑bit. |
| TYPE_TOOL_KEY2 [static] | int | r | Den 'Pat2' typverktygsinformationsnyckeln för 16-bitars. |
| TYPE_TOOL_KEY3 [static] | int | r | Den 'Pat3' typverktygsinformationsnyckeln för 32-bitars. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Hämtar eller anger mönsterdata; |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursblockets data. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Initierar en ny instans av klassen [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Initierar en ny instans av klassen [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | int | Resurstypsnyckeln. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Mönsterdata. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursblockets data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |


---
title: "KnkoResource-klass"
type: docs
weight: 450
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/
---

**Summary:** Class KnkoResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.KnkoResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [KnkoResource()](#KnkoResource__1) | Initierar en ny instans av klassen [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) . |
| [KnkoResource(data)](#KnkoResource_data_2) | Initierar en ny instans av klassen [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) .<br/>            Med anpassat eller okänt värde |
| [KnkoResource(knockout)](#KnkoResource_knockout_3) | Initierar en ny instans av klassen [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| knockout | bool | r/w | Hämtar eller anger ett värde som indikerar om [blend interior elements]. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar den angivna strömbehållaren. |


### Constructor: KnkoResource() {#KnkoResource__1}


```
 KnkoResource() 
```

Initierar en ny instans av klassen [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) .

### Constructor: KnkoResource(data) {#KnkoResource_data_2}


```
 KnkoResource(data) 
```

Initierar en ny instans av klassen [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) .<br/>            Med anpassat eller okänt värde

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Resursdata. |

### Constructor: KnkoResource(knockout) {#KnkoResource_knockout_3}


```
 KnkoResource(knockout) 
```

Initierar en ny instans av klassen [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| knockout | bool | om satt till <c>true</c> [blend interior elements]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| psd_version | int | PSD-versionen. |


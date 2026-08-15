---
title: "ClblResource-klass"
type: docs
weight: 160
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Initierar en ny instans av klassen [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Initierar en ny instans av klassen [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(data)](#ClblResource_data_3) | Initierar en ny instans av klassen [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).<br/>            Med anpassat eller okänt värde |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| blend_clipped_elements | bool | r/w | Hämtar eller anger ett värde som indikerar om [blend clipped elements]. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar den angivna strömbehållaren. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Initierar en ny instans av klassen [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Initierar en ny instans av klassen [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| blend_clipped_elements | bool | om den är satt till <c>true</c> [blend clipped elements]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Initierar en ny instans av klassen [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).<br/>            Med anpassat eller okänt värde

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Resursdata. |

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


---
title: "InfxResource-klass"
type: docs
weight: 420
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | Initierar en ny instans av klassen [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | Initierar en ny instans av klassen [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(data)](#InfxResource_data_3) | Initierar en ny instans av klassen [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            Med anpassat eller okänt värde |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| blend_interior_elements | bool | r/w | Hämtar eller anger ett värde som indikerar om [blend interior elements]. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar den angivna strömbehållaren. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

Initierar en ny instans av klassen [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

Initierar en ny instans av klassen [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| blend_interior_elements | bool | om satt till <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

Initierar en ny instans av klassen [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            Med anpassat eller okänt värde

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


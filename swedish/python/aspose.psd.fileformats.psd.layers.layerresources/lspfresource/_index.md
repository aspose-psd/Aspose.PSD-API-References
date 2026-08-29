---
title: "LspfResource-klass"
type: docs
weight: 640
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Initierar en ny instans av klassen [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
| [LspfResource(data)](#LspfResource_data_2) | Initierar en ny instans av klassen [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).<br/>            Med anpassat eller okänt värde |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Initierar en ny instans av klassen [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln 1819504742 |
| is_composite_protected | bool | r/w | Hämtar eller anger ett värde som indikerar om den här instansen är sammansatt skyddad. |
| is_position_protected | bool | r/w | Hämtar eller anger ett värde som indikerar om den här instansen är positionsskyddad. |
| is_transparency_protected | bool | r/w | Hämtar eller anger ett värde som indikerar om den här instansen är transparensskyddad. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Hämtar eller anger låstypen. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Initierar en ny instans av klassen [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Initierar en ny instans av klassen [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).<br/>            Med anpassat eller okänt värde

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Resursdata. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Initierar en ny instans av klassen [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_transparency_protected | bool | om satt till <c>true</c> [is transparency protected]. |
| is_composite_protected | bool | om satt till <c>true</c> [is composite protected]. |
| is_position_protected | bool | om satt till <c>true</c> [is position protected]. |

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


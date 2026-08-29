---
title: "LnsrResource-klass"
type: docs
weight: 600
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/
---

**Summary:** Class lnsrResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnsrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LnsrResource(bytes)](#LnsrResource_bytes_1) | Initierar en ny instans av klassen [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).<br/>            Med anpassat eller okänt värde |
| [LnsrResource(lnsr_resource_type)](#LnsrResource_lnsr_resource_type_2) | Initierar en ny instans av klassen [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| data | byte | r | Hämtar rådata. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| value | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | r | Hämtar värdet som LnsrResourceType om motsvarande enum är beskriven.<br/>            Annars returneras Unknown |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar den angivna strömbehållaren. |


### Constructor: LnsrResource(bytes) {#LnsrResource_bytes_1}


```
 LnsrResource(bytes) 
```

Initierar en ny instans av klassen [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).<br/>            Med anpassat eller okänt värde

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte. |

### Constructor: LnsrResource(lnsr_resource_type) {#LnsrResource_lnsr_resource_type_2}


```
 LnsrResource(lnsr_resource_type) 
```

Initierar en ny instans av klassen [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| lnsr_resource_type | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | Typ av LNSR. |

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


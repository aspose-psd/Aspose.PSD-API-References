---
title: "ExpaResource-klass"
type: docs
weight: 280
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Initierar en ny instans av klassen [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klass. |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Initierar en ny instans av klassen [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klass. |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Initierar en ny instans av klassen [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| exponering | float | r/w | Hämtar eller anger exponeringen. |
| gamma_correction | float | r/w | Hämtar eller anger gamma. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| offset | float | r/w | Hämtar eller anger förskjutningen. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| version | short | r | Hämtar versionen. Standard är 1 |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Initierar en ny instans av klassen [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klass.

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Initierar en ny instans av klassen [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Initierar en ny instans av klassen [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exponering | float | Exponeringen. |
| offset | float | Förskjutningen. |
| gamma | float | Gamma. |

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


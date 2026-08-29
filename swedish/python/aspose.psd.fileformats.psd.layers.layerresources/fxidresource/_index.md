---
title: "FXidResource-klass"
type: docs
weight: 290
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---

**Summary:** The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FXidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [FXidResource(key, version, filter_effect_masks)](#FXidResource_key_version_filter_effect_masks_1) | Initierar en ny instans av klassen [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| F_EID_TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln FEid. |
| F_XID_TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln FXid. |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | r | Hämtar filtereffektmaskerna. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
| version | int | r | Hämtar versionen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: FXidResource(key, version, filter_effect_masks) {#FXidResource_key_version_filter_effect_masks_1}


```
 FXidResource(key, version, filter_effect_masks) 
```

Initierar en ny instans av klassen [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nyckel | int | Resursnyckeln. |
| version | int | Versionen. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | Filtereffektmaskerna. |

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


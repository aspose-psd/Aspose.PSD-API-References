---
title: "PtFlResource klasse"
type: docs
weight: 860
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | Initialiseert een nieuw exemplaar van de [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) klasse. |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | Initialiseert een nieuw exemplaar van de [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| align_with_layer | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| hoek | double | r/w | Haalt of stelt de hoek in. |
| is_linked_with_layer | bool | r/w | Haalt op of stelt een waarde in die aangeeft of dit exemplaar is gekoppeld aan een laag. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | Haalt de offset op of stelt deze in. |
| pattern_id | string | r/w | Haalt de patroonidentificatie op of stelt deze in. |
| pattern_name | string | r/w | Haalt de naam van het patroon op of stelt deze in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| scale | double | r/w | Haalt de schaal op of stelt deze in. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

Initialiseert een nieuw exemplaar van de [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) klasse.

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

Initialiseert een nieuw exemplaar van de [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pattern_name | string | Naam van het patroon. |
| pattern_id | string | De patroonidentifier. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |


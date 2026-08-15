---
title: "ExpaResource Klasse"
type: docs
weight: 280
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Initialiseert een nieuw exemplaar van de [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klasse. |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Initialiseert een nieuw exemplaar van de [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klasse. |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Initialiseert een nieuw exemplaar van de [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| belichting | float | r/w | Haalt de belichting op of stelt deze in. |
| gamma_correctie | float | r/w | Haalt de gamma op of stelt deze in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| offset | float | r/w | Haalt de offset op of stelt deze in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| version | short | r | Haalt de versie op. Standaard is 1 |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Initialiseert een nieuw exemplaar van de [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klasse.

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Initialiseert een nieuw exemplaar van de [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De bytes. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Initialiseert een nieuw exemplaar van de [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| belichting | float | De belichting. |
| offset | float | De offset. |
| gamma | float | De gamma. |

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


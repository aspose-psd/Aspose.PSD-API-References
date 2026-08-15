---
title: "PattResource Klasse"
type: docs
weight: 770
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PattResource()](#PattResource__1) | Initialiseert een nieuw exemplaar van de [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) klasse. |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Initialiseert een nieuw exemplaar van de [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De 'Patt'-type gereedschaps‑infosleutel voor 8‑bits. |
| TYPE_TOOL_KEY2 [static] | int | r | De 'Pat2'-type gereedschaps‑infosleutel voor 16‑bits. |
| TYPE_TOOL_KEY3 [static] | int | r | De 'Pat3'-type gereedschaps‑infosleutel voor 32‑bits. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Haalt of stelt de patroongegevens in; |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de resourceblokgegevens op. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Initialiseert een nieuw exemplaar van de [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) klasse.

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Initialiseert een nieuw exemplaar van de [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | int | De resource‑type‑sleutel. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | De patroongegevens. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de resourceblokgegevens op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |


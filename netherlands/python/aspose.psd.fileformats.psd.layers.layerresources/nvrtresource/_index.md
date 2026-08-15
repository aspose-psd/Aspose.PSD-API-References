---
title: "NvrtResource Klasse"
type: docs
weight: 700
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---

**Summary:** Class NvrtResource. Resource of Invert Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.NvrtResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [NvrtResource()](#NvrtResource__1) | Initialiseert een nieuw exemplaar van de [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) klasse. |
| [NvrtResource(data)](#NvrtResource_data_2) | Initialiseert een nieuw exemplaar van de [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: NvrtResource() {#NvrtResource__1}


```
 NvrtResource() 
```

Initialiseert een nieuw exemplaar van de [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) klasse.

### Constructor: NvrtResource(data) {#NvrtResource_data_2}


```
 NvrtResource(data) 
```

Initialiseert een nieuw exemplaar van de [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De gegevens van de bron. |

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


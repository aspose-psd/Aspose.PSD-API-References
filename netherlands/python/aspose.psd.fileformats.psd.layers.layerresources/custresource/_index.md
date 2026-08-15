---
title: "CustResource Klasse"
type: docs
weight: 230
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [CustResource()](#CustResource__1) | Initialiseert een nieuw exemplaar van de [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) klasse. |
| [CustResource(data)](#CustResource_data_2) | Initialiseert een nieuw exemplaar van de [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| layer_created_date_time | datetime | r/w | Haalt of stelt de datum van de aangemaakte laag in. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Initialiseert een nieuw exemplaar van de [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) klasse.

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Initialiseert een nieuw exemplaar van de [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) klasse.

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


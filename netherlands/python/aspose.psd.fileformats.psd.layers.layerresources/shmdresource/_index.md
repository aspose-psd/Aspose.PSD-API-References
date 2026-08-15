---
title: "ShmdResource Klasse"
type: docs
weight: 890
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---

**Summary:** Class ShmdResource. Metadata settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ShmdResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ShmdResource()](#ShmdResource__1) | Initialiseert een nieuw exemplaar van de [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) klasse. |
| [ShmdResource(data)](#ShmdResource_data_2) | Initialiseert een nieuw exemplaar van de [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| SUB_RESOURCE_HEADER_LENGTH [static] | int | r | De subresource headerlengte |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| layer_created_date_time | datetime | r/w | Haalt of stelt de tijd van de aangemaakte laag in. Als de tijd van de aangemaakte laag niet is gespecificeerd, retourneert het een nieuwe DateTime(0). |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
| sub_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r | Haalt de subresources van de shmd-resource op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: ShmdResource() {#ShmdResource__1}


```
 ShmdResource() 
```

Initialiseert een nieuw exemplaar van de [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) klasse.

### Constructor: ShmdResource(data) {#ShmdResource_data_2}


```
 ShmdResource(data) 
```

Initialiseert een nieuw exemplaar van de [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De gegevens van de bron. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de opgegeven streamcontainer op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| psd_version | int | De PSD‑versie. |


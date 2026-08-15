---
title: "IopaResource Klasse"
type: docs
weight: 440
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Initialiseert een nieuw exemplaar van de [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) klasse. |
| [IopaResource(data)](#IopaResource_data_2) | Initialiseert een nieuw exemplaar van de [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| fill_opacity | byte | r/w | Haalt of stelt de vulopaciteit in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Initialiseert een nieuw exemplaar van de [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) klasse.

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Initialiseert een nieuw exemplaar van de [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De ruwe byte-gegevens. |

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


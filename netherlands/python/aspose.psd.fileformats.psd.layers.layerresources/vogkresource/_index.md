---
title: "VogkResource‑klasse"
type: docs
weight: 1110
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---

**Summary:** The Vector Origination Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VogkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [VogkResource()](#VogkResource__1) | Initialiseert een nieuw exemplaar van de [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| shape_origin_settings | [VectorShapeOriginSettings[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/) | r/w | Haalt de instellingen voor de vorm‑origin op of stelt ze in. |
| signature | int | r | Haalt de handtekening op. |
| version | int | r/w | Haalt de versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: VogkResource() {#VogkResource__1}


```
 VogkResource() 
```

Initialiseert een nieuw exemplaar van de [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) klasse.

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


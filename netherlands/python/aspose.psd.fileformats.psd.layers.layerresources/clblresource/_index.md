---
title: "ClblResource Klasse"
type: docs
weight: 160
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Initialiseert een nieuw exemplaar van de [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) klasse. |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Initialiseert een nieuw exemplaar van de [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) klasse. |
| [ClblResource(data)](#ClblResource_data_3) | Initialiseert een nieuw exemplaar van de [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) klasse.<br/>            Met aangepaste of onbekende waarde |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| blend_clipped_elements | bool | r/w | Haalt of stelt een waarde in die aangeeft of [gemengde bijgesneden elementen]. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Initialiseert een nieuw exemplaar van de [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) klasse.

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Initialiseert een nieuw exemplaar van de [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| blend_clipped_elements | bool | indien ingesteld op <c>true</c> [gemengde bijgesneden elementen]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Initialiseert een nieuw exemplaar van de [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) klasse.<br/>            Met aangepaste of onbekende waarde

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De resourcegegevens. |

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


---
title: "InfxResource Klasse"
type: docs
weight: 420
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | Initialiseert een nieuw exemplaar van de [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) klasse. |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | Initialiseert een nieuw exemplaar van de [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) klasse. |
| [InfxResource(data)](#InfxResource_data_3) | Initialiseert een nieuw exemplaar van de [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) klasse.<br/>            Met aangepaste of onbekende waarde |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| blend_interior_elements | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [blend interior elements]. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

Initialiseert een nieuw exemplaar van de [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) klasse.

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

Initialiseert een nieuw exemplaar van de [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| blend_interior_elements | bool | indien ingesteld op <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

Initialiseert een nieuw exemplaar van de [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) klasse.<br/>            Met aangepaste of onbekende waarde

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


---
title: "KnkoResource‑klasse"
type: docs
weight: 450
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/
---

**Summary:** Class KnkoResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.KnkoResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [KnkoResource()](#KnkoResource__1) | Initialiseert een nieuw exemplaar van de [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) klasse. |
| [KnkoResource(data)](#KnkoResource_data_2) | Initialiseert een nieuw exemplaar van de [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) klasse.<br/>            Met aangepaste of onbekende waarde |
| [KnkoResource(knockout)](#KnkoResource_knockout_3) | Initialiseert een nieuw exemplaar van de [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| key | int | r | Haalt de laagresource key op. |
| knockout | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [blend interior elements]. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: KnkoResource() {#KnkoResource__1}


```
 KnkoResource() 
```

Initialiseert een nieuw exemplaar van de [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) klasse.

### Constructor: KnkoResource(data) {#KnkoResource_data_2}


```
 KnkoResource(data) 
```

Initialiseert een nieuw exemplaar van de [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) klasse.<br/>            Met aangepaste of onbekende waarde

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De resourcegegevens. |

### Constructor: KnkoResource(knockout) {#KnkoResource_knockout_3}


```
 KnkoResource(knockout) 
```

Initialiseert een nieuw exemplaar van de [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| knockout | bool | indien ingesteld op <c>true</c> [blend interior elements]. |

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


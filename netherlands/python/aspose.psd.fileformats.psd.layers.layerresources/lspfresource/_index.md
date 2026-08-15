---
title: "LspfResource Klasse"
type: docs
weight: 640
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Initialiseert een nieuw exemplaar van de [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) klasse. |
| [LspfResource(data)](#LspfResource_data_2) | Initialiseert een nieuw exemplaar van de [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) klasse.<br/>            Met aangepaste of onbekende waarde |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Initialiseert een nieuw exemplaar van de [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info-sleutel 1819504742 |
| is_composite_protected | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar composiet beschermd is. |
| is_position_protected | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar positie‑beschermd is. |
| is_transparency_protected | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of dit exemplaar transparantie‑beschermd is. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Haalt een waarde op of stelt deze in voor het type van de vergrendeling. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Initialiseert een nieuw exemplaar van de [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) klasse.

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Initialiseert een nieuw exemplaar van de [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) klasse.<br/>            Met aangepaste of onbekende waarde

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De resourcegegevens. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Initialiseert een nieuw exemplaar van de [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| is_transparency_protected | bool | indien ingesteld op <c>true</c> [is transparantie beschermd]. |
| is_composite_protected | bool | indien ingesteld op <c>true</c> [is composiet beschermd]. |
| is_position_protected | bool | indien ingesteld op <c>true</c> [is positie beschermd]. |

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


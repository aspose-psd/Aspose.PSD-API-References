---
title: "LclrResource Klasse"
type: docs
weight: 470
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | Initialiseert een nieuw exemplaar van de [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) klasse. |
| [LclrResource(color)](#LclrResource_color_2) | Initialiseert een nieuw exemplaar van de [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) klasse. |
| [LclrResource(data)](#LclrResource_data_3) | Initialiseert een nieuw exemplaar van de [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Haalt op of stelt de kleur van de laag in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

Initialiseert een nieuw exemplaar van de [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) klasse.

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

Initialiseert een nieuw exemplaar van de [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | De kleur. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

Initialiseert een nieuw exemplaar van de [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De resourcegegevens. |

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


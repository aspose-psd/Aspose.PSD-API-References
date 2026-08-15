---
title: "LayerSectionResource Klasse"
type: docs
weight: 460
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/
---

**Summary:** The layer section resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LayerSectionResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LayerSectionResource()](#LayerSectionResource__1) | Initialiseert een nieuw exemplaar van de [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Geeft of stelt de blend‑modussleutel in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| section_type | [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype) | r/w | Haalt op of stelt het sectietype in. |
| signature | int | r | Haalt de handtekening op. |
| subtype | [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype) | r/w | Haalt op of stelt het subtype in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: LayerSectionResource() {#LayerSectionResource__1}


```
 LayerSectionResource() 
```

Initialiseert een nieuw exemplaar van de [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) klasse.

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


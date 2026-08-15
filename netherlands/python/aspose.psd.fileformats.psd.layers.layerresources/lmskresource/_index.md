---
title: "LmskResource Klasse"
type: docs
weight: 560
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | Initialiseert een nieuw exemplaar van de [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| color_component1 | ushort | r/w | Haalt de kleurcomponent 1 op. |
| color_component2 | ushort | r/w | Haalt de kleurcomponent 2 op. |
| color_component3 | ushort | r/w | Haalt de kleurcomponent 3 op. |
| color_component4 | ushort | r/w | Haalt de kleurcomponent 4 op. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | Haalt de kleurenruimte op. |
| flag | byte | r | Haalt de vlag op. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| opacity | short | r/w | Haalt de dekking op. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

Initialiseert een nieuw exemplaar van de [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) klasse.

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


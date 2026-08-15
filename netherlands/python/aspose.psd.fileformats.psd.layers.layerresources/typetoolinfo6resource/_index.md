---
title: "TypeToolInfo6Resource Klasse"
type: docs
weight: 990
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Initialiseert een nieuw exemplaar van de [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| bottom | int | r/w | Haalt de onderlocatie op of stelt deze in. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de class ID op of stelt deze in. |
| class_name | string | r/w | Haalt de class name op of stelt deze in. |
| descriptor_version | int | r/w | Haalt of stelt de descriptorversie in. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Haalt de items op of stelt ze in. |
| key | int | r | Haalt de laagresource key op. |
| left | int | r/w | Haalt de linkerlokatie op of stelt deze in. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| right | int | r/w | Haalt de rechterlocatie op of stelt deze in. |
| signature | int | r | Haalt de handtekening op. |
| text_version | short | r/w | Haalt de tekstversie op of stelt deze in. |
| boven | int | r/w | Haalt de bovenlocatie op of stelt deze in. |
| transform_matrix | double | r/w | Haalt de transformatiematrix op of stelt deze in. |
| version | short | r/w | Haalt de versie van de type‑tool op of stelt deze in. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Haalt de class ID op of stelt deze in. |
| warp_class_name | string | r/w | Haalt de warp‑klassennaam op of stelt deze in. |
| warp_descriptor_version | int | r/w | Haalt de warp‑descriptorversie op of stelt deze in. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Haalt of stelt de warp‑items in. |
| warp_version | short | r/w | Haalt de warp‑versie op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Initialiseert een nieuw exemplaar van de [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De klasse-ID. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | De warp‑klassen‑ID. |

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


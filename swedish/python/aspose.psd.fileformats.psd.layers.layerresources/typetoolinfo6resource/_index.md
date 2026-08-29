---
title: "TypeToolInfo6Resource-klass"
type: docs
weight: 990
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Initierar en ny instans av klassen [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| nedre | int | r/w | Hämtar eller anger den nedre platsen. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger class ID. |
| class_name | string | r/w | Hämtar eller anger class name. |
| descriptor_version | int | r/w | Hämtar eller anger descriptor-versionen. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Hämtar eller anger objekten. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| vänster | int | r/w | Hämtar eller anger den vänstra platsen. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| höger | int | r/w | Hämtar eller anger den högra platsen. |
| signatur | int | r | Hämtar signaturen. |
| text_version | short | r/w | Hämtar eller anger textversionen. |
| övre | int | r/w | Hämtar eller anger den övre platsen. |
| transform_matrix | double | r/w | Hämtar eller anger transformationsmatrisen. |
| version | short | r/w | Hämtar eller anger typverktygsversionen. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Hämtar eller anger class ID. |
| warp_class_name | string | r/w | Hämtar eller anger warp-klassnamnet. |
| warp_descriptor_version | int | r/w | Hämtar eller anger warp-deskriptörversionen. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Hämtar eller anger warp‑objekten. |
| warp_version | short | r/w | Hämtar eller anger warp-versionen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Initierar en ny instans av klassen [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Den class ID. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Warp-klassens ID. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |


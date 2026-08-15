---
title: "TypeToolInfoResource klass"
type: docs
weight: 1000
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Initierar en ny instans av TypeToolInfoResource klass |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| a_component | short | r/w | Hämtar eller anger en komponent. |
| b_component | short | r/w | Hämtar eller anger b-komponenten. |
| character_count | int | r/w | Hämtar eller anger teckenantalet. |
| color_space_value | short | r/w | Hämtar eller anger färgrymdsvärdet. |
| font_version | short | r/w | Hämtar eller anger teckensnittsversionen. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Hämtar eller anger teckensnitten. |
| fonts_count | short | r | Hämtar antalet teckensnitt. |
| g_component | short | r/w | Hämtar eller anger g-komponenten. |
| horizontal_placement | int | r/w | Hämtar eller anger horisontell placering. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| line_count | short | r | Hämtar antalet rader. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Hämtar eller anger raderna. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| r_component | short | r/w | Hämtar eller anger r-komponenten. |
| scale_factor | int | r/w | Hämtar eller anger skalningsfaktorn. |
| selection_end | int | r/w | Hämtar eller anger markeringsslutet. |
| selection_start | int | r/w | Hämtar eller anger markeringsstarten. |
| signatur | int | r | Hämtar signaturen. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Hämtar eller anger teckensnittsstilarna. |
| styles_count | short | r | Hämtar antalet stilar. |
| transform_matrix | double | r/w | Hämtar eller anger transformationsmatrisen. |
| type_value | short | r/w | Hämtar eller anger typvärdet. |
| version | short | r/w | Hämtar eller anger versionen. |
| vertical_placement | int | r/w | Hämtar eller anger den vertikala placeringen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar den angivna strömbehållaren. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Initierar en ny instans av TypeToolInfoResource klass

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| psd_version | int | PSD-versionen. |


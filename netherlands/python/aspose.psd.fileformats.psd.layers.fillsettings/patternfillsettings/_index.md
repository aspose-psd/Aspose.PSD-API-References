---
title: "PatternFillSettings Klasse"
type: docs
weight: 130
url: /nl/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Initialiseert een nieuw exemplaar van de PatternFillSettings klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Haalt of stelt een waarde in die aangeeft of [link with layer]. |
| hoek | double | r/w | Haalt of stelt de hoek in. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de kleur in. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Het vultype |
| horizontal_offset | int | r/w | Haalt of stelt de horizontale offset in. |
| linked | bool | r/w | Haalt of stelt een waarde in die aangeeft of deze [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) is gekoppeld. |
| pattern_data | int | r/w | Haalt of stelt de patroongegevens in. |
| pattern_height | int | r/w | Haalt de hoogte van het patroon op of stelt deze in. |
| pattern_id | string | r/w | Haalt de patroonidentificatie op of stelt deze in. |
| pattern_name | string | r/w | Haalt de naam van het patroon op of stelt deze in. |
| pattern_width | int | r/w | Haalt de breedte van het patroon op of stelt deze in. |
| point_type | string | r/w | Haalt het type van het punt op of stelt dit in. |
| scale | double | r/w | Haalt de schaal op of stelt deze in. |
| vertical_offset | int | r/w | Haalt de verticale offset op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Genereert de LFX2-resourceknooppunten. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Initialiseert een nieuw exemplaar van de PatternFillSettings klasse

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Genereert de LFX2-resourceknooppunten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point_type | string | Type van het punt. |
| color | [Color](/psd/python-net/aspose.psd/color) | De kleur. |
| pattern_name | string | Naam van het patroon. |
| identificatie | string | De identificatie. |
| scale | double | De schaal. |
| gekoppeld | bool | indien ingesteld op <c>true</c> [gekoppeld]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | De offset. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Lijst van [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |



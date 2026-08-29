---
title: "PatternFillSettings Class"
type: docs
weight: 130
url: /sv/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Initierar en ny instans av klassen PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Hämtar eller anger ett värde som indikerar om [link with layer]. |
| vinkel | double | r/w | Hämtar eller anger vinkeln. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger färgen. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Fylltypen |
| horizontal_offset | int | r/w | Hämtar eller anger den horisontella förskjutningen. |
| linked | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) är länkad. |
| pattern_data | int | r/w | Hämtar eller anger mönsterdata. |
| pattern_height | int | r/w | Hämtar eller anger höjden på mönstret. |
| pattern_id | string | r/w | Hämtar eller anger mönsteridentifieraren. |
| pattern_name | string | r/w | Hämtar eller anger namnet på mönstret. |
| pattern_width | int | r/w | Hämtar eller anger bredden på mönstret. |
| point_type | string | r/w | Hämtar eller anger typen av punkten. |
| skala | double | r/w | Hämtar eller anger skalan. |
| vertical_offset | int | r/w | Hämtar eller anger den vertikala förskjutningen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Genererar LFX2-resursnoderna. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Initierar en ny instans av klassen PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Genererar LFX2-resursnoderna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point_type | string | Typ av punkten. |
| color | [Color](/psd/python-net/aspose.psd/color) | Färgen. |
| pattern_name | string | Namnet på mönstret. |
| identifierare | string | Identifieraren. |
| skala | double | Skalan. |
| länkad | bool | om den är inställd på <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Förskjutningen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Lista över [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |



---
title: "PatternFillSettings Klasse"
type: docs
weight: 130
url: /de/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Initialisiert eine neue Instanz der PatternFillSettings Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [link with layer]. |
| angle | double | r/w | Liest oder setzt den Winkel. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Farbe. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Der Fülltyp |
| horizontal_offset | int | r/w | Liest oder setzt den horizontalen Versatz. |
| linked | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) verknüpft ist. |
| pattern_data | int | r/w | Liest oder setzt die Musterdaten. |
| pattern_height | int | r/w | Liest oder setzt die Höhe des Musters. |
| pattern_id | string | r/w | Liest oder setzt die Musterkennung. |
| pattern_name | string | r/w | Liest oder setzt den Namen des Musters. |
| pattern_width | int | r/w | Liest oder setzt die Breite des Musters. |
| point_type | string | r/w | Liest oder setzt den Typ des Punktes. |
| scale | double | r/w | Ruft den Maßstab ab oder legt ihn fest. |
| vertical_offset | int | r/w | Liest oder setzt den vertikalen Versatz. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Erzeugt die LFX2-Ressourcenknoten. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Initialisiert eine neue Instanz der PatternFillSettings Klasse

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Erzeugt die LFX2-Ressourcenknoten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point_type | string | Typ des Punktes. |
| color | [Color](/psd/python-net/aspose.psd/color) | Die Farbe. |
| pattern_name | string | Name des Musters. |
| identifier | string | Der Bezeichner. |
| scale | double | Die Skalierung. |
| verknüpft | bool | wenn auf <c>true</c> [verknüpft] gesetzt. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Der Versatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Liste von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |



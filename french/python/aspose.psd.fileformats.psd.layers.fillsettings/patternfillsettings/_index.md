---
title: "Classe PatternFillSettings"
type: docs
weight: 130
url: /fr/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Initialise une nouvelle instance de la classe PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Obtient ou définit une valeur indiquant si [link with layer]. |
| angle | double | r/w | Obtient ou définit l'angle. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Le type de remplissage |
| horizontal_offset | int | r/w | Obtient ou définit le décalage horizontal. |
| linked | bool | r/w | Obtient ou définit une valeur indiquant si ce [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) est lié. |
| pattern_data | int | r/w | Obtient ou définit les données du motif. |
| pattern_height | int | r/w | Obtient ou définit la hauteur du motif. |
| pattern_id | chaîne | r/w | Obtient ou définit l'identifiant du motif. |
| pattern_name | chaîne | r/w | Obtient ou définit le nom du motif. |
| pattern_width | int | r/w | Obtient ou définit la largeur du motif. |
| point_type | chaîne | r/w | Obtient ou définit le type du point. |
| scale | double | r/w | Obtient ou définit l'échelle. |
| vertical_offset | int | r/w | Obtient ou définit le décalage vertical. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Génère les nœuds de ressources LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Initialise une nouvelle instance de la classe PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Génère les nœuds de ressources LFX2.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point_type | chaîne | Type du point. |
| color | [Color](/psd/python-net/aspose.psd/color) | La couleur. |
| pattern_name | chaîne | Nom du motif. |
| identifiant | chaîne | L'identifiant. |
| scale | double | L'échelle. |
| lié | bool | si défini sur <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Le décalage. |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Liste de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |



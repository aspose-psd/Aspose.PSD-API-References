---
title: "Clase PatternFillSettings"
type: docs
weight: 130
url: /es/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Inicializa una nueva instancia de la clase PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Obtiene o establece un valor que indica si [link with layer]. |
| ángulo | double | r/w | Obtiene o establece el ángulo. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | El tipo de relleno |
| horizontal_offset | int | r/w | Obtiene o establece el desplazamiento horizontal. |
| linked | bool | r/w | Obtiene o establece un valor que indica si este [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) está vinculado. |
| pattern_data | int | r/w | Obtiene o establece los datos del patrón. |
| pattern_height | int | r/w | Obtiene o establece la altura del patrón. |
| pattern_id | string | r/w | Obtiene o establece el identificador del patrón. |
| pattern_name | string | r/w | Obtiene o establece el nombre del patrón. |
| pattern_width | int | r/w | Obtiene o establece el ancho del patrón. |
| point_type | string | r/w | Obtiene o establece el tipo del punto. |
| scale | double | r/w | Obtiene o establece la escala. |
| vertical_offset | int | r/w | Obtiene o establece el desplazamiento vertical. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Genera los nodos de recursos LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Inicializa una nueva instancia de la clase PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Genera los nodos de recursos LFX2.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point_type | string | Tipo del punto. |
| color | [Color](/psd/python-net/aspose.psd/color) | El color. |
| pattern_name | string | Nombre del patrón. |
| identificador | string | El identificador. |
| scale | double | La escala. |
| vinculado | bool | si se establece en <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | El desplazamiento. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Lista de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |



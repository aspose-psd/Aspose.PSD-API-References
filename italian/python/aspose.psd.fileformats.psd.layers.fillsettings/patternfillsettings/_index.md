---
title: "Classe PatternFillSettings"
type: docs
weight: 130
url: /it/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Inizializza una nuova istanza della classe PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Ottiene o imposta un valore che indica se [link with layer]. |
| angolo | double | r/w | Ottiene o imposta l'angolo. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Il tipo di riempimento |
| horizontal_offset | int | r/w | Ottiene o imposta lo spostamento orizzontale. |
| linked | bool | r/w | Ottiene o imposta un valore che indica se questo [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) è collegato. |
| pattern_data | int | r/w | Ottiene o imposta i dati del pattern. |
| pattern_height | int | r/w | Ottiene o imposta l'altezza del pattern. |
| pattern_id | string | r/w | Ottiene o imposta l'identificatore del pattern. |
| pattern_name | string | r/w | Ottiene o imposta il nome del pattern. |
| pattern_width | int | r/w | Ottiene o imposta la larghezza del pattern. |
| point_type | string | r/w | Ottiene o imposta il tipo del punto. |
| scale | double | r/w | Ottiene o imposta la scala. |
| vertical_offset | int | r/w | Ottiene o imposta lo spostamento verticale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Genera i nodi risorsa LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Inizializza una nuova istanza della classe PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Genera i nodi risorsa LFX2.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point_type | string | Tipo del punto. |
| color | [Color](/psd/python-net/aspose.psd/color) | Il colore. |
| pattern_name | string | Nome del pattern. |
| identifier | string | L'identificatore. |
| scale | double | La scala. |
| linked | bool | se impostato su <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Lo spostamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Elenco di [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |



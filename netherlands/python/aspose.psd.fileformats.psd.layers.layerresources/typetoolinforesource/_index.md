---
title: "TypeToolInfoResource Klasse"
type: docs
weight: 1000
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Initialiseert een nieuw exemplaar van de TypeToolInfoResource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| a_component | short | r/w | Haalt op of stelt een component in. |
| b_component | short | r/w | Haalt op of stelt de b-component in. |
| character_count | int | r/w | Haalt op of stelt het aantal tekens in. |
| color_space_value | short | r/w | Haalt op of stelt de kleurruimtewaarde in. |
| font_version | short | r/w | Haalt op of stelt de lettertypeversie in. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Haalt op of stelt de lettertypen in. |
| fonts_count | short | r | Haalt het aantal lettertypen op. |
| g_component | short | r/w | Haalt op of stelt de g-component in. |
| horizontal_placement | int | r/w | Haalt op of stelt de horizontale plaatsing in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| line_count | short | r | Haalt het aantal regels op. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Haalt de regels op of stelt ze in. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| r_component | short | r/w | Haalt de r-component op of stelt deze in. |
| scale_factor | int | r/w | Haalt de schaalfactor op of stelt deze in. |
| selection_end | int | r/w | Haalt het einde van de selectie op of stelt dit in. |
| selection_start | int | r/w | Haalt het begin van de selectie op of stelt dit in. |
| signature | int | r | Haalt de handtekening op. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Haalt de lettertype-stijlen op of stelt ze in. |
| styles_count | short | r | Haalt het aantal stijlen op. |
| transform_matrix | double | r/w | Haalt de transformatiematrix op of stelt deze in. |
| type_value | short | r/w | Haalt de typewaarde op of stelt deze in. |
| version | short | r/w | Haalt de versie op of stelt deze in. |
| vertical_placement | int | r/w | Haalt de verticale plaatsing op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de opgegeven streamcontainer op. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Initialiseert een nieuw exemplaar van de TypeToolInfoResource klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de opgegeven streamcontainer op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| psd_version | int | De PSD‑versie. |


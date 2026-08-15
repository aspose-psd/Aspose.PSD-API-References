---
title: "GradientFillSettings klasse"
type: docs
weight: 50
url: /nl/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Initialiseert een nieuw exemplaar van de [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| hoek | double | r/w | Haalt of stelt de hoek in. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt of stelt de kleur in. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Haalt de kleurpunten op of stelt ze in. |
| dither | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) geditherd is. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Het vultype |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Haalt de modus voor deze gradient op.<br/>            Bepaalt 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Haalt de naam van de gradient op of stelt deze in. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Haalt het type van de gradient op of stelt dit in. |
| horizontal_offset | double | r/w | Haalt de horizontale offset in procent op of stelt deze in. |
| interpolatie | short | r/w | Interpolatie. Bepaalt de gladheid, wanneer 'Gradient Type' = 'Solid'. Waardenbereik: 0-4096. |
| reverse | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of deze [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) omgekeerd is. |
| scale | int | r/w | Haalt de schaal op of stelt deze in. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Haalt de transparantiepunten op of stelt ze in. |
| vertical_offset | double | r/w | Haalt de verticale offset in procent op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Voegt het kleurpunt toe. |
| [add_transparency_point()](#add_transparency_point__2) | Voegt het kleurpunt toe. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Genereert de LFX2-resourceknooppunten. |
| [remove_color_point(point)](#remove_color_point_point_4) | Verwijdert het kleurpunt. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Verwijdert het transparantiepunt. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Initialiseert een nieuw exemplaar van de [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) klasse.

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Voegt het kleurpunt toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Aangemaakt kleurpunt |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Voegt het kleurpunt toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Aangemaakt transparantiepunt |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Genereert de LFX2-resourceknooppunten.

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Gegenereerde lijst van [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Verwijdert het kleurpunt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Het punt. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Verwijdert het transparantiepunt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Het punt. |


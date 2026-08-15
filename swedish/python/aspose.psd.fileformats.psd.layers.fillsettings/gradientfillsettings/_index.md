---
title: "GradientFillSettings-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Initierar en ny instans av klassen [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Hämtar eller anger ett värde som indikerar om [align with layer]. |
| vinkel | double | r/w | Hämtar eller anger vinkeln. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger färgen. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Hämtar eller anger färgpunkterna. |
| dither | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) är dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Fyllningstypen. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Hämtar läget för denna gradient.<br/>            Bestämmer 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Hämtar eller anger namnet på gradienten. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Hämtar eller anger typen på gradienten. |
| horizontal_offset | double | r/w | Hämtar eller anger den horisontella förskjutningen i procent. |
| interpolering | short | r/w | Interpolering. Bestämmer jämnhet när 'Gradient Type' = 'Solid'. Värdeintervall: 0-4096. |
| reverse | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) är omvänd. |
| skala | int | r/w | Hämtar eller anger skalan. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Hämtar eller anger transparenspunkterna. |
| vertical_offset | double | r/w | Hämtar eller anger den vertikala förskjutningen i procent. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Lägger till färgpunkt. |
| [add_transparency_point()](#add_transparency_point__2) | Lägger till färgpunkt. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Genererar LFX2-resursnoderna. |
| [remove_color_point(point)](#remove_color_point_point_4) | Tar bort färgpunkt. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Tar bort transparenspunkt. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Initierar en ny instans av klassen [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/).

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Lägger till färgpunkt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Skapad färgpunkt |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Lägger till färgpunkt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Skapad transparenspunkt |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Genererar LFX2-resursnoderna.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Genererad lista över [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Tar bort färgpunkt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Punkten. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Tar bort transparenspunkt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Punkten. |


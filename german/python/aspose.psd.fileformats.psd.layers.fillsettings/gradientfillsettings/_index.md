---
title: "Klasse GradientFillSettings"
type: docs
weight: 50
url: /de/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Initialisiert eine neue Instanz der Klasse [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [ausrichten mit Ebene]. |
| angle | double | r/w | Liest oder setzt den Winkel. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt die Farbe. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Liest oder setzt die Farbpunkte. |
| dither | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) dither ist. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Der Fülltyp. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Liest den Modus für diesen Farbverlauf.<br/>            Bestimmt 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Ruft den Namen des Verlaufs ab oder legt ihn fest. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Ruft den Typ des Verlaufs ab oder legt ihn fest. |
| horizontal_offset | double | r/w | Ruft den horizontalen Versatz in Prozent ab oder legt ihn fest. |
| Interpolation | short | r/w | Interpolation. Bestimmt die Glätte, wenn 'Gradient Type' = 'Solid'. Wertebereich: 0-4096. |
| reverse | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob dieses [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) umgekehrt ist. |
| scale | int | r/w | Ruft den Maßstab ab oder legt ihn fest. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Ruft die Transparenzpunkte ab oder legt sie fest. |
| vertical_offset | double | r/w | Ruft den vertikalen Versatz in Prozent ab oder legt ihn fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Fügt den Farbpunkt hinzu. |
| [add_transparency_point()](#add_transparency_point__2) | Fügt den Farbpunkt hinzu. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Erzeugt die LFX2-Ressourcenknoten. |
| [remove_color_point(point)](#remove_color_point_point_4) | Entfernt den Farbpunkt. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Entfernt den Transparenzpunkt. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Initialisiert eine neue Instanz der Klasse [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/).

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Fügt den Farbpunkt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Farbpunkt erstellt |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Fügt den Farbpunkt hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Transparenzpunkt erstellt |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Erzeugt die LFX2-Ressourcenknoten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Generierte Liste von [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Entfernt den Farbpunkt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Der Punkt. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Entfernt den Transparenzpunkt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Der Punkt. |


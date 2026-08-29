---
title: "Classe GradientFillSettings"
type: docs
weight: 50
url: /fr/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Initialise une nouvelle instance de la classe [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Obtient ou définit une valeur indiquant si [align with layer]. |
| angle | double | r/w | Obtient ou définit l'angle. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit la couleur. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Obtient ou définit les points de couleur. |
| dither | bool | r/w | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) est dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Le type de remplissage. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Obtient le mode pour ce dégradé.<br/>            Détermine 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | chaîne | r/w | Obtient ou définit le nom du dégradé. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Obtient ou définit le type du dégradé. |
| horizontal_offset | double | r/w | Obtient ou définit le décalage horizontal en pourcentage. |
| interpolation | short | r/w | Interpolation. Détermine la fluidité, lorsque 'Gradient Type' = 'Solid'. Plage de valeurs : 0-4096. |
| reverse | bool | r/w | Obtient ou définit une valeur indiquant si ce [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) est inversé. |
| scale | int | r/w | Obtient ou définit l'échelle. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Obtient ou définit les points de transparence. |
| vertical_offset | double | r/w | Obtient ou définit le décalage vertical en pourcentage. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Ajoute le point de couleur. |
| [add_transparency_point()](#add_transparency_point__2) | Ajoute le point de couleur. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Génère les nœuds de ressources LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | Supprime le point de couleur. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Supprime le point de transparence. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Initialise une nouvelle instance de la classe [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/).

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Ajoute le point de couleur.

**Returns**

| Type | Description |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Point de couleur créé |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Ajoute le point de couleur.

**Returns**

| Type | Description |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Point de transparence créé |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Génère les nœuds de ressources LFX2.

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Liste générée de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Supprime le point de couleur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Le point. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Supprime le point de transparence.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Le point. |


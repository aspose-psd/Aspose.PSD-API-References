---
title: "Clase GradientFillSettings"
type: docs
weight: 50
url: /es/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Inicializa una nueva instancia de la clase [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Obtiene o establece un valor que indica si [alinear con capa]. |
| ángulo | double | r/w | Obtiene o establece el ángulo. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece el color. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Obtiene o establece los puntos de color. |
| dither | bool | r/w | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) está dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | El tipo de relleno. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Obtiene el modo para este degradado.<br/>            Determina 'Tipo de Degradado' = 'Sólido/Ruido' (0/1). |
| gradient_name | string | r/w | Obtiene o establece el nombre del degradado. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Obtiene o establece el tipo del degradado. |
| horizontal_offset | double | r/w | Obtiene o establece el desplazamiento horizontal en porcentaje. |
| interpolación | short | r/w | Interpolación. Determina la suavidad, cuando 'Gradient Type' = 'Solid'. Rango de valores: 0-4096. |
| reverse | bool | r/w | Obtiene o establece un valor que indica si este [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) está invertido. |
| scale | int | r/w | Obtiene o establece la escala. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Obtiene o establece los puntos de transparencia. |
| vertical_offset | double | r/w | Obtiene o establece el desplazamiento vertical en porcentaje. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Añade el punto de color. |
| [add_transparency_point()](#add_transparency_point__2) | Añade el punto de color. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Genera los nodos de recursos LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | Elimina el punto de color. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Elimina el punto de transparencia. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Inicializa una nueva instancia de la clase [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/).

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Añade el punto de color.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Punto de color creado |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Añade el punto de color.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Punto de transparencia creado |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Genera los nodos de recursos LFX2.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Lista generada de [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Elimina el punto de color.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | El punto. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Elimina el punto de transparencia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | El punto. |


---
title: "PathGradientBrush-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med den angivna banan. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna och omslagsläget. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna och omslagsläget. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Hämtar eller anger en [Blend](/psd/python-net/aspose.psd/blend/) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger färgen i mitten av banans gradient. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Hämtar eller anger mittpunkten för stiggradienten. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Hämtar eller anger fokuspunkten för gradientens avtagande. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Hämtar grafikvägen som denna pensel byggdes på. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Hämtar eller anger en [ColorBlend](/psd/python-net/aspose.psd/colorblend/) som definierar en flerfärgad linjär gradient. |
| is_transform_changed | bool | r | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller<br/>            anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introducerades för bakåtkompatibilitet med GDI+. |
| opacity | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Hämtar stigpunkterna som denna pensel byggdes på. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger en matris av färger som motsvarar punkterna i banan som denna [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) fyller. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Hämtar eller anger en kopia av [Matrix](/psd/python-net/aspose.psd/matrix/) som definierar en lokal geometrisk transformation för denna [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Hämtar eller anger en [WrapMode](/psd/python-net/aspose.psd/wrapmode/)‑enumeration som indikerar omslagsläget för denna [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Skapar en ny djupklon av den aktuella [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) genom att föregå den angivna [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer egenskapen [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Rotera den lokala geometriska transformationen med den angivna mängden. Denna metod föregår rotationen till transformationen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod föregår skalningsmatrisen till transformationen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Skapar en gradient med en mittfärg och en linjär avtagning till en omgivande färg. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Skapar en gradient med en mittfärg och en linjär avtagning till varje omgivande färg. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Skapar en gradientpensel som ändrar färg från mitten av banan utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Skapar en gradientpensel som ändrar färg från mitten av banan utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med den angivna banan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Den [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) som definierar området som fylls av denna [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar de punkter som utgör vägens hörn. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar de punkter som utgör vägens hörn. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna och omslagsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar de punkter som utgör vägens hörn. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ett [WrapMode](/psd/python-net/aspose.psd/wrapmode/) som specificerar hur fyllningar ritade med denna [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) upprepas. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Initierar en ny instans av klassen [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) med de angivna punkterna och omslagsläget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | En array av [PointF](/psd/python-net/aspose.psd/pointf/) strukturer som representerar de punkter som utgör vägens hörn. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ett [WrapMode](/psd/python-net/aspose.psd/wrapmode/) som specificerar hur fyllningar ritade med denna [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) upprepas. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Skapar en ny djupklon av den aktuella [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | En ny [Brush](/psd/python-net/aspose.psd/brush/) som är den djupa klonen av denna [Brush](/psd/python-net/aspose.psd/brush/) instans. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) genom att föregå den angivna [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som används för att multiplicera den geometriska transformen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplicerar [Matrix](/psd/python-net/aspose.psd/matrix/) som representerar den lokala geometriska transformationen för denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Den [Matrix](/psd/python-net/aspose.psd/matrix/) som används för att multiplicera den geometriska transformen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar i vilken ordning de två matriserna ska multipliceras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Rotera den lokala geometriska transformationen med den angivna mängden. Denna metod föregår rotationen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Rotera den lokala geometriska transformationen med den angivna mängden i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformationen med de angivna värdena. Denna metod föregår skalningsmatrisen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden med vilken transformen ska skalas i x-axelns riktning. |
| sy | float | Mängden med vilken transformen ska skalas i y-axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformationen med de angivna värdena i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Mängden med vilken transformen ska skalas i x-axelns riktning. |
| sy | float | Mängden med vilken transformen ska skalas i y-axelns riktning. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Skapar en gradient med en mittfärg och en linjär avtagning till en omgivande färg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Skapar en gradient med en mittfärg och en linjär avtagning till varje omgivande färg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |
| skala | float | Ett värde från 0 till 1 som specificerar den maximala intensiteten för mittfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för mittfärgen, och det är standardvärdet. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Skapar en gradientpensel som ändrar färg från mitten av banan utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Skapar en gradientpensel som ändrar färg från mitten av banan utåt till banans gräns. Övergången från en färg till en annan baseras på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde från 0 till 1 som specificerar var, längs någon radie från banans mitt till banans gräns, mittfärgen har sin högsta intensitet. Ett värde på 1 (standard) placerar den högsta intensiteten i banans mitt. |
| skala | float | Ett värde från 0 till 1 som specificerar den maximala intensiteten för mittfärgen som blandas med gränsfärgen. Ett värde på 1 ger den högsta möjliga intensiteten för mittfärgen, och det är standardvärdet. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen (infoga före eller efter) i vilken translationen ska tillämpas. |


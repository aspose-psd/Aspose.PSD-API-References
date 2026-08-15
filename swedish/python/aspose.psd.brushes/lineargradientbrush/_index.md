---
title: "LinearGradientBrush-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med standardparametrar.<br/>            Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med angivna punkter och färger. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med angivna punkter och färger. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| vinkel | float | r/w | Hämtar eller anger gradientvinkeln. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Hämtar eller anger en [Blend](/psd/python-net/aspose.psd/blend/) som specificerar positioner och faktorer som definierar ett anpassat avtagande för gradienten. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger den avslutande gradientfärgen. |
| gamma_correction | bool | r/w | Hämtar eller anger ett värde som indikerar om gamma‑korrektion är aktiverad för detta [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Hämtar eller anger en [ColorBlend](/psd/python-net/aspose.psd/colorblend/) som definierar en flerfärgad linjär gradient. |
| is_angle_scalable | bool | r/w | Hämtar eller anger ett värde som indikerar om [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) ändras under transformationer med detta [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Hämtar ett värde som indikerar om transformationer har ändrats på något sätt. Till exempel genom att sätta transformationsmatrisen eller<br/>            anropa någon av metoderna som ändrar transformationsmatrisen. Egenskapen introducerades för bakåtkompatibilitet med GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger start- och slutfärgerna för gradienten. |
| opacity | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Värdet 0 betyder att penseln är helt synlig, värdet 1 betyder att penseln är helt ogenomskinlig. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Hämtar eller anger ett rektangulärt område som definierar start- och slutpunkterna för gradienten. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger startgradientfärgen. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Skapar ett gradientavtagande baserat på en klockformad kurva. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod föregår översättningen till transformationen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med standardparametrar.<br/>            Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med angivna punkter och färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | En [Point](/psd/python-net/aspose.psd/point/)‑struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | En [Point](/psd/python-net/aspose.psd/point/)‑struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar slutfärgen för den linjära gradienten. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) med angivna punkter och färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | En [Point](/psd/python-net/aspose.psd/point/)‑struktur som representerar startpunkten för den linjära gradienten. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | En [Point](/psd/python-net/aspose.psd/point/)‑struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar slutfärgen för den linjära gradienten. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| is_angle_scalable | bool | Om den är satt till <c>true</c> ändras vinkeln under transformationer med denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Initierar en ny instans av klassen [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) baserat på en rektangel, start- och slutfärger samt en orienteringsvinkel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En [RectangleF](/psd/python-net/aspose.psd/rectanglef/)‑struktur som specificerar gränserna för den linjära gradienten. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar startfärgen för gradienten. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | En [Color](/psd/python-net/aspose.psd/color/) struktur som representerar slutfärgen för gradienten. |
| vinkel | float | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| is_angle_scalable | bool | Om den är satt till <c>true</c> ändras vinkeln under transformationer med denna [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

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

Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar mitten av gradienten (punkten där gradienten endast består av slutfärgen). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Skapar en linjär gradient med en mittfärg och ett linjärt avtagande till en enda färg i båda ändar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar mitten av gradienten (punkten där gradienten endast består av slutfärgen). |
| skala | float | Ett värde mellan 0 och 1 som specificerar hur snabbt färgerna avtar från startfärgen till <paramref name="focus" /> (slutfärg) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar mitten av gradienten (punkten där startfärgen och slutfärgen blandas lika). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Skapar ett gradientavtagande baserat på en klockformad kurva.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fokus | float | Ett värde mellan 0 och 1 som specificerar mitten av gradienten (punkten där gradienten endast består av slutfärgen). |
| skala | float | Ett värde mellan 0 och 1 som specificerar hur snabbt färgerna avtar från <paramref name="focus" />. |

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


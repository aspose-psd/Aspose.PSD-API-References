---
title: "Pen-klass"
type: docs
weight: 3360
url: /sv/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Pen.brush](/psd/python-net/aspose.psd/pen/) och [Pen.width](/psd/python-net/aspose.psd/pen/). |
| [Pen(color)](#Pen_color_3) | Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med den angivna färgen. |
| [Pen(color, width)](#Pen_color_width_4) | Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med de angivna egenskaperna [Pen.color](/psd/python-net/aspose.psd/pen/) och [Pen.width](/psd/python-net/aspose.psd/pen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Hämtar eller anger justeringen för denna [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Hämtar eller anger [Pen.brush](/psd/python-net/aspose.psd/pen/) som bestämmer attributen för denna [Pen](/psd/python-net/aspose.psd/pen/). |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger färgen på denna [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Hämtar eller anger en array av värden som specificerar en sammansatt penna. En sammansatt penna ritar en sammansatt linje bestående av parallella linjer och mellanrum. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Hämtar eller anger en anpassad spets att använda i slutet av linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Hämtar eller anger en anpassad spets att använda i början av linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Hämtar eller anger spetsstilen som används i slutet av strecken som bildar streckade linjer ritat med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Hämtar eller anger avståndet från början av en linje till starten av ett streckmönster. |
| dash_pattern | float | r/w | Hämtar eller anger en array av anpassade streck och mellanrum. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Hämtar eller anger stilen som används för streckade linjer ritat med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Hämtar eller anger kapstilen som används i slutet av linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Hämtar eller anger sammankopplingsstilen för ändarna på två på varandra följande linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Hämtar eller anger gränsen för tjockleken på sammankopplingen i ett snedkantigt hörn. |
| opacity | float | r/w | Hämtar eller anger objektets opacitet. Värdet bör vara mellan 0 och 1. Värde 0 betyder att objektet är helt synligt, värde 1 betyder att objektet är helt ogenomskinligt. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Hämtar stilen på linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Hämtar eller anger kapstilen som används i början av linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Hämtar eller anger en kopia av den geometriska transformationen för denna [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Hämtar eller anger bredden på denna [Pen](/psd/python-net/aspose.psd/pen/), i enheter av Graphics-objektet som används för ritning. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Multiplicerar transformationsmatrisen för denna [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Multiplicerar transformationsmatrisen för denna [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen. |
| reset_transform() | Återställer den geometriska transformationsmatrisen för denna [Pen](/psd/python-net/aspose.psd/pen/) till identitet. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger rotationen först i transformationen. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger skalningsmatrisen först i transformationen. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Anger värdena som bestämmer kapstilens utseende för att avsluta linjer som ritas av denna [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger translationen först i transformationen. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Översätter den lokala geometriska transformationen med de angivna dimensionerna i den angivna ordningen. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Pen.brush](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | En [Pen.brush](/psd/python-net/aspose.psd/pen/) som bestämmer fyllningsegenskaperna för denna [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Pen.brush](/psd/python-net/aspose.psd/pen/) och [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | En [Pen.brush](/psd/python-net/aspose.psd/pen/) som bestämmer egenskaperna för denna [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Bredden på den nya [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med den angivna färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | En [Pen.color](/psd/python-net/aspose.psd/pen/) struktur som anger färgen på denna [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initierar en ny instans av klassen [Pen](/psd/python-net/aspose.psd/pen/) med de angivna egenskaperna [Pen.color](/psd/python-net/aspose.psd/pen/) och [Pen.width](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | En [Pen.color](/psd/python-net/aspose.psd/pen/) struktur som anger färgen på denna [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Ett värde som indikerar bredden på denna [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Multiplicerar transformationsmatrisen för denna [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/)‑objektet som ska multipliceras med transformationsmatrisen. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Multiplicerar transformationsmatrisen för denna [Pen](/psd/python-net/aspose.psd/pen/) med den angivna [Matrix](/psd/python-net/aspose.psd/matrix/) i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) som ska multipliceras med transformationsmatrisen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Ordningen i vilken multiplikationsoperationen ska utföras. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Roterar den lokala geometriska transformationen med den angivna vinkeln. Denna metod lägger rotationen först i transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Roterar den lokala geometriska transformationen med den angivna vinkeln i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Vinkeln för rotationen. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om rotationsmatrisen ska läggas till i slutet eller i början. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Skalar den lokala geometriska transformationen med de angivna faktorerna. Denna metod lägger skalningsmatrisen först i transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Faktorn som transformationen ska skalas med i x-axelns riktning. |
| sy | float | Faktorn som transformationen ska skalas med i y-axelns riktning. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Skalar den lokala geometriska transformationen med de angivna faktorerna i den angivna ordningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sx | float | Faktorn som transformationen ska skalas med i x-axelns riktning. |
| sy | float | Faktorn som transformationen ska skalas med i y-axelns riktning. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | En [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) som specificerar om skalningsmatrisen ska läggas till i slutet eller i början. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Anger värdena som bestämmer kapstilens utseende för att avsluta linjer som ritas av denna [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | En [LineCap](/psd/python-net/aspose.psd/linecap/) som representerar kapstilen att använda i början av linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | En [LineCap](/psd/python-net/aspose.psd/linecap/) som representerar kapstilen att använda i slutet av linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | En [LineCap](/psd/python-net/aspose.psd/linecap/) som representerar kapstilen att använda i början eller slutet av streckade linjer som ritas med denna [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Översätter den lokala geometriska transformationen med de angivna dimensionerna. Denna metod lägger translationen först i transformationen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | float | Värdet för translationen i x. |
| dy | float | Värdet för translationen i y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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


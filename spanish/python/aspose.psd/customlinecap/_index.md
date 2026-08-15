---
title: "Clase CustomLineCap"
type: docs
weight: 1010
url: /es/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Inicializa una nueva instancia de la clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) con el contorno y relleno especificados. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Inicializa una nueva instancia de la clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partir de la enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) existente especificada, con el contorno y relleno especificados. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Inicializa una nueva instancia de la clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partir de la enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) existente especificada, con el contorno, relleno y sangrado especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Obtiene o establece la enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) en la que se basa este [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| base_inset | float | r/w | Obtiene o establece la distancia entre la tapa y la línea. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Obtiene o establece el objeto que define el relleno para la tapa personalizada. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Obtiene o establece la enumeración [LineJoin](/psd/python-net/aspose.psd/linejoin/) que determina cómo se unen las líneas que componen este objeto [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Obtiene o establece el objeto que define el contorno de la tapa personalizada. |
| width_scale | float | r/w | Obtiene o establece la cantidad por la cual escalar este objeto de clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) con respecto al ancho del  objeto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Inicializa una nueva instancia de la clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) con el contorno y relleno especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el relleno para la tapa personalizada. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el contorno de la tapa personalizada. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Inicializa una nueva instancia de la clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partir de la enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) existente especificada, con el contorno y relleno especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el relleno para la tapa personalizada. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el contorno de la tapa personalizada. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | La tapa de línea a partir de la cual crear la tapa personalizada. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Inicializa una nueva instancia de la clase [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partir de la enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) existente especificada, con el contorno, relleno y sangrado especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el relleno para la tapa personalizada. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objeto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) que define el contorno de la tapa personalizada. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | La tapa de línea a partir de la cual crear la tapa personalizada. |
| base_inset | float | La distancia entre la tapa y la línea. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Obtiene las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | La enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) usada al comienzo de una línea dentro de esta tapa. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | La enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) usada al final de una línea dentro de esta tapa. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Establece las tapas usadas para iniciar y terminar las líneas que forman esta tapa personalizada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | La enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) usada al comienzo de una línea dentro de esta tapa. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | La enumeración [LineCap](/psd/python-net/aspose.psd/linecap/) usada al final de una línea dentro de esta tapa. |


---
title: "Classe GraphicsPath"
type: docs
weight: 1570
url: /it/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene o imposta i limiti dell'oggetto. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | Ottiene le figure del percorso. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | Ottiene o imposta un'enumerazione [FillMode](/psd/python-net/aspose.psd/fillmode/) che determina come vengono riempiti gli interni delle forme in questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | Aggiunge una nuova figura. |
| [add_figures(figures)](#add_figures_figures_2) | Aggiunge nuove figure. |
| [add_path(adding_path)](#add_path_adding_path_3) | Aggiunge alla fine il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato a questo percorso. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | Aggiunge alla fine il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato a questo percorso. |
| [deep_clone()](#deep_clone__5) | Esegue una clonazione profonda di questo percorso grafico. |
| flatten() | Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati. |
| [flatten(matrix)](#flatten_matrix_6) | Applica la trasformazione specificata e poi converte ogni curva in questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in una sequenza di segmenti di linea collegati. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | Converte ogni curva in questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in una sequenza di segmenti di linea collegati. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | Ottiene i limiti dell'oggetto. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [is_visible(point)](#is_visible_point_18) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(point)](#is_visible_point_19) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_22) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y)](#is_visible_x_y_23) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nella regione di ritaglio visibile della [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nella regione di ritaglio visibile della [Graphics](/psd/python-net/aspose.psd/graphics/) specificata. |
| [remove_figure(figure)](#remove_figure_figure_26) | Rimuove una figura. |
| [remove_figures(figures)](#remove_figures_figures_27) | Rimuove figure. |
| reset() | Svuota il percorso grafico e imposta il [FillMode](/psd/python-net/aspose.psd/fillmode/) su [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/). |
| reverse() | Inverte l'ordine di figure, forme e punti in ogni forma di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [transform(transform)](#transform_transform_28) | Applica la trasformazione specificata alla forma. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen)](#widen_pen_33) | Aggiunge un contorno aggiuntivo al percorso. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | Aggiunge un contorno aggiuntivo al [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | Sostituisce questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) con curve che racchiudono l'area riempita quando questo percorso è disegnato dalla penna specificata. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Le figure da cui inizializzare. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Le figure da cui inizializzare. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | La modalità di riempimento. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

Inizializza una nuova istanza della classe [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | La modalità di riempimento. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

Aggiunge una nuova figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | La figura da aggiungere. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

Aggiunge nuove figure.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Le figure da aggiungere. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

Aggiunge alla fine il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato a questo percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da aggiungere. |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

Aggiunge alla fine il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) specificato a questo percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) da aggiungere. |
| connetti | bool | Un valore Booleano che specifica se la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore true specifica che la prima figura nel percorso aggiunto fa parte dell'ultima figura in questo percorso. Un valore false specifica che la prima figura nel percorso aggiunto è separata dall'ultima figura in questo percorso. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Esegue una clonazione profonda di questo percorso grafico.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Una copia profonda del percorso grafico. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

Applica la trasformazione specificata e poi converte ogni curva in questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in una sequenza di segmenti di linea collegati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) con cui trasformare questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) prima di appiattire. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

Converte ogni curva in questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) in una sequenza di segmenti di linea collegati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) con cui trasformare questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) prima di appiattire. |
| piattezza | float | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita. Un valore di 0,25 è quello predefinito. Ridurre il valore di piattezza aumenterà il numero di segmenti lineari nell'approssimazione. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice da applicare prima dei limiti sarà calcolata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti stimati dell'oggetto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice da applicare prima dei limiti sarà calcolata. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La penna da usare per l'oggetto. Questo può influenzare la dimensione dei limiti dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti stimati dell'oggetto. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) così disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che specifica la posizione da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) così disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) così disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) quando viene disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata e utilizzando la [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La [Pen](/psd/python-net/aspose.psd/pen/) da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno (sotto) del contorno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) così disegnato con la [Pen](/psd/python-net/aspose.psd/pen/) specificata; altrimenti, false. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta il punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); altrimenti, false. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta il punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); altrimenti, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta il punto da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta il punto da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo; altrimenti, false. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); altrimenti, false. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); altrimenti, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nella regione di ritaglio visibile della [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); altrimenti, false. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

Indica se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nella regione di ritaglio visibile della [Graphics](/psd/python-net/aspose.psd/graphics/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | Il [Graphics](/psd/python-net/aspose.psd/graphics/) per cui testare la visibilità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto specificato è contenuto all'interno di questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/); altrimenti, false. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

Rimuove una figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | La figura da rimuovere. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

Rimuove figure.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | Le figure da rimuovere. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La trasformazione da applicare. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da <paramref name=\"srcRect\" />. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da <paramref name=\"destPoints\" />. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da <paramref name=\"srcRect\" />. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) che specifica una trasformazione geometrica da applicare al percorso. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da <paramref name=\"srcRect\" />. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) che specifica una trasformazione geometrica da applicare al percorso. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Una enumerazione [WarpMode](/psd/python-net/aspose.psd/warpmode/) che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

Applica una trasformazione di deformazione, definita da un rettangolo e un parallelogramma, a questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che definiscono un parallelogramma a cui viene trasformato il rettangolo definito da <paramref name=\"srcRect\" />. L'array può contenere tre o quattro elementi. Se l'array contiene tre elementi, l'angolo in basso a destra del parallelogramma è implicito nei primi tre punti. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo trasformato nel parallelogramma definito da <paramref name=\"destPoints\" />. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) che specifica una trasformazione geometrica da applicare al percorso. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | Una enumerazione [WarpMode](/psd/python-net/aspose.psd/warpmode/) che specifica se questa operazione di deformazione utilizza la modalità prospettiva o bilineare. |
| flatness | float | Un valore da 0 a 1 che specifica quanto è piatto il percorso risultante. Per ulteriori informazioni, vedere i metodi [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/). |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

Aggiunge un contorno aggiuntivo al percorso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Una [Pen](/psd/python-net/aspose.psd/pen/) che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

Aggiunge un contorno aggiuntivo al [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Una [Pen](/psd/python-net/aspose.psd/pen/) che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) che specifica una trasformazione da applicare al percorso prima di allargare. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

Sostituisce questo [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) con curve che racchiudono l'area riempita quando questo percorso è disegnato dalla penna specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Una [Pen](/psd/python-net/aspose.psd/pen/) che specifica la larghezza tra il contorno originale del percorso e il nuovo contorno creato da questo metodo. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Una [Matrix](/psd/python-net/aspose.psd/matrix/) che specifica una trasformazione da applicare al percorso prima di allargare. |
| piattezza | float | Un valore che specifica la piattezza per le curve. |


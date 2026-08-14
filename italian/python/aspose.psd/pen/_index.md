---
title: "Classe Pen"
type: docs
weight: 3360
url: /it/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con il [Pen.brush](/psd/python-net/aspose.psd/pen/) specificato. |
| [Pen(brush, width)](#Pen_brush_width_2) | Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con il [Pen.brush](/psd/python-net/aspose.psd/pen/) e il [Pen.width](/psd/python-net/aspose.psd/pen/) specificati. |
| [Pen(color)](#Pen_color_3) | Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con il colore specificato. |
| [Pen(color, width)](#Pen_color_width_4) | Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con le proprietà [Pen.color](/psd/python-net/aspose.psd/pen/) e [Pen.width](/psd/python-net/aspose.psd/pen/) specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | Ottiene o imposta l'allineamento per questo [Pen](/psd/python-net/aspose.psd/pen/). |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | Ottiene o imposta il [Pen.brush](/psd/python-net/aspose.psd/pen/) che determina gli attributi di questo [Pen](/psd/python-net/aspose.psd/pen/). |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore di questo [Pen](/psd/python-net/aspose.psd/pen/). |
| compound_array | float | r/w | Ottiene o imposta un array di valori che specifica una penna composta. Una penna composta disegna una linea composta formata da linee parallele e spazi. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Ottiene o imposta un cap personalizzato da utilizzare alla fine delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | Ottiene o imposta un cap personalizzato da utilizzare all'inizio delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | Ottiene o imposta lo stile del cap usato alla fine dei trattini che compongono le linee tratteggiate disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_offset | float | r/w | Ottiene o imposta la distanza dall'inizio di una linea all'inizio di un modello di trattini. |
| dash_pattern | float | r/w | Ottiene o imposta un array di trattini e spazi personalizzati. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | Ottiene o imposta lo stile usato per le linee tratteggiate disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Ottiene o imposta lo stile del cap usato alla fine delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Ottiene o imposta lo stile di unione per le estremità di due linee consecutive disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| miter_limit | float | r/w | Ottiene o imposta il limite dello spessore dell'unione in un angolo a spigolo. |
| opacity | float | r/w | Ottiene o imposta l'opacità dell'oggetto. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che l'oggetto è completamente visibile, un valore di 1 indica che l'oggetto è completamente opaco. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | Ottiene lo stile delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Ottiene o imposta lo stile del cap usato all'inizio delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Ottiene o imposta una copia della trasformazione geometrica per questo [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | r/w | Ottiene o imposta la larghezza di questo [Pen](/psd/python-net/aspose.psd/pen/), in unità dell'oggetto Graphics utilizzato per il disegno. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | Moltiplica la matrice di trasformazione per questo [Pen](/psd/python-net/aspose.psd/pen/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | Moltiplica la matrice di trasformazione per questo [Pen](/psd/python-net/aspose.psd/pen/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata nell'ordine specificato. |
| reset_transform() | Reimposta la matrice di trasformazione geometrica per questo [Pen](/psd/python-net/aspose.psd/pen/) all'identità. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | Imposta i valori che determinano lo stile di cappuccio usato per terminare le linee disegnate da questo [Pen](/psd/python-net/aspose.psd/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con il [Pen.brush](/psd/python-net/aspose.psd/pen/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Pen.brush](/psd/python-net/aspose.psd/pen/) che determina le proprietà di riempimento di questo [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con il [Pen.brush](/psd/python-net/aspose.psd/pen/) e il [Pen.width](/psd/python-net/aspose.psd/pen/) specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | Un [Pen.brush](/psd/python-net/aspose.psd/pen/) che determina le caratteristiche di questo [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | La larghezza del nuovo [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con il colore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Pen.color](/psd/python-net/aspose.psd/pen/) che indica il colore di questo [Pen](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Inizializza una nuova istanza della classe [Pen](/psd/python-net/aspose.psd/pen/) con le proprietà [Pen.color](/psd/python-net/aspose.psd/pen/) e [Pen.width](/psd/python-net/aspose.psd/pen/) specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Pen.color](/psd/python-net/aspose.psd/pen/) che indica il colore di questo [Pen](/psd/python-net/aspose.psd/pen/). |
| width | float | Un valore che indica la larghezza di questo [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

Moltiplica la matrice di trasformazione per questo [Pen](/psd/python-net/aspose.psd/pen/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | L'oggetto [Matrix](/psd/python-net/aspose.psd/matrix/) con cui moltiplicare la matrice di trasformazione. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

Moltiplica la matrice di trasformazione per questo [Pen](/psd/python-net/aspose.psd/pen/) per la [Matrix](/psd/python-net/aspose.psd/matrix/) specificata nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Il [Matrix](/psd/python-net/aspose.psd/matrix/) con cui moltiplicare la matrice di trasformazione. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine in cui eseguire l'operazione di moltiplicazione. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale dell'angolo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica se aggiungere o anteporre la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale dei fattori specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | Il fattore con cui scalare la trasformazione nella direzione dell'asse y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica se aggiungere o anteporre la matrice di scala. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Imposta i valori che determinano lo stile di cappuccio usato per terminare le linee disegnate da questo [Pen](/psd/python-net/aspose.psd/pen/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) che rappresenta lo stile di cappuccio da usare all'inizio delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) che rappresenta lo stile di cappuccio da usare alla fine delle linee disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | Un [LineCap](/psd/python-net/aspose.psd/linecap/) che rappresenta lo stile di cappuccio da usare all'inizio o alla fine delle linee tratteggiate disegnate con questo [Pen](/psd/python-net/aspose.psd/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traduzione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traduzione in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | L'ordine (anteporre o aggiungere) con cui applicare la traduzione. |


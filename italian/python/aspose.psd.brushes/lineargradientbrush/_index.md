---
title: "Classe LinearGradientBrush"
type: docs
weight: 20
url: /it/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con parametri predefiniti.<br/>Il colore iniziale è nero, il colore finale è bianco, l'angolo è di 45 gradi e il rettangolo è posizionato in (0,0) con dimensioni (1,1). |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con i punti e i colori specificati. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con i punti e i colori specificati. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angolo | float | r/w | Ottiene o imposta l'angolo del gradiente. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Ottiene o imposta un [Blend](/psd/python-net/aspose.psd/blend/) che specifica le posizioni e i fattori che definiscono un decadimento personalizzato per il gradiente. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore finale del gradiente. |
| gamma_correction | bool | r/w | Ottiene o imposta un valore che indica se la correzione gamma è abilitata per questo [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Ottiene o imposta un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) che definisce un gradiente lineare multicolore. |
| is_angle_scalable | bool | r/w | Ottiene o imposta un valore che indica se [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) è modificato durante le trasformazioni con questo [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/). |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta i colori iniziale e finale del gradiente. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | Ottiene o imposta una regione rettangolare che definisce i punti di inizio e fine del gradiente. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore iniziale del gradiente. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Ottiene o imposta una copia del [Matrix](/psd/python-net/aspose.psd/matrix/) che definisce una trasformazione geometrica locale per questo [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Ottiene o imposta un'enumerazione [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che indica la modalità di avvolgimento per questo [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea un nuovo clone profondo del corrente [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Moltiplica il [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) per il [Matrix] specificato, anteponendo il [Matrix] specificato. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Moltiplica il [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) per il [Matrix] specificato nell'ordine specificato. |
| reset_transform() | Ripristina la proprietà [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) a identità. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Ruota la trasformazione geometrica locale dell'importo specificato. Questo metodo antepone la rotazione alla trasformazione. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Scala la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di scala alla trasformazione. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato. |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Crea un decadimento del gradiente basato su una curva a campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Crea un decadimento del gradiente basato su una curva a campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con parametri predefiniti.<br/>Il colore iniziale è nero, il colore finale è bianco, l'angolo è di 45 gradi e il rettangolo è posizionato in (0,0) con dimensioni (1,1).

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con i punti e i colori specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Una struttura [Point](/psd/python-net/aspose.psd/point/) che rappresenta il punto iniziale del gradiente lineare. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Una struttura [Point](/psd/python-net/aspose.psd/point/) che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore finale del gradiente lineare. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) con i punti e i colori specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Una struttura [Point](/psd/python-net/aspose.psd/point/) che rappresenta il punto iniziale del gradiente lineare. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Una struttura [Point](/psd/python-net/aspose.psd/point/) che rappresenta il punto finale del gradiente lineare. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore iniziale del gradiente lineare. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore finale del gradiente lineare. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore finale per la sfumatura. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore finale per la sfumatura. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore finale per la sfumatura. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| is_angle_scalable | bool | se impostato su <c>true</c> l'angolo viene modificato durante le trasformazioni con questo [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

Inizializza una nuova istanza della classe [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) basata su un rettangolo, colori iniziale e finale, e un angolo di orientamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che specifica i limiti del gradiente lineare. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore iniziale per il gradiente. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | Una struttura [Color](/psd/python-net/aspose.psd/color/) che rappresenta il colore finale per la sfumatura. |
| angolo | float | L'angolo, misurato in gradi in senso orario dall'asse x, della linea di orientamento del gradiente. |
| is_angle_scalable | bool | se impostato su <c>true</c> l'angolo viene modificato durante le trasformazioni con questo [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/). |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea un nuovo clone profondo del corrente [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Un nuovo [Brush](/psd/python-net/aspose.psd/brush/) che è la copia profonda di questa istanza [Brush](/psd/python-net/aspose.psd/brush/). |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Moltiplica il [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) per il [Matrix] specificato, anteponendo il [Matrix] specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) con cui moltiplicare la trasformazione geometrica. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Moltiplica il [Matrix](/psd/python-net/aspose.psd/matrix/) che rappresenta la trasformazione geometrica locale di questo [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) per il [Matrix] specificato nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La [Matrix](/psd/python-net/aspose.psd/matrix/) con cui moltiplicare la trasformazione geometrica. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica in quale ordine moltiplicare le due matrici. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Ruota la trasformazione geometrica locale dell'importo specificato. Questo metodo antepone la rotazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Ruota la trasformazione geometrica locale dell'importo specificato nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angolo | float | L'angolo di rotazione. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica se aggiungere o anteporre la matrice di rotazione. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Scala la trasformazione geometrica locale degli importi specificati. Questo metodo antepone la matrice di scala alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | La quantità con cui scalare la trasformazione nella direzione dell'asse y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Scala la trasformazione geometrica locale degli importi specificati nell'ordine specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sx | float | La quantità con cui scalare la trasformazione nella direzione dell'asse x. |
| sy | float | La quantità con cui scalare la trasformazione nella direzione dell'asse y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Un [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) che specifica se aggiungere o anteporre la matrice di scala. |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica il centro della sfumatura (il punto in cui la sfumatura è composta solo dal colore finale). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea un gradiente lineare con un colore centrale e un decadimento lineare verso un unico colore su entrambe le estremità.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica il centro della sfumatura (il punto in cui la sfumatura è composta solo dal colore finale). |
| scale | float | Un valore da 0 a 1 che specifica la rapidità con cui i colori sfumano dal colore iniziale a <paramref name="focus" /> (colore finale) |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Crea un decadimento del gradiente basato su una curva a campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica il centro della sfumatura (il punto in cui il colore iniziale e il colore finale sono mescolati in modo uguale). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea un decadimento del gradiente basato su una curva a campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica il centro della sfumatura (il punto in cui la sfumatura è composta solo dal colore finale). |
| scale | float | Un valore da 0 a 1 che specifica la rapidità con cui i colori sfumano dal <paramref name="focus" />. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | float | Il valore della traslazione in x. |
| dy | float | Il valore della traduzione in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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


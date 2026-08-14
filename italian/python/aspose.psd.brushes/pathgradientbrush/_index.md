---
title: "Classe PathGradientBrush"
type: docs
weight: 50
url: /it/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con il percorso specificato. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | Ottiene o imposta un [Blend](/psd/python-net/aspose.psd/blend/) che specifica le posizioni e i fattori che definiscono un decadimento personalizzato per il gradiente. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore al centro della sfumatura del percorso. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta il punto centrale del gradiente del percorso. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta il punto focale per la diminuzione del gradiente. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Ottiene il percorso grafico su cui è stato costruito questo pennello. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Ottiene o imposta un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) che definisce un gradiente lineare multicolore. |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta un array di colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) riempie. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | Crea una sfumatura con un colore centrale e una caduta lineare verso un colore circostante. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | Crea una sfumatura con un colore centrale e una caduta lineare verso ciascun colore circostante. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | Crea un pennello sfumatura che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | Crea un pennello sfumatura che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con il percorso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce l'area riempita da questo [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/). |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come i riempimenti disegnati con questo [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) vengono affiancati. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

Inizializza una nuova istanza della classe [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) con i punti specificati e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come i riempimenti disegnati con questo [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) vengono affiancati. |

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

Crea una sfumatura con un colore centrale e una caduta lineare verso un colore circostante.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

Crea una sfumatura con un colore centrale e una caduta lineare verso ciascun colore circostante.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |
| scale | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore di confine. Un valore di 1 produce l'intensità più alta possibile del colore centrale, ed è il valore predefinito. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

Crea un pennello sfumatura che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

Crea un pennello sfumatura che cambia colore partendo dal centro del percorso verso l'esterno fino al confine del percorso. La transizione da un colore all'altro è basata su una curva a forma di campana.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| focus | float | Un valore da 0 a 1 che specifica dove, lungo qualsiasi radiale dal centro del percorso al confine del percorso, il colore centrale avrà la massima intensità. Un valore di 1 (predefinito) posiziona la massima intensità al centro del percorso. |
| scale | float | Un valore da 0 a 1 che specifica l'intensità massima del colore centrale che viene mescolato con il colore di confine. Un valore di 1 produce l'intensità più alta possibile del colore centrale, ed è il valore predefinito. |

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


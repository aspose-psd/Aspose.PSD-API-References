---
title: "Classe PathMulticolorGradientBrush"
type: docs
weight: 70
url: /it/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con il percorso specificato. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati e la modalità di avvolgimento. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati e la modalità di avvolgimento. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta il punto centrale del gradiente del percorso. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta il punto focale per la diminuzione del gradiente. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Ottiene il percorso grafico su cui è stato costruito questo pennello. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | Ottiene o imposta un [ColorBlend](/psd/python-net/aspose.psd/colorblend/) che definisce un gradiente lineare multicolore. |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Ottiene i punti del percorso su cui è stato costruito questo pennello. |
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
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Trasla la trasformazione geometrica locale delle dimensioni specificate. Questo metodo antepone la traslazione alla trasformazione. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con il percorso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Il [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce l'area riempita da questo [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Una [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come i riempimenti disegnati con questo [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) vengono affiancati. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Inizializza una nuova istanza della classe [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) con i punti specificati e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | Un array di strutture [PointF](/psd/python-net/aspose.psd/pointf/) che rappresentano i punti che costituiscono i vertici del percorso. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Una [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come i riempimenti disegnati con questo [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) vengono affiancati. |

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


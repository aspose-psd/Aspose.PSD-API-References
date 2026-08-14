---
title: "Classe TextureBrush"
type: docs
weight: 90
url: /it/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata e la modalità di avvolgimento. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Ottiene l'oggetto [Image](/psd/python-net/aspose.psd/image/) associato a questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Ottiene le [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) associate a questo [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene il [Rectangle](/psd/python-net/aspose.psd/rectangle/) associato a questo [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | Restituisce un valore che indica se le trasformazioni sono state modificate in qualche modo. Ad esempio impostando la matrice di trasformazione o<br/>            chiamando uno dei metodi che alterano la matrice di trasformazione. La proprietà è introdotta per compatibilità retroattiva con GDI+. |
| opacity | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
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


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Un oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, il rettangolo di delimitazione e gli attributi dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Un oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) che contiene informazioni aggiuntive sull'immagine utilizzata da questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata e la modalità di avvolgimento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Una enumerazione [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) è piastrellato. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Una enumerazione [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) è piastrellato. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Inizializza una nuova istanza della classe [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) che utilizza l'immagine specificata, la modalità di avvolgimento e il rettangolo di delimitazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'oggetto [Image](/psd/python-net/aspose.psd/image/) con cui questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) riempie gli interni. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Una enumerazione [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) è piastrellato. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta il rettangolo di delimitazione per questo oggetto [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |

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


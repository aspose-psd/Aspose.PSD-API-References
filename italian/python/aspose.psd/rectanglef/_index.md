---
title: "Classe RectangleF"
type: docs
weight: 3830
url: /it/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Inizializza una nuova istanza della classe RectangleF |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Inizializza una nuova istanza della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la posizione e le dimensioni specificate. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Inizializza una nuova istanza della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la posizione e le dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Ottiene o imposta la coordinata y che è la somma di [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) e [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene una nuova istanza della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che ha i valori [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) e [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) impostati a zero. |
| height | float | r/w | Ottiene o imposta l'altezza di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| is_empty | bool | r | Ottiene un valore che indica se la proprietà [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) o [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) di questa [RectangleF](/psd/python-net/aspose.psd/rectanglef/) ha valore zero. |
| left | float | r/w | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| right | float | r/w | Ottiene o imposta la coordinata x che è la somma di [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) e [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Ottiene o imposta le dimensioni di questa [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Ottiene o imposta la coordinata y del bordo superiore di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| width | float | r/w | Ottiene o imposta la larghezza di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| x | float | r/w | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | r/w | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(rect)](#contains_rect_2) | Determina se la regione rettangolare rappresentata da <paramref name="rect" /> è interamente contenuta all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [contains(x, y)](#contains_x_y_3) | Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Crea una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Crea un nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/) da due punti specificati. Due vertici del [Rectangle](/psd/python-net/aspose.psd/rectangle/) creato saranno uguali ai parametri <paramref name="point1" /> e <paramref name="point2" />. Questi sono tipicamente i vertici opposti. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Crea e restituisce una copia ingrandita della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato. |
| [inflate(size)](#inflate_size_7) | Ingrandisce questo [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dell'importo specificato. |
| [inflate(x, y)](#inflate_x_y_8) | Ingrandisce questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dell'importo specificato. |
| [intersect(a, b)](#intersect_a_b_9) | Restituisce una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta l'intersezione di due rettangoli. Se non c'è alcuna intersezione, viene restituito un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) vuoto. |
| [intersect(rect)](#intersect_rect_10) | Sostituisce questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con l'intersezione di sé stessa e della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. |
| [intersects_with(rect)](#intersects_with_rect_11) | Determina se questo rettangolo interseca con <paramref name="rect" />. |
| normalize() | Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e alto minore di basso. |
| [offset(pos)](#offset_pos_12) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(x, y)](#offset_x_y_13) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [union(a, b)](#union_a_b_14) | Crea il terzo rettangolo più piccolo possibile che possa contenere entrambi i due rettangoli che formano un'unione. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Inizializza una nuova istanza della classe RectangleF

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Inizializza una nuova istanza della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la posizione e le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Un [PointF](/psd/python-net/aspose.psd/pointf/) che rappresenta l'angolo superiore sinistro della regione rettangolare. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Un [SizeF](/psd/python-net/aspose.psd/sizef/) che rappresenta la larghezza e l'altezza della regione rettangolare. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Inizializza una nuova istanza della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con la posizione e le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | float | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | float | La larghezza del rettangolo. |
| altezza | float | L'altezza del rettangolo. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il [PointF](/psd/python-net/aspose.psd/pointf/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto rappresentato dal parametro <paramref name="point" /> è contenuto all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/); altrimenti false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Determina se la regione rettangolare rappresentata da <paramref name="rect" /> è interamente contenuta all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se la regione rettangolare rappresentata da <paramref name="rect" /> è interamente contenuta nella regione rettangolare rappresentata da questo [RectangleF](/psd/python-net/aspose.psd/rectanglef/); altrimenti false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La coordinata x del punto da testare. |
| y | float | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto definito da <paramref name="x" /> e <paramref name="y" /> è contenuto all'interno di questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/); altrimenti false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con l'angolo superiore sinistro e l'angolo inferiore destro nelle posizioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sinistra | float | La coordinata x dell'angolo superiore sinistro della regione rettangolare. |
| superiore | float | La coordinata y dell'angolo superiore sinistro della regione rettangolare. |
| destra | float | La coordinata x dell'angolo inferiore destro della regione rettangolare. |
| bottom | float | La coordinata y dell'angolo inferiore destro della regione rettangolare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il nuovo [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che questo metodo crea. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Crea un nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/) da due punti specificati. Due vertici del [Rectangle](/psd/python-net/aspose.psd/rectangle/) creato saranno uguali ai parametri <paramref name="point1" /> e <paramref name="point2" />. Questi sono tipicamente i vertici opposti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Il primo [Point](/psd/python-net/aspose.psd/point/) per il nuovo rettangolo. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Il secondo [Point](/psd/python-net/aspose.psd/point/) per il nuovo rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) appena creato. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Crea e restituisce una copia ingrandita della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata. La copia è ingrandita dell'importo specificato. Il rettangolo originale rimane invariato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da copiare. Questo rettangolo non viene modificato. |
| x | float | La quantità con cui gonfiare orizzontalmente la copia del rettangolo. |
| y | float | La quantità con cui gonfiare verticalmente la copia del rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) gonfiato. |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Ingrandisce questo [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La quantità con cui gonfiare questo rettangolo. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Ingrandisce questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La quantità con cui gonfiare orizzontalmente questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| y | float | La quantità con cui gonfiare verticalmente questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Restituisce una struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che rappresenta l'intersezione di due rettangoli. Se non c'è alcuna intersezione, viene restituito un [RectangleF](/psd/python-net/aspose.psd/rectanglef/) vuoto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un primo rettangolo da intersecare. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un secondo rettangolo da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una terza struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) le cui dimensioni rappresentano l'area sovrapposta dei due rettangoli specificati. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Sostituisce questa struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) con l'intersezione di sé stessa e della struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo da intersecare. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Determina se questo rettangolo interseca con <paramref name="rect" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se esiste qualche intersezione. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | La quantità di spostamento della posizione. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | float | La quantità di spostamento della posizione orizzontalmente. |
| y | float | La quantità di spostamento della posizione verticalmente. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Crea il terzo rettangolo più piccolo possibile che possa contenere entrambi i due rettangoli che formano un'unione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un primo rettangolo da unire. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Un secondo rettangolo da unire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Una terza struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) che contiene entrambi i rettangoli che formano l'unione. |



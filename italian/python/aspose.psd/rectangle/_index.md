---
title: "Classe Rectangle"
type: docs
weight: 3810
url: /it/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Inizializza una nuova istanza della classe Rectangle |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Inizializza una nuova istanza della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la posizione e le dimensioni specificate. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Inizializza una nuova istanza della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la posizione e le dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Ottiene o imposta la coordinata y che è la somma dei valori delle proprietà [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) e [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Ottiene una nuova istanza della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che ha i valori [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) e [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) impostati a zero. |
| height | int | r/w | Ottiene o imposta l'altezza di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| is_empty | bool | r | Ottiene un valore che indica se tutte le proprietà numeriche di questa [Rectangle](/psd/python-net/aspose.psd/rectangle/) hanno valore zero. |
| left | int | r/w | Ottiene o imposta la coordinata x del bordo sinistro di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Ottiene o imposta le coordinate dell'angolo in alto a sinistra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | r/w | Ottiene o imposta la coordinata x che è la somma dei valori delle proprietà [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) e [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Ottiene o imposta le dimensioni di questa [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Ottiene o imposta la coordinata y del bordo superiore di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| width | int | r/w | Ottiene o imposta la larghezza di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| x | int | r/w | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | r/w | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Converte la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata in una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) arrotondando i valori di [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al prossimo intero superiore. |
| [contains(point)](#contains_point_2) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(rect)](#contains_rect_3) | Determina se la regione rettangolare rappresentata da <paramref name=\"rect\" /> è interamente contenuta all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [contains(x, y)](#contains_x_y_4) | Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Crea una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con le posizioni dei bordi specificate. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Crea un nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/) da due punti specificati. I due verticali del [Rectangle](/psd/python-net/aspose.psd/rectangle/) creato saranno uguali ai parametri <paramref name=\"point1\" /> e <paramref name=\"point2\" />. Questi saranno tipicamente i vertici opposti. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Crea e restituisce una copia ingrandita della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) specificata. La copia è ingrandita dell'importo specificato. La struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) originale rimane non modificata. |
| [inflate(size)](#inflate_size_8) | Ingrandisce questo [Rectangle](/psd/python-net/aspose.psd/rectangle/) dell'importo specificato. |
| [inflate(width, height)](#inflate_width_height_9) | Ingrandisce questo [Rectangle](/psd/python-net/aspose.psd/rectangle/) dell'importo specificato. |
| [intersect(a, b)](#intersect_a_b_10) | Restituisce una terza struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta l'intersezione di due altre strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/). Se non c'è alcuna intersezione, viene restituito un [Rectangle](/psd/python-net/aspose.psd/rectangle/) vuoto. |
| [intersect(rect)](#intersect_rect_11) | Sostituisce questo [Rectangle](/psd/python-net/aspose.psd/rectangle/) con l'intersezione di sé stesso e del [Rectangle](/psd/python-net/aspose.psd/rectangle/) specificato. |
| [intersects_with(rect)](#intersects_with_rect_12) | Determina se questo rettangolo interseca con <paramref name="rect" />. |
| normalize() | Normalizza il rettangolo rendendo la sua larghezza e altezza positive, sinistra minore di destra e alto minore di basso. |
| [offset(pos)](#offset_pos_13) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [offset(x, y)](#offset_x_y_14) | Regola la posizione di questo rettangolo dell'importo specificato. |
| [round(value)](#round_value_15) | Converte il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato in un [Rectangle](/psd/python-net/aspose.psd/rectangle/) arrotondando i valori del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al numero intero più vicino. |
| [truncate(value)](#truncate_value_16) | Converte il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato in un [Rectangle](/psd/python-net/aspose.psd/rectangle/) troncando i valori del [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [union(a, b)](#union_a_b_17) | Ottiene una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che contiene l'unione di due strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Inizializza una nuova istanza della classe Rectangle

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Inizializza una nuova istanza della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la posizione e le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Un [Point](/psd/python-net/aspose.psd/point/) che rappresenta l'angolo in alto a sinistra della regione rettangolare. |
| size | [Size](/psd/python-net/aspose.psd/size) | Una [Size](/psd/python-net/aspose.psd/size/) che rappresenta la larghezza e l'altezza della regione rettangolare. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Inizializza una nuova istanza della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con la posizione e le dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x dell'angolo superiore sinistro del rettangolo. |
| y | int | La coordinata y dell'angolo superiore sinistro del rettangolo. |
| width | int | La larghezza del rettangolo. |
| altezza | int | L'altezza del rettangolo. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Converte la struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificata in una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) arrotondando i valori di [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al prossimo intero superiore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | La struttura [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Restituisce un [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto rappresentato da <paramref name=\"point\" /> è contenuto all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/); altrimenti false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Determina se la regione rettangolare rappresentata da <paramref name=\"rect\" /> è interamente contenuta all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il [Rectangle](/psd/python-net/aspose.psd/rectangle/) da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se la regione rettangolare rappresentata da <paramref name=\"rect\" /> è interamente contenuta all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/); altrimenti false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determina se il punto specificato è contenuto all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La coordinata x del punto da testare. |
| y | int | La coordinata y del punto da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se il punto definito da <paramref name=\"x\" /> e <paramref name=\"y\" /> è contenuto all'interno di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/); altrimenti false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Crea una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) con le posizioni dei bordi specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left | int | La coordinata x dell'angolo in alto a sinistra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | La coordinata y dell'angolo in alto a sinistra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| right | int | La coordinata x dell'angolo in basso a destra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| bottom | int | La coordinata y dell'angolo in basso a destra di questa struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/) che questo metodo crea. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Crea un nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/) da due punti specificati. I due verticali del [Rectangle](/psd/python-net/aspose.psd/rectangle/) creato saranno uguali ai parametri <paramref name=\"point1\" /> e <paramref name=\"point2\" />. Questi saranno tipicamente i vertici opposti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Il primo [Point](/psd/python-net/aspose.psd/point/) per il nuovo rettangolo. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Il secondo [Point](/psd/python-net/aspose.psd/point/) per il nuovo rettangolo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) appena creato. |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Crea e restituisce una copia ingrandita della struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) specificata. La copia è ingrandita dell'importo specificato. La struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) originale rimane non modificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il [Rectangle](/psd/python-net/aspose.psd/rectangle/) con cui iniziare. Questo rettangolo non viene modificato. |
| x | int | L'importo con cui ingrandire orizzontalmente questo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| y | int | L'importo con cui ingrandire verticalmente questo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il [Rectangle](/psd/python-net/aspose.psd/rectangle/) ingrandito. |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Ingrandisce questo [Rectangle](/psd/python-net/aspose.psd/rectangle/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | La quantità con cui gonfiare questo rettangolo. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Ingrandisce questo [Rectangle](/psd/python-net/aspose.psd/rectangle/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | L'importo con cui ingrandire orizzontalmente questo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| height | int | L'importo con cui ingrandire verticalmente questo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Restituisce una terza struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta l'intersezione di due altre strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/). Se non c'è alcuna intersezione, viene restituito un [Rectangle](/psd/python-net/aspose.psd/rectangle/) vuoto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un primo rettangolo da intersecare. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un secondo rettangolo da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un [Rectangle](/psd/python-net/aspose.psd/rectangle/) che rappresenta l'intersezione di <paramref name=\"a\" /> e <paramref name=\"b\" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Sostituisce questo [Rectangle](/psd/python-net/aspose.psd/rectangle/) con l'intersezione di sé stesso e del [Rectangle](/psd/python-net/aspose.psd/rectangle/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il [Rectangle](/psd/python-net/aspose.psd/rectangle/) con cui intersecare. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Determina se questo rettangolo interseca con <paramref name="rect" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Il rettangolo da testare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Questo metodo restituisce true se esiste un'intersezione, altrimenti false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Quantità per spostare la posizione. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Regola la posizione di questo rettangolo dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | Lo spostamento orizzontale. |
| y | int | Lo spostamento verticale. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Converte il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato in un [Rectangle](/psd/python-net/aspose.psd/rectangle/) arrotondando i valori del [RectangleF](/psd/python-net/aspose.psd/rectanglef/) al numero intero più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Converte il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) specificato in un [Rectangle](/psd/python-net/aspose.psd/rectangle/) troncando i valori del [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il [RectangleF](/psd/python-net/aspose.psd/rectanglef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un nuovo [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Ottiene una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che contiene l'unione di due strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un primo rettangolo da unire. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Un secondo rettangolo da unire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Una struttura [Rectangle](/psd/python-net/aspose.psd/rectangle/) che delimita l'unione delle due strutture [Rectangle](/psd/python-net/aspose.psd/rectangle/). |



---
title: "Classe Point"
type: docs
weight: 3530
url: /it/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Inizializza una nuova istanza della classe Point |
| [Point(dw)](#Point_dw_2) | Inizializza una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) usando coordinate specificate da un valore intero. |
| [Point(size)](#Point_size_3) | Inizializza una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) dalla struttura [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | Inizializza una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) con le coordinate specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Ottiene una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) con i valori [Point.x](/psd/python-net/aspose.psd/point/) e [Point.y](/psd/python-net/aspose.psd/point/) impostati a zero. |
| is_empty | bool | r | Ottiene un valore che indica se questo [Point](/psd/python-net/aspose.psd/point/) è vuoto. |
| x | int | r/w | Ottiene o imposta la coordinata x di questo [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Ottiene o imposta la coordinata y di questo [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Aggiunge il [Size](/psd/python-net/aspose.psd/size/) specificato al [Point](/psd/python-net/aspose.psd/point/) specificato. |
| [ceiling(point)](#ceiling_point_2) | Converte il [PointF](/psd/python-net/aspose.psd/pointf/) specificato in un [Point](/psd/python-net/aspose.psd/point/) arrotondando i valori del [PointF](/psd/python-net/aspose.psd/pointf/) al prossimo intero più alto. |
| [offset(dx, dy)](#offset_dx_dy_3) | Trasla questo [Point](/psd/python-net/aspose.psd/point/) dell'importo specificato. |
| [offset(point)](#offset_point_4) | Trasla questo [Point](/psd/python-net/aspose.psd/point/) del [Point](/psd/python-net/aspose.psd/point/) specificato. |
| [round(point)](#round_point_5) | Converte il [PointF](/psd/python-net/aspose.psd/pointf/) specificato in un oggetto [Point](/psd/python-net/aspose.psd/point/) arrotondando i valori del [Point](/psd/python-net/aspose.psd/point/) all'intero più vicino. |
| [subtract(point, size)](#subtract_point_size_6) | Restituisce il risultato della sottrazione del [Size](/psd/python-net/aspose.psd/size/) specificato dal [Point](/psd/python-net/aspose.psd/point/) specificato. |
| [truncate(point)](#truncate_point_7) | Converte il [PointF](/psd/python-net/aspose.psd/pointf/) specificato in un [Point](/psd/python-net/aspose.psd/point/) troncando i valori del [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Inizializza una nuova istanza della classe Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Inizializza una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) usando coordinate specificate da un valore intero.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dw | int | Un intero a 32 bit che specifica le coordinate per il nuovo punto. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Inizializza una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) dalla struttura [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Contiene le coordinate del nuovo punto. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Inizializza una nuova istanza della struttura [Point](/psd/python-net/aspose.psd/point/) con le coordinate specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La posizione orizzontale del punto. |
| y | int | La posizione verticale del punto. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Aggiunge il [Size](/psd/python-net/aspose.psd/size/) specificato al [Point](/psd/python-net/aspose.psd/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) a cui aggiungere. |
| size | [Size](/psd/python-net/aspose.psd/size) | Il [Size](/psd/python-net/aspose.psd/size/) da aggiungere al <paramref name="point" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) che è il risultato dell'operazione di aggiunta. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Converte il [PointF](/psd/python-net/aspose.psd/pointf/) specificato in un [Point](/psd/python-net/aspose.psd/point/) arrotondando i valori del [PointF](/psd/python-net/aspose.psd/pointf/) al prossimo intero più alto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il [PointF](/psd/python-net/aspose.psd/pointf/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) in cui questo metodo converte. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Trasla questo [Point](/psd/python-net/aspose.psd/point/) dell'importo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dx | int | L'importo per spostare la coordinata x. |
| dy | int | L'importo per spostare la coordinata y. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Trasla questo [Point](/psd/python-net/aspose.psd/point/) del [Point](/psd/python-net/aspose.psd/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) usato per spostare questo [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Converte il [PointF](/psd/python-net/aspose.psd/pointf/) specificato in un oggetto [Point](/psd/python-net/aspose.psd/point/) arrotondando i valori del [Point](/psd/python-net/aspose.psd/point/) all'intero più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il [PointF](/psd/python-net/aspose.psd/pointf/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) in cui questo metodo converte. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Restituisce il risultato della sottrazione del [Size](/psd/python-net/aspose.psd/size/) specificato dal [Point](/psd/python-net/aspose.psd/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) da cui sottrarre. |
| size | [Size](/psd/python-net/aspose.psd/size) | Il [Size](/psd/python-net/aspose.psd/size/) da sottrarre dal <paramref name="point" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) che è il risultato dell'operazione di sottrazione. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Converte il [PointF](/psd/python-net/aspose.psd/pointf/) specificato in un [Point](/psd/python-net/aspose.psd/point/) troncando i valori del [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il [PointF](/psd/python-net/aspose.psd/pointf/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) in cui questo metodo converte. |



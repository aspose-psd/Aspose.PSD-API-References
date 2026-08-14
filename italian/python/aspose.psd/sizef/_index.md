---
title: "Classe SizeF"
type: docs
weight: 4090
url: /it/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Inizializza una nuova istanza della classe SizeF |
| [SizeF(point)](#SizeF_point_2) | Inizializza una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dal [PointF](/psd/python-net/aspose.psd/pointf/) specificato. |
| [SizeF(size)](#SizeF_size_3) | Inizializza una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dal [SizeF](/psd/python-net/aspose.psd/sizef/) specificato. |
| [SizeF(width, height)](#SizeF_width_height_4) | Inizializza una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dalle dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Ottiene una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) con i valori [SizeF.width](/psd/python-net/aspose.psd/sizef/) e [SizeF.height](/psd/python-net/aspose.psd/sizef/) impostati a zero. |
| height | float | r/w | Ottiene o imposta il componente verticale di questo [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Ottiene un valore che indica se questo [SizeF](/psd/python-net/aspose.psd/sizef/) ha larghezza e altezza pari a zero. |
| width | float | r/w | Ottiene o imposta il componente orizzontale di questo [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Aggiunge la larghezza e l'altezza di una struttura [SizeF](/psd/python-net/aspose.psd/sizef/) alla larghezza e all'altezza di un'altra struttura [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Sottrae la larghezza e l'altezza di una struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dalla larghezza e dall'altezza di un'altra struttura [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [to_point_f()](#to_point_f__3) | Converte un [SizeF](/psd/python-net/aspose.psd/sizef/) in un [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Converte un [SizeF](/psd/python-net/aspose.psd/sizef/) in una struttura [Size](/psd/python-net/aspose.psd/size/) con valori di dimensione troncati. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Inizializza una nuova istanza della classe SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Inizializza una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dal [PointF](/psd/python-net/aspose.psd/pointf/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Il [PointF](/psd/python-net/aspose.psd/pointf/) da cui inizializzare questo [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Inizializza una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dal [SizeF](/psd/python-net/aspose.psd/sizef/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Il [SizeF](/psd/python-net/aspose.psd/sizef/) da cui creare il nuovo [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Inizializza una nuova istanza della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dalle dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | float | Il componente di larghezza del nuovo [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | Il componente di altezza del nuovo [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Aggiunge la larghezza e l'altezza di una struttura [SizeF](/psd/python-net/aspose.psd/sizef/) alla larghezza e all'altezza di un'altra struttura [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Il primo [SizeF](/psd/python-net/aspose.psd/sizef/) da aggiungere. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Il secondo [SizeF](/psd/python-net/aspose.psd/sizef/) da aggiungere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Una struttura [SizeF](/psd/python-net/aspose.psd/sizef/) che è il risultato dell'operazione di addizione. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Sottrae la larghezza e l'altezza di una struttura [SizeF](/psd/python-net/aspose.psd/sizef/) dalla larghezza e dall'altezza di un'altra struttura [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | La struttura [SizeF](/psd/python-net/aspose.psd/sizef/) sul lato sinistro dell'operatore di sottrazione. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | La struttura [SizeF](/psd/python-net/aspose.psd/sizef/) sul lato destro dell'operatore di sottrazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Il [SizeF](/psd/python-net/aspose.psd/sizef/) che è il risultato dell'operazione di sottrazione. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Converte un [SizeF](/psd/python-net/aspose.psd/sizef/) in un [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Restituisce una struttura [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Converte un [SizeF](/psd/python-net/aspose.psd/sizef/) in una struttura [Size](/psd/python-net/aspose.psd/size/) con valori di dimensione troncati.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Restituisce una struttura [Size](/psd/python-net/aspose.psd/size/). |



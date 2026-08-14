---
title: "Classe Size"
type: docs
weight: 4080
url: /it/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | Inizializza una nuova istanza della classe Size |
| [Size(point)](#Size_point_2) | Inizializza una nuova istanza della struttura [Size](/psd/python-net/aspose.psd/size/) a partire dal [Point](/psd/python-net/aspose.psd/point/) specificato. |
| [Size(width, height)](#Size_width_height_3) | Inizializza una nuova istanza della struttura [Size](/psd/python-net/aspose.psd/size/) a partire dalle dimensioni specificate. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Ottiene una nuova istanza della struttura [Size](/psd/python-net/aspose.psd/size/) con i valori [Size.width](/psd/python-net/aspose.psd/size/) e [Size.height](/psd/python-net/aspose.psd/size/) impostati a zero. |
| height | int | r/w | Ottiene o imposta la componente verticale di questo [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Ottiene un valore che indica se questo [Size](/psd/python-net/aspose.psd/size/) ha larghezza e altezza pari a 0. |
| width | int | r/w | Ottiene o imposta la componente orizzontale di questo [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Aggiunge la larghezza e l'altezza di una struttura [Size](/psd/python-net/aspose.psd/size/) alla larghezza e all'altezza di un'altra struttura [Size](/psd/python-net/aspose.psd/size/). |
| [ceiling(size)](#ceiling_size_2) | Converte la struttura [SizeF](/psd/python-net/aspose.psd/sizef/) specificata in una struttura [Size](/psd/python-net/aspose.psd/size/) arrotondando i valori della struttura [Size](/psd/python-net/aspose.psd/size/) al prossimo intero più alto. |
| [round(size)](#round_size_3) | Converte la struttura [SizeF](/psd/python-net/aspose.psd/sizef/) specificata in una struttura [Size](/psd/python-net/aspose.psd/size/) arrotondando i valori della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) ai valori interi più vicini. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Sottrae la larghezza e l'altezza di una struttura [Size](/psd/python-net/aspose.psd/size/) dalla larghezza e dall'altezza di un'altra struttura [Size](/psd/python-net/aspose.psd/size/). |
| [truncate(size)](#truncate_size_5) | Converte la struttura [SizeF](/psd/python-net/aspose.psd/sizef/) specificata in una struttura [Size](/psd/python-net/aspose.psd/size/) troncando i valori della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) al più prossimo intero inferiore. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Inizializza una nuova istanza della classe Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Inizializza una nuova istanza della struttura [Size](/psd/python-net/aspose.psd/size/) a partire dal [Point](/psd/python-net/aspose.psd/point/) specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Il [Point](/psd/python-net/aspose.psd/point/) da cui inizializzare questo [Size](/psd/python-net/aspose.psd/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Inizializza una nuova istanza della struttura [Size](/psd/python-net/aspose.psd/size/) a partire dalle dimensioni specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | Il componente larghezza del nuovo [Size](/psd/python-net/aspose.psd/size/). |
| height | int | Il componente altezza del nuovo [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Aggiunge la larghezza e l'altezza di una struttura [Size](/psd/python-net/aspose.psd/size/) alla larghezza e all'altezza di un'altra struttura [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Il primo [Size](/psd/python-net/aspose.psd/size/) da aggiungere. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Il secondo [Size](/psd/python-net/aspose.psd/size/) da aggiungere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Una struttura [Size](/psd/python-net/aspose.psd/size/) che è il risultato dell'operazione di aggiunta. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Converte la struttura [SizeF](/psd/python-net/aspose.psd/sizef/) specificata in una struttura [Size](/psd/python-net/aspose.psd/size/) arrotondando i valori della struttura [Size](/psd/python-net/aspose.psd/size/) al prossimo intero più alto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La struttura [SizeF](/psd/python-net/aspose.psd/sizef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La struttura [Size](/psd/python-net/aspose.psd/size/) a cui questo metodo converte. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Converte la struttura [SizeF](/psd/python-net/aspose.psd/sizef/) specificata in una struttura [Size](/psd/python-net/aspose.psd/size/) arrotondando i valori della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) ai valori interi più vicini.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La struttura [SizeF](/psd/python-net/aspose.psd/sizef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La struttura [Size](/psd/python-net/aspose.psd/size/) a cui questo metodo converte. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Sottrae la larghezza e l'altezza di una struttura [Size](/psd/python-net/aspose.psd/size/) dalla larghezza e dall'altezza di un'altra struttura [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | La struttura [Size](/psd/python-net/aspose.psd/size/) sul lato sinistro dell'operatore di sottrazione. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | La struttura [Size](/psd/python-net/aspose.psd/size/) sul lato destro dell'operatore di sottrazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Il [Size](/psd/python-net/aspose.psd/size/) che è il risultato dell'operazione di sottrazione. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Converte la struttura [SizeF](/psd/python-net/aspose.psd/sizef/) specificata in una struttura [Size](/psd/python-net/aspose.psd/size/) troncando i valori della struttura [SizeF](/psd/python-net/aspose.psd/sizef/) al più prossimo intero inferiore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | La struttura [SizeF](/psd/python-net/aspose.psd/sizef/) da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | La struttura [Size](/psd/python-net/aspose.psd/size/) a cui questo metodo converte. |



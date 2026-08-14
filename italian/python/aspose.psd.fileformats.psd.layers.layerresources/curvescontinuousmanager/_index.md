---
title: "Classe CurvesContinuousManager"
type: docs
weight: 200
url: /it/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Summary:** Manager for Curves Adjustment Layer that manipulates curves

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvesContinuousManager

**Inheritance:** CurvesManager

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvesContinuousManager(max_channel_count)](#CurvesContinuousManager_max_channel_count_1) | Inizializza una nuova istanza della classe [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_channel_count | int | r | Restituisce il conteggio massimo dei canali. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_curve_point(channel_index, x, y)](#add_curve_point_channel_index_x_y_1) | Aggiunge il punto della curva. |
| [get_curve_point_by_index(channel_index, point_index)](#get_curve_point_by_index_channel_index_point_index_2) | Restituisce il punto della curva per indice. |
| [get_curve_point_count(channel_index)](#get_curve_point_count_channel_index_3) | Restituisce il numero di punti della curva. |
| [remove_curve_point(channel_index, point_index)](#remove_curve_point_channel_index_point_index_4) | Rimuove il punto della curva. |
| [update_curve_point(channel_index, point_index, x, y)](#update_curve_point_channel_index_point_index_x_y_5) | Aggiorna il punto della curva. |


### Constructor: CurvesContinuousManager(max_channel_count) {#CurvesContinuousManager_max_channel_count_1}


```
 CurvesContinuousManager(max_channel_count) 
```

Inizializza una nuova istanza della classe [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| max_channel_count | int | Il conteggio massimo dei canali. |

### Method: add_curve_point(channel_index, x, y) {#add_curve_point_channel_index_x_y_1}


```
 add_curve_point(channel_index, x, y) 
```

Aggiunge il punto della curva.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| x | byte | La posizione x. |
| y | byte | La posizione y. |

### Method: get_curve_point_by_index(channel_index, point_index) {#get_curve_point_by_index_channel_index_point_index_2}


```
 get_curve_point_by_index(channel_index, point_index) 
```

Restituisce il punto della curva per indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| point_index | int | Indice del punto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Punto della curva per indice del canale |


### Method: get_curve_point_count(channel_index) {#get_curve_point_count_channel_index_3}


```
 get_curve_point_count(channel_index) 
```

Restituisce il numero di punti della curva.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Numero di punti della curva nel canale |


### Method: remove_curve_point(channel_index, point_index) {#remove_curve_point_channel_index_point_index_4}


```
 remove_curve_point(channel_index, point_index) 
```

Rimuove il punto della curva.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| point_index | int | Indice del punto. |

### Method: update_curve_point(channel_index, point_index, x, y) {#update_curve_point_channel_index_point_index_x_y_5}


```
 update_curve_point(channel_index, point_index, x, y) 
```

Aggiorna il punto della curva.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| channel_index | int | Indice del canale. |
| point_index | int | Indice del punto. |
| x | byte | La posizione x. |
| y | byte | La posizione y. |


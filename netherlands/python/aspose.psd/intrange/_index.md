---
title: "IntRange-klasse"
type: docs
weight: 2340
url: /nl/python-net/aspose.psd/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IntRange

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | Initialiseert een nieuw exemplaar van de [IntRange](/psd/python-net/aspose.psd/intrange/) klasse. |
| [IntRange(start, count)](#IntRange_start_count_2) | Initialiseert een nieuw exemplaar van de [IntRange](/psd/python-net/aspose.psd/intrange/) klasse. |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | Initialiseert een nieuw exemplaar van de [IntRange](/psd/python-net/aspose.psd/intrange/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bereik | int | r/w | Haalt het bereik op of stelt het in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | Retourneert een array met één item vanaf de opgegeven index |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | Haalt het bereik van het aantal int-elementen op dat begint bij start |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

Initialiseert een nieuw exemplaar van de [IntRange](/psd/python-net/aspose.psd/intrange/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bereik | int | Het bereik. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

Initialiseert een nieuw exemplaar van de [IntRange](/psd/python-net/aspose.psd/intrange/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| begin | int | Het begin. |
| count | int | Het aantal. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

Initialiseert een nieuw exemplaar van de [IntRange](/psd/python-net/aspose.psd/intrange/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| begin | int | Het begin. |
| count | int | Het aantal. |
| delta | int | De delta. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

Retourneert een array met één item vanaf de opgegeven index

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De index van het bereik. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De array van int |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

Haalt het bereik van het aantal int-elementen op dat begint bij start

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| begin | int | Het begin. |
| count | int | Het aantal. |
| delta | int | De delta. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| iter[int] | Array van items |



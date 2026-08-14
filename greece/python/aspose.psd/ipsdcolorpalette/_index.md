---
title: "Κλάση IPsdColorPalette"
type: docs
weight: 1990
url: /el/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Λαμβάνει έναν πίνακα δομών 32-bit ARGB. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Λαμβάνει έναν πίνακα δομών [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| έχει_διαφανές_χρώμα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει αν υπάρχει διαφανές χρώμα. |
| is_compact_palette | bool | r | Λαμβάνει μια τιμή που υποδεικνύει αν χρησιμοποιείται συμπαγή παλέτα. |
| raw_entries | byte | r | Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων χρωματικής παλέτας. |
| raw_entries_count | int | r | Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων χρωματικής παλέτας. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Λαμβάνει το διαφανές χρώμα. |
| transparent_index | short | r | Λαμβάνει το ευρετήριο του διαφανούς χρώματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Λαμβάνει το χρώμα παλέτας 32-bit ARGB με βάση το ευρετήριο. |
| [get_color(index)](#get_color_index_2) | Λαμβάνει το χρώμα της παλέτας με βάση το ευρετήριο. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος 32-bit ARGB. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Λαμβάνει το δείκτη του πλησιέστερου χρώματος 32-bit ARGB. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

Λαμβάνει το χρώμα παλέτας 32-bit ARGB με βάση το ευρετήριο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Ο δείκτης χρώματος παλέτας 32-bit ARGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Η καταχώρηση παλέτας χρώματος που καθορίζεται από το <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

Λαμβάνει το χρώμα της παλέτας με βάση το ευρετήριο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Ο δείκτης χρώματος παλέτας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Η καταχώρηση παλέτας χρώματος που καθορίζεται από το <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Λαμβάνει το δείκτη του πλησιέστερου χρώματος 32-bit ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_32_color | int | Το χρώμα 32-bit ARGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο δείκτης του πλησιέστερου χρώματος. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Λαμβάνει το δείκτη του πλησιέστερου χρώματος 32-bit ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο δείκτης του πλησιέστερου χρώματος. |



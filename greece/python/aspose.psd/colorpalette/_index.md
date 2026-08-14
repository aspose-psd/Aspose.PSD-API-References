---
title: "ColorPalette Τάξη"
type: docs
weight: 800
url: /el/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) και το IsCompactPalette είναι ψευδές. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) και το IsCompactPalette είναι ψευδές. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Λαμβάνει έναν πίνακα δομών 32-bit ARGB. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Λαμβάνει έναν πίνακα δομών [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| is_compact_palette | bool | r | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγής παλέτα. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Αντιγράφει την παλέτα. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Αντιγράφει την παλέτα. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Λαμβάνει το χρώμα παλέτας 32-bit ARGB με βάση το ευρετήριο. |
| [get_color(index)](#get_color_index_4) | Λαμβάνει το χρώμα της παλέτας με βάση το ευρετήριο. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Λαμβάνει τον δείκτη του πλησιέστερου χρώματος. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Λαμβάνει τον δείκτη του πλησιέστερου χρώματος. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) και το IsCompactPalette είναι ψευδές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_32_entries | int | Οι καταχωρήσεις της παλέτας χρωμάτων 32-bit ARGB. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_32_entries | int | Οι καταχωρήσεις της παλέτας χρωμάτων 32-bit ARGB. |
| is_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) και το IsCompactPalette είναι ψευδές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Αντιγράφει την παλέτα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Η νεοδημιουργημένη και αντιγραμμένη παλέτα ή null εάν περάστηκε null παλέτα. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Αντιγράφει την παλέτα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| use_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Η νεοδημιουργημένη και αντιγραμμένη παλέτα ή null εάν περάστηκε null παλέτα. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


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


### Method: get_color(index) {#get_color_index_4}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Λαμβάνει τον δείκτη του πλησιέστερου χρώματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_32_color | int | Το χρώμα 32-bit ARGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο δείκτης του πλησιέστερου χρώματος. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Λαμβάνει τον δείκτη του πλησιέστερου χρώματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο δείκτης του πλησιέστερου χρώματος. |



---
title: "PsdColorPalette Κλάση"
type: docs
weight: 1750
url: /el/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Λαμβάνει έναν πίνακα 32-bit ARGB χρωμάτων. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Λαμβάνει έναν πίνακα δομών [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Λαμβάνει τον αριθμό των καταχωρήσεων. |
| έχει_διαφανές_χρώμα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει αν υπάρχει διαφανές χρώμα. |
| is_compact_palette | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα είναι συμπαγής. |
| raw_entries | byte | r | Λαμβάνει τα ακατέργαστα δεδομένα καταχωρήσεων χρωματικής παλέτας. |
| raw_entries_count | int | r | Λαμβάνει τον αριθμό των ακατέργαστων καταχωρήσεων χρωματικής παλέτας. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Λαμβάνει το διαφανές χρώμα. |
| transparent_index | short | r | Λαμβάνει το ευρετήριο του διαφανούς χρώματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Αντιγράφει την παλέτα. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Αντιγράφει την παλέτα. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Λαμβάνει το χρώμα παλέτας 32-bit ARGB με βάση το ευρετήριο. |
| [get_color(index)](#get_color_index_4) | Λαμβάνει το χρώμα της παλέτας με βάση το ευρετήριο. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Λαμβάνει τον δείκτη του πλησιέστερου χρώματος. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Λαμβάνει τον δείκτη του πλησιέστερου χρώματος. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| transparent_index | short | Ο δείκτης διαφανούς χρώματος. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Η παλέτα χρωμάτων 32-bit ARGB καταχωρήσεις. |
| is_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| is_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| transparent_index | short | Ο δείκτης διαφανούς χρώματος. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Οι καταχωρήσεις της παλέτας χρωμάτων. |
| transparent_index | short | Ο δείκτης διαφανούς χρώματος. |
| use_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raw_entries_data | byte | Τα ακατέργαστα δεδομένα καταχωρήσεων. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raw_entries_data | byte | Τα ακατέργαστα δεδομένα καταχωρήσεων. |
| is_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης και το IsCompactPalette είναι ψευδές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raw_entries_data | byte | Τα ακατέργαστα δεδομένα καταχωρήσεων. |
| transparent_index | short | Ο δείκτης διαφανούς χρώματος. Σημειώστε ότι ο δείκτης δεν είναι ο δείκτης των ακατέργαστων καταχωρήσεων, αλλά αφορά τον μετατρεπόμενο πίνακα χρωμάτων. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Αρχικοποιεί μια νέα παρουσία του [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raw_entries_data | byte | Τα ακατέργαστα δεδομένα καταχωρήσεων. |
| transparent_index | short | Ο δείκτης διαφανούς χρώματος. Σημειώστε ότι ο δείκτης δεν είναι ο δείκτης των ακατέργαστων καταχωρήσεων, αλλά αφορά τον μετατρεπόμενο πίνακα χρωμάτων. |
| use_compact_palette | bool | Υποδεικνύει εάν η παλέτα είναι συμπαγής. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Η νεοδημιουργημένη και αντιγραμμένη παλέτα ή null εάν περάστηκε null παλέτα. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | Η νεοδημιουργημένη και αντιγραμμένη παλέτα ή null εάν περάστηκε null παλέτα. |


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



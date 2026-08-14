---
title: "Κλάση ColorPaletteHelper"
type: docs
weight: 810
url: /el/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Δημιουργεί την παλέτα χρωμάτων 4 bit. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Δημιουργεί την παλέτα αποχρώσεων του γκρι 4 bit. |
| [create_8_bit()](#create_8_bit__3) | Δημιουργεί την παλέτα χρωμάτων 8 bit. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Δημιουργεί την παλέτα αποχρώσεων του γκρι 8 bit. |
| [create_monochrome()](#create_monochrome__5) | Δημιουργεί μια μονοχρωματική παλέτα χρωμάτων που περιέχει μόνο 2 χρώματα. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πλαττοποιεί την εικόνα) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πλαττοποιεί την εικόνα) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πλαττοποιεί την εικόνα) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών. |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | Λάβετε παλέτα 256 χρωμάτων, συντεθειμένη από τα υψηλότερα bits των αρχικών τιμών χρώματος της εικόνας. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | Λάβετε ομοιόμορφη παλέτα 256 χρωμάτων. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | Καθορίζει εάν η καθορισμένη παλέτα έχει διαφανή χρώματα. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Δημιουργεί την παλέτα χρωμάτων 4 bit.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα χρωμάτων 4 bit. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Δημιουργεί την παλέτα αποχρώσεων του γκρι 4 bit.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| min_is_white | bool | εάν οριστεί σε <c>true</c> η παλέτα ξεκινά με λευκό χρώμα, διαφορετικά ξεκινά με μαύρο χρώμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η 4 bit παλέτα γκρι κλίμακας. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Δημιουργεί την παλέτα χρωμάτων 8 bit.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η 8 bit χρωματική παλέτα. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Δημιουργεί την παλέτα αποχρώσεων του γκρι 8 bit.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| min_is_white | bool | εάν οριστεί σε <c>true</c> η παλέτα ξεκινά με λευκό χρώμα, διαφορετικά ξεκινά με μαύρο χρώμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η 8 bit παλέτα γκρι κλίμακας. |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

Δημιουργεί μια μονοχρωματική παλέτα χρωμάτων που περιέχει μόνο 2 χρώματα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Παλέτα χρωμάτων για μονόχρωμες εικόνες. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πλαττοποιεί την εικόνα) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η raster εικόνα. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Τα όρια της εικόνας προορισμού. |
| entries_count | int | Ο επιθυμητός αριθμός καταχωρίσεων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η χρωματική παλέτα που ξεκινά με τα πιο συχνά χρώματα από το <paramref name="image" /> και περιέχει <paramref name="entriesCount" /> καταχωρίσεις. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πλαττοποιεί την εικόνα) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η raster εικόνα. |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Τα όρια της εικόνας προορισμού. |
| entries_count | int | Ο επιθυμητός αριθμός καταχωρίσεων. |
| use_image_palette | bool | Εάν οριστεί, θα χρησιμοποιήσει τη δική του παλέτα εικόνας εάν είναι διαθέσιμη. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η χρωματική παλέτα που ξεκινά με τα πιο συχνά χρώματα από το <paramref name="image" /> και περιέχει <paramref name="entriesCount" /> καταχωρίσεις. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

Λαμβάνει την παλέτα χρωμάτων από εικόνα raster (πλαττοποιεί την εικόνα) σε περίπτωση που η εικόνα δεν έχει παλέτα. Σε περίπτωση που η παλέτα υπάρχει, θα χρησιμοποιηθεί αντί για την εκτέλεση υπολογισμών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η raster εικόνα. |
| entries_count | int | Ο επιθυμητός αριθμός καταχωρίσεων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η χρωματική παλέτα που ξεκινά με τα πιο συχνά χρώματα από το <paramref name="image" /> και περιέχει <paramref name="entriesCount" /> καταχωρίσεις. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

Λάβετε παλέτα 256 χρωμάτων, συντεθειμένη από τα υψηλότερα bits των αρχικών τιμών χρώματος της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η εικόνα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Η [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

Λάβετε ομοιόμορφη παλέτα 256 χρωμάτων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η εικόνα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | Η [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

Καθορίζει εάν η καθορισμένη παλέτα έχει διαφανή χρώματα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η καθορισμένη παλέτα έχει διαφανή χρώματα· διαφορετικά, <c>false</c>. |



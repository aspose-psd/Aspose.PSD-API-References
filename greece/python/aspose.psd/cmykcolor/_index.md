---
title: "Κλάση CmykColor"
type: docs
weight: 630
url: /el/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| c | byte | r | Λαμβάνει την τιμή του κυανό στοιχείου αυτής της δομής [Color](/psd/python-net/aspose.psd/color/). |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Λαμβάνει το κενό. |
| is_empty | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η δομή [Color](/psd/python-net/aspose.psd/color/) δεν έχει αρχικοποιηθεί. |
| k | byte | r | Λαμβάνει την τιμή του μαύρου στοιχείου αυτής της δομής [Color](/psd/python-net/aspose.psd/color/). |
| m | byte | r | Λαμβάνει την τιμή του ματζέντα στοιχείου αυτής της δομής [Color](/psd/python-net/aspose.psd/color/). |
| y | byte | r | Λαμβάνει την τιμή του κίτρινου στοιχείου αυτής της δομής [Color](/psd/python-net/aspose.psd/color/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Δημιουργεί μια δομή [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) από τιμές 32-bit κυανό, ματζέντα, κίτρινο και μαύρο.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Η μετατροπή από CMYKColor σε 32-bit χρώμα ARGB χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Η μετατροπή από 32-bit χρώμα ARGB σε CMYKColor.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Η μετατροπή από 32-bit χρώμα ARGB σε CMYKColor.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | Η τιμή του to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Δημιουργεί μια δομή [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) από τιμές 32-bit κυανό, ματζέντα, κίτρινο και μαύρο.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| κυανό | int | Το κυανό συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |
| ματζέντα | int | Το ματζέντα συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |
| κίτρινο | int | Το κίτρινο συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |
| μαύρο | int | Το μαύρο συστατικό. Οι έγκυρες τιμές είναι από 0 έως 255. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Το [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Η μετατροπή από CMYKColor σε 32-bit χρώμα ARGB χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο πίνακας του 32-bit χρώματος ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Η μετατροπή από 32-bit χρώμα ARGB σε CMYKColor.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Το <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Η μετατροπή από 32-bit χρώμα ARGB σε CMYKColor.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_pixels | int | Τα pixel της μορφής 32-bit ARGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Το <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Ο πίνακας των χρωμάτων ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Ο πίνακας των χρωμάτων ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Το [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ icc rgb. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Το [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc με προεπιλεγμένα προφίλ.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Το [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Η μετατροπή από CMYKColor σε Color χρησιμοποιώντας μετατροπή icc.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποδοτική Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Τα pixel τύπου CMYKColor σε μορφή CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ icc rgb. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Το [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Η τιμή του to.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| long | Το int. |



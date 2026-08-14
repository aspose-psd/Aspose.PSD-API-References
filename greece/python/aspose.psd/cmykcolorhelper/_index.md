---
title: "CmykColorHelper Κλάση"
type: docs
weight: 640
url: /el/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Δημιουργεί CMYK από τιμές 32-bit κυανίου, ματζέντας, κίτρινου και μαύρου. |
| [get_c(cmyk)](#get_c_cmyk_2) | Λαμβάνει την τιμή του συστατικού κυανίου. |
| [get_k(cmyk)](#get_k_cmyk_3) | Λαμβάνει την τιμή του συστατικού μαύρου. |
| [get_m(cmyk)](#get_m_cmyk_4) | Λαμβάνει την τιμή του συστατικού ματζέντας. |
| [get_y(cmyk)](#get_y_cmyk_5) | Λαμβάνει την τιμή του συστατικού κίτρινου. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας τη μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας τη μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Μετατρέπει RGB σε CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Δημιουργεί CMYK από τιμές 32-bit κυανίου, ματζέντας, κίτρινου και μαύρου.

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
| int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Λαμβάνει την τιμή του συστατικού κυανίου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Η τιμή του κυανό συστατικού. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Λαμβάνει την τιμή του συστατικού μαύρου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Η τιμή του μαύρου συστατικού. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Λαμβάνει την τιμή του συστατικού ματζέντας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Η τιμή του ματζέντα συστατικού. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Λαμβάνει την τιμή του συστατικού κίτρινου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk | int | Το χρώμα CMYK που παρουσιάζεται ως τιμή ακέραιου 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Η τιμή του κίτρινου συστατικού. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα ARGB που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας τη μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc RGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας τη μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | int | Τα pixel CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Η μετατροπή από χρώματα CMYK σε χρώματα ARGB χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cmyk_pixels | int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc RGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_pixels | int | Τα χρώματα ARGB που παρουσιάζονται ως τιμές ακέραιων 32-bit. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Μετατρέπει RGB σε CMYK.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| argb_pixels | int | Τα χρώματα RGB που παρουσιάζονται ως τιμές 32-bit ακέραιων. |
| start_index | int | Ο αρχικός δείκτης του χρώματος RGB. |
| μήκος | int | Ο αριθμός των εικονοστοιχείων RGB προς μετατροπή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Τα χρώματα CMYK που παρουσιάζονται ως πίνακας byte. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc CMYK. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προεπιλεγμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Η μετατροπή από χρώματα ARGB σε χρώματα CMYK χρησιμοποιώντας μετατροπή Icc με προσαρμοσμένα προφίλ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Τα χρώματα ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή που περιέχει το προφίλ Icc CMYK. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα χρώματα CMYK που παρουσιάζονται ως τιμές ακέραιων 32-bit. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixels | int | Τα χρώματα RGB που παρουσιάζονται ως τιμές 32-bit ακέραιων. |
| start_index | int | Ο αρχικός δείκτης του χρώματος RGB. |
| μήκος | int | Ο αριθμός των εικονοστοιχείων RGB προς μετατροπή. |
| rgb_icc_stream | _io.BufferedRandom | Η ροή προφίλ RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Η ροή προφίλ CMYK. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Τα χρώματα CMYK που παρουσιάζονται ως πίνακας byte. |



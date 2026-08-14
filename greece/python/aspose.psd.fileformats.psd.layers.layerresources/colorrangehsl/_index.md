---
title: "ColorRangeHsl Κλάση"
type: docs
weight: 180
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) . |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| hue | short | r/w | Λαμβάνει ή ορίζει το hue. |
| left_border | short | r/w | Λαμβάνει ή ορίζει το αριστερό όριο. |
| lightness | short | r/w | Λαμβάνει ή ορίζει το lightness. |
| most_left_border | short | r/w | Λαμβάνει ή ορίζει το πιο αριστερό όριο. |
| most_right_border | short | r/w | Λαμβάνει ή ορίζει το πιο δεξιό όριο. |
| right_border | short | r/w | Λαμβάνει ή ορίζει το δεξιό όριο. |
| κορεσμός | short | r/w | Λαμβάνει ή ορίζει τον κορεσμό. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Λαμβάνει τον συντελεστή εύρους. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Καθορίζει εάν η απόχρωση είναι σε μεγάλο εύρος. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Καθορίζει εάν η απόχρωση είναι σε μικρό εύρος. |
| [save(stream_container)](#save_stream_container_4) | Αποθηκεύει τα δεδομένα στο καθορισμένο δοχείο ροής. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) .

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) .

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα εύρους χρώματος. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Λαμβάνει τον συντελεστή εύρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| hue | double | Η τιμή απόχρωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Συντελεστής εύρους κορεσμού. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Καθορίζει εάν η απόχρωση είναι σε μεγάλο εύρος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| hue | double | Η τιμή απόχρωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η απόχρωση είναι σε μεγάλο εύρος· διαφορετικά, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Καθορίζει εάν η απόχρωση είναι σε μικρό εύρος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| hue | double | Η τιμή απόχρωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η απόχρωση είναι σε μικρή περιοχή· διαφορετικά, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Αποθηκεύει τα δεδομένα στο καθορισμένο δοχείο ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |


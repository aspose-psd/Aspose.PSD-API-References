---
title: "RawColor Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Δημιουργεί μια νέα παρουσία της [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) κλάσης. |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Δημιουργεί μια νέα παρουσία της [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) κλάσης από μορφή δεδομένων εικονοστοιχείων χρησιμοποιώντας προεπιλεγμένες λειτουργίες χρώματος. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Λειτουργία για το χρώμα που ακολουθεί. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Αποκτά τα συστατικά του χρώματος. Κάθε συστατικό είναι ξεχωριστό κανάλι, και εάν χρησιμοποιείτε μη δημοφιλές<br/>            σχήμα χρώματος, είναι καλύτερο να εργάζεστε με κάθε κανάλι ξεχωριστά. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Αποκτά το χρώμα ως int εάν είναι δυνατόν να το λάβει. |
| [get_as_long()](#get_as_long__2) | Αποκτά το χρώμα ως long εάν είναι δυνατόν να το λάβει. |
| [get_bit_depth()](#get_bit_depth__3) | Αποκτά το βάθος bit του Raw Color. <br/>            Για παράδειγμα για χρώμα ARGB με 8 bit ανά κανάλι/συστατικό είναι 32<br/>            Το βάθος bit πλήρους χρώματος ARGB με 16 bit ανά κανάλι/συστατικό είναι 64.<br/>            Το βάθος bit συσσωρεύεται από το άθροισμα των βάθους των καναλιών. <br/>            Είναι δυνατόν εάν διαφορετικά κανάλια έχουν διαφορετικά βάθη bit. |
| [get_color_mode_name()](#get_color_mode_name__4) | Αποκτά το όνομα της λειτουργίας χρώματος. Το όνομα λειτουργίας χρώματος συσσωρεύεται από τα ονόματα των καναλιών/συστατικών. |
| [set_as_int(value)](#set_as_int_value_5) | Ορίζει δεδομένα σε όλα τα κανάλια από όρισμα τύπου int εάν είναι δυνατόν. |
| [set_as_long(value)](#set_as_long_value_6) | Ορίζει δεδομένα σε όλα τα κανάλια από όρισμα τύπου int εάν είναι δυνατόν. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Δημιουργεί μια νέα παρουσία της [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Τα προσαρμοσμένα συστατικά χρώματος. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Δημιουργεί μια νέα παρουσία της [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) κλάσης από μορφή δεδομένων εικονοστοιχείων χρησιμοποιώντας προεπιλεγμένες λειτουργίες χρώματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Η μορφή δεδομένων εικονοστοιχείων. |
| color_mode | short | Λειτουργία για το χρώμα που ακολουθεί. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Αποκτά το χρώμα ως int εάν είναι δυνατόν να το λάβει.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Δεδομένα καναλιών αποθηκευμένα σε Int. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Αποκτά το χρώμα ως long εάν είναι δυνατόν να το λάβει.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| long | Δεδομένα καναλιών αποθηκευμένα σε Int. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Αποκτά το βάθος bit του Raw Color. <br/>            Για παράδειγμα για χρώμα ARGB με 8 bit ανά κανάλι/συστατικό είναι 32<br/>            Το βάθος bit πλήρους χρώματος ARGB με 16 bit ανά κανάλι/συστατικό είναι 64.<br/>            Το βάθος bit συσσωρεύεται από το άθροισμα των βάθους των καναλιών. <br/>            Είναι δυνατόν εάν διαφορετικά κανάλια έχουν διαφορετικά βάθη bit.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το άθροισμα όλων των βάθους bit των καναλιών. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Αποκτά το όνομα της λειτουργίας χρώματος. Το όνομα λειτουργίας χρώματος συσσωρεύεται από τα ονόματα των καναλιών/συστατικών.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Συμβολοσειρά με το όνομα λειτουργίας χρώματος. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Ορίζει δεδομένα σε όλα τα κανάλια από όρισμα τύπου int εάν είναι δυνατόν.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | int | Η τιμή int που περιέχει τα δεδομένα του συστατικού. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Ορίζει δεδομένα σε όλα τα κανάλια από όρισμα τύπου int εάν είναι δυνατόν.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | long | Η τιμή int που περιέχει τα δεδομένα του συστατικού. |


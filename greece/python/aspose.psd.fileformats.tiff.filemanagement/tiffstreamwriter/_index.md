---
title: "TiffStreamWriter Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Summary:** Tiff stream writer.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TiffStreamWriter(writer)](#TiffStreamWriter_writer_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| position | long | r/w | Λαμβάνει ή ορίζει τη θέση της ροής. |
| sync_root | object | r | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [write(data)](#write_data_1) | Γράφει τα καθορισμένα δεδομένα. |
| [write(data, offset, data_length)](#write_data_offset_data_length_2) | Γράφει τα καθορισμένα δεδομένα. |
| [write_double(data)](#write_double_data_3) | Γράφει μια μοναδική τιμή double στη ροή. |
| [write_double_array(data)](#write_double_array_data_4) | Γράφει έναν πίνακα τιμών double στη ροή. |
| [write_float(data)](#write_float_data_5) | Γράφει μια μοναδική τιμή float στη ροή. |
| [write_float_array(data)](#write_float_array_data_6) | Γράφει έναν πίνακα τιμών float στη ροή. |
| [write_rational(data)](#write_rational_data_7) | Γράφει μια μοναδική τιμή ρητού αριθμού στη ροή. |
| [write_rational_array(data)](#write_rational_array_data_8) | Γράφει έναν πίνακα τιμών μη υπογεγραμμένων ρητών στη ροή. |
| [write_s_byte(data)](#write_s_byte_data_9) | Γράφει μια μοναδική τιμή υπογεγραμμένου byte στη ροή. |
| [write_s_byte_array(data)](#write_s_byte_array_data_10) | Γράφει έναν πίνακα τιμών υπογεγραμμένων byte στη ροή. |
| [write_s_long_array(data)](#write_s_long_array_data_11) | Γράφει έναν πίνακα τιμών ακεραίων στη ροή. |
| [write_s_rational(data)](#write_s_rational_data_12) | Γράφει μια μοναδική τιμή υπογεγραμμένου ρητού αριθμού στη ροή. |
| [write_s_rational_array(data)](#write_s_rational_array_data_13) | Γράφει έναν πίνακα τιμών υπογεγραμμένων ρητών στη ροή. |
| [write_s_short(data)](#write_s_short_data_14) | Γράφει μια μοναδική τιμή short στη ροή. |
| [write_s_short_array(data)](#write_s_short_array_data_15) | Γράφει έναν πίνακα τιμών short στη ροή. |
| [write_slong(data)](#write_slong_data_16) | Γράφει μια μοναδική τιμή ακεραίου στη ροή. |
| [write_u_byte(data)](#write_u_byte_data_17) | Γράφει μια μοναδική τιμή byte στη ροή. |
| [write_u_long(data)](#write_u_long_data_18) | Γράφει μια μοναδική τιμή μη υπογεγραμμένου ακεραίου στη ροή. |
| [write_u_long_array(data)](#write_u_long_array_data_19) | Γράφει έναν πίνακα τιμών μη υπογεγραμμένων ακεραίων στη ροή. |
| [write_u_short(data)](#write_u_short_data_20) | Γράφει μια μοναδική τιμή μη υπογεγραμμένου short στη ροή. |
| [write_u_short_array(data)](#write_u_short_array_data_21) | Γράφει έναν πίνακα τιμών μη υπογεγραμμένων short στη ροή. |


### Constructor: TiffStreamWriter(writer) {#TiffStreamWriter_writer_1}


```
 TiffStreamWriter(writer) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| writer | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Ο συγγραφέας ροής. |

### Method: write(data) {#write_data_1}


```
 write(data) 
```

Γράφει τα καθορισμένα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα προς εγγραφή. |

### Method: write(data, offset, data_length) {#write_data_offset_data_length_2}


```
 write(data, offset, data_length) 
```

Γράφει τα καθορισμένα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα προς εγγραφή. |
| offset | int | Η μετατόπιση δεδομένων. |
| data_length | int | Μήκος των δεδομένων προς εγγραφή. |

### Method: write_double(data) {#write_double_data_3}


```
 write_double(data) 
```

Γράφει μια μοναδική τιμή double στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | double | Η τιμή προς εγγραφή. |

### Method: write_double_array(data) {#write_double_array_data_4}


```
 write_double_array(data) 
```

Γράφει έναν πίνακα τιμών double στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | double | Ο πίνακας προς εγγραφή. |

### Method: write_float(data) {#write_float_data_5}


```
 write_float(data) 
```

Γράφει μια μοναδική τιμή float στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | float | Η τιμή προς εγγραφή. |

### Method: write_float_array(data) {#write_float_array_data_6}


```
 write_float_array(data) 
```

Γράφει έναν πίνακα τιμών float στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | float | Ο πίνακας προς εγγραφή. |

### Method: write_rational(data) {#write_rational_data_7}


```
 write_rational(data) 
```

Γράφει μια μοναδική τιμή ρητού αριθμού στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Η τιμή προς εγγραφή. |

### Method: write_rational_array(data) {#write_rational_array_data_8}


```
 write_rational_array(data) 
```

Γράφει έναν πίνακα τιμών μη υπογεγραμμένων ρητών στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ο πίνακας προς εγγραφή. |

### Method: write_s_byte(data) {#write_s_byte_data_9}


```
 write_s_byte(data) 
```

Γράφει μια μοναδική τιμή υπογεγραμμένου byte στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | sbyte | Η τιμή προς εγγραφή. |

### Method: write_s_byte_array(data) {#write_s_byte_array_data_10}


```
 write_s_byte_array(data) 
```

Γράφει έναν πίνακα τιμών υπογεγραμμένων byte στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | sbyte | Ο πίνακας προς εγγραφή. |

### Method: write_s_long_array(data) {#write_s_long_array_data_11}


```
 write_s_long_array(data) 
```

Γράφει έναν πίνακα τιμών ακεραίων στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | int | Ο πίνακας προς εγγραφή. |

### Method: write_s_rational(data) {#write_s_rational_data_12}


```
 write_s_rational(data) 
```

Γράφει μια μοναδική τιμή υπογεγραμμένου ρητού αριθμού στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Η τιμή προς εγγραφή. |

### Method: write_s_rational_array(data) {#write_s_rational_array_data_13}


```
 write_s_rational_array(data) 
```

Γράφει έναν πίνακα τιμών υπογεγραμμένων ρητών στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data | [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ο πίνακας προς εγγραφή. |

### Method: write_s_short(data) {#write_s_short_data_14}


```
 write_s_short(data) 
```

Γράφει μια μοναδική τιμή short στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | short | Η τιμή προς εγγραφή. |

### Method: write_s_short_array(data) {#write_s_short_array_data_15}


```
 write_s_short_array(data) 
```

Γράφει έναν πίνακα τιμών short στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | short | Ο πίνακας προς εγγραφή. |

### Method: write_slong(data) {#write_slong_data_16}


```
 write_slong(data) 
```

Γράφει μια μοναδική τιμή ακεραίου στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | int | Η τιμή προς εγγραφή. |

### Method: write_u_byte(data) {#write_u_byte_data_17}


```
 write_u_byte(data) 
```

Γράφει μια μοναδική τιμή byte στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Η τιμή προς εγγραφή. |

### Method: write_u_long(data) {#write_u_long_data_18}


```
 write_u_long(data) 
```

Γράφει μια μοναδική τιμή μη υπογεγραμμένου ακεραίου στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | uint | Η τιμή προς εγγραφή. |

### Method: write_u_long_array(data) {#write_u_long_array_data_19}


```
 write_u_long_array(data) 
```

Γράφει έναν πίνακα τιμών μη υπογεγραμμένων ακεραίων στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | uint | Ο πίνακας προς εγγραφή. |

### Method: write_u_short(data) {#write_u_short_data_20}


```
 write_u_short(data) 
```

Γράφει μια μοναδική τιμή μη υπογεγραμμένου short στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | ushort | Η τιμή προς εγγραφή. |

### Method: write_u_short_array(data) {#write_u_short_array_data_21}


```
 write_u_short_array(data) 
```

Γράφει έναν πίνακα τιμών μη υπογεγραμμένων short στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | ushort | Ο πίνακας προς εγγραφή. |


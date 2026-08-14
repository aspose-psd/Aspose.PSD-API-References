---
title: "Τάξη TiffStreamReader"
type: docs
weight: 10
url: /el/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Summary:** The tiff stream for handling little endian tiff file format.

**Module:** [aspose.psd.fileformats.tiff.filemanagement](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/)

**Full Name:** aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TiffStreamReader(data)](#TiffStreamReader_data_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) . |
| [TiffStreamReader(data, start_index)](#TiffStreamReader_data_start_index_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) . |
| [TiffStreamReader(data, start_index, data_length)](#TiffStreamReader_data_start_index_data_length_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) . |
| [TiffStreamReader(stream_container)](#TiffStreamReader_stream_container_4) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| μήκος | long | r | Λαμβάνει το μήκος του αναγνώστη. |
| throw_exceptions | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι εξαιρέσεις ρίχνονται κατά την εσφαλμένη επεξεργασία δεδομένων (ανάγνωση ή εγγραφή στη ροή). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [read_bytes(array, array_index, position, count)](#read_bytes_array_array_index_position_count_1) | Διαβάζει έναν πίνακα τιμών byte από τη ροή. |
| [read_bytes(position, count)](#read_bytes_position_count_2) | Διαβάζει έναν πίνακα τιμών unsigned byte από τη ροή. |
| [read_double(position)](#read_double_position_3) | Διαβάζει μία τιμή double από τη ροή. |
| [read_double_array(position, count)](#read_double_array_position_count_4) | Διαβάζει έναν πίνακα τιμών double από τη ροή. |
| [read_float(position)](#read_float_position_5) | Διαβάζει μία τιμή float από τη ροή. |
| [read_float_array(position, count)](#read_float_array_position_count_6) | Διαβάζει έναν πίνακα τιμών float από τη ροή. |
| [read_rational(position)](#read_rational_position_7) | Διαβάζει μία τιμή ρητού αριθμού από τη ροή. |
| [read_rational_array(position, count)](#read_rational_array_position_count_8) | Διαβάζει έναν πίνακα τιμών ρητών αριθμών από τη ροή. |
| [read_s_byte(position)](#read_s_byte_position_9) | Διαβάζει δεδομένα signed byte από τη ροή. |
| [read_s_byte_array(position, count)](#read_s_byte_array_position_count_10) | Διαβάζει έναν πίνακα τιμών signed byte από τη ροή. |
| [read_s_long(position)](#read_s_long_position_11) | Διαβάζει τιμή signed integer από τη ροή. |
| [read_s_long_array(position, count)](#read_s_long_array_position_count_12) | Διαβάζει έναν πίνακα τιμών signed integer από τη ροή. |
| [read_s_rational(position)](#read_s_rational_position_13) | Διαβάζει μία τιμή signed rational number από τη ροή. |
| [read_s_rational_array(position, count)](#read_s_rational_array_position_count_14) | Διαβάζει έναν πίνακα τιμών signed rational από τη ροή. |
| [read_s_short(position)](#read_s_short_position_15) | Διαβάζει τιμή signed short από τη ροή. |
| [read_s_short_array(position, count)](#read_s_short_array_position_count_16) | Διαβάζει έναν πίνακα τιμών signed short από τη ροή. |
| [read_u_long(position)](#read_u_long_position_17) | Διαβάζει τιμή unsigned integer από τη ροή. |
| [read_u_long_array(position, count)](#read_u_long_array_position_count_18) | Διαβάζει έναν πίνακα τιμών unsigned integer από τη ροή. |
| [read_u_short(position)](#read_u_short_position_19) | Διαβάζει τιμή unsigned short από τη ροή. |
| [read_u_short_array(position, count)](#read_u_short_array_position_count_20) | Διαβάζει έναν πίνακα τιμών unsigned integer από τη ροή. |
| [to_stream_container(start_position)](#to_stream_container_start_position_21) | Μετατρέπει τα υποκείμενα δεδομένα σε stream container. |


### Constructor: TiffStreamReader(data) {#TiffStreamReader_data_1}


```
 TiffStreamReader(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) .

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα πίνακα byte. |

### Constructor: TiffStreamReader(data, start_index) {#TiffStreamReader_data_start_index_2}


```
 TiffStreamReader(data, start_index) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) .

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα πίνακα byte. |
| start_index | int | Ο αρχικός δείκτης στο <paramref name="data" />. |

### Constructor: TiffStreamReader(data, start_index, data_length) {#TiffStreamReader_data_start_index_data_length_3}


```
 TiffStreamReader(data, start_index, data_length) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) .

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα πίνακα byte. |
| start_index | int | Ο αρχικός δείκτης στο <paramref name="data" />. |
| data_length | int | Μήκος των δεδομένων. |

### Constructor: TiffStreamReader(stream_container) {#TiffStreamReader_stream_container_4}


```
 TiffStreamReader(stream_container) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) .

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |

### Method: read_bytes(array, array_index, position, count) {#read_bytes_array_array_index_position_count_1}


```
 read_bytes(array, array_index, position, count) 
```

Διαβάζει έναν πίνακα τιμών byte από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| πίνακας | byte | Ο πίνακας προς συμπλήρωση. |
| array_index | int | Ο δείκτης του πίνακα για να αρχίσετε να τοποθετείτε τιμές. |
| position | long | Η θέση της ροής από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων προς ανάγνωση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| long | Ο πίνακας τιμών byte. |


### Method: read_bytes(position, count) {#read_bytes_position_count_2}


```
 read_bytes(position, count) 
```

Διαβάζει έναν πίνακα τιμών unsigned byte από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Ο πίνακας τιμών απυρόσημων byte. |


### Method: read_double(position) {#read_double_position_3}


```
 read_double(position) 
```

Διαβάζει μία τιμή double από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Η μοναδική τιμή double. |


### Method: read_double_array(position, count) {#read_double_array_position_count_4}


```
 read_double_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών double από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Ο πίνακας τιμών double. |


### Method: read_float(position) {#read_float_position_5}


```
 read_float(position) 
```

Διαβάζει μία τιμή float από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| float | Η μοναδική τιμή float. |


### Method: read_float_array(position, count) {#read_float_array_position_count_6}


```
 read_float_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών float από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| float | Ο πίνακας τιμών float. |


### Method: read_rational(position) {#read_rational_position_7}


```
 read_rational(position) 
```

Διαβάζει μία τιμή ρητού αριθμού από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ο ρητός αριθμός. |


### Method: read_rational_array(position, count) {#read_rational_array_position_count_8}


```
 read_rational_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών ρητών αριθμών από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ο πίνακας ρητών τιμών. |


### Method: read_s_byte(position) {#read_s_byte_position_9}


```
 read_s_byte(position) 
```

Διαβάζει δεδομένα signed byte από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| sbyte | Η τιμή του υπογεγραμμένου byte. |


### Method: read_s_byte_array(position, count) {#read_s_byte_array_position_count_10}


```
 read_s_byte_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών signed byte από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| sbyte | Ο πίνακας τιμών υπογεγραμμένων byte. |


### Method: read_s_long(position) {#read_s_long_position_11}


```
 read_s_long(position) 
```

Διαβάζει τιμή signed integer από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Μια τιμή υπογεγραμμένου ακέραιου. |


### Method: read_s_long_array(position, count) {#read_s_long_array_position_count_12}


```
 read_s_long_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών signed integer από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο πίνακας τιμών υπογεγραμμένων ακεραίων. |


### Method: read_s_rational(position) {#read_s_rational_position_13}


```
 read_s_rational(position) 
```

Διαβάζει μία τιμή signed rational number από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ο υπογεγραμμένος ρητός αριθμός. |


### Method: read_s_rational_array(position, count) {#read_s_rational_array_position_count_14}


```
 read_s_rational_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών signed rational από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffSRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ο πίνακας υπογεγραμμένων ρητών τιμών. |


### Method: read_s_short(position) {#read_s_short_position_15}


```
 read_s_short(position) 
```

Διαβάζει τιμή signed short από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| short | Μια τιμή υπογεγραμμένου short. |


### Method: read_s_short_array(position, count) {#read_s_short_array_position_count_16}


```
 read_s_short_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών signed short από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| short | Ο πίνακας τιμών υπογεγραμμένων short. |


### Method: read_u_long(position) {#read_u_long_position_17}


```
 read_u_long(position) 
```

Διαβάζει τιμή unsigned integer από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| uint | Μια τιμή απυρόσημου ακέραιου. |


### Method: read_u_long_array(position, count) {#read_u_long_array_position_count_18}


```
 read_u_long_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών unsigned integer από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| uint | Ο πίνακας τιμών απυρόσημων ακεραίων. |


### Method: read_u_short(position) {#read_u_short_position_19}


```
 read_u_short(position) 
```

Διαβάζει τιμή unsigned short από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| ushort | Μια τιμή απυρόσημου short. |


### Method: read_u_short_array(position, count) {#read_u_short_array_position_count_20}


```
 read_u_short_array(position, count) 
```

Διαβάζει έναν πίνακα τιμών unsigned integer από τη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα διαβάσετε. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| ushort | Ο πίνακας τιμών απυρόσημων ακεραίων. |


### Method: to_stream_container(start_position) {#to_stream_container_start_position_21}


```
 to_stream_container(start_position) 
```

Μετατρέπει τα υποκείμενα δεδομένα σε stream container.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| start_position | long | Η θέση έναρξης από την οποία ξεκινά η μετατροπή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) με τα μετατρεπόμενα δεδομένα. |



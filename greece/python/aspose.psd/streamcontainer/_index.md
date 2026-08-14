---
title: "StreamContainer Κλάση"
type: docs
weight: 4230
url: /el/python-net/aspose.psd/streamcontainer/
---

**Summary:** Represents stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StreamContainer

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [StreamContainer(stream)](#StreamContainer_stream_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [StreamContainer(stream, dispose_stream)](#StreamContainer_stream_dispose_stream_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | Καθορίζει τον αριθμό των byte ανάγνωσης και εγγραφής κατά τη ανάγνωση διαδοχικά. |
| can_read | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει ανάγνωση. |
| can_seek | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει αναζήτηση. |
| can_write | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει εγγραφή. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| is_stream_disposed_on_close | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η ροή απελευθερώνεται κατά το κλείσιμο. |
| μήκος | long | r/w | Λαμβάνει ή ορίζει το μήκος της ροής σε byte. Αυτή η τιμή είναι μικρότερη από τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer. |
| position | long | r/w | Λαμβάνει ή ορίζει την τρέχουσα θέση μέσα στη ροή. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer. |
| ροή | _io.BufferedRandom | r | Λαμβάνει τη ροή δεδομένων. |
| sync_root | object | r | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για το συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| flush() | Καθαρίζει όλες τις προσωρινές μνήμες για αυτή τη ροή και προκαλεί την εγγραφή τυχόν προσωρινών δεδομένων στη βασική συσκευή. |
| [read(buffer, offset, count)](#read_buffer_offset_count_1) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| [read(bytes)](#read_bytes_2) | Διαβάζει byte για να γεμίσει το καθορισμένο buffer byte. |
| [read_byte()](#read_byte__3) | Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν βρίσκεται στο τέλος της ροής. |
| [save(destination_stream)](#save_destination_stream_4) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) και την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_5) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στη συγκεκριμένη ροή. Χρησιμοποιεί την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_6) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή. |
| [save(file_path)](#save_file_path_7) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) και την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_8) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο ροή. Χρησιμοποιεί την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_9) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή. |
| [seek(offset, origin)](#seek_offset_origin_10) | Ορίζει τη θέση εντός της τρέχουσας ροής. |
| seek_begin() | Ορίζει τη θέση της ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer. |
| [to_bytes()](#to_bytes__11) | Μετατρέπει τα δεδομένα της ροής σε πίνακα ακεραίων. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_12) | Μετατρέπει τα δεδομένα της ροής σε πίνακα ακεραίων. |
| [write(buffer, offset, count)](#write_buffer_offset_count_13) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση εντός αυτής της ροής κατά τον αριθμό των γραμμένων byte. |
| [write(bytes)](#write_bytes_14) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| [write_byte(value)](#write_byte_value_15) | Γράφει ένα byte στη τρέχουσα θέση στη ροή και προχωρά τη θέση εντός της ροής κατά ένα byte. |
| [write_to(stream_container)](#write_to_stream_container_16) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_17) | Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: StreamContainer(stream) {#StreamContainer_stream_1}


```
 StreamContainer(stream) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |

### Constructor: StreamContainer(stream, dispose_stream) {#StreamContainer_stream_dispose_stream_2}


```
 StreamContainer(stream, dispose_stream) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή δεδομένων. |
| dispose_stream | bool | αν οριστεί σε <c>true</c> η ροή θα διαγραφεί όταν το container διαγραφεί. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_1}


```
 read(buffer, offset, count) 
```

Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| buffer | byte | Ένας πίνακας byte. Όταν αυτή η μέθοδος επιστρέψει, η προσωρινή μνήμη περιέχει τον καθορισμένο πίνακα byte με τις τιμές μεταξύ <paramref name="offset" /> και (<paramref name="offset" /> + <paramref name="count" /> - 1) που αντικαταστάθηκαν από τα byte που διαβάστηκαν από την τρέχουσα πηγή. |
| offset | int | Η μηδενική βάση offset byte στο <paramref name="buffer" /> στην οποία θα αρχίσει η αποθήκευση των δεδομένων που διαβάζονται από την τρέχουσα ροή. |
| count | int | Ο μέγιστος αριθμός byte που θα διαβαστούν από την τρέχουσα ροή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο συνολικός αριθμός byte που διαβάστηκαν στη προσωρινή μνήμη. Αυτό μπορεί να είναι λιγότερο από τον αριθμό των ζητούμενων byte εάν δεν είναι διαθέσιμα τόσα byte, ή μηδέν (0) εάν έχει φτάσει το τέλος της ροής. |


### Method: read(bytes) {#read_bytes_2}


```
 read(bytes) 
```

Διαβάζει byte για να γεμίσει το καθορισμένο buffer byte.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bytes | byte | Τα byte για γέμισμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο αριθμός των διαβασμένων byte. Αυτή η τιμή μπορεί να είναι μικρότερη από τον αριθμό των byte στη προσωρινή μνήμη εάν δεν υπάρχουν αρκετά byte στη ροή. |


### Method: read_byte() {#read_byte__3}


```
 read_byte() 
```

Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν βρίσκεται στο τέλος της ροής.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το μη υπογεγραμμένο byte μετατρεπόμενο σε Int32, ή -1 εάν βρίσκεται στο τέλος της ροής. |


### Method: save(destination_stream) {#save_destination_stream_4}


```
 save(destination_stream) 
```

Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) και την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_5}


```
 save(destination_stream, buffer_size) 
```

Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στη συγκεκριμένη ροή. Χρησιμοποιεί την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα. |
| buffer_size | int | Η προσωρινή μνήμη. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_6}


```
 save(destination_stream, buffer_size, length) 
```

Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα. |
| buffer_size | int | Το μέγεθος της προσωρινής μνήμης. Από προεπιλογή χρησιμοποιείται η τιμή [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | Το μήκος δεδομένων ροής προς αντιγραφή. Από προεπιλογή, το μήκος ορίζεται στην τιμή [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path) {#save_file_path_7}


```
 save(file_path) 
```

Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) και την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα ροής. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_8}


```
 save(file_path, buffer_size) 
```

Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο ροή. Χρησιμοποιεί την τιμή της ροής [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα ροής. |
| buffer_size | int | Το μέγεθος της προσωρινής μνήμης. Από προεπιλογή χρησιμοποιείται η τιμή [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_9}


```
 save(file_path, buffer_size, length) 
```

Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στη συγκεκριμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα ροής. |
| buffer_size | int | Το μέγεθος της προσωρινής μνήμης. Από προεπιλογή χρησιμοποιείται η τιμή [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/). |
| length | long | Το μήκος δεδομένων ροής προς αντιγραφή. Από προεπιλογή, το μήκος ορίζεται στην τιμή [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_10}


```
 seek(offset, origin) 
```

Ορίζει τη θέση εντός της τρέχουσας ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| offset | long | Μία μετατόπιση byte σε σχέση με την παράμετρο <paramref name="origin" />. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση εκκίνησης της ροής που δόθηκε στον κατασκευαστή StreamContainer. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Μία τιμή τύπου SeekOrigin που υποδεικνύει το σημείο αναφοράς που χρησιμοποιείται για την απόκτηση της νέας θέσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| long | Η νέα θέση εντός της τρέχουσας ροής. |


### Method: to_bytes() {#to_bytes__11}


```
 to_bytes() 
```

Μετατρέπει τα δεδομένα της ροής σε πίνακα ακεραίων.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Τα δεδομένα ροής μετατρεπόμενα σε πίνακα int. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_12}


```
 to_bytes(position, bytes_count) 
```

Μετατρέπει τα δεδομένα της ροής σε πίνακα ακεραίων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| position | long | Η θέση από την οποία θα ξεκινήσει η ανάγνωση των byte. |
| bytes_count | long | Ο αριθμός των byte προς ανάγνωση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Τα δεδομένα ροής μετατρεπόμενα σε πίνακα int. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_13}


```
 write(buffer, offset, count) 
```

Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση εντός αυτής της ροής κατά τον αριθμό των γραμμένων byte.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| buffer | byte | Ένας πίνακας byte. Αυτή η μέθοδος αντιγράφει <paramref name="count" /> byte από το <paramref name="buffer" /> στην τρέχουσα ροή. |
| offset | int | Η μηδενική βάση μετατόπιση byte στο <paramref name="buffer" /> στην οποία θα ξεκινήσει η αντιγραφή byte στην τρέχουσα ροή. |
| count | int | Ο αριθμός των byte που θα γραφούν στην τρέχουσα ροή. |

### Method: write(bytes) {#write_bytes_14}


```
 write(bytes) 
```

Γράφει όλα τα καθορισμένα byte στη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bytes | byte | Τα byte προς εγγραφή. |

### Method: write_byte(value) {#write_byte_value_15}


```
 write_byte(value) 
```

Γράφει ένα byte στη τρέχουσα θέση στη ροή και προχωρά τη θέση εντός της ροής κατά ένα byte.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | byte | Το byte προς εγγραφή στη ροή. |

### Method: write_to(stream_container) {#write_to_stream_container_16}


```
 write_to(stream_container) 
```

Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής προς αντιγραφή. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_17}


```
 write_to(stream_container, length) 
```

Αντιγράφει τα περιεχόμενα δεδομένα σε ένα άλλο [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής προς αντιγραφή. |
| μήκος | long | Ο αριθμός των byte προς εγγραφή. |


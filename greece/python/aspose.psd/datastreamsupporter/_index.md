---
title: "Κλάση DataStreamSupporter"
type: docs
weight: 1030
url: /el/python-net/aspose.psd/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataStreamSupporter

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| είναι_στη_μνήμη | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| cache_data() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| save() | Αποθηκεύει τα δεδομένα του αντικειμένου στο τρέχον [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [save(file_path)](#save_file_path_1) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(stream)](#save_stream_3) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |
| over_write | bool | εάν οριστεί σε <c>true</c> θα αντικαταστήσει τα περιεχόμενα του αρχείου, διαφορετικά θα γίνει προσθήκη. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |


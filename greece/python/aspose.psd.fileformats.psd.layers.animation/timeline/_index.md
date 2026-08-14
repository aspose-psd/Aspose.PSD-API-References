---
title: "Κλάση Timeline"
type: docs
weight: 40
url: /el/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Timeline()](#Timeline__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Λαμβάνει το ενεργό δείκτη πλαισίου. |
| af_st | int | r/w | Λαμβάνει ή ορίζει την τιμή AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Λαμβάνει τη λίστα των πλαισίων. |
| fs_id | int | r/w | Λαμβάνει ή ορίζει την τιμή FsID. |
| loopes_count | ushort | r/w | Λαμβάνει ή ορίζει τον αριθμό των βρόχων. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στην καθορισμένη τοποθεσία αρχείου στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(output_stream, options)](#save_output_stream_options_2) | Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στην καθορισμένη ροή στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Αλλάζει το ενεργό πλαίσιο στο στοχευμένο. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στην καθορισμένη τοποθεσία αρχείου στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Αποθηκεύει τα δεδομένα του PsdImage και του Timeline στην καθορισμένη ροή στην καθορισμένη μορφή σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Η ροή εξόδου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Αλλάζει το ενεργό πλαίσιο στο στοχευμένο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_active_frame_index | int | Ο δείκτης του στόχου πλαισίου. |


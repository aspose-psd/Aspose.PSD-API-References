---
title: "TiffDataType Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.psd.fileformats.tiff/tiffdatatype/
---

**Summary:** The tiff data type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffDataType

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| aligned_data_size | uint | r | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| count | uint | r | Λαμβάνει τον αριθμό των στοιχείων. |
| data_size | uint | r | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| id | ushort | r | Λαμβάνει την ακέραια αναπαράσταση του αναγνωριστικού ετικέτας. |
| is_valid | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της ετικέτας είναι έγκυρα. Η έγκυρη ετικέτα περιέχει δεδομένα που μπορούν να διατηρηθούν. Η μη έγκυρη ετικέτα δεν μπορεί να αποθηκευτεί. |
| tag_id | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | r | Λαμβάνει το αναγνωριστικό της ετικέτας. |
| tag_type | [TiffDataTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffdatatypes/) | r | Λαμβάνει τον τύπο της ετικέτας. |
| value | object | r/w | Λαμβάνει ή ορίζει την τιμή που περιέχει αυτός ο τύπος δεδομένων. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Συγκρίνει την τρέχουσα παρουσία με ένα άλλο αντικείμενο του ίδιου τύπου και επιστρέφει έναν ακέραιο που υποδεικνύει εάν η τρέχουσα παρουσία προηγείται, ακολουθεί ή βρίσκεται στην ίδια θέση στη σειρά ταξινόμησης με το άλλο αντικείμενο. |
| [deep_clone()](#deep_clone__2) | Δημιουργεί ένα βαθύ αντίγραφο αυτής της παρουσίασης. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_3) | Αναγνώνει τα δεδομένα της ετικέτας. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_4) | Γράφει τα πρόσθετα δεδομένα της ετικέτας. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_5) | Γράφει τα δεδομένα της ετικέτας. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Συγκρίνει την τρέχουσα παρουσία με ένα άλλο αντικείμενο του ίδιου τύπου και επιστρέφει έναν ακέραιο που υποδεικνύει εάν η τρέχουσα παρουσία προηγείται, ακολουθεί ή βρίσκεται στην ίδια θέση στη σειρά ταξινόμησης με το άλλο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| obj | object | Ένα αντικείμενο για σύγκριση με αυτήν την παρουσία. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ένας 32-bit υπογεγραμμένος ακέραιος που υποδεικνύει τη σχετική σειρά των αντικειμένων που συγκρίνονται. Η τιμή επιστροφής έχει τις ακόλουθες σημασίες:<br/>            Τιμή<br/>            Σημασία<br/>            Μικρότερο του μηδενός<br/>            Αυτή η παρουσία είναι μικρότερη από <paramref name="obj" />.<br/>            Μηδέν<br/>            Αυτή η παρουσία είναι ίση με <paramref name="obj" />.<br/>            Μεγαλύτερο του μηδενός<br/>            Αυτή η παρουσία είναι μεγαλύτερη από <paramref name="obj" />. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Δημιουργεί ένα βαθύ αντίγραφο αυτής της παρουσίασης.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Ένα βαθύ κλώνο της τρέχουσας παρουσίας. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_3}


```
 read_tag(data_stream, position) 
```

Αναγνώνει τα δεδομένα της ετικέτας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/) | Η ροή δεδομένων. |
| position | long | Η θέση της ετικέτας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype) | Η ετικέτα ανάγνωσης. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_4}


```
 write_additional_data(data_stream) 
```

Γράφει τα πρόσθετα δεδομένα της ετικέτας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Η ροή δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| long | Τα πραγματικά bytes που γράφτηκαν. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_5}


```
 write_tag(data_stream, additional_data_offset) 
```

Γράφει τα δεδομένα της ετικέτας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/psd/python-net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/) | Η ροή δεδομένων. |
| additional_data_offset | long | Η μετατόπιση για την εγγραφή πρόσθετων δεδομένων. |


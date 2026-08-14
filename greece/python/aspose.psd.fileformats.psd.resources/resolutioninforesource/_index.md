---
title: "ResolutionInfoResource Κλάση"
type: docs
weight: 230
url: /el/python-net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Summary:** The resolution info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ResolutionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ResolutionInfoResource()](#ResolutionInfoResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης ResolutionInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Η υπογραφή πόρου του ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Η κανονική υπογραφή πόρου του Photoshop. |
| data_size | int | r | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
| h_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | Οριζόντια DPI. |
| h_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | Μονάδες εμφάνισης για την οριζόντια ανάλυση.  Αυτό επηρεάζει μόνο το<br/>            περιβάλλον χρήστη· η ανάλυση εξακολουθεί να αποθηκεύεται στο αρχείο PSD<br/>            ως pixel/ίντσα. |
| height_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Λαμβάνει ή ορίζει τη μονάδα εμφάνισης ύψους. |
| id | short | r/w | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| minimal_version | int | r | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| name | string | r/w | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, συμπληρωμένη ώστε το μέγεθος να είναι άρτιο (ένα κενό όνομα αποτελείται από δύο byte τιμής 0). |
| signature | int | r | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει πάντα να είναι '8BIM'. |
| μέγεθος | int | r | Λαμβάνει το μέγεθος του μπλοκ πόρου σε byte, συμπεριλαμβανομένων των δεδομένων του. |
| v_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | Κάθετη DPI. |
| v_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | Μονάδες εμφάνισης για την κάθετη ανάλυση. |
| width_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Λαμβάνει ή ορίζει τη μονάδα εμφάνισης πλάτους. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream)](#save_stream_1) | Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή. |
| validate_values() | Επικυρώνει τις τιμές του πόρου. |


### Constructor: ResolutionInfoResource() {#ResolutionInfoResource__1}


```
 ResolutionInfoResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης ResolutionInfoResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Η ροή στην οποία θα αποθηκευτεί το μπλοκ πόρου. |


---
title: "GridAndGuidesResouce Κλάση"
type: docs
weight: 110
url: /el/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Η υπογραφή πόρου του ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Η κανονική υπογραφή πόρου του Photoshop. |
| data_size | int | r | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
| grid_cycle_x | int | r/w | Λαμβάνει ή ορίζει τον οριζόντιο κύκλο πλέγματος. Η προεπιλογή είναι 576. |
| grid_cycle_y | int | r/w | Λαμβάνει ή ορίζει τον κάθετο κύκλο πλέγματος. Η προεπιλογή είναι 576. |
| guide_count | int | r | Λαμβάνει τον αριθμό των μπλοκ πόρων οδηγών. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Λαμβάνει ή ορίζει τις οδηγίες. |
| header_version | int | r/w | Αποκτά ή ορίζει την έκδοση της κεφαλίδας. Αυτή η τιμή πρέπει πάντα να είναι 1. |
| id | short | r/w | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| minimal_version | int | r | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση psd. |
| name | string | r/w | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, συμπληρωμένη ώστε το μέγεθος να είναι άρτιο (ένα κενό όνομα αποτελείται από δύο byte τιμής 0). |
| signature | int | r | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει πάντα να είναι '8BIM'. |
| μέγεθος | int | r | Λαμβάνει το μέγεθος του μπλοκ πόρου σε byte, συμπεριλαμβανομένων των δεδομένων του. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream)](#save_stream_1) | Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή. |
| validate_values() | Επικυρώνει τις τιμές του πόρου. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Η ροή στην οποία θα αποθηκευτεί το μπλοκ πόρου. |


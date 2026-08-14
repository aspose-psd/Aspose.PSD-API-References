---
title: "UnknownResource Κλάση"
type: docs
weight: 280
url: /el/python-net/aspose.psd.fileformats.psd.resources/unknownresource/
---

**Summary:** The unknown resource. When a resource block is not recognized then this resource block is created.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.UnknownResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Η υπογραφή πόρου του ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Η κανονική υπογραφή πόρου του Photoshop. |
| δεδομένα | byte | r | Λαμβάνει τα δεδομένα του πόρου. |
| data_size | int | r | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
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


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Η ροή στην οποία θα αποθηκευτεί το μπλοκ πόρου. |


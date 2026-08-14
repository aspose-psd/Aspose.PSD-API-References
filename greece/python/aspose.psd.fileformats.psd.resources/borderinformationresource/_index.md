---
title: "BorderInformationResource Κλάση"
type: docs
weight: 30
url: /el/python-net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---

**Summary:** The resource with border information of image print settings.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.BorderInformationResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [BorderInformationResource()](#BorderInformationResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης BorderInformationResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Η υπογραφή πόρου του ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Η κανονική υπογραφή πόρου του Photoshop. |
| data_size | int | r | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
| id | short | r/w | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| minimal_version | int | r | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| name | string | r/w | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, συμπληρωμένη ώστε το μέγεθος να είναι άρτιο (ένα κενό όνομα αποτελείται από δύο byte τιμής 0). |
| signature | int | r | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει πάντα να είναι '8BIM'. |
| μέγεθος | int | r | Λαμβάνει το μέγεθος του μπλοκ πόρου σε byte, συμπεριλαμβανομένων των δεδομένων του. |
| unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | Λαμβάνει ή ορίζει τις μονάδες του περιγράμματος. |
| width | double | r/w | Λαμβάνει ή ορίζει το πλάτος του περιγράμματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream)](#save_stream_1) | Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή. |
| validate_values() | Επικυρώνει τις τιμές του πόρου. |


### Constructor: BorderInformationResource() {#BorderInformationResource__1}


```
 BorderInformationResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης BorderInformationResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Αποθηκεύει το μπλοκ πόρου στη συγκεκριμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Η ροή στην οποία θα αποθηκευτεί το μπλοκ πόρου. |


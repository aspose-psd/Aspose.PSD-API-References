---
title: "Κλάση ThumbnailResource"
type: docs
weight: 250
url: /el/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ThumbnailResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Η υπογραφή πόρου του ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Η κανονική υπογραφή πόρου του Photoshop. |
| bits_pixel | short | r/w | Λαμβάνει ή ορίζει τα bits ανά pixel. |
| data_size | int | r | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Λαμβάνει ή ορίζει τη μορφή δεδομένων μικρογραφίας. |
| height | int | r/w | Λαμβάνει ή ορίζει το ύψος της μικρογραφίας σε εικονοστοιχεία. |
| id | short | r/w | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Λαμβάνει ή ορίζει τις επιλογές JPEG. Κατάλληλο όταν ο πόρος μικρογραφίας αποθηκεύεται μόνο σε μορφή αρχείου JPEG. Αυτή η επιλογή δεν έχει καμία επίδραση όταν έχει οριστεί η μορφή RAW. |
| minimal_version | int | r | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση psd. |
| name | string | r/w | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, συμπληρωμένη ώστε το μέγεθος να είναι άρτιο (ένα κενό όνομα αποτελείται από δύο byte τιμής 0). |
| planes_count | short | r/w | Λαμβάνει ή ορίζει τον αριθμό των επιπέδων. |
| signature | int | r | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει πάντα να είναι '8BIM'. |
| μέγεθος | int | r | Λαμβάνει το μέγεθος του μπλοκ πόρου σε byte, συμπεριλαμβανομένων των δεδομένων του. |
| size_after_compression | int | r | Λαμβάνει ή ορίζει το μέγεθος μετά τη συμπίεση. Χρησιμοποιείται για έλεγχο συνέπειας. |
| thumbnail_argb_32_data | int | r/w | Λαμβάνει ή ορίζει τα δεδομένα μικρογραφίας ARGB 32-bit. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει τα δεδομένα μικρογραφίας. |
| total_size | int | r | Λαμβάνει το συνολικό μέγεθος δεδομένων. |
| width | int | r/w | Λαμβάνει ή ορίζει το πλάτος της μικρογραφίας σε εικονοστοιχεία. |
| width_bytes | int | r | Λαμβάνει το πλάτος γραμμής σε byte. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream)](#save_stream_1) | Αποθηκεύει τα δεδομένα του μπλοκ πόρων. |
| validate_values() | Επικυρώνει τις τιμές του πόρου. |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ThumbnailResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Αποθηκεύει τα δεδομένα του μπλοκ πόρων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |


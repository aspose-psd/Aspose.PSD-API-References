---
title: "Κλάση PattResourceData"
type: docs
weight: 780
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PattResourceData |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| height | short | r | Λαμβάνει το ύψος. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Επιστρέφει τη λειτουργία εικόνας. |
| μήκος | int | r | Επιστρέφει το μήκος του μοτίβου. |
| name | string | r/w | Επιστρέφει ή ορίζει το όνομα. |
| pattern_data | int | r | Επιστρέφει τα δεδομένα του μοτίβου. |
| pattern_id | string | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου. |
| version | int | r | Λαμβάνει την έκδοση. |
| width | short | r | Λαμβάνει το πλάτος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Αποθηκεύει τα δεδομένα του μοτίβου. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Ορίζει το μοτίβο. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PattResourceData

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Αποθηκεύει τα δεδομένα του μοτίβου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Ορίζει το μοτίβο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixels | int | Τα pixel. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Τα όρια. |


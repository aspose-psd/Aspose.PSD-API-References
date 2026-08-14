---
title: "Κλάση IImageLoaderDescriptor"
type: docs
weight: 1820
url: /el/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει τη υποστηριζόμενη μορφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Καθορίζει εάν ο φορτωτής εικόνας μπορεί να διαβάσει μια νέα εικόνα από το καθορισμένο ρεύμα και προαιρετικά χρησιμοποιώντας το <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Δημιουργεί ένα νέο αντικείμενο φορτωτή. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Καθορίζει εάν ο φορτωτής εικόνας μπορεί να διαβάσει μια νέα εικόνα από το καθορισμένο ρεύμα και προαιρετικά χρησιμοποιώντας το <paramref name="loadOptions" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι λεπτομέρειες μορφής αρχείου που καθορίζονται από το <paramref name="loadOptions" />. Το <paramref name="loadOptions" /> μπορεί να είναι null. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν ο φορτωτής εικόνας που δημιουργήθηκε από αυτόν τον περιγραφέα μπορεί να διαβάσει εικόνα από το ρεύμα· διαφορετικά, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Δημιουργεί ένα νέο αντικείμενο φορτωτή.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Ένα νέο αντικείμενο φορτωτή. |



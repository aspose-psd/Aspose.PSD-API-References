---
title: "IImageCreatorDescriptor Κλάση"
type: docs
weight: 1770
url: /el/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει τη υποστηριζόμενη μορφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Καθορίζει εάν ο δημιουργός εικόνας μπορεί να δημιουργήσει μια νέα εικόνα χρησιμοποιώντας το <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Δημιουργεί μια νέα παρουσία δημιουργού. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Καθορίζει εάν ο δημιουργός εικόνας μπορεί να δημιουργήσει μια νέα εικόνα χρησιμοποιώντας το <paramref name="imageOptions" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>True</c> εάν ο δημιουργός εικόνας που δημιουργείται από αυτόν τον περιγραφέα μπορεί να δημιουργήσει δεδομένα εικόνας χρησιμοποιώντας το καθορισμένο <paramref name="imageOptions" />· διαφορετικά, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Δημιουργεί μια νέα παρουσία δημιουργού.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Μια νέα παρουσία δημιουργού. |



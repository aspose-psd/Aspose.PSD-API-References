---
title: "IImageExporterDescriptor Κλάση"
type: docs
weight: 1800
url: /el/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει τη υποστηριζόμενη μορφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Καθορίζει εάν ο εξαγωγέας εικόνας μπορεί να εξάγει την καθορισμένη εικόνα στη καθορισμένη μορφή εικόνας που ορίζεται από τις επιλογές αποθήκευσης. |
| [create_instance()](#create_instance__2) | Δημιουργεί μια νέα παρουσία εξαγωγέα. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Καθορίζει εάν ο εξαγωγέας εικόνας μπορεί να εξάγει την καθορισμένη εικόνα στη καθορισμένη μορφή εικόνας που ορίζεται από τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα προς εξαγωγή. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Η βάση των επιλογών. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>True</c> εάν ο εξαγωγέας που δημιουργήθηκε από αυτόν τον περιγραφέα μπορεί να εξάγει την καθορισμένη εικόνα στη καθορισμένη μορφή αρχείου· διαφορετικά, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Δημιουργεί μια νέα παρουσία εξαγωγέα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Μια νέα παρουσία εξαγωγέα. |



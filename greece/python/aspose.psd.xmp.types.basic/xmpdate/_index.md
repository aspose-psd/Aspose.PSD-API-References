---
title: "XmpDate Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.psd.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.psd.xmp.types.basic](/psd/python-net/aspose.psd.xmp.types.basic/)

**Full Name:** aspose.psd.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/). |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | Η συμβολοσειρά μορφής ISO 8601 (roundtrip). |
| μορφή | string | r | Λαμβάνει τη συμβολοσειρά μορφής για την τρέχουσα τιμή. |
| value | datetime | r/w | Λαμβάνει ή ορίζει την τιμή της ημερομηνίας. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Επιστρέφει την τιμή της συμβολοσειράς σε μορφή XMP. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| date_string | string | Η συμβολοσειρά αναπαράστασης της ημερομηνίας. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| date_time | datetime | Μια τιμή ημερομηνίας-ώρας που αναπαρίσταται χρησιμοποιώντας ένα υποσύνολο της μορφοποίησης ISO RFC 8601. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Επιστρέφει την τιμή της συμβολοσειράς σε μορφή XMP.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει την τιμή της συμβολοσειράς σε μορφή XMP. |



---
title: "PdfPackage Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης PdfPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Λαμβάνει το URI του ονόματος χώρου. |
| πρόθεμα | string | r | Λαμβάνει το πρόθεμα. |
| xml_namespace | string | r | Λαμβάνει το χώρο ονομάτων XML. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Προσθέτει ιδιότητα συμβολοσειράς. |
| clear() | Καθαρίζει αυτήν την παρουσία. |
| [contains_key(key)](#contains_key_key_2) | Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί. |
| [get_xml_value()](#get_xml_value__3) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [remove(key)](#remove_key_4) | Αφαιρεί την τιμή με το καθορισμένο κλειδί. |
| [set_keywords(keywords)](#set_keywords_keywords_5) | Ορίζει τις λέξεις-κλειδιά. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Ορίζει την έκδοση PDF. |
| [set_producer(producer)](#set_producer_producer_7) | Ορίζει το όνομα του εργαλείου που δημιούργησε το Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Ορίζει το trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Ορίζει την τιμή. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Ορίζει την τιμή τύπου XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης PdfPackage

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Προσθέτει ιδιότητα συμβολοσειράς.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | string | Η τιμή συμβολοσειράς. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Το κλειδί που θα ελεγχθεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Επιστρέφει true εάν το καθορισμένο κλειδί περιέχει το κλειδί. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Μετατρέπει την τιμή XMP στην αναπαράσταση XML.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει την τιμή XMP μετατρεπόμενη στην αναπαράσταση XML. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Αφαιρεί την τιμή με το καθορισμένο κλειδί.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την αφαιρεθείσα τιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Επιστρέφει true εάν η τιμή με το καθορισμένο κλειδί αφαιρέθηκε. |


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Ορίζει τις λέξεις-κλειδιά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| λέξεις-κλειδιά | string | Οι λέξεις-κλειδιά. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Ορίζει την έκδοση PDF.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| version | string | Έκδοση Pdf, για παράδειγμα: 1.0, 1.3 κ.λπ. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Ορίζει το όνομα του εργαλείου που δημιούργησε το Pdf.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| παραγωγός | string | Το όνομα του παραγωγού. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Ορίζει το trapped.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| is_trapped | bool | αν οριστεί σε <c>true</c> το έγγραφο έχει γίνει trapped. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Ορίζει την τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Η τιμή για προσθήκη σε. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Ορίζει την τιμή τύπου XMP.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την ορισμένη τιμή. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Η τιμή για ορισμό σε. |


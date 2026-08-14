---
title: "XmpPackage Κλάση"
type: docs
weight: 430
url: /el/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Λαμβάνει το URI του ονόματος χώρου. |
| πρόθεμα | string | r | Λαμβάνει το πρόθεμα. |
| xml_namespace | string | r | Λαμβάνει το χώρο ονομάτων XML. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Προσθέτει την τιμή. |
| clear() | Καθαρίζει αυτήν την παρουσία. |
| [contains_key(key)](#contains_key_key_2) | Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί. |
| [get_xml_value()](#get_xml_value__3) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [remove(key)](#remove_key_4) | Αφαιρεί την τιμή με το καθορισμένο κλειδί. |
| [set_value(key, value)](#set_value_key_value_5) | Ορίζει την τιμή. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Ορίζει την τιμή τύπου XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Προσθέτει την τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | string | Η τιμή για προσθήκη σε. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Ορίζει την τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η συμβολοσειρά αναπαράστασης του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Η τιμή για προσθήκη σε. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Ορίζει την τιμή τύπου XMP.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | string | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την ορισμένη τιμή. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Η τιμή για ορισμό σε. |


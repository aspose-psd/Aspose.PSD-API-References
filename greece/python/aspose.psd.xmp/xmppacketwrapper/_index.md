---
title: "XmpPacketWrapper Κλάση"
type: docs
weight: 450
url: /el/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Αρχικοποιεί μια νέα παρουσία της [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) κλάσης. |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Αρχικοποιεί μια νέα παρουσία της [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) κλάσης. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Αποκτά την εντολή επεξεργασίας του κεφαλίδας. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Αποκτά τα μεταδεδομένα XMP. Προαιρετικό. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Αποκτά τον πίνακα των [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) μέσα στο XMP. |
| packages_count | int | r | Αποκτά τον αριθμό των πακέτων μέσα στη δομή XMP. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Αποκτά την εντολή επεξεργασίας του τερματικού. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Προσθέτει το πακέτο. |
| clear_packages() | Αφαιρεί όλα τα [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) μέσα στο XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Καθορίζει αν το πακέτο υπάρχει στο xmp wrapper. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Αποκτά το πακέτο με βάση το namespace URI. |
| [remove_package(package)](#remove_package_package_4) | Αφαιρεί το πακέτο XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Αρχικοποιεί μια νέα παρουσία της [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) κλάσης.

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Αρχικοποιεί μια νέα παρουσία της [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) κλάσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | Η κεφαλίδα XMP της εντολής επεξεργασίας. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | Το τερματικό XMP της εντολής επεξεργασίας. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | Τα μεταδεδομένα XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Προσθέτει το πακέτο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Το πακέτο. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Καθορίζει αν το πακέτο υπάρχει στο xmp wrapper.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| namespace_uri | string | URI σχήματος πακέτου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Επιστρέφει true εάν το πακέτο με το συγκεκριμένο namespace Uri υπάρχει στο XMP wrapper. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Αποκτά το πακέτο με βάση το namespace URI.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| namespace_uri | string | Το URI του σχήματος του πακέτου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Επιστρέφει το πακέτο XMP για το καθορισμένο URI ονοματοχώρου. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Αφαιρεί το πακέτο XMP.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Το πακέτο. |


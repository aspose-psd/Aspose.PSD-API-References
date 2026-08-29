---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιέχει σειριοποιημένο πακέτο xmp, συμπεριλαμβανομένης της κεφαλίδας και του τέλους."
type: docs
weight: 20
url: /el/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Περιέχει σειριοποιημένο πακέτο xmp, συμπεριλαμβανομένης της κεφαλίδας και του τέλους.

Ένας περιτύλιγμα που αποτελείται από ένα ζεύγος οδηγιών επεξεργασίας XML (PIs) μπορεί να τοποθετηθεί γύρω από το στοιχείο rdf:RDF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  XmpPacketWrapper . |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  XmpPacketWrapper . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Προσθέτει το πακέτο. |
| [clearPackages()](#clearPackages--) | Αφαιρεί όλα τα  XmpPackage  μέσα στο XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Καθορίζει εάν το πακέτο υπάρχει στο περιτύλιγμα xmp. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Λαμβάνει την οδηγία επεξεργασίας της κεφαλίδας. |
| [getMeta()](#getMeta--) | Λαμβάνει τα μεταδεδομένα XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Λαμβάνει το πακέτο με βάση το URI του χώρου ονομάτων. |
| [getPackages()](#getPackages--) | Λαμβάνει τον πίνακα των  XmpPackage  μέσα στο XMP. |
| [getPackagesCount()](#getPackagesCount--) | Λαμβάνει τον αριθμό των πακέτων μέσα στη δομή XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Λαμβάνει το ριζικό στοιχείο RDF. |
| [getTrailerPi()](#getTrailerPi--) | Λαμβάνει την οδηγία επεξεργασίας του trailer. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Αφαιρεί το πακέτο XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Ορίζει την οδηγία επεξεργασίας της κεφαλίδας. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Ορίζει τα μεταδεδομένα XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Ορίζει το ριζικό στοιχείο RDF. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Ορίζει την οδηγία επεξεργασίας του trailer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  XmpPacketWrapper .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Η κεφαλίδα XMP της οδηγίας επεξεργασίας. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Η υποσέλιδο XMP της οδηγίας επεξεργασίας. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Τα μεταδεδομένα XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  XmpPacketWrapper .

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Προσθέτει το πακέτο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Το πακέτο. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Αφαιρεί όλα τα  XmpPackage  μέσα στο XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Καθορίζει εάν το πακέτο υπάρχει στο περιτύλιγμα xmp.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI σχήματος πακέτου. |

**Returns:**
boolean - Επιστρέφει true εάν υπάρχει πακέτο με το καθορισμένο namespace Uri στο XMP wrapper.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Λαμβάνει την οδηγία επεξεργασίας της κεφαλίδας.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Αποκτά το XMP meta. Προαιρετικό.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Λαμβάνει το πακέτο με βάση το URI του χώρου ονομάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| namespaceUri | java.lang.String | Το URI σχήματος πακέτου. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Λαμβάνει τον πίνακα των  XmpPackage  μέσα στο XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - Ο πίνακας των XmpPackage μέσα στο XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Λαμβάνει τον αριθμό των πακέτων μέσα στη δομή XMP.

**Returns:**
int - Ο αριθμός των πακέτων μέσα στη δομή XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Λαμβάνει το ριζικό στοιχείο RDF.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Λαμβάνει την οδηγία επεξεργασίας του trailer.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Μετατρέπει την τιμή XMP στην αναπαράσταση XML.

**Returns:**
java.lang.String - Επιστρέφει τη μετατρεπόμενη τιμή XMP σε XML.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Αφαιρεί το πακέτο XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Το πακέτο. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Ορίζει την οδηγία επεξεργασίας της κεφαλίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Η Επικεφαλίδα της οδηγίας επεξεργασίας. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Ορίζει το XMP meta. Προαιρετικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Το XMP meta. Προαιρετικό. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Ορίζει το ριζικό στοιχείο RDF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | Το στοιχείο ρίζας RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Ορίζει την οδηγία επεξεργασίας του trailer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Οδηγία επεξεργασίας υποσέλιδου. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


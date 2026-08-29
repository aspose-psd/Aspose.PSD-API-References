---
title: "XmpBasicPackage"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά το βασικό χώρο ονομάτων XMP."
type: docs
weight: 10
url: /el/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Αναπαριστά το βασικό χώρο ονομάτων XMP.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης  XmpBasicPackage  . |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης  XmpBasicPackage  . |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [RatingMax](#RatingMax) | Μέγιστη τιμή αξιολόγησης. |
| [RatingMin](#RatingMin) | Ελάχιστη τιμή αξιολόγησης. |
| [RatingRejected](#RatingRejected) | Απορριπτέα τιμή αξιολόγησης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Προσθέτει το namespace του σύνθετου τύπου. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Προσθέτει ιδιότητα τύπου string. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Αναθέτει το καθορισμένο πακέτο XMP στο τρέχον. |
| [clear()](#clear--) | Καθαρίζει αυτό το αντικείμενο. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Συνδυάζει το πακέτο. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Λαμβάνει τα κλειδιά στο πακέτο XMP. |
| [getNamespaceUri()](#getNamespaceUri--) | Λαμβάνει το URI του χώρου ονομάτων. |
| [getPrefix()](#getPrefix--) | Ανακτά το πρόθεμα. |
| [getXmlNamespace()](#getXmlNamespace--) | Λαμβάνει το χώρο ονομάτων XML. |
| [getXmlValue()](#getXmlValue--) | Μετατρέπει την τιμή XMP στην αναπαράσταση XML. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Ανακτά ή ορίζει το Object με το καθορισμένο κλειδί. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Αφαιρέστε την τιμή με το συγκεκριμένο κλειδί. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Προσθέτει την ημερομηνία δημιουργίας του πόρου. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Προσθέτει την ημερομηνία δημιουργίας του πόρου. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Ορίζει το εργαλείο δημιουργού. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Ορίζει το αναγνωριστικό. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Ορίζει την ετικέτα. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Προσθέτει την ημερομηνία τελευταίας αλλαγής των μεταδεδομένων. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Προσθέτει την ημερομηνία τελευταίας αλλαγής των μεταδεδομένων. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Προσθέτει την ημερομηνία τελευταίας τροποποίησης του πόρου. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Προσθέτει την ημερομηνία τελευταίας τροποποίησης του πόρου. |
| [setRating(int choise)](#setRating-int-) | Ορίζει την αξιολόγηση. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Ορίζει την τιμή. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Ορίζει την λογική τιμή του XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Ορίζει το μοναδικό αναγνωριστικό του XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Ορίζει την τιμή τύπου του XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Ανακτά ή ορίζει το Object με το καθορισμένο κλειδί. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης  XmpBasicPackage  .

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης  XmpBasicPackage  .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πρόθεμα | java.lang.String | Το πρόθεμα. |
| namespaceUri | java.lang.String | Το URI του χώρου ονομάτων. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Μέγιστη τιμή αξιολόγησης.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Ελάχιστη τιμή αξιολόγησης.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Απορριπτέα τιμή αξιολόγησης.

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Προσθέτει το namespace του σύνθετου τύπου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typePrefix | java.lang.String | Το πρόθεμα τύπου. |
| typeNamespaceUri | java.lang.String | Το URI του χώρου ονομάτων τύπου. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Προσθέτει ιδιότητα τύπου string.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| τιμή | java.lang.String | Η τιμή συμβολοσειράς. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Αναθέτει το καθορισμένο πακέτο XMP στο τρέχον.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Το πακέτο XMP. |

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει αυτό το αντικείμενο.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Συνδυάζει το πακέτο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Το άλλο πακέτο για συνδυασμό. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Καθορίζει εάν το καθορισμένο κλειδί περιέχει το κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί που θα ελεγχθεί. |

**Returns:**
boolean - Επιστρέφει true εάν το καθορισμένο κλειδί περιέχει το κλειδί.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Λαμβάνει τα κλειδιά στο πακέτο XMP.

Τιμή: Τα κλειδιά στο πακέτο XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Λαμβάνει το URI του χώρου ονομάτων.

Τιμή: Το URI του χώρου ονομάτων.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ανακτά το πρόθεμα.

Τιμή: Το πρόθεμα.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Λαμβάνει το χώρο ονομάτων XML.

Τιμή: Ο χώρος ονομάτων XML.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Μετατρέπει την τιμή XMP στην αναπαράσταση XML.

**Returns:**
java.lang.String - Επιστρέφει την τιμή XMP μετατρεπόμενη στην αναπαράσταση XML.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Ανακτά ή ορίζει το Object με το καθορισμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί που προσδιορίζει την τιμή. Τιμή: Το Object. |

**Returns:**
java.lang.Object - Επιστρέφει το Object με το καθορισμένο κλειδί.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Ένα  T:System.Collections.Generic.IEnumerator1  που μπορεί να χρησιμοποιηθεί για επανάληψη στη συλλογή.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Αφαιρέστε την τιμή με το συγκεκριμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την αφαιρεμένη τιμή. |

**Returns:**
boolean - Επιστρέφει true εάν η τιμή με το καθορισμένο κλειδί αφαιρέθηκε.
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Προσθέτει την ημερομηνία δημιουργίας του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createdDate | java.lang.String | Ημερομηνία δημιουργίας. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Προσθέτει την ημερομηνία δημιουργίας του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Ημερομηνία δημιουργίας. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Ορίζει το εργαλείο δημιουργού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| creatorTool | java.lang.String | Όνομα εργαλείου. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Ορίζει το αναγνωριστικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αναγνωριστικό | java.lang.String[] | Το αναγνωριστικό. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Ορίζει την ετικέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ετικέτα | java.lang.String | Η ετικέτα. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Προσθέτει την ημερομηνία τελευταίας αλλαγής των μεταδεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| metadataDate | java.lang.String | Ημερομηνία μεταδεδομένων. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Προσθέτει την ημερομηνία τελευταίας αλλαγής των μεταδεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Ημερομηνία μεταδεδομένων. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Προσθέτει την ημερομηνία τελευταίας τροποποίησης του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| modifiedDate | java.lang.String | Τελευταία ημερομηνία τροποποίησης. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Προσθέτει την ημερομηνία τελευταίας τροποποίησης του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Τελευταία ημερομηνία τροποποίησης. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Ορίζει την αξιολόγηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επιλογή | int | Από -1 έως 5 |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Ορίζει την τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | Η τιμή προς προσθήκη. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Ορίζει την λογική τιμή του XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την ορισμένη τιμή. |
| boolValue | java.lang.String | Η λογική τιμή. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Ορίζει το μοναδικό αναγνωριστικό του XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την ορισμένη τιμή GUID. |
| guid | java.lang.String | Το μοναδικό αναγνωριστικό. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Ορίζει την τιμή τύπου του XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την ορισμένη τιμή. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | Η τιμή στην οποία θα οριστεί. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Ανακτά ή ορίζει το Object με το καθορισμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί που προσδιορίζει την τιμή. Τιμή: Το Object. |
| τιμή | java.lang.Object |  |

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


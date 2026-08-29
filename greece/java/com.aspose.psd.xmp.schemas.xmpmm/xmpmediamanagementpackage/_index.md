---
title: "XmpMediaManagementPackage"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά το χώρο ονομάτων XMP Media Management."
type: docs
weight: 10
url: /el/java/com.aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class XmpMediaManagementPackage extends XmpPackage
```

Αναπαριστά το χώρο ονομάτων XMP Media Management.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης XmpMediaManagementPackage. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Λαμβάνει ή ορίζει το  Object  με το συγκεκριμένο κλειδί. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Αφαιρέστε την τιμή με το συγκεκριμένο κλειδί. |
| [setDerivedFrom(ResourceRef resourceRef)](#setDerivedFrom-com.aspose.psd.xmp.types.complex.resourceref.ResourceRef-) | Ορίζει το derived from. |
| [setDocumentId(String guid)](#setDocumentId-java.lang.String-) | Ορίζει το αναγνωριστικό του εγγράφου. |
| [setDocumentId(UUID guid)](#setDocumentId-java.util.UUID-) | Ορίζει το αναγνωριστικό του εγγράφου. |
| [setDocumentId_internalized(System.Guid guid)](#setDocumentId-internalized-com.aspose.ms.System.Guid-) |  |
| [setInstanceId(String guid)](#setInstanceId-java.lang.String-) | Ορίζει το instance id. |
| [setInstanceId(UUID guid)](#setInstanceId-java.util.UUID-) | Ορίζει το instance id. |
| [setInstanceId_internalized(System.Guid guid)](#setInstanceId-internalized-com.aspose.ms.System.Guid-) |  |
| [setOriginalDocumentId(String guid)](#setOriginalDocumentId-java.lang.String-) | Ορίζει το αρχικό αναγνωριστικό εγγράφου. |
| [setOriginalDocumentId(UUID guid)](#setOriginalDocumentId-java.util.UUID-) | Ορίζει το αρχικό αναγνωριστικό εγγράφου. |
| [setOriginalDocumentId_internalized(System.Guid guid)](#setOriginalDocumentId-internalized-com.aspose.ms.System.Guid-) |  |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Ορίζει την τιμή. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Ορίζει την λογική τιμή του XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Ορίζει το μοναδικό αναγνωριστικό του XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Ορίζει την τιμή τύπου του XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Ορίζει το  Object  με το καθορισμένο κλειδί. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMediaManagementPackage() {#XmpMediaManagementPackage--}
```
public XmpMediaManagementPackage()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης XmpMediaManagementPackage.

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


Λαμβάνει ή ορίζει το  Object  με το συγκεκριμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί που προσδιορίζει την τιμή. |

**Returns:**
java.lang.Object - Επιστρέφει το  Object  με το καθορισμένο κλειδί.
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
### setDerivedFrom(ResourceRef resourceRef) {#setDerivedFrom-com.aspose.psd.xmp.types.complex.resourceref.ResourceRef-}
```
public void setDerivedFrom(ResourceRef resourceRef)
```


Ορίζει το derived from.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceRef | [ResourceRef](../../com.aspose.psd.xmp.types.complex.resourceref/resourceref) | Η αναφορά πόρου. |

### setDocumentId(String guid) {#setDocumentId-java.lang.String-}
```
public void setDocumentId(String guid)
```


Ορίζει το αναγνωριστικό του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | java.lang.String | Το μοναδικό αναγνωριστικό. |

### setDocumentId(UUID guid) {#setDocumentId-java.util.UUID-}
```
public void setDocumentId(UUID guid)
```


Ορίζει το αναγνωριστικό του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | java.util.UUID | Το μοναδικό αναγνωριστικό. |

### setDocumentId_internalized(System.Guid guid) {#setDocumentId-internalized-com.aspose.ms.System.Guid-}
```
public void setDocumentId_internalized(System.Guid guid)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

### setInstanceId(String guid) {#setInstanceId-java.lang.String-}
```
public void setInstanceId(String guid)
```


Ορίζει το instance id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | java.lang.String | Το μοναδικό αναγνωριστικό. |

### setInstanceId(UUID guid) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID guid)
```


Ορίζει το instance id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | java.util.UUID | Το μοναδικό αναγνωριστικό. |

### setInstanceId_internalized(System.Guid guid) {#setInstanceId-internalized-com.aspose.ms.System.Guid-}
```
public void setInstanceId_internalized(System.Guid guid)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

### setOriginalDocumentId(String guid) {#setOriginalDocumentId-java.lang.String-}
```
public void setOriginalDocumentId(String guid)
```


Ορίζει το αρχικό αναγνωριστικό εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | java.lang.String | Το μοναδικό αναγνωριστικό. |

### setOriginalDocumentId(UUID guid) {#setOriginalDocumentId-java.util.UUID-}
```
public void setOriginalDocumentId(UUID guid)
```


Ορίζει το αρχικό αναγνωριστικό εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | java.util.UUID | Το μοναδικό αναγνωριστικό. |

### setOriginalDocumentId_internalized(System.Guid guid) {#setOriginalDocumentId-internalized-com.aspose.ms.System.Guid-}
```
public void setOriginalDocumentId_internalized(System.Guid guid)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

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


Ορίζει το  Object  με το καθορισμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί που προσδιορίζει την τιμή. |
| τιμή | java.lang.Object | Η τιμή του  Object  . |

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


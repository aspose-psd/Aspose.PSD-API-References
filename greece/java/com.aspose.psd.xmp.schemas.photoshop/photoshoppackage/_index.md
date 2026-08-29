---
title: "PhotoshopPackage"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει το namespace του Adobe Photoshop."
type: docs
weight: 12
url: /el/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Αντιπροσωπεύει το namespace του Adobe Photoshop.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PhotoshopPackage. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Μέγιστη τιμή επείγοντος. |
| [UrgencyMin](#UrgencyMin) | Ελάχιστη τιμή επείγοντος. |
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
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Ορίζει τη θέση των συγγραφέων. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Ορίζει τον συγγραφέα της λεζάντας. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Ορίζει την κατηγορία. |
| [setCity(String city)](#setCity-java.lang.String-) | Ορίζει την πόλη. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Ορίζει τη λειτουργία χρώματος. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Ορίζει τη χώρα. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Ορίζει την ημερομηνία δημιουργίας. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Ορίζει την αναφορά. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Ορίζει τους προγόνους του εγγράφου. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Ορίζει την επικεφαλίδα. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Ορίζει το ιστορικό. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | Ορίζει το προφίλ icc. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Ορίζει τις οδηγίες. |
| [setSource(String source)](#setSource-java.lang.String-) | Ορίζει την πηγή. |
| [setState(String state)](#setState-java.lang.String-) | Ορίζει την πολιτεία. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Ορίζει συμπληρωματικές κατηγορίες. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | Ορίζει την αναφορά μετάδοσης. |
| [setUrgency(int urgency)](#setUrgency-int-) | Ορίζει την επείγουσα κατάσταση. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Ορίζει την τιμή. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Ορίζει την λογική τιμή του XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Ορίζει το μοναδικό αναγνωριστικό του XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Ορίζει την τιμή τύπου του XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Ορίζει το  Object  με το καθορισμένο κλειδί. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PhotoshopPackage.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Μέγιστη τιμή επείγοντος.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Ελάχιστη τιμή επείγοντος.

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Ορίζει τη θέση των συγγραφέων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| authorsPosition | java.lang.String | Η θέση των συγγραφέων. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Ορίζει τον συγγραφέα της λεζάντας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| captionWriter | java.lang.String | Ο δημιουργός λεζάντας. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Ορίζει την κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| category | java.lang.String | Η κατηγορία. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Ορίζει την πόλη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| city | java.lang.String | Το όνομα της πόλης. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Ορίζει τη λειτουργία χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorMode | byte | Η λειτουργία χρώματος. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Ορίζει τη χώρα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| country | java.lang.String | Η χώρα. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Ορίζει την ημερομηνία δημιουργίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createdDate | java.util.Date | Η ημερομηνία δημιουργίας. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Ορίζει την αναφορά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| credit | java.lang.String | Η πίστωση. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Ορίζει τους προγόνους του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ancestors | java.lang.String[] | Οι πρόγονοι. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Ορίζει την επικεφαλίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| headline | java.lang.String | Ο τίτλος. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Ορίζει το ιστορικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| history | java.lang.String | Το ιστορικό. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


Ορίζει το προφίλ icc.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iccProfile | java.lang.String | Το προφίλ icc. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Ορίζει τις οδηγίες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| οδηγίες | java.lang.String | Οι οδηγίες. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Ορίζει την πηγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πηγή | java.lang.String | Η πηγή. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Ορίζει την πολιτεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κατάσταση | java.lang.String | Η κατάσταση. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Ορίζει συμπληρωματικές κατηγορίες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | Οι συμπληρωματικές κατηγορίες. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


Ορίζει την αναφορά μετάδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| transmissionReference | java.lang.String | Η αναφορά μετάδοσης. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Ορίζει την επείγουσα κατάσταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επείγον | int | Το επείγον. |

Το επείγον πρέπει να είναι σε εύρος από 1 έως 8. |

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


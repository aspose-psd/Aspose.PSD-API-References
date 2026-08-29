---
title: "ResourceEvent"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιέχει διαστάσεις για ένα σχεδιασμένο αντικείμενο."
type: docs
weight: 10
url: /el/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Περιέχει διαστάσεις για ένα σχεδιασμένο αντικείμενο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Αρχικοποιεί μια νέα παρουσία της  ResourceEvent  class. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Προσθέτει το καθορισμένο κλειδί. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Λαμβάνει τη δράση. |
| [getActionDate()](#getActionDate--) | Λαμβάνει ή ορίζει την ημερομηνία δράσης. |
| [getChanged()](#getChanged--) | Λαμβάνει τη λίστα διαχωρισμένη με ερωτηματικό των τμημάτων του πόρου που άλλαξαν από την προηγούμενη ιστορία συμβάντων. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Λαμβάνει την τιμή του xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Ανακτά το προεπιλεγμένο URI του χώρου ονομάτων. |
| [getParameters()](#getParameters--) | Λαμβάνει ή ορίζει την πρόσθετη περιγραφή της δράσης. |
| [getPrefix()](#getPrefix--) | Ανακτά το πρόθεμα. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Λαμβάνει ή ορίζει το όνομα του λογισμικού πράκτορα. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Ορίζει τη δράση. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Λαμβάνει ή ορίζει την ημερομηνία δράσης. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Ορίζει τη λίστα διαχωρισμένη με ερωτηματικό των τμημάτων του πόρου που άλλαξαν από την προηγούμενη ιστορία συμβάντων. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Λαμβάνει ή ορίζει την τιμή του xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Λαμβάνει ή ορίζει την πρόσθετη περιγραφή της δράσης. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του λογισμικού πράκτορα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Αρχικοποιεί μια νέα παρουσία της  ResourceEvent  class.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Προσθέτει το καθορισμένο κλειδί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Η αναπαράσταση συμβολοσειράς του κλειδιού που προσδιορίζεται με την προστιθέμενη τιμή. |
| τιμή | java.lang.Object | Η τιμή προς προσθήκη. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Λαμβάνει τη δράση.

Οι καθορισμένες τιμές είναι: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Οι νέες τιμές πρέπει να είναι ρήματα σε αόριστο χρόνο.

**Returns:**
java.lang.String - Η δράση.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Λαμβάνει ή ορίζει την ημερομηνία δράσης.

**Returns:**
java.util.Date - Η ημερομηνία δράσης.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Λαμβάνει τη λίστα διαχωρισμένη με ερωτηματικό των τμημάτων του πόρου που άλλαξαν από την προηγούμενη ιστορία συμβάντων.

**Returns:**
java.lang.String - Η λίστα διαχωρισμένη με ερωτηματικό των τμημάτων του πόρου που άλλαξαν από την προηγούμενη ιστορία συμβάντων.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Λαμβάνει την τιμή του xmpMM:InstanceId.

**Returns:**
java.util.UUID - Η τιμή του xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ανακτά το προεπιλεγμένο URI του χώρου ονομάτων.

**Returns:**
java.lang.String - Η προεπιλεγμένη διεύθυνση URI του ονοματοχώρου.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Λαμβάνει ή ορίζει την πρόσθετη περιγραφή της δράσης.

Τιμή: Η πρόσθετη περιγραφή της ενέργειας.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ανακτά το πρόθεμα.

**Returns:**
java.lang.String - Το πρόθεμα.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Λαμβάνει ή ορίζει το όνομα του λογισμικού πράκτορα.

**Returns:**
java.lang.String - Το όνομα του λογισμικού πράκτορα.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Λαμβάνει την τιμή συμβολοσειράς σε μορφή XMP.

**Returns:**
java.lang.String - Επιστρέφει την τιμή συμβολοσειράς σε μορφή XMP.
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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Ορίζει τη δράση.

Οι καθορισμένες τιμές είναι: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Οι νέες τιμές πρέπει να είναι ρήματα σε αόριστο χρόνο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Η ενέργεια. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Λαμβάνει ή ορίζει την ημερομηνία δράσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Date | Η ημερομηνία της ενέργειας. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Ορίζει τη λίστα διαχωρισμένη με ερωτηματικό των τμημάτων του πόρου που άλλαξαν από την προηγούμενη ιστορία συμβάντων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Η λίστα διαχωρισμένη με άνω τελεία των τμημάτων του πόρου που άλλαξαν από το προηγούμενο ιστορικό συμβάντων. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Λαμβάνει ή ορίζει την τιμή του xmpMM:InstanceId.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID | Η τιμή του xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Λαμβάνει ή ορίζει την πρόσθετη περιγραφή της δράσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Η πρόσθετη περιγραφή της ενέργειας. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Λαμβάνει ή ορίζει το όνομα του λογισμικού πράκτορα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Το όνομα του λογισμικού πράκτορα. |

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


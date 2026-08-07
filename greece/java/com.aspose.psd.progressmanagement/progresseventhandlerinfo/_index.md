---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αυτή η κλάση αντιπροσωπεύει πληροφορίες σχετικά με την πρόοδο των λειτουργιών φόρτωσης/αποθήκευσης/εξαγωγής εικόνας που μπορούν να χρησιμοποιηθούν σε εξωτερική εφαρμογή για την εμφάνιση της προόδου της μετατροπής στον τελικό χρήστη."
type: docs
weight: 10
url: /el/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Αυτή η κλάση αντιπροσωπεύει πληροφορίες σχετικά με την πρόοδο των λειτουργιών φόρτωσης/αποθήκευσης/εξαγωγής εικόνας, οι οποίες μπορούν να χρησιμοποιηθούν σε εξωτερική εφαρμογή για την εμφάνιση της προόδου της μετατροπής στον τελικό χρήστη.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Προσθέτει τον διαχειριστή γεγονότος προόδου. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Αποκτά την περιγραφή του γεγονότος |
| [getEventType()](#getEventType--) | Αποκτά τον τύπο του γεγονότος. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Αποκτά τον πιο πρόσφατο διαχειριστή γεγονότος προόδου. |
| [getMaxValue()](#getMaxValue--) | Αποκτά το άνω όριο τιμής προόδου. |
| [getValue()](#getValue--) | Αποκτά την τρέχουσα τιμή προόδου. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Δείχνει την πρόοδο. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Δείχνει την πρόοδο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Το άνω όριο τιμής προόδου. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Τρέχουσα τιμή προόδου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Προσθέτει τον διαχειριστή γεγονότος προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Ο διαχειριστής γεγονότος προόδου. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σύνολο | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Αποκτά την περιγραφή του γεγονότος

Τιμή: Η περιγραφή.

**Returns:**
java.lang.String - η περιγραφή του γεγονότος
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Αποκτά τον τύπο του γεγονότος.

Τιμή: Ο τύπος του γεγονότος.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Αποκτά τον πιο πρόσφατο διαχειριστή γεγονότος προόδου.

Τιμή: Ο πιο πρόσφατος διαχειριστής γεγονότος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Αποκτά το άνω όριο τιμής προόδου.

Τιμή: Το άνω όριο τιμής προόδου.

**Returns:**
int - το άνω όριο τιμής προόδου.
### getValue() {#getValue--}
```
public final int getValue()
```


Αποκτά την τρέχουσα τιμή προόδου.

Τιμή: Η τιμή προόδου.

**Returns:**
int - τρέχουσα τιμή προόδου.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


Δείχνει την πρόοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Τύπος του γεγονότος. |

**Returns:**
boolean - true αν είναι επιτυχές, false διαφορετικά
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Δείχνει την πρόοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Τύπος του γεγονότος. |
| τιμή | int | Η τιμή. |

**Returns:**
boolean - true αν είναι επιτυχές, false διαφορετικά
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


Το άνω όριο τιμής προόδου.

Τιμή: Το άνω όριο τιμής προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | το άνω όριο τιμής προόδου. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Τρέχουσα τιμή προόδου.

Τιμή: Η τιμή προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | τρέχουσα τιμή προόδου. |

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


---
title: "ColorComponent"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το συστατικό χρώματος είναι μια αφαίρεση πάνω στην Τιμή Καναλιού και την Τιμή Καναλιού."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Το συστατικό χρώματος είναι μια αφαίρεση πάνω από το Channel Value και το Channel Value. Κάθε χρώμα αποτελείται από έναν πίνακα των ColorComponent
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Λαμβάνει το βάθος bit του Συστατικού Χρώματος/Καναλιού |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Λαμβάνει την περιγραφή του Συστατικού Χρώματος |
| [getFullName()](#getFullName--) | Λαμβάνει το πλήρες όνομα του συστατικού χρώματος με το όνομα και την περιγραφή χωρισμένη με κενά |
| [getName()](#getName--) | Λαμβάνει το όνομα του συστατικού χρώματος. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Λαμβάνει τα επιτρεπόμενα πλήρη ονόματα. |
| [getValue()](#getValue--) | Αποκτά ή ορίζει την τιμή. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Αποκτά ή ορίζει την τιμή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Παρακαλώ ελέγξτε

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitDepth | byte | Το βάθος bit. |
| fullName | java.lang.String | Το πλήρες όνομα. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Λαμβάνει το βάθος bit του Συστατικού Χρώματος/Καναλιού

Τιμή: Το βάθος bit.

**Returns:**
byte
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


Λαμβάνει την περιγραφή του Συστατικού Χρώματος

Τιμή: Η περιγραφή.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Λαμβάνει το πλήρες όνομα του συστατικού χρώματος με το όνομα και την περιγραφή χωρισμένη με κενά

Τιμή: Το πλήρες όνομα.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα του συστατικού χρώματος.

Τιμή: Το όνομα.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Λαμβάνει τα επιτρεπόμενα πλήρη ονόματα.

Τιμή: Τα επιτρεπόμενα πλήρη ονόματα.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Λαμβάνει ή ορίζει την τιμή. Παρακαλώ σημειώστε, εάν προσπαθήσετε να ορίσετε τιμή που είναι μεγαλύτερη από αυτή που μπορεί να αποθηκευτεί στο τρέχον βάθος bit, θα λάβετε μια εξαίρεση.

Value: Η τιμή.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Λαμβάνει ή ορίζει την τιμή. Παρακαλώ σημειώστε, εάν προσπαθήσετε να ορίσετε τιμή που είναι μεγαλύτερη από αυτή που μπορεί να αποθηκευτεί στο τρέχον βάθος bit, θα λάβετε μια εξαίρεση.

Value: Η τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

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


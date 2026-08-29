---
title: "Brush"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η βασική κλάση πινέλου."
type: docs
weight: 12
url: /el/java/com.aspose.psd/brush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class Brush extends DisposableObject
```

Η βασική κλάση πινέλου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Brush()](#Brush--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια του πινέλου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOpacity(float value)](#setOpacity-float-) | Ορίζει τη διαφάνεια του πινέλου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Brush() {#Brush--}
```
public Brush()
```


### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

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
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Λαμβάνει τη διαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές.

**Returns:**
float - Η τιμή διαφάνειας του πινέλου.
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




### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ορίζει τη διαφάνεια της πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η τιμή διαφάνειας του πινέλου. |

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


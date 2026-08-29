---
title: "FileSource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει μια πηγή αρχείου που είναι ικανή για χειρισμό αρχείων."
type: docs
weight: 12
url: /el/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

Αντιπροσωπεύει μια πηγή αρχείου που είναι ικανή για χειρισμό αρχείων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | Λαμβάνει το container της ροής. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Λαμβάνει μια τιμή που υποδεικνύει αν το αρχείο θα είναι προσωρινό. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSource() {#FileSource--}
```
public FileSource()
```


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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
```


Λαμβάνει το container της ροής.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Χρησιμοποιήστε με προσοχή. Θα χρειαστεί να διαγράψετε το κοντέινερ της ροής μετά την ανάκτηση.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public abstract boolean isTemporal()
```


Λαμβάνει μια τιμή που υποδεικνύει αν το αρχείο θα είναι προσωρινό.

**Returns:**
boolean -  true  αν το αρχείο θα είναι προσωρινό· διαφορετικά,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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


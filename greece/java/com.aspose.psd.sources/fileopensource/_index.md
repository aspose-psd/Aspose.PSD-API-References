---
title: "FileOpenSource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά μια πηγή αρχείου για άνοιγμα."
type: docs
weight: 11
url: /el/java/com.aspose.psd.sources/fileopensource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Αναπαριστά μια πηγή αρχείου για άνοιγμα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  FileOpenSource . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Λαμβάνει τη διαδρομή αρχείου για άνοιγμα. |
| [getStreamContainer()](#getStreamContainer--) | Λαμβάνει το container της ροής. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Λαμβάνει μια τιμή που υποδεικνύει αν το αρχείο θα είναι προσωρινό. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  FileOpenSource .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου για άνοιγμα. |

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
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Λαμβάνει τη διαδρομή αρχείου για άνοιγμα.

Τιμή: Η διαδρομή αρχείου για άνοιγμα.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
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
public boolean isTemporal()
```


Λαμβάνει μια τιμή που υποδεικνύει αν το αρχείο θα είναι προσωρινό.

Τιμή:  true  αν το αρχείο θα είναι προσωρινό· διαφορετικά,  false .

**Returns:**
boolean
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


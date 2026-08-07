---
title: "SplitStreamContainer"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει το χωριστό δοχείο ροής που περιέχει τη ροή και παρέχει ρουτίνες επεξεργασίας ροής."
type: docs
weight: 102
url: /el/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Αντιπροσωπεύει το χωριστό δοχείο ροής που περιέχει τη ροή και παρέχει ρουτίνες επεξεργασίας ροής.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Καθορίζει τον αριθμό των byte ανάγνωσης και εγγραφής κατά την διαδοχική ανάγνωση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [canRead()](#canRead--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει ανάγνωση. |
| [canSeek()](#canSeek--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει αναζήτηση. |
| [canWrite()](#canWrite--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει εγγραφή. |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Καθαρίζει όλες τις προσωρινές μνήμες για αυτήν τη ροή και προκαλεί την εγγραφή τυχόν προσωρινών δεδομένων στη βασική συσκευή. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getLength()](#getLength--) | Λαμβάνει ή ορίζει το μήκος της ροής σε byte. |
| [getPosition()](#getPosition--) | Λαμβάνει ή ορίζει την τρέχουσα θέση μέσα στη ροή. |
| [getStream()](#getStream--) | Λαμβάνει τη ροή δεδομένων. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Εισάγει το κοντέινερ ροής στη συγκεκριμένη θέση. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η ροή διαγράφεται κατά το κλείσιμο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Διαβάζει byte για να γεμίσει το καθορισμένο buffer byte. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| [readByte()](#readByte--) | Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν είναι στο τέλος της ροής. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στο καθορισμένο stream. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream. |
| [save(String filePath)](#save-java.lang.String-) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Ορίζει τη θέση μέσα στην τρέχουσα ροή. |
| [seekBegin()](#seekBegin--) | Ορίζει τη θέση της ροής στην αρχή της ροής. |
| [setLength(long value)](#setLength-long-) | Λαμβάνει ή ορίζει το μήκος της ροής σε byte. |
| [setPosition(long value)](#setPosition-long-) | Λαμβάνει ή ορίζει την τρέχουσα θέση μέσα στη ροή. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Μετατρέπει τα δεδομένα της ροής σε πίνακα  byte. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Μετατρέπει τα δεδομένα της ροής σε πίνακα  byte. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Εκτελεί μια ρητή μετατροπή από  com.aspose.imaging.StreamContainer  σε  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Γράφει όλα τα καθορισμένα byte στη ροή. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν. |
| [writeByte(byte value)](#writeByte-byte-) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Αντιγράφει τα περιεχόμενα δεδομένα σε άλλο  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Αντιγράφει τα περιεχόμενα δεδομένα σε άλλο  StreamContainer . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή δεδομένων. |
| disposeStream | boolean | εάν οριστεί σε  true  η ροή θα διαγραφεί όταν το κοντέινερ διαγραφεί. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| disposeStream | boolean | αν οριστεί σε  true  απελευθερώνει τη ροή. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Καθορίζει τον αριθμό των byte ανάγνωσης και εγγραφής κατά την διαδοχική ανάγνωση.

### canRead() {#canRead--}
```
public boolean canRead()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει ανάγνωση.

Τιμή:  true  εάν η ροή υποστηρίζει ανάγνωση· διαφορετικά,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει αναζήτηση.

Τιμή:  true  εάν η ροή υποστηρίζει αναζήτηση· διαφορετικά,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή υποστηρίζει εγγραφή.

Τιμή:  true  εάν η ροή υποστηρίζει εγγραφή· διαφορετικά,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
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
### flush() {#flush--}
```
public void flush()
```


Καθαρίζει όλες τις προσωρινές μνήμες για αυτήν τη ροή και προκαλεί την εγγραφή τυχόν προσωρινών δεδομένων στη βασική συσκευή.

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
### getLength() {#getLength--}
```
public long getLength()
```


Αποκτά ή ορίζει το μήκος της ροής σε byte. Αυτή η τιμή είναι μικρότερη από το  System.IO.Stream.Length  κατά τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer.

Τιμή: Το μήκος της ροής.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Αποκτά ή ορίζει την τρέχουσα θέση μέσα στη ροή. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer.

Τιμή: Η τρέχουσα θέση της ροής.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Λαμβάνει τη ροή δεδομένων.

Τιμή: Η ροή δεδομένων.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Λαμβάνει ένα αντικείμενο που μπορεί να χρησιμοποιηθεί για τον συγχρονισμό της πρόσβασης στον συγχρονισμένο πόρο.

Τιμή: Το αντικείμενο που μπορεί να χρησιμοποιηθεί για συγχρονισμό πρόσβασης στον συγχρονισμένο πόρο.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


Εισάγει το κοντέινερ ροής στη συγκεκριμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Η θέση για εισαγωγή. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το δοχείο ροής για εισαγωγή. |
| disposeStream | boolean | αν οριστεί σε  true  απελευθερώνει τη ροή. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η ροή διαγράφεται κατά το κλείσιμο.

Τιμή:  true  εάν η ροή απελευθερώνεται κατά το κλείσιμο· διαφορετικά,  false .

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




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Διαβάζει byte για να γεμίσει το καθορισμένο buffer byte.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | byte[] | Τα bytes για γέμισμα. |

**Returns:**
int - Ο αριθμός των bytes που διαβάστηκαν. Αυτή η τιμή μπορεί να είναι μικρότερη από τον αριθμό των bytes στο buffer εάν δεν υπάρχουν αρκετά bytes στη ροή.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | byte[] | Ένας πίνακας bytes. Όταν αυτή η μέθοδος επιστρέψει, το buffer περιέχει τον καθορισμένο πίνακα byte με τις τιμές μεταξύ  offset  και ( offset  +  count  - 1) που αντικαταστάθηκαν από τα bytes που διαβάστηκαν από την τρέχουσα πηγή. |
| μετατόπιση | int | Η μηδενική βάση offset byte στο  buffer  από την οποία θα αρχίσει η αποθήκευση των δεδομένων που διαβάστηκαν από την τρέχουσα ροή. |
| count | int | Ο μέγιστος αριθμός bytes που θα διαβαστούν από την τρέχουσα ροή. |

**Returns:**
int - Ο συνολικός αριθμός των bytes που διαβάστηκαν στο buffer. Αυτό μπορεί να είναι μικρότερο από τον αριθμό των bytes που ζητήθηκαν εάν δεν είναι διαθέσιμα τόσα bytes, ή μηδέν (0) εάν έχει φθάσει το τέλος της ροής.
### readByte() {#readByte--}
```
public int readByte()
```


Διαβάζει ένα byte από τη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν είναι στο τέλος της ροής.

**Returns:**
int - Το μη υπογεγραμμένο byte μετατρεπόμενο σε Int32, ή -1 εάν βρίσκεται στο τέλος της ροής.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer  ReadWriteBytesCount  και την τιμή της ροής  Length .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Αποθηκεύει (αντιγράφει) όλα τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί την τιμή της ροής  Length .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα. |
| bufferSize | int | Η προσωρινή μνήμη. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Η ροή στην οποία θα αποθηκευτούν τα δεδομένα. |
| bufferSize | int | Το μέγεθος της προσωρινής μνήμης. Από προεπιλογή χρησιμοποιείται η τιμή [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT). |
| length | long | Το μήκος των δεδομένων ροής προς αντιγραφή. Από προεπιλογή το μήκος ορίζεται στην τιμή Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στον καθορισμένο προορισμό. Χρησιμοποιεί το προεπιλεγμένο μέγεθος buffer  ReadWriteBytesCount  και την τιμή της ροής  Length .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα ροής. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο ρεύμα. Χρησιμοποιεί την τιμή Length.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα ροής. |
| bufferSize | int | Το μέγεθος της προσωρινής μνήμης. Από προεπιλογή χρησιμοποιείται η τιμή ReadWriteBytesCount. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Αποθηκεύει (αντιγράφει) τα δεδομένα της ροής στο καθορισμένο stream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευτούν τα δεδομένα ροής. |
| bufferSize | int | Το μέγεθος της προσωρινής μνήμης. Από προεπιλογή χρησιμοποιείται η τιμή ReadWriteBytesCount. |
| μήκος | long | Το μήκος των δεδομένων ροής προς αντιγραφή. Από προεπιλογή το μήκος ορίζεται στην τιμή Length. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| μήκος | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Ορίζει τη θέση μέσα στην τρέχουσα ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μετατόπιση | long | Μία μετατόπιση byte σε σχέση με την παράμετρο origin. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης της ροής που περάστηκε στον κατασκευαστή StreamContainer. |
| origin | int | Μία τιμή τύπου [SeekOrigin](../../com.aspose.psd/seekorigin) που υποδεικνύει το σημείο αναφοράς που χρησιμοποιείται για την απόκτηση της νέας θέσης. |

**Returns:**
long - Η νέα θέση εντός της τρέχουσας ροής.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Ορίζει τη θέση της ροής στην αρχή της ροής. Αυτή η τιμή αντιπροσωπεύει τη μετατόπιση από τη θέση έναρξης της ροής που περάστηκε στον κατασκευαστή StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Αποκτά ή ορίζει το μήκος της ροής σε byte. Αυτή η τιμή είναι μικρότερη από το  System.IO.Stream.Length  κατά τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer.

Τιμή: Το μήκος της ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Αποκτά ή ορίζει την τρέχουσα θέση μέσα στη ροή. Αυτή η τιμή αντιπροσωπεύει την απόσταση από τη θέση εκκίνησης της ροής που περάστηκε στον κατασκευαστή StreamContainer.

Τιμή: Η τρέχουσα θέση της ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Μετατρέπει τα δεδομένα της ροής σε πίνακα  byte.

**Returns:**
byte[] - Τα δεδομένα της ροής μετατρεπόμενα σε πίνακα byte.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Μετατρέπει τα δεδομένα της ροής σε πίνακα  byte.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία θα ξεκινήσει η ανάγνωση των byte. |
| bytesCount | long | Ο αριθμός των byte προς ανάγνωση. |

**Returns:**
byte[] - Τα δεδομένα της ροής μετατρεπόμενα σε πίνακα byte.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Εκτελεί μια ρητή μετατροπή από  com.aspose.imaging.StreamContainer  σε  System.IO.Stream .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |

**Returns:**
com.aspose.ms.System.IO.Stream - Το αποτέλεσμα της μετατροπής.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Γράφει όλα τα καθορισμένα byte στη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | byte[] | Τα byte προς εγγραφή. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη τρέχουσα θέση μέσα σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | byte[] | Ένας πίνακας byte. Αυτή η μέθοδος αντιγράφει count byte από buffer στο τρέχον ρεύμα. |
| μετατόπιση | int | Η μηδενική μετατόπιση byte στο buffer από την οποία θα αρχίσει η αντιγραφή byte στο τρέχον ρεύμα. |
| count | int | Ο αριθμός των byte που θα γραφούν στο τρέχον ρεύμα. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Γράφει ένα byte στην τρέχουσα θέση στη ροή και προχωρά τη θέση μέσα στη ροή κατά ένα byte.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte | Το byte που θα γραφτεί στην ροή. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Αντιγράφει τα περιεχόμενα δεδομένα σε άλλο  StreamContainer .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το container ροής προς αντιγραφή. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Αντιγράφει τα περιεχόμενα δεδομένα σε άλλο  StreamContainer .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το container ροής προς αντιγραφή. |
| μήκος | long | Ο αριθμός των byte προς εγγραφή. |


---
title: "TiffStreamReader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η ροή tiff για τη διαχείριση του μορφότυπου αρχείου little endian tiff."
type: docs
weight: 10
url: /el/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Η ροή tiff για τη διαχείριση του μορφότυπου αρχείου little endian tiff.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του αναγνώστη. |
| [getThrowExceptions()](#getThrowExceptions--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εξαιρέσεις εκτοξεύονται κατά την εσφαλμένη επεξεργασία δεδομένων (ανάγνωση ή εγγραφή στο ρεύμα). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Διαβάζει έναν πίνακα τιμών byte από το ρεύμα. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Διαβάζει έναν πίνακα τιμών unsigned byte από το ρεύμα. |
| [readDouble(long position)](#readDouble-long-) | Διαβάζει μια μοναδική τιμή double από το ρεύμα. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Διαβάζει έναν πίνακα τιμών double από το ρεύμα. |
| [readFloat(long position)](#readFloat-long-) | Διαβάζει μια μοναδική τιμή float από το ρεύμα. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Διαβάζει έναν πίνακα τιμών float από το ρεύμα. |
| [readRational(long position)](#readRational-long-) | Διαβάζει μια μοναδική τιμή λογιστικού αριθμού από το ρεύμα. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Διαβάζει έναν πίνακα λογιστικών τιμών από το ρεύμα. |
| [readSByte(long position)](#readSByte-long-) | Διαβάζει δεδομένα signed byte από το ρεύμα. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Διαβάζει έναν πίνακα τιμών signed byte από το ρεύμα. |
| [readSLong(long position)](#readSLong-long-) | Διαβάζει μια τιμή signed integer από το ρεύμα. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Διαβάζει έναν πίνακα τιμών signed integer από το ρεύμα. |
| [readSRational(long position)](#readSRational-long-) | Διαβάζει μια μοναδική τιμή signed rational number από το ρεύμα. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Διαβάζει έναν πίνακα τιμών signed rational από το ρεύμα. |
| [readSShort(long position)](#readSShort-long-) | Διαβάζει μια τιμή signed short από το ρεύμα. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Διαβάζει έναν πίνακα υπογεγραμμένων τιμών short από τη ροή. |
| [readString_internalized(long position)](#readString-internalized-long-) | Διαβάζει τη συμβολοσειρά από τη ροή. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Διαβάζει τη συμβολοσειρά από τη ροή. |
| [readULong(long position)](#readULong-long-) | Διαβάζει τιμή ακεραίου χωρίς πρόσημο από τη ροή. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Διαβάζει έναν πίνακα τιμών ακεραίων χωρίς πρόσημο από τη ροή. |
| [readUShort(long position)](#readUShort-long-) | Διαβάζει τιμή unsigned short από τη ροή. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Διαβάζει έναν πίνακα τιμών ακεραίων χωρίς πρόσημο από τη ροή. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εξαιρέσεις εκτοξεύονται κατά την εσφαλμένη επεξεργασία δεδομένων (ανάγνωση ή εγγραφή στο ρεύμα). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Μετατρέπει τα υποκείμενα δεδομένα σε κοντέινερ ροής. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] | Τα δεδομένα του πίνακα byte. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] | Τα δεδομένα του πίνακα byte. |
| startIndex | int | Ο αρχικός δείκτης στα δεδομένα. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] | Τα δεδομένα του πίνακα byte. |
| startIndex | int | Ο αρχικός δείκτης στα δεδομένα. |
| dataLength | int | Μήκος των δεδομένων. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης TiffStreamReader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |

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
### getLength() {#getLength--}
```
public long getLength()
```


Λαμβάνει το μήκος του αναγνώστη.

Τιμή: Το μήκος του αναγνώστη.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εξαιρέσεις εκτοξεύονται κατά την εσφαλμένη επεξεργασία δεδομένων (ανάγνωση ή εγγραφή στο ρεύμα).

Τιμή:  true  εάν εξαπολύονται εξαιρέσεις σε λανθασμένη επεξεργασία δεδομένων· διαφορετικά, οι συνθήκες σφάλματος αγνοούνται σιωπηρά.

**Returns:**
boolean
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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Διαβάζει έναν πίνακα τιμών byte από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | byte[] | Ο πίνακας προς γέμισμα. |
| arrayIndex | int | Ο δείκτης πίνακα από όπου αρχίζει η εισαγωγή τιμών. |
| position | long | Η θέση της ροής από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων προς ανάγνωση. |

**Returns:**
long - Ο πίνακας τιμών byte.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Διαβάζει έναν πίνακα τιμών unsigned byte από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
byte[] - Ο πίνακας τιμών unsigned byte.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Διαβάζει μια μοναδική τιμή double από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
double - Η μοναδική τιμή double.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών double από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
double[] - Ο πίνακας των τιμών double.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Διαβάζει μια μοναδική τιμή float από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
float - Η μοναδική τιμή float.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών float από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
float[] - Ο πίνακας των τιμών float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Διαβάζει μια μοναδική τιμή λογιστικού αριθμού από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Διαβάζει έναν πίνακα λογιστικών τιμών από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Ο πίνακας των ρητών τιμών.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Διαβάζει δεδομένα signed byte από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
byte - Η υπογεγραμμένη τιμή byte.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών signed byte από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
byte[] - Ο πίνακας των υπογεγραμμένων τιμών byte.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Διαβάζει μια τιμή signed integer από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
int - Μια υπογεγραμμένη τιμή ακέραιου.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών signed integer από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
int[] - Ο πίνακας των υπογεγραμμένων τιμών ακέραιου.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Διαβάζει μια μοναδική τιμή signed rational number από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών signed rational από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - Ο πίνακας των υπογεγραμμένων ρητών τιμών.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Διαβάζει μια τιμή signed short από το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
short - Μια υπογεγραμμένη τιμή short.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Διαβάζει έναν πίνακα υπογεγραμμένων τιμών short από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
short[] - Ο πίνακας των υπογεγραμμένων τιμών short.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Διαβάζει τη συμβολοσειρά από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση. |

**Returns:**
java.lang.String - Η συμβολοσειρά.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Διαβάζει τη συμβολοσειρά από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση. |
| μήκος | long | Το μήκος. |

**Returns:**
java.lang.String - Η συμβολοσειρά.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Διαβάζει τιμή ακεραίου χωρίς πρόσημο από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
long - Μια μη υπογεγραμμένη τιμή ακέραιου.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών ακεραίων χωρίς πρόσημο από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
long[] - Ο πίνακας των μη υπογεγραμμένων τιμών ακέραιου.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Διαβάζει τιμή unsigned short από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |

**Returns:**
int - Μια μη υπογεγραμμένη τιμή short.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Διαβάζει έναν πίνακα τιμών ακεραίων χωρίς πρόσημο από τη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | long | Η θέση από την οποία διαβάζεται. |
| count | long | Ο αριθμός των στοιχείων. |

**Returns:**
int[] - Ο πίνακας των μη υπογεγραμμένων τιμών ακέραιου.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εξαιρέσεις εκτοξεύονται κατά την εσφαλμένη επεξεργασία δεδομένων (ανάγνωση ή εγγραφή στο ρεύμα).

Τιμή:  true  εάν εξαπολύονται εξαιρέσεις σε λανθασμένη επεξεργασία δεδομένων· διαφορετικά, οι συνθήκες σφάλματος αγνοούνται σιωπηρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Μετατρέπει τα υποκείμενα δεδομένα σε κοντέινερ ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startPosition | long | Η θέση έναρξης για την έναρξη της μετατροπής. |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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


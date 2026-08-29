---
title: "Thumbnail4Resource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά τον πόρο μικρογραφίας για psd 4.0."
type: docs
weight: 34
url: /el/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

Αναπαριστά τον πόρο μικρογραφίας για psd 4.0.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Η υπογραφή πόρου του ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Η κανονική υπογραφή πόρου του Photoshop. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Λαμβάνει ή ορίζει το bits pixel. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Λαμβάνει το μέγεθος δεδομένων πόρου σε bytes. |
| [getFormat()](#getFormat--) | Λαμβάνει ή ορίζει τη μορφή δεδομένων μικρογραφίας. |
| [getHeight()](#getHeight--) | Λαμβάνει ή ορίζει το ύψος της μικρογραφίας σε εικονοστοιχεία. |
| [getID()](#getID--) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [getJpegOptions()](#getJpegOptions--) | Λαμβάνει ή ορίζει τις επιλογές JPEG. |
| [getMinimalVersion()](#getMinimalVersion--) | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| [getName()](#getName--) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [getPlanesCount()](#getPlanesCount--) | Λαμβάνει ή ορίζει τον αριθμό επιπέδων. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος του μπλοκ πόρου σε bytes, συμπεριλαμβανομένων των δεδομένων του. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Λαμβάνει ή ορίζει το μέγεθος μετά τη συμπίεση. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Λαμβάνει ή ορίζει τα 32-bit ARGB δεδομένα μικρογραφίας. |
| [getThumbnailData()](#getThumbnailData--) | Λαμβάνει ή ορίζει τα δεδομένα μικρογραφίας. |
| [getTotalSize()](#getTotalSize--) | Λαμβάνει το συνολικό μέγεθος δεδομένων. |
| [getWidth()](#getWidth--) | Λαμβάνει ή ορίζει το πλάτος της μικρογραφίας σε εικονοστοιχεία. |
| [getWidthBytes()](#getWidthBytes--) | Λαμβάνει το πλάτος γραμμής σε bytes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Λαμβάνει ή ορίζει το bits pixel. |
| [setFormat(int value)](#setFormat-int-) | Λαμβάνει ή ορίζει τη μορφή δεδομένων μικρογραφίας. |
| [setHeight(int value)](#setHeight-int-) | Λαμβάνει ή ορίζει το ύψος της μικρογραφίας σε εικονοστοιχεία. |
| [setID(short value)](#setID-short-) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Λαμβάνει ή ορίζει τις επιλογές JPEG. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Λαμβάνει ή ορίζει τις πληροφορίες layer και mask. |
| [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Λαμβάνει ή ορίζει τον αριθμό επιπέδων. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Λαμβάνει ή ορίζει την κατάσταση του μπλοκ πόρου. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Λαμβάνει ή ορίζει τα 32-bit ARGB δεδομένα μικρογραφίας. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Λαμβάνει ή ορίζει τα δεδομένα μικρογραφίας. |
| [setWidth(int value)](#setWidth-int-) | Λαμβάνει ή ορίζει το πλάτος της μικρογραφίας σε εικονοστοιχεία. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Επικυρώνει τις τιμές του πόρου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Η υπογραφή πόρου του ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Η κανονική υπογραφή πόρου του Photoshop.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Λαμβάνει ή ορίζει το bits pixel.

Τιμή: Τα bits pixel της μικρογραφίας.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Λαμβάνει το μέγεθος δεδομένων πόρου σε bytes.

Τιμή: Το μέγεθος δεδομένων του πόρου.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Λαμβάνει ή ορίζει τη μορφή δεδομένων μικρογραφίας.

Τιμή: Η μορφή δεδομένων μικρογραφίας.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει ή ορίζει το ύψος της μικρογραφίας σε εικονοστοιχεία.

Τιμή: Το ύψος της μικρογραφίας.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο.

Τιμή: Το μοναδικό αναγνωριστικό για τον πόρο.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Λαμβάνει ή ορίζει τις επιλογές JPEG. Κατάλληλο όταν ο πόρος μικρογραφίας αποθηκεύεται μόνο σε μορφή αρχείου JPEG. Αυτή η επιλογή δεν έχει καμία επίδραση όταν ορίζεται η μορφή RAW.

Τιμή: Οι επιλογές JPEG.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD.

Τιμή: Η ελάχιστη έκδοση psd.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, γεμισμένη ώστε το μέγεθος να είναι άρτιο (ένα μηδενικό όνομα αποτελείται από δύο byte του 0).

Τιμή: Το όνομα του πόρου.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Λαμβάνει ή ορίζει τον αριθμό επιπέδων.

Τιμή: Ο αριθμός επιπέδων της μικρογραφίας.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Λαμβάνει την υπογραφή του πόρου. Θα πρέπει πάντα να είναι '8BIM'.

Τιμή: Η υπογραφή του πόρου.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Λαμβάνει το μέγεθος του μπλοκ πόρου σε bytes, συμπεριλαμβανομένων των δεδομένων του.

Τιμή: Το μέγεθος του μπλοκ πόρου.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Λαμβάνει ή ορίζει το μέγεθος μετά τη συμπίεση. Χρησιμοποιείται για έλεγχο συνέπειας.

Τιμή: Το μέγεθος μετά τη συμπίεση.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Λαμβάνει ή ορίζει τα 32-bit ARGB δεδομένα μικρογραφίας.

Τιμή: Τα 32-bit ARGB δεδομένα μικρογραφίας.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Λαμβάνει ή ορίζει τα δεδομένα μικρογραφίας.

Τιμή: Τα δεδομένα μικρογραφίας.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Λαμβάνει το συνολικό μέγεθος δεδομένων.

Τιμή: Το συνολικό μέγεθος δεδομένων.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει ή ορίζει το πλάτος της μικρογραφίας σε εικονοστοιχεία.

Τιμή: Το πλάτος μικρογραφίας.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Λαμβάνει το πλάτος γραμμής σε bytes.

Τιμή: Το πλάτος γραμμής σε bytes.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή για αποθήκευση του μπλοκ πόρου. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Λαμβάνει ή ορίζει το bits pixel.

Τιμή: Τα bits pixel της μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Λαμβάνει ή ορίζει τη μορφή δεδομένων μικρογραφίας.

Τιμή: Η μορφή δεδομένων μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Λαμβάνει ή ορίζει το ύψος της μικρογραφίας σε εικονοστοιχεία.

Τιμή: Το ύψος της μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο.

Τιμή: Το μοναδικό αναγνωριστικό για τον πόρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Λαμβάνει ή ορίζει τις επιλογές JPEG. Κατάλληλο όταν ο πόρος μικρογραφίας αποθηκεύεται μόνο σε μορφή αρχείου JPEG. Αυτή η επιλογή δεν έχει καμία επίδραση όταν ορίζεται η μορφή RAW.

Τιμή: Οι επιλογές JPEG.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Λαμβάνει ή ορίζει τις πληροφορίες layer και mask.

Τιμή: Οι πληροφορίες στρώματος και μάσκας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, γεμισμένη ώστε το μέγεθος να είναι άρτιο (ένα μηδενικό όνομα αποτελείται από δύο byte του 0).

Τιμή: Το όνομα του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Λαμβάνει ή ορίζει τον αριθμό επιπέδων.

Τιμή: Ο αριθμός επιπέδων της μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογραφή | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Λαμβάνει ή ορίζει την κατάσταση του μπλοκ πόρου.

Τιμή: Η κατάσταση του μπλοκ πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Λαμβάνει ή ορίζει τα 32-bit ARGB δεδομένα μικρογραφίας.

Τιμή: Τα 32-bit ARGB δεδομένα μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Λαμβάνει ή ορίζει τα δεδομένα μικρογραφίας.

Τιμή: Τα δεδομένα μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Λαμβάνει ή ορίζει το πλάτος της μικρογραφίας σε εικονοστοιχεία.

Τιμή: Το πλάτος μικρογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Επικυρώνει τις τιμές του πόρου.

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


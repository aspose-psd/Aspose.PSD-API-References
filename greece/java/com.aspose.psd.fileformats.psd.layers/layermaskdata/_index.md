---
title: "LayerMaskData"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει τη βασική κλάση LayerMaskData που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας επιπέδου στο αρχείο PSD."
type: docs
weight: 21
url: /el/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

Ορίζει τη βασική κλάση LayerMaskData που περιέχει πληροφορίες για τα δεδομένα μάσκας επιπέδου στο αρχείο PSD. Μπορεί να βοηθήσει στην προγραμματιστική τροποποίηση αρχείων Adobe\ufffd Photoshop\ufffd και στην αυτοματοποίηση της επεξεργασίας μορφής PSD. Εάν το επίπεδο έχει μόνο μια ραστική μάσκα, το ImageData περιέχει τα bytes δεδομένων της ραστικής μάσκας. Εάν το επίπεδο έχει μόνο μια διανυσματική μάσκα, το ImageData περιέχει τα bytes δεδομένων της διανυσματικής μάσκας που έχουν ραστεριστεί (cached). Εάν το επίπεδο έχει και ραστική και διανυσματική μάσκα, το ImageData περιέχει τη ραστική μάσκα και τη ραστερισμένη διανυσματική μάσκα συνδυασμένες. Τα bytes του ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) πρέπει να έχουν μήκος ίσο με Width \* Height του MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) properties. Σημειώστε ότι η απλή αφαίρεση / προσθήκη / ενημέρωση του LayerMaskData δεν αρκεί για σωστή αποθήκευση, επειδή τα κανάλια δεν ενημερώνονται· ωστόσο μπορεί να παρέχει σωστή απόδοση. Η μέθοδος [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) πρέπει να χρησιμοποιηθεί για αυτό.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Κλωνοποιεί τη μάσκα επιπέδου. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας επιπέδου. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Λαμβάνει το μέγεθος των δεδομένων μάσκας του επιπέδου. |
| [getDefaultColor()](#getDefaultColor--) | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [getFlags()](#getFlags--) | Λαμβάνει ή ορίζει τις σημαίες της μάσκας επιπέδου. |
| [getHeight_internalized()](#getHeight-internalized--) | Λαμβάνει το ύψος της μάσκας. |
| [getImageData()](#getImageData--) | Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας επιπέδου. |
| [getMaskRectangle()](#getMaskRectangle--) | Λαμβάνει ή ορίζει το  Rectangle  της μάσκας του επιπέδου στο αρχείο PSD. |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας επιπέδου. |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει τη θέση της άνω μάσκας επιπέδου. |
| [getWidth_internalized()](#getWidth-internalized--) | Λαμβάνει το πλάτος της μάσκας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Αποθηκεύει το [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) στο καθορισμένο  StreamContainer . |
| [setBottom(int value)](#setBottom-int-) | Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας επιπέδου. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [setFlags(byte value)](#setFlags-byte-) | Λαμβάνει ή ορίζει τις σημαίες της μάσκας επιπέδου. |
| [setImageData(byte[] value)](#setImageData-byte---) | Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| [setLeft(int value)](#setLeft-int-) | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας επιπέδου. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει το  Rectangle  της μάσκας του επιπέδου στο αρχείο PSD. |
| [setRight(int value)](#setRight-int-) | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας επιπέδου. |
| [setTop(int value)](#setTop-int-) | Λαμβάνει ή ορίζει τη θέση της άνω μάσκας επιπέδου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Κλωνοποιεί τη μάσκα επιπέδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Η μάσκα. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας επιπέδου.

Τιμή: Η θέση της κάτω μάσκας επιδίου.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Λαμβάνει το μέγεθος των δεδομένων μάσκας του επιπέδου.

Value: Το μέγεθος των δεδομένων μάσκας της μάσκας στρώσης.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα.

Value: Το προεπιλεγμένο χρώμα.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Λαμβάνει ή ορίζει τις σημαίες της μάσκας επιπέδου.

Value: Οι σημαίες της μάσκας στρώσης.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Λαμβάνει το ύψος της μάσκας.

Value: Το ύψος.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD.

Value: Τα δεδομένα εικόνας.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας επιπέδου.

Value: Η θέση αριστερής μάσκας στρώσης.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Λαμβάνει ή ορίζει το mask Rectangle της μάσκας στρώσης στο αρχείο PSD. Παίρνει τις ιδιότητες left, right, top και bottom και δημιουργεί Rectangle

Value: Το ορθογώνιο της μάσκας.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRight() {#getRight--}
```
public final int getRight()
```


Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας επιπέδου.

Value: Η θέση δεξιάς μάσκας στρώσης.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Λαμβάνει ή ορίζει τη θέση της άνω μάσκας επιπέδου.

Value: Η θέση επάνω μάσκας στρώσης.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Λαμβάνει το πλάτος της μάσκας.

Value: Το πλάτος.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public abstract void save_internalized(StreamContainer streamContainer)
```


Αποθηκεύει το [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) στο καθορισμένο  StreamContainer .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής για αποθήκευση δεδομένων. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας επιπέδου.

Τιμή: Η θέση της κάτω μάσκας επιδίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα.

Value: Το προεπιλεγμένο χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Λαμβάνει ή ορίζει τις σημαίες της μάσκας επιπέδου.

Value: Οι σημαίες της μάσκας στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD.

Value: Τα δεδομένα εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας επιπέδου.

Value: Η θέση αριστερής μάσκας στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Λαμβάνει ή ορίζει το mask Rectangle της μάσκας στρώσης στο αρχείο PSD. Παίρνει τις ιδιότητες left, right, top και bottom και δημιουργεί Rectangle

Value: Το ορθογώνιο της μάσκας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας επιπέδου.

Value: Η θέση δεξιάς μάσκας στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Λαμβάνει ή ορίζει τη θέση της άνω μάσκας επιπέδου.

Value: Η θέση επάνω μάσκας στρώσης.

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


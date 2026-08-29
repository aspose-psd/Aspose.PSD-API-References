---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει την κλάση LayerMaskDataFull που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο επίπεδο αρχείου PSD όταν το επίπεδο έχει και μάσκα επιπέδου και διανυσματική μάσκα."
type: docs
weight: 22
url: /el/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Ορίζει την κλάση LayerMaskDataFull που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο επίπεδο αρχείου PSD όταν το επίπεδο έχει τόσο μάσκα επιπέδου όσο και μάσκα διανύσματος. Διαφορετικά, χρησιμοποιείται ένα [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). Τα ImageData περιέχουν τη raster mask και τη rasterized vector mask συνδυασμένα. Το μήκος των bytes των ImageData πρέπει να είναι ίσο με τις ιδιότητες MaskRectangle.Width \* MaskRectangle.Height.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Κλωνοποιεί τη μάσκα επιπέδου. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει ή ορίζει το χρώμα φόντου. |
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας επιπέδου. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Λαμβάνει το μέγεθος των δεδομένων μάσκας του επιπέδου. |
| [getDefaultColor()](#getDefaultColor--) | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Λαμβάνει ή ορίζει τη θέση του κάτω raster mask που περιβάλλει στο επίπεδο εικόνας PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Λαμβάνει ή ορίζει τη θέση του αριστερού raster mask που περιβάλλει στο επίπεδο αρχείου PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | Λαμβάνει ή ορίζει τη θέση του δεξιού raster mask που περιβάλλει στο επίπεδο αρχείου PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | Λαμβάνει ή ορίζει τη θέση του πάνω raster mask που περιβάλλει στο επίπεδο εικόνας PSD. |
| [getFlags()](#getFlags--) | Λαμβάνει ή ορίζει τις σημαίες της μάσκας επιπέδου. |
| [getHeight_internalized()](#getHeight-internalized--) | Λαμβάνει το ύψος της μάσκας. |
| [getImageData()](#getImageData--) | Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας επιπέδου. |
| [getMaskRectangle()](#getMaskRectangle--) | Λαμβάνει ή ορίζει το  Rectangle  της μάσκας του επιπέδου στο αρχείο PSD. |
| [getRealFlags()](#getRealFlags--) | Λαμβάνει ή ορίζει τις layer mask flags που χρησιμοποιούνται για τη μάσκα χρήστη / raster. |
| [getRight()](#getRight--) | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας επιπέδου. |
| [getTop()](#getTop--) | Λαμβάνει ή ορίζει τη θέση της άνω μάσκας επιπέδου. |
| [getUserMaskData()](#getUserMaskData--) | Λαμβάνει ή ορίζει τα δεδομένα μάσκας χρήστη (raster) ενός στρώματος στο αρχείο PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Λαμβάνει ή ορίζει το ορθογώνιο (περιβάλλει) της μάσκας χρήστη στο στρώμα εικόνας PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | Λαμβάνει το πλάτος της μάσκας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Αποθηκεύει το [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) στο καθορισμένο  StreamContainer . |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Λαμβάνει ή ορίζει το χρώμα φόντου. |
| [setBottom(int value)](#setBottom-int-) | Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας επιπέδου. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Λαμβάνει ή ορίζει τη θέση του κάτω raster mask που περιβάλλει στο επίπεδο εικόνας PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Λαμβάνει ή ορίζει τη θέση του αριστερού raster mask που περιβάλλει στο επίπεδο αρχείου PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Λαμβάνει ή ορίζει τη θέση του δεξιού raster mask που περιβάλλει στο επίπεδο αρχείου PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Λαμβάνει ή ορίζει τη θέση του πάνω raster mask που περιβάλλει στο επίπεδο εικόνας PSD. |
| [setFlags(byte value)](#setFlags-byte-) | Λαμβάνει ή ορίζει τις σημαίες της μάσκας επιπέδου. |
| [setImageData(byte[] value)](#setImageData-byte---) | Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| [setLeft(int value)](#setLeft-int-) | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας επιπέδου. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει το  Rectangle  της μάσκας του επιπέδου στο αρχείο PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Λαμβάνει ή ορίζει τις layer mask flags που χρησιμοποιούνται για τη μάσκα χρήστη / raster. |
| [setRight(int value)](#setRight-int-) | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας επιπέδου. |
| [setTop(int value)](#setTop-int-) | Λαμβάνει ή ορίζει τη θέση της άνω μάσκας επιπέδου. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Λαμβάνει ή ορίζει τα δεδομένα μάσκας χρήστη (raster) ενός στρώματος στο αρχείο PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει το ορθογώνιο (περιβάλλει) της μάσκας χρήστη στο στρώμα εικόνας PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Λαμβάνει ή ορίζει το χρώμα φόντου.

Τιμή: Το χρώμα φόντου.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Λαμβάνει ή ορίζει τη θέση του κάτω raster mask που περιβάλλει στο επίπεδο εικόνας PSD.

Τιμή: Η θέση της κάτω μάσκας επιδίου.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Λαμβάνει ή ορίζει τη θέση του αριστερού raster mask που περιβάλλει στο επίπεδο αρχείου PSD.

Value: Η θέση αριστερής μάσκας στρώσης.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Λαμβάνει ή ορίζει τη θέση του δεξιού raster mask που περιβάλλει στο επίπεδο αρχείου PSD.

Value: Η θέση δεξιάς μάσκας στρώσης.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Λαμβάνει ή ορίζει τη θέση του πάνω raster mask που περιβάλλει στο επίπεδο εικόνας PSD.

Value: Η θέση επάνω μάσκας στρώσης.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Λαμβάνει ή ορίζει τις layer mask flags που χρησιμοποιούνται για τη μάσκα χρήστη / raster. Για τη διανυσματική μάσκα χρησιμοποιείται η ιδιότητα Flags.

Τιμή: Οι πραγματικές layer mask flags.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Λαμβάνει ή ορίζει τα δεδομένα μάσκας χρήστη (raster) ενός στρώματος στο αρχείο PSD. (Υπάρχει μια rasterized διανυσματική μάσκα στην ιδιότητα MaskData).

Τιμή: Τα δεδομένα εικόνας του στρώματος στην εικόνα PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Λαμβάνει ή ορίζει το ορθογώνιο (περιβάλλει) της μάσκας χρήστη στο στρώμα εικόνας PSD.

Τιμή: Το ορθογώνιο της μάσκας χρήστη.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
public void save_internalized(StreamContainer streamContainer)
```


Αποθηκεύει το [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) στο καθορισμένο  StreamContainer .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής για αποθήκευση δεδομένων. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Λαμβάνει ή ορίζει το χρώμα φόντου.

Τιμή: Το χρώμα φόντου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Λαμβάνει ή ορίζει τη θέση του κάτω raster mask που περιβάλλει στο επίπεδο εικόνας PSD.

Τιμή: Η θέση της κάτω μάσκας επιδίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Λαμβάνει ή ορίζει τη θέση του αριστερού raster mask που περιβάλλει στο επίπεδο αρχείου PSD.

Value: Η θέση αριστερής μάσκας στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Λαμβάνει ή ορίζει τη θέση του δεξιού raster mask που περιβάλλει στο επίπεδο αρχείου PSD.

Value: Η θέση δεξιάς μάσκας στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Λαμβάνει ή ορίζει τη θέση του πάνω raster mask που περιβάλλει στο επίπεδο εικόνας PSD.

Value: Η θέση επάνω μάσκας στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Λαμβάνει ή ορίζει τις layer mask flags που χρησιμοποιούνται για τη μάσκα χρήστη / raster. Για τη διανυσματική μάσκα χρησιμοποιείται η ιδιότητα Flags.

Τιμή: Οι πραγματικές layer mask flags.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Λαμβάνει ή ορίζει τα δεδομένα μάσκας χρήστη (raster) ενός στρώματος στο αρχείο PSD. (Υπάρχει μια rasterized διανυσματική μάσκα στην ιδιότητα MaskData).

Τιμή: Τα δεδομένα εικόνας του στρώματος στην εικόνα PSD.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Λαμβάνει ή ορίζει το ορθογώνιο (περιβάλλει) της μάσκας χρήστη στο στρώμα εικόνας PSD.

Τιμή: Το ορθογώνιο της μάσκας χρήστη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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


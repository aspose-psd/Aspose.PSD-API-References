---
title: "AiLayerSection"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η ενότητα στρώματος μορφής Ai"
type: docs
weight: 15
url: /el/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Η ενότητα στρώματος μορφής Ai
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Προσθέτει τη raster εικόνα. |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Λαμβάνει ή ορίζει το μπλε χρωματικό συστατικό. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Λαμβάνει ή ορίζει τον δείκτη του χρώματος. |
| [getColorNumber()](#getColorNumber--) | Λαμβάνει ή ορίζει τον αριθμό χρώματος. |
| [getData()](#getData--) | Λαμβάνει τα δεδομένα συμβολοσειράς. |
| [getDimValue()](#getDimValue--) | Λαμβάνει ή ορίζει την τιμή σκίασης ως ποσοστό. |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getGreen()](#getGreen--) | Λαμβάνει ή ορίζει το πράσινο στοιχείο χρώματος. |
| [getName()](#getName--) | Λαμβάνει ή ορίζει το όνομα του στρώματος. |
| [getRasterImages()](#getRasterImages--) | Λαμβάνει τις εικόνες raster. |
| [getRed()](#getRed--) | Λαμβάνει ή ορίζει το κόκκινο στοιχείο χρώματος. |
| [getStream_internalized()](#getStream-internalized--) | Λαμβάνει τη εσωτερική ροή |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μάσκες πολλαπλών επιπέδων. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι αμυδρό. |
| [isLocked()](#isLocked--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι κλειδωμένο. |
| [isPreview()](#isPreview--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι προεπισκόπηση. |
| [isPrinted()](#isPrinted--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι εκτυπωμένο. |
| [isShown()](#isShown--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο εμφανίζεται. |
| [isTemplate()](#isTemplate--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι επίπεδο προτύπου. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Λαμβάνει ή ορίζει το μπλε χρωματικό συστατικό. |
| [setColorIndex(int value)](#setColorIndex-int-) | Λαμβάνει ή ορίζει τον δείκτη του χρώματος. |
| [setColorNumber(int value)](#setColorNumber-int-) | Λαμβάνει ή ορίζει τον αριθμό χρώματος. |
| [setDimValue(int value)](#setDimValue-int-) | Λαμβάνει ή ορίζει την τιμή σκίασης ως ποσοστό. |
| [setGreen(int value)](#setGreen-int-) | Λαμβάνει ή ορίζει το πράσινο στοιχείο χρώματος. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι αμυδρό. |
| [setLocked(boolean value)](#setLocked-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι κλειδωμένο. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μάσκες πολλαπλών επιπέδων. |
| [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του στρώματος. |
| [setPreview(boolean value)](#setPreview-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι προεπισκόπηση. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι εκτυπωμένο. |
| [setRed(int value)](#setRed-int-) | Λαμβάνει ή ορίζει το κόκκινο στοιχείο χρώματος. |
| [setShown(boolean value)](#setShown-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο εμφανίζεται. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι επίπεδο προτύπου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Προσθέτει τη raster εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | Η εικόνα raster. |

### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |
| ιδιότητες | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Λαμβάνει ή ορίζει το μπλε χρωματικό συστατικό.

Τιμή: Το μπλε στοιχείο χρώματος.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Λαμβάνει ή ορίζει το δείκτη του χρώματος. Αυτό το όρισμα μπορεί να έχει τιμές μεταξύ \\u20131 και 26. Κάθε ακέραιος αντιπροσωπεύει ένα χρώμα που μπορεί να ανατεθεί στο επίπεδο για σκοπούς ταυτοποίησης χρήστη.

Τιμή: Ο δείκτης του χρώματος.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Λαμβάνει ή ορίζει τον αριθμό χρώματος. -1 είναι η προσαρμοσμένη τιμή χρώματος από τις ιδιότητες Red, Green, Blue. Καθορίζει τη ρύθμιση χρώματος του layer\\u2019s.

Τιμή: Ο αριθμός χρώματος.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Λαμβάνει τα δεδομένα συμβολοσειράς.

**Returns:**
java.lang.String - Τα δεδομένα συμβολοσειράς της ενότητας
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Λαμβάνει ή ορίζει την τιμή αμυδρότητας ως ποσοστό. Μειώνει την ένταση των συνδεδεμένων εικόνων και των bitmap εικόνων που περιέχονται στο επίπεδο στο καθορισμένο ποσοστό.

Τιμή: Η τιμή αμυδρότητας ως ποσοστό.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Λαμβάνει ή ορίζει το πράσινο στοιχείο χρώματος.

Τιμή: Το πράσινο στοιχείο χρώματος.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει ή ορίζει το όνομα του επιπέδου. Καθορίζει το όνομα του αντικειμένου όπως εμφανίζεται στον πίνακα Layers panel.

Τιμή: Το όνομα του στρώματος.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Λαμβάνει τις εικόνες raster.

Τιμή: Οι εικόνες raster.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Λαμβάνει ή ορίζει το κόκκινο στοιχείο χρώματος.

Τιμή: Το κόκκινο στοιχείο χρώματος.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Λαμβάνει τη εσωτερική ροή

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μάσκες πολλαπλών επιπέδων.

Τιμή:  true  εάν αυτή η παρουσία έχει μάσκες πολλαπλών επιπέδων· διαφορετικά,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι αμυδρό. Μειώνει την ένταση των συνδεδεμένων εικόνων και των bitmap εικόνων που περιέχονται στο επίπεδο.

Τιμή:  true  εάν αυτό το επίπεδο είναι αμυδρό· διαφορετικά,  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι κλειδωμένη. Αποτρέπει τις αλλαγές στο στοιχείο.

Τιμή:  true  εάν αυτή η στρώση είναι κλειδωμένη; διαφορετικά,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι προεπισκόπηση. Εμφανίζει το έργο τέχνης που περιέχεται στη στρώση σε χρώμα αντί για περιγράμματα.

Τιμή:  true  εάν αυτή η στρώση είναι προεπισκόπηση; διαφορετικά,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι εκτυπώσιμη. Καθιστά το έργο τέχνης που περιέχεται στη στρώση εκτυπώσιμο εάν είναι true.

Τιμή:  true  εάν αυτή η στρώση είναι εκτυπώσιμη; διαφορετικά,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι εμφανιζόμενη. Εμφανίζει όλο το έργο τέχνης που περιέχεται στη στρώση στον πίνακα σχεδίασης εάν είναι true.

Τιμή:  true  εάν αυτή η στρώση είναι εμφανιζόμενη; διαφορετικά,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι επίπεδο προτύπου.

Τιμή:  true  εάν αυτή η στρώση είναι πρότυπο; διαφορετικά,  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Λαμβάνει ή ορίζει το μπλε χρωματικό συστατικό.

Τιμή: Το μπλε στοιχείο χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Λαμβάνει ή ορίζει το δείκτη του χρώματος. Αυτό το όρισμα μπορεί να έχει τιμές μεταξύ \\u20131 και 26. Κάθε ακέραιος αντιπροσωπεύει ένα χρώμα που μπορεί να ανατεθεί στο επίπεδο για σκοπούς ταυτοποίησης χρήστη.

Τιμή: Ο δείκτης του χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Λαμβάνει ή ορίζει τον αριθμό χρώματος. -1 είναι η προσαρμοσμένη τιμή χρώματος από τις ιδιότητες Red, Green, Blue. Καθορίζει τη ρύθμιση χρώματος του layer\\u2019s.

Τιμή: Ο αριθμός χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Λαμβάνει ή ορίζει την τιμή αμυδρότητας ως ποσοστό. Μειώνει την ένταση των συνδεδεμένων εικόνων και των bitmap εικόνων που περιέχονται στο επίπεδο στο καθορισμένο ποσοστό.

Τιμή: Η τιμή αμυδρότητας ως ποσοστό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Λαμβάνει ή ορίζει το πράσινο στοιχείο χρώματος.

Τιμή: Το πράσινο στοιχείο χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι αμυδρό. Μειώνει την ένταση των συνδεδεμένων εικόνων και των bitmap εικόνων που περιέχονται στο επίπεδο.

Τιμή:  true  εάν αυτό το επίπεδο είναι αμυδρό· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι κλειδωμένη. Αποτρέπει τις αλλαγές στο στοιχείο.

Τιμή:  true  εάν αυτή η στρώση είναι κλειδωμένη; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μάσκες πολλαπλών επιπέδων.

Τιμή:  true  εάν αυτή η παρουσία έχει μάσκες πολλαπλών επιπέδων· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Λαμβάνει ή ορίζει το όνομα του επιπέδου. Καθορίζει το όνομα του αντικειμένου όπως εμφανίζεται στον πίνακα Layers panel.

Τιμή: Το όνομα του στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι προεπισκόπηση. Εμφανίζει το έργο τέχνης που περιέχεται στη στρώση σε χρώμα αντί για περιγράμματα.

Τιμή:  true  εάν αυτή η στρώση είναι προεπισκόπηση; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι εκτυπώσιμη. Καθιστά το έργο τέχνης που περιέχεται στη στρώση εκτυπώσιμο εάν είναι true.

Τιμή:  true  εάν αυτή η στρώση είναι εκτυπώσιμη; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Λαμβάνει ή ορίζει το κόκκινο στοιχείο χρώματος.

Τιμή: Το κόκκινο στοιχείο χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η στρώση είναι εμφανιζόμενη. Εμφανίζει όλο το έργο τέχνης που περιέχεται στη στρώση στον πίνακα σχεδίασης εάν είναι true.

Τιμή:  true  εάν αυτή η στρώση είναι εμφανιζόμενη; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το επίπεδο είναι επίπεδο προτύπου.

Τιμή:  true  εάν αυτή η στρώση είναι πρότυπο; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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


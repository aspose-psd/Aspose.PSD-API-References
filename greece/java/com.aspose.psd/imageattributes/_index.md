---
title: "ImageAttributes"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ένα αντικείμενο com.aspose.psd.ImageAttributes περιέχει πληροφορίες σχετικά με το πώς τα χρώματα bitmap και metafile τροποποιούνται κατά την απόδοση."
type: docs
weight: 55
url: /el/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

Ένα αντικείμενο com.aspose.psd.ImageAttributes περιέχει πληροφορίες σχετικά με το πώς τα χρώματα bitmap και metafile τροποποιούνται κατά την απόδοση. Ένα αντικείμενο com.aspose.psd.ImageAttributes διατηρεί πολλές ρυθμίσεις προσαρμογής χρώματος, συμπεριλαμβανομένων πινάκων προσαρμογής χρώματος, πινάκων προσαρμογής σε αποχρώσεις του γκρι, τιμών διόρθωσης γάμμα, πινάκων αντιστοίχισης χρωμάτων και τιμών κατωφλίου χρώματος. Κατά την απόδοση, τα χρώματα μπορούν να διορθωθούν, να σκουραθούν, να φωτιστούν και να αφαιρεθούν. Για να εφαρμόσετε τέτοιες τροποποιήσεις, αρχικοποιήστε ένα αντικείμενο com.aspose.psd.ImageAttributes και περάστε τη διαδρομή αυτού του αντικειμένου com.aspose.psd.ImageAttributes (μαζί με τη διαδρομή ενός [Image](../../com.aspose.psd/image)) στη μέθοδο drawImage.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | Αρχικοποιεί μια νέα παρουσία της κλάσης com.aspose.psd.ImageAttributes. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | Τα χαρακτηριστικά εικόνας GDI. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος πινέλου αυτού του αντικειμένου com.aspose.psd.ImageAttributes. |
| [clearColorKey()](#clearColorKey--) | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [clearColorKey(int type)](#clearColorKey-int-) | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [clearColorMatrix()](#clearColorMatrix--) | Καθαρίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία. |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | Καθαρίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία. |
| [clearGamma()](#clearGamma--) | Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία. |
| [clearGamma(int type)](#clearGamma-int-) | Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία. |
| [clearNoOp()](#clearNoOp--) | Καθαρίζει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία. |
| [clearNoOp(int type)](#clearNoOp-int-) | Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία. |
| [clearOutputChannel()](#clearOutputChannel--) | Καθαρίζει τη ρύθμιση εξόδου καναλιού CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | Καθαρίζει τη ρύθμιση εξόδου καναλιού (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | Καθαρίζει τη ρύθμιση προφίλ χρώματος εξόδου καναλιού για την προεπιλεγμένη κατηγορία. |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | Καθαρίζει τη ρύθμιση προφίλ χρώματος εξόδου καναλιού για μια καθορισμένη κατηγορία. |
| [clearRemapTable()](#clearRemapTable--) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [clearRemapTable(int type)](#clearRemapTable-int-) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [clearThreshold()](#clearThreshold--) | Καθαρίζει την τιμή κατωφλίου για την προεπιλεγμένη κατηγορία. |
| [clearThreshold(int type)](#clearThreshold-int-) | Καθαρίζει την τιμή κατωφλίου για μια καθορισμένη κατηγορία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου. |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία. |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία. |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για μια καθορισμένη κατηγορία. |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | Ορίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία. |
| [setGamma(float gamma)](#setGamma-float-) | Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία. |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία. |
| [setNoOp()](#setNoOp--) | Απενεργοποιεί τη ρύθμιση χρώματος για την προεπιλεγμένη κατηγορία. |
| [setNoOp(int type)](#setNoOp-int-) | Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία. |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [setThreshold(float threshold)](#setThreshold-float-) | Ορίζει το κατώφλι (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | Ορίζει το κατώφλι (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [setWrapMode(int mode)](#setWrapMode-int-) | Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης com.aspose.psd.ImageAttributes.

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


Τα χαρακτηριστικά εικόνας GDI.

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος πινέλου αυτού του αντικειμένου com.aspose.psd.ImageAttributes.

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία.

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία το κλειδί χρώματος διαγράφεται. |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


Καθαρίζει τον πίνακα προσαρμογής χρώματος για την προεπιλεγμένη κατηγορία.

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


Καθαρίζει τον πίνακα προσαρμογής χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ο πίνακας ρύθμισης χρώματος διαγράφεται. |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία.

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία η διόρθωση γάμμα είναι απενεργοποιημένη. |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


Καθαρίζει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία.

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία η ρύθμιση NoOp διαγράφεται. |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


Καθαρίζει τη ρύθμιση εξόδου καναλιού CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία.

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


Καθαρίζει τη ρύθμιση εξόδου καναλιού (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία η ρύθμιση καναλιού εξόδου διαγράφεται. |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


Καθαρίζει τη ρύθμιση προφίλ χρώματος εξόδου καναλιού για την προεπιλεγμένη κατηγορία.

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


Καθαρίζει τη ρύθμιση προφίλ χρώματος εξόδου καναλιού για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία η ρύθμιση προφίλ καναλιού εξόδου διαγράφεται. |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία.

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ο πίνακας επαναχαρτογράφησης διαγράφεται. |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


Καθαρίζει την τιμή κατωφλίου για την προεπιλεγμένη κατηγορία.

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


Καθαρίζει την τιμή κατωφλίου για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία το όριο διαγράφεται. |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Ένας πίνακας αντικειμένων  com.aspose.psd.ColorMap . |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Η χαμηλή τιμή κλειδιού χρώματος. |
| colorHigh | [Color](../../com.aspose.psd/color) | Η υψηλή τιμή κλειδιού χρώματος. |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | Η χαμηλή τιμή κλειδιού χρώματος. |
| colorHigh | [Color](../../com.aspose.psd/color) | Η υψηλή τιμή κλειδιού χρώματος. |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται το κλειδί χρώματος. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |
| σημαίες | int | Ένα στοιχείο του  Aspose.Imaging.ColorMatrixFlag  που καθορίζει τον τύπο εικόνας και χρώματος που θα επηρεαστεί από τους πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |
| mode | int | Ένα στοιχείο του  Aspose.Imaging.ColorMatrixFlag  που καθορίζει τον τύπο εικόνας και χρώματος που θα επηρεαστεί από τους πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζονται οι πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| σημαίες | int | Ένα στοιχείο του  Aspose.Imaging.ColorMatrixFlag  που καθορίζει τον τύπο εικόνας και χρώματος που θα επηρεαστεί από τον πίνακα προσαρμογής χρώματος. |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


Ορίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| mode | int | Ένα στοιχείο του  Aspose.Imaging.ColorMatrixFlag  που καθορίζει τον τύπο εικόνας και χρώματος που θα επηρεαστεί από τον πίνακα προσαρμογής χρώματος. |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται ο πίνακας προσαρμογής χρώματος. |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| gamma | float | Η τιμή διόρθωσης γάμμα. |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| gamma | float | Η τιμή διόρθωσης γάμμα. |
| τύπος | int | Ένα στοιχείο της απαρίθμησης  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται η τιμή γάμμα. |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


Απενεργοποιεί τη ρύθμιση χρώματος για την προεπιλεγμένη κατηγορία.

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία η διόρθωση χρώματος απενεργοποιείται. |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σημαίες | int | Ένα στοιχείο του  Aspose.Imaging.ColorChannelFlag  που καθορίζει το κανάλι εξόδου. |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σημαίες | int | Ένα στοιχείο του  Aspose.Imaging.ColorChannelFlag  που καθορίζει το κανάλι εξόδου. |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται το κανάλι εξόδου. |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Το όνομα διαδρομής ενός αρχείου προφίλ χρώματος. Εάν το αρχείο προφίλ χρώματος βρίσκεται στον κατάλογο %SystemRoot%\\System32\\Spool\\Drivers\\Color, αυτή η παράμετρος μπορεί να είναι το όνομα του αρχείου. Διαφορετικά, αυτή η παράμετρος πρέπει να είναι το πλήρως προσδιορισμένο όνομα διαδρομής. |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | Το όνομα διαδρομής ενός αρχείου προφίλ χρώματος. Εάν το αρχείο προφίλ χρώματος βρίσκεται στον κατάλογο %SystemRoot%\\System32\\Spool\\Drivers\\Color, αυτή η παράμετρος μπορεί να είναι το όνομα του αρχείου. Διαφορετικά, αυτή η παράμετρος πρέπει να είναι το πλήρως προσδιορισμένο όνομα διαδρομής. |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται το αρχείο προφίλ χρώματος του καναλιού εξόδου. |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Ένας πίνακας ζευγών χρωμάτων τύπου  com.aspose.psd.ColorMap . Κάθε ζεύγος χρωμάτων περιέχει ένα υπάρχον χρώμα (η πρώτη τιμή) και το χρώμα στο οποίο θα αντιστοιχιστεί (η δεύτερη τιμή). |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | Ένας πίνακας ζευγών χρωμάτων τύπου  com.aspose.psd.ColorMap . Κάθε ζεύγος χρωμάτων περιέχει ένα υπάρχον χρώμα (η πρώτη τιμή) και το χρώμα στο οποίο θα αντιστοιχιστεί (η δεύτερη τιμή). |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται ο πίνακας επαναχρωματισμού. |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


Ορίζει το κατώφλι (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Ένας πραγματικός αριθμός που καθορίζει την τιμή κατωφλίου. |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


Ορίζει το κατώφλι (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Μια τιμή κατωφλίου από 0.0 έως 1.0 που χρησιμοποιείται ως σημείο διακοπής για την ταξινόμηση χρωμάτων που θα αντιστοιχιστούν είτε σε μέγιστη είτε σε ελάχιστη τιμή. |
| τύπος | int | Ένα στοιχείο του  Aspose.Imaging.ColorAdjustType  που καθορίζει την κατηγορία για την οποία ορίζεται το κατώφλι χρώματος. |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Ένα στοιχείο του  Aspose.Imaging.WrapMode  που καθορίζει πώς χρησιμοποιούνται οι επαναλαμβανόμενα αντίγραφα μιας εικόνας για την κάλυψη μιας περιοχής. |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί μια υφή σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Ένα στοιχείο του  Aspose.Imaging.WrapMode  που καθορίζει πώς χρησιμοποιούνται οι επαναλαμβανόμενα αντίγραφα μιας εικόνας για την κάλυψη μιας περιοχής. |
| color | [Color](../../com.aspose.psd/color) | Ένα αντικείμενο  com.aspose.psd.ImageAttributes  που καθορίζει το χρώμα των εικονοστοιχείων εκτός μιας αποδοθείσας εικόνας. Αυτό το χρώμα είναι ορατό εάν η παράμετρος λειτουργίας οριστεί σε  WrapMode.Clamp  και το πηγαίο ορθογώνιο που περνιέται στο DrawImage είναι μεγαλύτερο από την ίδια την εικόνα. |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί μια υφή σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Ένα στοιχείο του  Aspose.Imaging.WrapMode  που καθορίζει πώς χρησιμοποιούνται οι επαναλαμβανόμενα αντίγραφα μιας εικόνας για την κάλυψη μιας περιοχής. |
| color | [Color](../../com.aspose.psd/color) | Ένα αντικείμενο χρώματος που καθορίζει το χρώμα των εικονοστοιχείων εκτός μιας αποδοθείσας εικόνας. Αυτό το χρώμα είναι ορατό εάν η παράμετρος λειτουργίας οριστεί σε  WrapMode.Clamp  και το πηγαίο ορθογώνιο που περνιέται στο DrawImage είναι μεγαλύτερο από την ίδια την εικόνα. |
| συσπασμός | boolean | Αυτή η παράμετρος δεν έχει καμία επίδραση. Ορίστε την σε ψευδές. |

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


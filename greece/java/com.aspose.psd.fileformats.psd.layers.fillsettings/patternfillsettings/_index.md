---
title: "PatternFillSettings"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ρυθμίσεις εφέ γεμίσματος μοτίβου"
type: docs
weight: 20
url: /el/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Ρυθμίσεις εφέ γεμίσματος μοτίβου
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Δημιουργεί τους κόμβους πόρων LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [link with layer]. |
| [getAngle()](#getAngle--) | Λαμβάνει ή ορίζει τη γωνία. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Λαμβάνει ή ορίζει το χρώμα. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Ο τύπος γεμίσματος |
| [getHorizontalOffset()](#getHorizontalOffset--) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| [getLinked()](#getLinked--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) είναι linked. |
| [getPatternData()](#getPatternData--) | Λαμβάνει ή ορίζει τα δεδομένα του μοτίβου. |
| [getPatternHeight()](#getPatternHeight--) | Λαμβάνει ή ορίζει το ύψος του μοτίβου. |
| [getPatternId()](#getPatternId--) | Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου. |
| [getPatternName()](#getPatternName--) | Λαμβάνει ή ορίζει το όνομα του μοτίβου. |
| [getPatternWidth()](#getPatternWidth--) | Λαμβάνει ή ορίζει το πλάτος του μοτίβου. |
| [getPhase_internalized()](#getPhase-internalized--) | Λαμβάνει ή ορίζει τη φάση. |
| [getPointType()](#getPointType--) | Λαμβάνει ή ορίζει τον τύπο του σημείου. |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την κλίμακα. |
| [getVerticalOffset()](#getVerticalOffset--) | Λαμβάνει ή ορίζει την κάθετη μετατόπιση. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Εγείρει την αλλαγή τιμής. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει το χρώμα. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| [setLinked(boolean value)](#setLinked-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) είναι linked. |
| [setPatternData(int[] value)](#setPatternData-int---) | Λαμβάνει ή ορίζει τα δεδομένα του μοτίβου. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Ορίζει το buffer εικονοστοιχείων του μοτίβου και τη λειτουργία συμπίεσης που θα χρησιμοποιηθεί κατά την αποθήκευση. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Λαμβάνει ή ορίζει το ύψος του μοτίβου. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του μοτίβου. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Λαμβάνει ή ορίζει το πλάτος του μοτίβου. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Λαμβάνει ή ορίζει τη φάση. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Λαμβάνει ή ορίζει τον τύπο του σημείου. |
| [setScale(double value)](#setScale-double-) | Λαμβάνει ή ορίζει την κλίμακα. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Λαμβάνει ή ορίζει την κάθετη μετατόπιση. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Ρυθμίζει τα προεπιλεγμένα δεδομένα του μοτίβου σε παρουσία [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Ενημερώνει τις ιδιότητες του μοτίβου από την παρουσία [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Δημιουργεί τους κόμβους πόρων LFX2.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pointType | java.lang.String | Τύπος του σημείου. |
| color | [Color](../../com.aspose.psd/color) | Το χρώμα. |
| patternName | java.lang.String | Όνομα του μοτίβου. |
| identifier | java.lang.String | Το αναγνωριστικό. |
| κλίμακα | double | Η κλίμακα. |
| συνδεδεμένο | boolean | αν έχει οριστεί σε  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | Η μετατόπιση. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Λίστα των [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [link with layer].

Τιμή:  true  αν [link with layer]; διαφορετικά,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Λαμβάνει ή ορίζει τη γωνία.

Τιμή: Η γωνία.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Λαμβάνει ή ορίζει το χρώμα.

Value: Το χρώμα.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


Ο τύπος γεμίσματος

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση.

Τιμή: Η οριζόντια μετατόπιση.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) είναι linked.

Τιμή:  true  αν συνδεδεμένο; διαφορετικά,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Λαμβάνει ή ορίζει τα δεδομένα του μοτίβου.

Τιμή: Τα δεδομένα του μοτίβου.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Λαμβάνει ή ορίζει το ύψος του μοτίβου.

Τιμή: Το ύψος του μοτίβου.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου.

Τιμή: Το αναγνωριστικό του μοτίβου.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Λαμβάνει ή ορίζει το όνομα του μοτίβου.

Τιμή: Το όνομα του μοτίβου.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Λαμβάνει ή ορίζει το πλάτος του μοτίβου.

Τιμή: Το πλάτος του μοτίβου.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Λαμβάνει ή ορίζει τη φάση.

Τιμή: Η φάση.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Λαμβάνει ή ορίζει τον τύπο του σημείου.

Τιμή: Ο τύπος του σημείου.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Λαμβάνει ή ορίζει την κλίμακα.

Τιμή: Η κλίμακα.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Λαμβάνει ή ορίζει την κάθετη μετατόπιση.

Τιμή: Η κατακόρυφη μετατόπιση.

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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Εγείρει την αλλαγή τιμής.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [link with layer].

Τιμή:  true  αν [link with layer]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία.

Τιμή: Η γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Λαμβάνει ή ορίζει το χρώμα.

Value: Το χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση.

Τιμή: Η οριζόντια μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) είναι linked.

Τιμή:  true  αν συνδεδεμένο; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Λαμβάνει ή ορίζει τα δεδομένα του μοτίβου.

Τιμή: Τα δεδομένα του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Ορίζει το buffer εικονοστοιχείων του μοτίβου και τη λειτουργία συμπίεσης που θα χρησιμοποιηθεί κατά την αποθήκευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| patternData | int[] | 32-bit pixel σε  0xAARRGGBB . |
| compressionModeOnSave | byte | Η λειτουργία συμπίεσης που χρησιμοποιείται για τον ορισμό της συμπίεσης των δεδομένων μοτίβου κατά την αποθήκευση αρχείου psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Λαμβάνει ή ορίζει το ύψος του μοτίβου.

Τιμή: Το ύψος του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου.

Τιμή: Το αναγνωριστικό του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Λαμβάνει ή ορίζει το όνομα του μοτίβου.

Τιμή: Το όνομα του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Λαμβάνει ή ορίζει το πλάτος του μοτίβου.

Τιμή: Το πλάτος του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Λαμβάνει ή ορίζει τη φάση.

Τιμή: Η φάση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Λαμβάνει ή ορίζει τον τύπο του σημείου.

Τιμή: Ο τύπος του σημείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Λαμβάνει ή ορίζει την κλίμακα.

Τιμή: Η κλίμακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Λαμβάνει ή ορίζει την κάθετη μετατόπιση.

Τιμή: Η κατακόρυφη μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Ρυθμίζει τα προεπιλεγμένα δεδομένα του μοτίβου σε παρουσία [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Οι ρυθμίσεις γεμίσματος μοτίβου. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


Ενημερώνει τις ιδιότητες του μοτίβου από την παρουσία [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Η παρουσία [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) με δεδομένα μοτίβου. |

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


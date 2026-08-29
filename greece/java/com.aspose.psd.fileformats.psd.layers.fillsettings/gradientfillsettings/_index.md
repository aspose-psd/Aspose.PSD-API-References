---
title: "GradientFillSettings"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ρυθμίσεις εφέ γεμίσματος διαβάθμισης."
type: docs
weight: 14
url: /el/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Ρυθμίσεις εφέ γεμίσματος διαβάθμισης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [getAngle()](#getAngle--) | Λαμβάνει ή ορίζει τη γωνία. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Λαμβάνει ή ορίζει τα όρια του container του layer για να υπολογίζει σωστά τη θέση του gradient. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Υπολογίζει και επιστρέφει την  **denormalized**  κλίμακα κλίσης (UI Scale) που αντιστοιχεί στην τρέχουσα τιμή του  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι dither. |
| [getFillType()](#getFillType--) | Ο τύπος γεμίσματος. |
| [getGradient()](#getGradient--) | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [getReverse()](#getReverse--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι reverse. |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό) |
| [getVerticalOffset()](#getVerticalOffset--) | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Εγείρει την αλλαγή τιμής. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Λαμβάνει ή ορίζει τα όρια του container του layer για να υπολογίζει σωστά τη θέση του gradient. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Μετατρέπει την καθορισμένη μη κανονικοποιημένη κλίμακα (UI) σε τιμή στην  **normalized**  ισοδύναμη και την αντιστοιχίζει στο  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [setReverse(boolean value)](#setReverse-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι reverse. |
| [setScale(int value)](#setScale-int-) | Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer].

Τιμή:  true  εάν [align with layer]; διαφορετικά,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Λαμβάνει ή ορίζει τη γωνία.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Λαμβάνει ή ορίζει τα όρια του container του layer για να υπολογίζει σωστά τη θέση του gradient.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Υπολογίζει και επιστρέφει την  **denormalized**  κλίμακα κλίσης (UI Scale) που αντιστοιχεί στην τρέχουσα τιμή του  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Τα όρια της κλίσης. |

**Returns:**
int - Η μη κανονικοποιημένη (UI) κλίμακα σε ποσοστό όπως εμφανίζεται στο Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι dither.

Τιμή:  true  εάν dither· διαφορετικά,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Ο τύπος γεμίσματος.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Λαμβάνει ή ορίζει τον τύπο του gradient.

Τιμή: Ο τύπος του gradient.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό.

Τιμή: Η οριζόντια μετατόπιση.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό)

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό.

Τιμή: Η κατακόρυφη μετατόπιση.

**Returns:**
double
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


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer].

Τιμή:  true  εάν [align with layer]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Λαμβάνει ή ορίζει τα όρια του container του layer για να υπολογίζει σωστά τη θέση του gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Μετατρέπει την καθορισμένη μη κανονικοποιημένη κλίμακα (UI) σε τιμή στην  **normalized**  ισοδύναμη και την αντιστοιχίζει στο  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). Η μετατροπή εφαρμόζει την τρέχουσα γωνία της gradient\\u2019s ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) και το παρεχόμενο  fillArea  για να υπολογίσει τον παράγοντα κανονικοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η μη κανονικοποιημένη κλίμακα, UI Scale σε ποσοστό όπως εμφανίζεται στο Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | Τα όρια της κλίσης. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι dither.

Τιμή:  true  εάν dither· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του gradient.

Τιμή: Ο τύπος του gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό.

Τιμή: Η οριζόντια μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό.

Τιμή: Η κατακόρυφη μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

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


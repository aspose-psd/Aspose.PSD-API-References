---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση ορισμού διαβάθμισης θορύβου."
type: docs
weight: 18
url: /el/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Κλάση ορισμού διαβάθμισης θορύβου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) class. |
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
| [getColorModel()](#getColorModel--) | Λαμβάνει ή ορίζει το Μοντέλο Χρώματος - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither. |
| [getExpansionCount()](#getExpansionCount--) | Λαμβάνει ή ορίζει τον αριθμό Επέκτασης ( = 2 για Photoshop 6.0). |
| [getFillType()](#getFillType--) | Ο τύπος γεμίσματος. |
| [getGradientMode()](#getGradientMode--) | Λαμβάνει τη λειτουργία για αυτό το gradient. |
| [getGradientName()](#getGradientName--) | Λαμβάνει ή ορίζει το όνομα του gradient. |
| [getGradientType()](#getGradientType--) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [getMaximumColor()](#getMaximumColor--) | Λαμβάνει ή ορίζει το Μέγιστο χρώμα του PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Λαμβάνει ή ορίζει το Ελάχιστο χρώμα του PixelDataFormat. |
| [getReverse()](#getReverse--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Λαμβάνει ή ορίζει τον σπόρο τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για το Noise gradient. |
| [getRoughness()](#getRoughness--) | Λαμβάνει ή ορίζει τον συντελεστή τραχύτητας. |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την κλίμακα. |
| [getShowTransparency()](#getShowTransparency--) | Λαμβάνει ή ορίζει τη σημαία για εμφάνιση διαφάνειας. |
| [getUseVectorColor()](#getUseVectorColor--) | Λαμβάνει ή ορίζει τη σημαία για χρήση διανυσματικού χρώματος. |
| [getVerticalOffset()](#getVerticalOffset--) | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Εγείρει την αλλαγή τιμής. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία. |
| [setColorModel(short value)](#setColorModel-short-) | Λαμβάνει ή ορίζει το Μοντέλο Χρώματος - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Λαμβάνει ή ορίζει τον αριθμό Επέκτασης ( = 2 για Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Λαμβάνει τη λειτουργία για αυτό το gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του gradient. |
| [setGradientType(int value)](#setGradientType-int-) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Λαμβάνει ή ορίζει το Μέγιστο χρώμα του PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Λαμβάνει ή ορίζει το Ελάχιστο χρώμα του PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Λαμβάνει ή ορίζει τον σπόρο τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για το Noise gradient. |
| [setRoughness(int value)](#setRoughness-int-) | Λαμβάνει ή ορίζει τον συντελεστή τραχύτητας. |
| [setScale(int value)](#setScale-int-) | Λαμβάνει ή ορίζει την κλίμακα. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Λαμβάνει ή ορίζει τη σημαία για εμφάνιση διαφάνειας. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Λαμβάνει ή ορίζει τη σημαία για χρήση διανυσματικού χρώματος. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) class.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Λαμβάνει ή ορίζει το Μοντέλο Χρώματος - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither.

Τιμή:  true  εάν dither· διαφορετικά,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Λαμβάνει ή ορίζει τον αριθμό Επέκτασης ( = 2 για Photoshop 6.0).

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


Ο τύπος γεμίσματος.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Λαμβάνει τη λειτουργία για αυτό το gradient. Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Λαμβάνει ή ορίζει το όνομα του gradient.

Τιμή: Το όνομα του gradient.

**Returns:**
java.lang.String
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Λαμβάνει ή ορίζει το Μέγιστο χρώμα του PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Λαμβάνει ή ορίζει το Ελάχιστο χρώμα του PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Λαμβάνει ή ορίζει τον σπόρο τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για το Noise gradient.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Λαμβάνει ή ορίζει τον συντελεστή τραχύτητας.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Λαμβάνει ή ορίζει την κλίμακα.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Λαμβάνει ή ορίζει τη σημαία για εμφάνιση διαφάνειας.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Λαμβάνει ή ορίζει τη σημαία για χρήση διανυσματικού χρώματος.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Λαμβάνει ή ορίζει το Μοντέλο Χρώματος - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither.

Τιμή:  true  εάν dither· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Λαμβάνει ή ορίζει τον αριθμό Επέκτασης ( = 2 για Photoshop 6.0).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Λαμβάνει τη λειτουργία για αυτό το gradient. Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Λαμβάνει ή ορίζει το όνομα του gradient.

Τιμή: Το όνομα του gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Λαμβάνει ή ορίζει το Μέγιστο χρώμα του PixelDataFormat.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Λαμβάνει ή ορίζει το Ελάχιστο χρώμα του PixelDataFormat.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Λαμβάνει ή ορίζει τον σπόρο τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για το Noise gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Λαμβάνει ή ορίζει τον συντελεστή τραχύτητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Λαμβάνει ή ορίζει την κλίμακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για εμφάνιση διαφάνειας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία για χρήση διανυσματικού χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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


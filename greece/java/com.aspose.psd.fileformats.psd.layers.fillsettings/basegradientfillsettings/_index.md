---
title: "BaseGradientFillSettings"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Βασική κλάση ορισμού διαβάθμισης."
type: docs
weight: 11
url: /el/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Κλάση ορισμού Base gradient. Περιέχει κοινές ιδιότητες για και τους δύο τύπους gradient (Solid και Noise).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings). |
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
| [getDither()](#getDither--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither. |
| [getFillType()](#getFillType--) | Ο τύπος γεμίσματος. |
| [getGradientMode()](#getGradientMode--) | Λαμβάνει τη λειτουργία για αυτό το gradient. |
| [getGradientName()](#getGradientName--) | Λαμβάνει ή ορίζει το όνομα του gradient. |
| [getGradientType()](#getGradientType--) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [getReverse()](#getReverse--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse. |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την κλίμακα. |
| [getVerticalOffset()](#getVerticalOffset--) | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Εγείρει την αλλαγή τιμής. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία. |
| [setDither(boolean value)](#setDither-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Λαμβάνει τη λειτουργία για αυτό το gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του gradient. |
| [setGradientType(int value)](#setGradientType-int-) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| [setReverse(boolean value)](#setReverse-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse. |
| [setScale(int value)](#setScale-int-) | Λαμβάνει ή ορίζει την κλίμακα. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση σε ποσοστό. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings).

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
### getDither() {#getDither--}
```
public final boolean getDither()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι dither.

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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Λαμβάνει ή ορίζει την κλίμακα.

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

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Λαμβάνει ή ορίζει την κλίμακα.

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


---
title: "IGradientFillSettings"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Βασική διεπαφή για τις ρυθμίσεις γεμίσματος διαβάθμισης."
type: docs
weight: 23
url: /el/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Βασική διεπαφή για τις ρυθμίσεις γεμίσματος διαβάθμισης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [getAngle()](#getAngle--) | Λαμβάνει ή ορίζει τη γωνία. |
| [getDither()](#getDither--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι dither. |
| [getGradient()](#getGradient--) | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [getReverse()](#getReverse--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι reverse. |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό). |
| [getVerticalOffset()](#getVerticalOffset--) | Λαμβάνει ή ορίζει την κάθετη μετατόπιση. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία. |
| [setDither(boolean value)](#setDither-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [setReverse(boolean value)](#setReverse-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι reverse. |
| [setScale(int value)](#setScale-int-) | Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Λαμβάνει ή ορίζει την κάθετη μετατόπιση. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer].

Τιμή:  true  εάν [align with layer]; διαφορετικά,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Λαμβάνει ή ορίζει τη γωνία.

Τιμή: Η γωνία.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι dither.

Τιμή:  true  εάν dither· διαφορετικά,  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Λαμβάνει ή ορίζει τον τύπο του gradient.

Τιμή: Ο τύπος του gradient.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση.

Τιμή: Η οριζόντια μετατόπιση.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό).

Τιμή: Η κλίμακα.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Λαμβάνει ή ορίζει την κάθετη μετατόπιση.

Τιμή: Η κατακόρυφη μετατόπιση.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer].

Τιμή:  true  εάν [align with layer]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία.

Τιμή: Η γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι dither.

Τιμή:  true  εάν dither· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Λαμβάνει ή ορίζει συγκεκριμένη παρουσία ορισμού διαβάθμισης (Solid/Noise).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του gradient.

Τιμή: Ο τύπος του gradient.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Λαμβάνει ή ορίζει την οριζόντια μετατόπιση.

Τιμή: Η οριζόντια μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) είναι reverse.

Τιμή:  true  εάν reverse· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Λαμβάνει ή ορίζει την  **normalized**  κλίμακα κλίσης (σε ποσοστό).

Τιμή: Η κλίμακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Λαμβάνει ή ορίζει την κάθετη μετατόπιση.

Τιμή: Η κατακόρυφη μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |


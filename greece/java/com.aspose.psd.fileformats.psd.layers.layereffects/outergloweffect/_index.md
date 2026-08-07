---
title: "OuterGlowEffect"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Εφέ εξωτερικής λάμψης στρώματος"
type: docs
weight: 15
url: /el/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Εφέ εξωτερικής λάμψης στρώματος
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Υπολογίζει και λαμβάνει τα όρια των εικονοστοιχείων εφέ βάσει των ορίων των εικονοστοιχείων εισόδου του στρώματος. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Λαμβάνει την οντότητα |
| [getEffectType()](#getEffectType--) | Λαμβάνει έναν τύπο εφέ |
| [getFillColor()](#getFillColor--) | Λαμβάνει ή ορίζει το χρώμα. |
| [getIntensity()](#getIntensity--) | Λαμβάνει ή ορίζει τη γωνία σε μοίρες. |
| [getJitter()](#getJitter--) | Λαμβάνει ή ορίζει τον θόρυβο. |
| [getNoise()](#getNoise--) | Λαμβάνει ή ορίζει τον θόρυβο. |
| [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [getRange()](#getRange--) | Λαμβάνει ή ορίζει τον θόρυβο. |
| [getSize()](#getSize--) | Λαμβάνει την τιμή θολώματος σε εικονοστοιχεία. |
| [getSpread()](#getSpread--) | Λαμβάνει ή ορίζει την ένταση ως ποσοστό. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Λαμβάνει ή ορίζει το ενεργοποιημένο εφέ AntiAliasing |
| [isSoftBlend()](#isSoftBlend--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [knocks out]. |
| [isVisible()](#isVisible--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Λαμβάνει ή ορίζει το ενεργοποιημένο εφέ AntiAliasing |
| [setBlendMode(long value)](#setBlendMode-long-) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Λαμβάνει ή ορίζει το χρώμα. |
| [setIntensity(int value)](#setIntensity-int-) | Λαμβάνει ή ορίζει τη γωνία σε μοίρες. |
| [setJitter(int value)](#setJitter-int-) | Λαμβάνει ή ορίζει τον θόρυβο. |
| [setNoise(int value)](#setNoise-int-) | Λαμβάνει ή ορίζει τον θόρυβο. |
| [setOpacity(byte value)](#setOpacity-byte-) | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [setRange(int value)](#setRange-int-) | Λαμβάνει ή ορίζει τον θόρυβο. |
| [setSize(int value)](#setSize-int-) | Λαμβάνει την τιμή θολώματος σε εικονοστοιχεία. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Λαμβάνει ή ορίζει την ένταση ως ποσοστό. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης.

Τιμή: Η λειτουργία ανάμειξης.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Υπολογίζει και λαμβάνει τα όρια των εικονοστοιχείων εφέ βάσει των ορίων των εικονοστοιχείων εισόδου του στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια των εικονοστοιχείων του στρώματος. |
| globalAngle | int | Η παγκόσμια γωνία για τον υπολογισμό της γωνίας παγκόσμιου φωτός. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Λαμβάνει την οντότητα

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Λαμβάνει έναν τύπο εφέ

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Λαμβάνει ή ορίζει το χρώμα.

Value: Το χρώμα.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Λαμβάνει ή ορίζει τη γωνία σε μοίρες.

Τιμή: Η γωνία.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Λαμβάνει ή ορίζει τον θόρυβο.

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Λαμβάνει ή ορίζει τον θόρυβο.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Λαμβάνει ή ορίζει τη διαφάνεια.

Τιμή: Η διαφάνεια.

**Returns:**
byte
### getRange() {#getRange--}
```
public final int getRange()
```


Λαμβάνει ή ορίζει τον θόρυβο.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Λαμβάνει την τιμή θολώματος σε εικονοστοιχεία.

Τιμή: Το μέγεθος.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Λαμβάνει ή ορίζει την ένταση ως ποσοστό.

Τιμή: Η εξάπλωση.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


Λαμβάνει ή ορίζει το ενεργοποιημένο εφέ AntiAliasing

Τιμή: Η απόσταση.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [knocks out].

Τιμή:  true  εάν [knocks out]; διαφορετικά,  false .

**Returns:**
boolean
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή.

Τιμή:  true  εάν αυτή η παρουσία είναι ορατή· διαφορετικά,  false .

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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Λαμβάνει ή ορίζει το ενεργοποιημένο εφέ AntiAliasing

Τιμή: Η απόσταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης.

Τιμή: Η λειτουργία ανάμειξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Λαμβάνει ή ορίζει το χρώμα.

Value: Το χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Λαμβάνει ή ορίζει τη γωνία σε μοίρες.

Τιμή: Η γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Λαμβάνει ή ορίζει τον θόρυβο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Λαμβάνει ή ορίζει τον θόρυβο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Λαμβάνει ή ορίζει τη διαφάνεια.

Τιμή: Η διαφάνεια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Λαμβάνει ή ορίζει τον θόρυβο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Λαμβάνει την τιμή θολώματος σε εικονοστοιχεία.

Τιμή: Το μέγεθος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [knocks out].

Τιμή:  true  εάν [knocks out]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Λαμβάνει ή ορίζει την ένταση ως ποσοστό.

Τιμή: Η εξάπλωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή.

Τιμή:  true  εάν αυτή η παρουσία είναι ορατή· διαφορετικά,  false .

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


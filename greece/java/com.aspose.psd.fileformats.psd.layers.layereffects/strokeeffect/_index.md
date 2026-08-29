---
title: "StrokeEffect"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το εφέ γραμμής του Adobe Photoshop για το στρώμα PSD."
type: docs
weight: 17
url: /el/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

Το εφέ γραμμής Adobe® Photoshop® για το στρώμα PSD.
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
| [getFillSettings()](#getFillSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις γεμίσματος. |
| [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [getOverprint()](#getOverprint--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) θα ενσωματώνει το stroke με το τρέχον περιεχόμενο του στρώματος. |
| [getPosition()](#getPosition--) | Λαμβάνει ή ορίζει τη θέση του εφέ γραμμής για να ελέγχει την ευθυγράμμιση της γραμμής σας με το περιεχόμενο του στρώματος PSD. |
| [getSize()](#getSize--) | Λαμβάνει ή ορίζει το πλάτος του εφέ γραμμής. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Λαμβάνει ή ορίζει τις ρυθμίσεις γεμίσματος. |
| [setOpacity(byte value)](#setOpacity-byte-) | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) θα ενσωματώνει το stroke με το τρέχον περιεχόμενο του στρώματος. |
| [setPosition(short value)](#setPosition-short-) | Λαμβάνει ή ορίζει τη θέση του εφέ γραμμής για να ελέγχει την ευθυγράμμιση της γραμμής σας με το περιεχόμενο του στρώματος PSD. |
| [setSize(int value)](#setSize-int-) | Λαμβάνει ή ορίζει το πλάτος του εφέ γραμμής. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις γεμίσματος.

Τιμή: Οι ρυθμίσεις γεμίσματος.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Λαμβάνει ή ορίζει τη διαφάνεια.

Τιμή: Η διαφάνεια.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) θα ενσωματώνει το stroke με το τρέχον περιεχόμενο του στρώματος.

Τιμή:  true  εάν πρέπει να ενσωματώνει το stroke με το τρέχον περιεχόμενο του στρώματος; διαφορετικά,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Λαμβάνει ή ορίζει τη θέση του εφέ γραμμής για να ελέγχει την ευθυγράμμιση της γραμμής σας με το περιεχόμενο του στρώματος PSD. Η τιμή μπορεί να είναι [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) για να σχεδιάζει τη γραμμή μέσα στο περιεχόμενο του στρώματος PSD, ή [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) για να σχεδιάζει τη γραμμή γύρω από το περιεχόμενο του στρώματος PSD, και [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) για να σχεδιάζει τη γραμμή τόσο μέσα όσο και έξω.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Λαμβάνει ή ορίζει το πλάτος του εφέ γραμμής.

Τιμή: Το πλάτος του εφέ γραμμής.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις γεμίσματος.

Τιμή: Οι ρυθμίσεις γεμίσματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) θα ενσωματώνει το stroke με το τρέχον περιεχόμενο του στρώματος.

Τιμή:  true  εάν πρέπει να ενσωματώνει το stroke με το τρέχον περιεχόμενο του στρώματος; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Λαμβάνει ή ορίζει τη θέση του εφέ γραμμής για να ελέγχει την ευθυγράμμιση της γραμμής σας με το περιεχόμενο του στρώματος PSD. Η τιμή μπορεί να είναι [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) για να σχεδιάζει τη γραμμή μέσα στο περιεχόμενο του στρώματος PSD, ή [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) για να σχεδιάζει τη γραμμή γύρω από το περιεχόμενο του στρώματος PSD, και [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) για να σχεδιάζει τη γραμμή τόσο μέσα όσο και έξω.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Λαμβάνει ή ορίζει το πλάτος του εφέ γραμμής.

Τιμή: Το πλάτος του εφέ γραμμής.

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


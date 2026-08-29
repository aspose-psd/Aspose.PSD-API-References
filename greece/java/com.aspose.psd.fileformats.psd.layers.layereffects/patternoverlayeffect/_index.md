---
title: "PatternOverlayEffect"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Εφέ στρώματος μοτίβου"
type: docs
weight: 16
url: /el/java/com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class PatternOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Εφέ στρώματος μοτίβου
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
| [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [getSettings()](#getSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [setOpacity(byte value)](#setOpacity-byte-) | Λαμβάνει ή ορίζει τη διαφάνεια. |
| [setSettings(PatternFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Λαμβάνει ή ορίζει τις ρυθμίσεις. |
| [setVisible(boolean value)](#setVisible-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static PatternOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect)
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
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Λαμβάνει ή ορίζει τη διαφάνεια.

Τιμή: Η διαφάνεια.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final PatternFillSettings getSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις.

Τιμή: Οι ρυθμίσεις.

**Returns:**
[PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)
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

### setSettings(PatternFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setSettings(PatternFillSettings value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις.

Τιμή: Οι ρυθμίσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) |  |

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


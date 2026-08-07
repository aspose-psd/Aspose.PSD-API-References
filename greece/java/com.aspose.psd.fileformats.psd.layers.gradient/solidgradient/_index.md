---
title: "SolidGradient"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ρυθμίσεις εφέ γεμίσματος διαβάθμισης."
type: docs
weight: 13
url: /el/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Ρυθμίσεις εφέ γεμίσματος διαβάθμισης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Προσθέτει το σημείο χρώματος. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Προσθέτει το σημείο χρώματος. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Δημιουργεί τους κόμβους πόρων LFX2. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| [getGradientMode()](#getGradientMode--) | Λαμβάνει τη λειτουργία για αυτό το gradient. |
| [getGradientName()](#getGradientName--) | Λαμβάνει ή ορίζει το όνομα του gradient. |
| [getInterpolation()](#getInterpolation--) | Λαμβάνει ή ορίζει την Interpolation. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Αφαιρεί το σημείο χρώματος. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Αφαιρεί το σημείο διαφάνειας. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του gradient. |
| [setInterpolation(short value)](#setInterpolation-short-) | Λαμβάνει ή ορίζει την Interpolation. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient).

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Προσθέτει το σημείο χρώματος.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Προσθέτει το σημείο χρώματος.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Δημιουργεί τους κόμβους πόρων LFX2.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Δημιουργημένη λίστα του [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Λαμβάνει ή ορίζει τα σημεία χρώματος.

Τιμή: Τα σημεία χρώματος.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
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
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Λαμβάνει ή ορίζει την Interpolation. Καθορίζει την ομαλότητα, όταν 'Gradient Type' = 'Solid'. Εύρος τιμών: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Λαμβάνει ή ορίζει τα σημεία διαφάνειας.

Τιμή: Τα σημεία διαφάνειας.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


Αφαιρεί το σημείο χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Το σημείο. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Αφαιρεί το σημείο διαφάνειας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Το σημείο. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Λαμβάνει ή ορίζει τα σημεία χρώματος.

Τιμή: Τα σημεία χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Λαμβάνει ή ορίζει την Interpolation. Καθορίζει την ομαλότητα, όταν 'Gradient Type' = 'Solid'. Εύρος τιμών: 0-4096.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Λαμβάνει ή ορίζει τα σημεία διαφάνειας.

Τιμή: Τα σημεία διαφάνειας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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


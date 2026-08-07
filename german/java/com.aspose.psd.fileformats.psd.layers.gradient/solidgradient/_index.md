---
title: "SolidGradient"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Einstellungen für den Gradient-Füllungseffekt."
type: docs
weight: 13
url: /de/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Einstellungen für den Gradient-Füllungseffekt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Initialisiert eine neue Instanz der [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Fügt den Farbpunkt hinzu. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Fügt den Farbpunkt hinzu. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Erzeugt die LFX2-Ressourcenknoten. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Liest oder setzt die Farbpunkte. |
| [getGradientMode()](#getGradientMode--) | Ruft den Modus für diesen Gradient ab. |
| [getGradientName()](#getGradientName--) | Liest oder setzt den Namen des Gradienten. |
| [getInterpolation()](#getInterpolation--) | Liest oder setzt Interpolation. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Liest oder setzt die Transparenzpunkte. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Entfernt den Farbpunkt. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Entfernt den Transparenzpunkt. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Liest oder setzt die Farbpunkte. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Liest oder setzt den Namen des Gradienten. |
| [setInterpolation(short value)](#setInterpolation-short-) | Liest oder setzt Interpolation. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Liest oder setzt die Transparenzpunkte. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Initialisiert eine neue Instanz der [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient)-Klasse.

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Fügt den Farbpunkt hinzu.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Fügt den Farbpunkt hinzu.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Erzeugt die LFX2-Ressourcenknoten.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Generierte Liste von [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
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


Liest oder setzt die Farbpunkte.

Wert: Die Farbpunkte.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


Ruft den Modus für diesen Gradient ab. Bestimmt 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Liest oder setzt den Namen des Gradienten.

Wert: Der Name des Gradienten.

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Liest oder setzt Interpolation. Bestimmt die Glätte, wenn 'Gradient Type' = 'Solid'. Wertebereich: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Liest oder setzt die Transparenzpunkte.

Wert: Die Transparenzpunkte.

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


Entfernt den Farbpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Der Punkt. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Entfernt den Transparenzpunkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Der Punkt. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Liest oder setzt die Farbpunkte.

Wert: Die Farbpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Liest oder setzt den Namen des Gradienten.

Wert: Der Name des Gradienten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Liest oder setzt Interpolation. Bestimmt die Glätte, wenn 'Gradient Type' = 'Solid'. Wertebereich: 0-4096.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Liest oder setzt die Transparenzpunkte.

Wert: Die Transparenzpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


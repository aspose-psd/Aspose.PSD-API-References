---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt die Argumente dar, die für automatisierte Maskierungsmethoden angegeben werden."
type: docs
weight: 11
url: /de/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Stellt die Argumente dar, die für automatisierte Maskierungsmethoden angegeben werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Ermittelt die maximale Anzahl von Iterationen. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Ermittelt die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund). |
| [getObjectsPoints()](#getObjectsPoints--) | Ruft die Punkte ab, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Ruft die Rechtecke der Objekte ab, die zu getrennten Objekten gehören (optional). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Ruft die Punkte ab, die zu keinem Objekt mehr gehören (optional). |
| [getPrecision()](#getPrecision--) | Ruft die Präzision der Segmentierungsmethode ab (optional). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Legt die maximale Anzahl von Iterationen fest. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Legt die Anzahl der Objekte fest, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Legt die Punkte fest, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Legt die Rechtecke der Objekte fest, die zu getrennten Objekten gehören (optional). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Legt die Punkte fest, die zu keinem Objekt mehr gehören (optional). |
| [setPrecision(double value)](#setPrecision-double-) | Legt die Präzision der Segmentierungsmethode fest (optional). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Ermittelt die maximale Anzahl von Iterationen.

Wert: Die maximale maximale Anzahl von Iterationen.

**Returns:**
int - die maximale Anzahl von Iterationen.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Ermittelt die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund).

Wert: Die Anzahl der Objekte.

**Returns:**
int - die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Ruft die Punkte ab, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Punkte der Objekte.

**Returns:**
com.aspose.psd.Point[][] - die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Ruft die Rechtecke der Objekte ab, die zu getrennten Objekten gehören (optional). Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Rechtecke der Objekte.

**Returns:**
com.aspose.psd.Rectangle[] - die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Ruft die Punkte ab, die zu keinem Objekt mehr gehören (optional). Dieser Parameter wird nur im Fall einer erneuten Segmentierung verwendet.

Wert: Die verwaisten Punkte.

**Returns:**
com.aspose.psd.Point[] - die Punkte, die zu keinem Objekt mehr gehören (optional).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Ruft die Präzision der Segmentierungsmethode ab (optional).

Wert: Die Präzision der Segmentierungsmethode (optional).

**Returns:**
double - die Präzision der Segmentierungsmethode (optional).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Legt die maximale Anzahl von Iterationen fest.

Wert: Die maximale maximale Anzahl von Iterationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die maximale Anzahl von Iterationen. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Legt die Anzahl der Objekte fest, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund).

Wert: Die Anzahl der Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Anzahl der Objekte, in die das Ausgangsbild zu trennen ist (optional), Standardwert ist 2 (Objekt und Hintergrund). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Legt die Punkte fest, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Punkte der Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Legt die Rechtecke der Objekte fest, die zu getrennten Objekten gehören (optional). Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen.

Wert: Die Rechtecke der Objekte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Legt die Punkte fest, die keinem Objekt mehr zugeordnet sind (optional). Dieser Parameter wird nur im Falle einer erneuten Segmentierung verwendet.

Wert: Die verwaisten Punkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | die Punkte, die keinem Objekt mehr zugeordnet sind (optional). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Legt die Präzision der Segmentierungsmethode fest (optional).

Wert: Die Präzision der Segmentierungsmethode (optional).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | die Präzision der Segmentierungsmethode (optional). |

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


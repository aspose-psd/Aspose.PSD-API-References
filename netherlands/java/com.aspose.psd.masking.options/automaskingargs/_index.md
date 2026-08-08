---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Geeft de argumenten weer die zijn gespecificeerd voor geautomatiseerde maskermethoden."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Geeft de argumenten weer die zijn gespecificeerd voor geautomatiseerde maskermethoden.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Haalt het maximum aantal iteraties op. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Haalt het aantal objecten op waarmee het initiële beeld wordt gescheiden (optioneel), standaardwaarde is 2 (object en achtergrond). |
| [getObjectsPoints()](#getObjectsPoints--) | Haalt de punten op die behoren tot gescheiden objecten (optioneel) NumberOfObjects coördinaten die behoren tot NumberOfObjects objecten van het initiële beeld. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Haalt de rechthoeken van objecten op die behoren tot gescheiden objecten (optioneel). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Haalt de punten op die niet langer tot een object behoren (optioneel). |
| [getPrecision()](#getPrecision--) | Haalt de precisie van de segmentatiemethode op (optioneel). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Stelt het maximum aantal iteraties in. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Stelt het aantal objecten in waarmee het initiële beeld wordt gescheiden (optioneel), standaardwaarde is 2 (object en achtergrond). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Stelt de punten in die behoren tot gescheiden objecten (optioneel) NumberOfObjects coördinaten die behoren tot NumberOfObjects objecten van het initiële beeld. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Stelt de rechthoeken van objecten in die behoren tot gescheiden objecten (optioneel). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Stelt de punten in die niet langer tot een object behoren (optioneel). |
| [setPrecision(double value)](#setPrecision-double-) | Stelt de precisie van de segmentatiemethode in (optioneel). |
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
| Parameter | Type | Beschrijving |
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


Haalt het maximum aantal iteraties op.

Waarde: Het maximale maximum aantal iteraties.

**Returns:**
int - het maximum aantal iteraties.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Haalt het aantal objecten op waarmee het initiële beeld wordt gescheiden (optioneel), standaardwaarde is 2 (object en achtergrond).

Waarde: Het aantal objecten.

**Returns:**
int - het aantal objecten om het initiële beeld mee te scheiden (optioneel), standaardwaarde is 2 (object en achtergrond).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Haalt de punten op die behoren tot gescheiden objecten (optioneel) NumberOfObjects coördinaten die behoren tot NumberOfObjects objecten van het initiële beeld. Deze parameter wordt gebruikt om de precisie van de segmentatiemethode te verhogen.

Waarde: De punten van de objecten.

**Returns:**
com.aspose.psd.Point[][] - de punten die behoren tot gescheiden objecten (optioneel) NumberOfObjects coördinaten die behoren tot NumberOfObjects objecten van de oorspronkelijke afbeelding.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Haalt de rechthoeken van de objecten op die behoren tot gescheiden objecten (optioneel). Deze parameter wordt gebruikt om de precisie van de segmentatiemethode te verhogen.

Waarde: De rechthoeken van de objecten.

**Returns:**
com.aspose.psd.Rectangle[] - de rechthoeken van de objecten die behoren tot gescheiden objecten (optioneel).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Haalt de punten op die niet langer tot een object behoren (optioneel). Deze parameter wordt alleen gebruikt bij hersegmentatie.

Waarde: De verweesde punten.

**Returns:**
com.aspose.psd.Point[] - de punten die niet langer tot een object behoren (optioneel).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Haalt de precisie van de segmentatiemethode op (optioneel).

Waarde: De precisie van de segmentatiemethode (optioneel).

**Returns:**
double - de precisie van de segmentatiemethode (optioneel).
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


Stelt het maximum aantal iteraties in.

Waarde: Het maximale maximum aantal iteraties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | het maximale aantal iteraties. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Stelt het aantal objecten in waarmee het initiële beeld wordt gescheiden (optioneel), standaardwaarde is 2 (object en achtergrond).

Waarde: Het aantal objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | het aantal objecten om de oorspronkelijke afbeelding in te scheiden (optioneel), standaardwaarde is 2 (object en achtergrond). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Stelt de punten in die behoren tot gescheiden objecten (optioneel) NumberOfObjects coördinaten die behoren tot NumberOfObjects objecten van de oorspronkelijke afbeelding. Deze parameter wordt gebruikt om de precisie van de segmentatiemethode te verhogen.

Waarde: De punten van de objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | de punten die behoren tot gescheiden objecten (optioneel) NumberOfObjects coördinaten die behoren tot NumberOfObjects objecten van de oorspronkelijke afbeelding. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Stelt de rechthoeken van de objecten in die behoren tot gescheiden objecten (optioneel). Deze parameter wordt gebruikt om de precisie van de segmentatiemethode te verhogen.

Waarde: De rechthoeken van de objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | de rechthoeken van de objecten die behoren tot gescheiden objecten (optioneel). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Stelt de punten in die niet langer tot een object behoren (optioneel). Deze parameter wordt alleen gebruikt bij hersegmentatie.

Waarde: De verweesde punten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | de punten die niet langer tot een object behoren (optioneel). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Stelt de precisie van de segmentatiemethode in (optioneel).

Waarde: De precisie van de segmentatiemethode (optioneel).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | de precisie van de segmentatiemethode (optioneel). |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


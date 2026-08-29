---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar argumenten som specificeras för automatiska maskningsmetoder"
type: docs
weight: 11
url: /sv/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Representerar argumenten som specificeras för automatiska maskningsmetoder
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Hämtar det maximala antalet iterationer. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Hämtar antalet objekt att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund). |
| [getObjectsPoints()](#getObjectsPoints--) | Hämtar de punkter som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Hämtar de objektrektanglar som tillhör separerade objekt (valfritt). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Hämtar de punkter som inte längre tillhör något objekt (valfritt). |
| [getPrecision()](#getPrecision--) | Hämtar precisionen för segmenteringsmetoden (valfritt). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Ställer in maximalt antal iterationer. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Ställer in antalet objekt att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Ställer in punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Ställer in rektanglarna för objekten som tillhör separerade objekt (valfritt). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Ställer in punkterna som inte längre tillhör något objekt (valfritt). |
| [setPrecision(double value)](#setPrecision-double-) | Ställer in precisionen för segmenteringsmetoden (valfritt). |
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
| Parameter | Typ | Beskrivning |
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


Hämtar det maximala antalet iterationer.

Värde: Det maximala maximala antalet iterationer.

**Returns:**
int - det maximala antalet iterationer.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Hämtar antalet objekt att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund).

Värde: Antalet objekt.

**Returns:**
int - antalet objekt att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Hämtar punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. Denna parameter används för att öka precisionen för segmenteringsmetoden.

Värde: Objektens punkter.

**Returns:**
com.aspose.psd.Point[][] - punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Hämtar objektens rektanglar som tillhör separerade objekt (valfritt). Denna parameter används för att öka precisionen för segmenteringsmetoden.

Värde: Objektens rektanglar.

**Returns:**
com.aspose.psd.Rectangle[] - objektens rektanglar som tillhör separerade objekt (valfritt).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Hämtar punkterna som inte längre tillhör något objekt (valfritt). Denna parameter används endast vid omsegmentering.

Värde: De övergivna punkterna.

**Returns:**
com.aspose.psd.Point[] - punkterna som inte längre tillhör något objekt (valfritt).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Hämtar precisionen för segmenteringsmetoden (valfritt).

Värde: Precisionen för segmenteringsmetoden (valfritt).

**Returns:**
double - precisionen för segmenteringsmetoden (valfritt).
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


Ställer in maximalt antal iterationer.

Värde: Det maximala maximala antalet iterationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | det maximala antalet iterationer. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Ställer in antalet objekt att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund).

Värde: Antalet objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | antalet objekt att separera den ursprungliga bilden i (valfritt), standardvärdet är 2 (objekt och bakgrund). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Ställer in punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. Denna parameter används för att öka precisionen för segmenteringsmetoden.

Värde: Objektens punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | punkterna som tillhör separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i den ursprungliga bilden. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Ställer in objektens rektanglar som tillhör separerade objekt (valfritt). Denna parameter används för att öka segmenteringsmetodens precision.

Värde: Objektens rektanglar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | objektens rektanglar som tillhör separerade objekt (valfritt). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Ställer in punkterna som inte längre tillhör något objekt (valfritt). Denna parameter används endast vid omsegmentering.

Värde: De övergivna punkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | punkterna som inte längre tillhör något objekt (valfritt). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Ställer in precisionen för segmenteringsmetoden (valfritt).

Värde: Precisionen för segmenteringsmetoden (valfritt).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | precisionen för segmenteringsmetoden (valfritt). |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


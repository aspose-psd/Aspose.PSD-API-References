---
title: "FixedPointDecimal"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Vastekommagetal met een 16-bit geheel getal en een 16-bit breuk."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Inheritance:**
java.lang.Object
```
public class FixedPointDecimal
```

Vaste‑punt decimaal, met een 16‑bit geheel getal en 16‑bit breuk.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FixedPointDecimal(int integer, int fraction)](#FixedPointDecimal-int-int-) | Initialiseert een nieuw exemplaar van de [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) klasse. |
| [FixedPointDecimal(long value)](#FixedPointDecimal-long-) | Initialiseert een nieuw exemplaar van de [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) klasse. |
| [FixedPointDecimal(double value)](#FixedPointDecimal-double-) | Initialiseert een nieuw exemplaar van de [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFraction()](#getFraction--) | Haalt de breuk op of stelt deze in. |
| [getInteger()](#getInteger--) | Haalt het geheel getal op of stelt dit in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFraction(int value)](#setFraction-int-) | Haalt de breuk op of stelt deze in. |
| [setInteger(int value)](#setInteger-int-) | Haalt het geheel getal op of stelt dit in. |
| [toDouble()](#toDouble--) | Converteert het huidige vastekommagetal naar double. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FixedPointDecimal(int integer, int fraction) {#FixedPointDecimal-int-int-}
```
public FixedPointDecimal(int integer, int fraction)
```


Initialiseert een nieuw exemplaar van de [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integer | int | Het geheel getal. |
| fraction | int | De breuk. |

### FixedPointDecimal(long value) {#FixedPointDecimal-long-}
```
public FixedPointDecimal(long value)
```


Initialiseert een nieuw exemplaar van de [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) klasse. Splits de hoge en lage woorden van een 32-bit geheel getal in een vastekommagetal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De waarde. |

### FixedPointDecimal(double value) {#FixedPointDecimal-double-}
```
public FixedPointDecimal(double value)
```


Initialiseert een nieuw exemplaar van de [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De waarde. |

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
### getFraction() {#getFraction--}
```
public final int getFraction()
```


Haalt de breuk op of stelt deze in.

Waarde: De breuk.

**Returns:**
int
### getInteger() {#getInteger--}
```
public final int getInteger()
```


Haalt het geheel getal op of stelt dit in.

Waarde: Het geheel getal.

**Returns:**
int
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




### setFraction(int value) {#setFraction-int-}
```
public final void setFraction(int value)
```


Haalt de breuk op of stelt deze in.

Waarde: De breuk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setInteger(int value) {#setInteger-int-}
```
public final void setInteger(int value)
```


Haalt het geheel getal op of stelt dit in.

Waarde: Het geheel getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converteert het huidige vastekommagetal naar double.

**Returns:**
double - De geconverteerde waarde.
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


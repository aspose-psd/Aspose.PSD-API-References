---
title: "TiffRational"
second_title: "Aspose.PSD för Java API-referens"
description: "Tiff-rationella typen."
type: docs
weight: 12
url: /sv/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Tiff-rationella typen.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TiffRational()](#TiffRational--) | Initierar en ny instans av klassen  TiffRational  . |
| [TiffRational(long value)](#TiffRational-long-) | Initierar en ny instans av klassen  TiffRational  . |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Initierar en ny instans av klassen  TiffRational  . |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Epsilon](#Epsilon) | Epsilon för bråktalsberäkning |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Approximerar det angivna värdet till ett bråk. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approximerar det angivna värdet till ett bråk. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approximerar det angivna värdet till ett bråk. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approximerar det angivna värdet till ett bråk. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna Object är lika med denna instans. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Hämtar nämnaren. |
| [getNominator()](#getNominator--) | Hämtar täljaren. |
| [getValue()](#getValue--) | Hämtar flyttalsvärdet. |
| [getValueD()](#getValueD--) | Hämtar dubbelvärdet. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en  System.String  som representerar detta objekt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Initierar en ny instans av klassen  TiffRational  .

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Initierar en ny instans av klassen  TiffRational  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | long | Täljarevärdet. |

Täljaren kommer att användas som det angivna värdet och nämnaren blir lika med 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Initierar en ny instans av klassen  TiffRational  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| täljare | long | Nämnaren. |
| nämnare | long | Nämnaren. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


Epsilon för bråktalsberäkning

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Approximerar det angivna värdet till ett bråk.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna Object är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna objektet är lika med den här instansen; annars,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


Hämtar nämnaren.

Värde: Nämnaren.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Hämtar täljaren.

Värde: Täljaren.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Hämtar flyttalsvärdet.

Värde: Float‑värdet.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Hämtar dubbelvärdet.

Värde: Det dubbla värdet.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Returnerar en  System.String  som representerar detta objekt.

**Returns:**
java.lang.String - En  System.String  som representerar detta objekt.
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


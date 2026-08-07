---
title: "TiffRational"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der TIFF-Rationaltyp."
type: docs
weight: 12
url: /de/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Der TIFF-Rationaltyp.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffRational()](#TiffRational--) | Initialisiert eine neue Instanz der Klasse  TiffRational . |
| [TiffRational(long value)](#TiffRational-long-) | Initialisiert eine neue Instanz der Klasse  TiffRational . |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Initialisiert eine neue Instanz der Klasse  TiffRational . |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Epsilon](#Epsilon) | Das Epsilon für die Bruchberechnung |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Nähert den bereitgestellten Wert an einen Bruch an. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Nähert den bereitgestellten Wert an einen Bruch an. |
| [approximateFraction(float value)](#approximateFraction-float-) | Nähert den bereitgestellten Wert an einen Bruch an. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Nähert den bereitgestellten Wert an einen Bruch an. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Liest den Nenner. |
| [getNominator()](#getNominator--) | Liest den Zähler. |
| [getValue()](#getValue--) | Liest den Gleitkommawert. |
| [getValueD()](#getValueD--) | Liest den double-Wert. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt einen  System.String  zurück, der diese Instanz darstellt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Initialisiert eine neue Instanz der Klasse  TiffRational .

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Initialisiert eine neue Instanz der Klasse  TiffRational .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | long | Der Zählerwert. |

Der Zähler wird als der angegebene Wert verwendet und der Nenner wird gleich 1 sein. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Initialisiert eine neue Instanz der Klasse  TiffRational .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zähler | long | Der Zähler. |
| Nenner | long | Der Nenner. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


Das Epsilon für die Bruchberechnung

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Nähert den bereitgestellten Wert an einen Bruch an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Nähert den bereitgestellten Wert an einen Bruch an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | Der Wert. |
| epsilon | double | Der zulässige Fehler. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Nähert den bereitgestellten Wert an einen Bruch an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Nähert den bereitgestellten Wert an einen Bruch an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Wert. |
| epsilon | double | Der zulässige Fehler. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls  false .
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


Liest den Nenner.

Wert: Der Nenner.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Liest den Zähler.

Wert: Der Zähler.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Liest den Gleitkommawert.

Wert: Der float-Wert.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Liest den double-Wert.

Wert: Der Gleitkommawert.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
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


Gibt einen  System.String  zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein  System.String  der diese Instanz darstellt.
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


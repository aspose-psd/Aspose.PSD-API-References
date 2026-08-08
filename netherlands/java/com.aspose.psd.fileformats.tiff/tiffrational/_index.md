---
title: "TiffRational"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Het TIFF-rationele type."
type: docs
weight: 12
url: /nl/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Het TIFF-rationele type.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TiffRational()](#TiffRational--) | Initialiseert een nieuw exemplaar van de TiffRational klasse. |
| [TiffRational(long value)](#TiffRational-long-) | Initialiseert een nieuw exemplaar van de TiffRational klasse. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Initialiseert een nieuw exemplaar van de TiffRational klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Epsilon](#Epsilon) | De epsilon voor breukberekening |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Benadert de opgegeven waarde tot een breuk. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Benadert de opgegeven waarde tot een breuk. |
| [approximateFraction(float value)](#approximateFraction-float-) | Benadert de opgegeven waarde tot een breuk. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Benadert de opgegeven waarde tot een breuk. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Haalt de noemer op. |
| [getNominator()](#getNominator--) | Haalt de teller op. |
| [getValue()](#getValue--) | Haalt de floatwaarde op. |
| [getValueD()](#getValueD--) | Haalt de double-waarde op. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een  System.String  die deze instantie vertegenwoordigt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Initialiseert een nieuw exemplaar van de TiffRational klasse.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Initialiseert een nieuw exemplaar van de TiffRational klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | long | De tellerwaarde. |

De teller wordt gebruikt als de opgegeven waarde en de noemer zal gelijk zijn aan 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Initialiseert een nieuw exemplaar van de TiffRational klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| teller | long | De teller. |
| noemer | long | De noemer. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


De epsilon voor breukberekening

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Benadert de opgegeven waarde tot een breuk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De waarde. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Benadert de opgegeven waarde tot een breuk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | De waarde. |
| epsilon | double | De toegestane fout. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Benadert de opgegeven waarde tot een breuk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De waarde. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Benadert de opgegeven waarde tot een breuk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | De waarde. |
| epsilon | double | De toegestane fout. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met deze instantie. |

**Returns:**
boolean - true als het opgegeven Object gelijk is aan deze instantie; anders false.
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


Haalt de noemer op.

Waarde: De noemer.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Haalt de teller op.

Waarde: De teller.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Haalt de floatwaarde op.

Waarde: De floatwaarde.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Haalt de double-waarde op.

Waarde: De doublewaarde.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
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


Retourneert een  System.String  die deze instantie vertegenwoordigt.

**Returns:**
java.lang.String - Een  System.String  die deze instantie vertegenwoordigt.
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


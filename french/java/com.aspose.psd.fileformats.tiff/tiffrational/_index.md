---
title: "TiffRational"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le type rationnel tiff."
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

Le type rationnel tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffRational()](#TiffRational--) | Initialise une nouvelle instance de la classe  TiffRational . |
| [TiffRational(long value)](#TiffRational-long-) | Initialise une nouvelle instance de la classe  TiffRational . |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | Initialise une nouvelle instance de la classe  TiffRational . |
## Champs

| Champ | Description |
| --- | --- |
| [Epsilon](#Epsilon) | L'epsilon pour le calcul de fraction |
## Méthodes

| Méthode | Description |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Approxime la valeur fournie en une fraction. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approxime la valeur fournie en une fraction. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approxime la valeur fournie en une fraction. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approxime la valeur fournie en une fraction. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'Object spécifié est égal à cette instance. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Obtient le dénominateur. |
| [getNominator()](#getNominator--) | Obtient le numérateur. |
| [getValue()](#getValue--) | Obtient la valeur flottante. |
| [getValueD()](#getValueD--) | Obtient la valeur double. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourne une  System.String  qui représente cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


Initialise une nouvelle instance de la classe  TiffRational .

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


Initialise une nouvelle instance de la classe  TiffRational .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | long | La valeur du nominator. |

Le nominator sera utilisé comme la valeur spécifiée et le denominator sera égal à 1. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


Initialise une nouvelle instance de la classe  TiffRational .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| numérateur | long | Le numérateur. |
| dénominateur | long | Le dénominateur. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


L'epsilon pour le calcul de fraction

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La valeur. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | La valeur. |
| epsilon | double | L'erreur autorisée. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


Approxime la valeur fournie en une fraction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur. |
| epsilon | double | L'erreur autorisée. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'Object spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Returns:**
booléen -  true  si l'objet spécifié est égal à cette instance ; sinon,  false .
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


Obtient le dénominateur.

Valeur: le denominator.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


Obtient le numérateur.

Valeur: le nominator.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


Obtient la valeur flottante.

Valeur: la valeur flottante.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Obtient la valeur double.

Valeur: la valeur double.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
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


Retourne une  System.String  qui représente cette instance.

**Returns:**
java.lang.String - Une System.String qui représente cette instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


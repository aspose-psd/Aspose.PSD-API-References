---
title: TiffSRational
second_title: Aspose.PSD for Java API Reference
description: The tiff rational type.
type: docs
weight: 13
url: /java/com.aspose.psd.fileformats.tiff/tiffsrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

The tiff rational type.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | Initializes a new instance of the  TiffSRational  class. |
| [TiffSRational(int value)](#TiffSRational-int-) | Initializes a new instance of the  TiffRational  class. |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | Initializes a new instance of the  TiffSRational  class. |
## Fields

| Field | Description |
| --- | --- |
| [Epsilon](#Epsilon) | The epsilon for fraction calculation |
## Methods

| Method | Description |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | Approximates the provided value to a fraction. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | Approximates the provided value to a fraction. |
| [approximateFraction(float value)](#approximateFraction-float-) | Approximates the provided value to a fraction. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | Approximates the provided value to a fraction. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified  Object  is equal to this instance. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | Gets the denominator. |
| [getNominator()](#getNominator--) | Gets the nominator. |
| [getValue()](#getValue--) | Gets the float value. |
| [getValueD()](#getValueD--) | Gets the double value. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a  System.String  that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


Initializes a new instance of the  TiffSRational  class.

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


Initializes a new instance of the  TiffRational  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The nominator value.

The nominator will be used as the value specified and denominator will be equal 1. |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


Initializes a new instance of the  TiffSRational  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nominator | int | The nominator. |
| denominator | int | The denominator. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


The epsilon for fraction calculation

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value. |
| epsilon | double | The error allowed. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


Approximates the provided value to a fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The value. |
| epsilon | double | The error allowed. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified  Object  is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  Object  to compare with this instance. |

**Returns:**
boolean -  true  if the specified  Object  is equal to this instance; otherwise,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


Gets the denominator.

Value: The denominator.

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


Gets the nominator.

Value: The nominator.

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


Gets the float value.

Value: The float value.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


Gets the double value.

Value: The double value.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
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


Returns a  System.String  that represents this instance.

**Returns:**
java.lang.String - A  System.String  that represents this instance.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


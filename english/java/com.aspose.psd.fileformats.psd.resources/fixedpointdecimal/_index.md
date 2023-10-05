---
title: FixedPointDecimal
second_title: Aspose.PSD for Java API Reference
description: Fixed-point decimal with 16-bit integer and 16-bit fraction.
type: docs
weight: 17
url: /java/com.aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Inheritance:**
java.lang.Object
```
public class FixedPointDecimal
```

Fixed-point decimal, with 16-bit integer and 16-bit fraction.
## Constructors

| Constructor | Description |
| --- | --- |
| [FixedPointDecimal(int integer, int fraction)](#FixedPointDecimal-int-int-) | Initializes a new instance of the [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) class. |
| [FixedPointDecimal(long value)](#FixedPointDecimal-long-) | Initializes a new instance of the [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) class. |
| [FixedPointDecimal(double value)](#FixedPointDecimal-double-) | Initializes a new instance of the [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFraction()](#getFraction--) | Gets or sets the fraction. |
| [getInteger()](#getInteger--) | Gets or sets the integer. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFraction(int value)](#setFraction-int-) | Gets or sets the fraction. |
| [setInteger(int value)](#setInteger-int-) | Gets or sets the integer. |
| [toDouble()](#toDouble--) | Converts current fixed point decimal to double. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FixedPointDecimal(int integer, int fraction) {#FixedPointDecimal-int-int-}
```
public FixedPointDecimal(int integer, int fraction)
```


Initializes a new instance of the [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integer | int | The integer. |
| fraction | int | The fraction. |

### FixedPointDecimal(long value) {#FixedPointDecimal-long-}
```
public FixedPointDecimal(long value)
```


Initializes a new instance of the [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) class. Split the high and low words of a 32-bit integer into a fixed-point number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The value. |

### FixedPointDecimal(double value) {#FixedPointDecimal-double-}
```
public FixedPointDecimal(double value)
```


Initializes a new instance of the [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The value. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Gets or sets the fraction.

Value: The fraction.

**Returns:**
int
### getInteger() {#getInteger--}
```
public final int getInteger()
```


Gets or sets the integer.

Value: The integer.

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


Gets or sets the fraction.

Value: The fraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setInteger(int value) {#setInteger-int-}
```
public final void setInteger(int value)
```


Gets or sets the integer.

Value: The integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converts current fixed point decimal to double.

**Returns:**
double - The converted value.
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


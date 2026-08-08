---
title: "FixedPointDecimal"
second_title: "Java용 Aspose.PSD API 참조"
description: "16비트 정수와 16비트 분수를 갖는 고정 소수점 십진수."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Inheritance:**
java.lang.Object
```
public class FixedPointDecimal
```

고정 소수점 십진수, 16비트 정수와 16비트 소수 부분을 가집니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FixedPointDecimal(int integer, int fraction)](#FixedPointDecimal-int-int-) | 새 인스턴스를 초기화합니다. [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 클래스. |
| [FixedPointDecimal(long value)](#FixedPointDecimal-long-) | 새 인스턴스를 초기화합니다. [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 클래스. |
| [FixedPointDecimal(double value)](#FixedPointDecimal-double-) | 새 인스턴스를 초기화합니다. [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFraction()](#getFraction--) | 분수를 가져오거나 설정합니다. |
| [getInteger()](#getInteger--) | 정수를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFraction(int value)](#setFraction-int-) | 분수를 가져오거나 설정합니다. |
| [setInteger(int value)](#setInteger-int-) | 정수를 가져오거나 설정합니다. |
| [toDouble()](#toDouble--) | 현재 고정 소수점 십진수를 double로 변환합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FixedPointDecimal(int integer, int fraction) {#FixedPointDecimal-int-int-}
```
public FixedPointDecimal(int integer, int fraction)
```


새 인스턴스를 초기화합니다. [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 정수 | int | 정수. |
| 분수 | int | 분수. |

### FixedPointDecimal(long value) {#FixedPointDecimal-long-}
```
public FixedPointDecimal(long value)
```


새 인스턴스를 초기화합니다. [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 클래스. 32비트 정수의 상위 및 하위 워드를 분리하여 고정 소수점 숫자로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | 값. |

### FixedPointDecimal(double value) {#FixedPointDecimal-double-}
```
public FixedPointDecimal(double value)
```


새 인스턴스를 초기화합니다. [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 값. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


분수를 가져오거나 설정합니다.

값: 분수.

**Returns:**
int
### getInteger() {#getInteger--}
```
public final int getInteger()
```


정수를 가져오거나 설정합니다.

값: 정수.

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


분수를 가져오거나 설정합니다.

값: 분수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setInteger(int value) {#setInteger-int-}
```
public final void setInteger(int value)
```


정수를 가져오거나 설정합니다.

값: 정수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


현재 고정 소수점 십진수를 double로 변환합니다.

**Returns:**
double - 변환된 값.
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


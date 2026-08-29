---
title: "TiffRational"
second_title: "Java용 Aspose.PSD API 참조"
description: "tiff 유리수 유형."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

tiff 유리수 유형.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffRational()](#TiffRational--) | 새 인스턴스를 초기화합니다 TiffRational 클래스. |
| [TiffRational(long value)](#TiffRational-long-) | 새 인스턴스를 초기화합니다 TiffRational 클래스. |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | 새 인스턴스를 초기화합니다 TiffRational 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Epsilon](#Epsilon) | 분수 계산을 위한 epsilon |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | 제공된 값을 분수로 근사합니다. |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | 제공된 값을 분수로 근사합니다. |
| [approximateFraction(float value)](#approximateFraction-float-) | 제공된 값을 분수로 근사합니다. |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | 제공된 값을 분수로 근사합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 Object가 이 인스턴스와 같은지 여부를 판단합니다. |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | 분모를 가져옵니다. |
| [getNominator()](#getNominator--) | 분자를 가져옵니다. |
| [getValue()](#getValue--) | 부동 소수점 값을 가져옵니다. |
| [getValueD()](#getValueD--) | double 값을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이 인스턴스를 나타내는  System.String  을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


새 인스턴스를 초기화합니다 TiffRational 클래스.

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


새 인스턴스를 초기화합니다 TiffRational 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | long | 분자 값. |

분자는 지정된 값으로 사용되고 분모는 1이 됩니다. |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


새 인스턴스를 초기화합니다 TiffRational 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 분자 | long | 분자. |
| 분모 | long | 분모. |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


분수 계산을 위한 epsilon

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


제공된 값을 분수로 근사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 값. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


제공된 값을 분수로 근사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 값. |
| epsilon | double | 허용되는 오류. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


제공된 값을 분수로 근사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 값. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


제공된 값을 분수로 근사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 값. |
| epsilon | double | 허용되는 오류. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 Object가 이 인스턴스와 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 Object입니다. |

**Returns:**
boolean - 지정된 Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
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


분모를 가져옵니다.

값: 분모.

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


분자를 가져옵니다.

값: 분자.

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


부동 소수점 값을 가져옵니다.

값: float 값.

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


double 값을 가져옵니다.

값: double 값.

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
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


이 인스턴스를 나타내는  System.String  을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 System.String.
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


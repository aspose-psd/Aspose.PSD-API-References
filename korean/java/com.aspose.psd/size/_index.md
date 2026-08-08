---
title: "크기"
second_title: "Java용 Aspose.PSD API 참조"
description: "크기를 나타냅니다."
type: docs
weight: 98
url: /ko/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

크기를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | 지정된 Aspose.Imaging.Point에서 Aspose.Imaging.Size 구조체의 새 인스턴스를 초기화합니다. |
| [Size(int width, int height)](#Size-int-int-) | 지정된 차원에서 Aspose.Imaging.Size 구조체의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | 하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에 추가합니다. |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | 지정된 Aspose.Imaging.SizeF 구조를 Aspose.Imaging.Size 구조로 변환하며, Aspose.Imaging.Size 구조의 값을 다음 높은 정수값으로 반올림합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 이 Aspose.Imaging.Size와 동일한 차원을 가진 Aspose.Imaging.Size인지 테스트합니다. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Aspose.Imaging.Size.Width 및 Aspose.Imaging.Size.Height 값이 0으로 설정된 Aspose.Imaging.Size 구조의 새 인스턴스를 가져옵니다. |
| [getHeight()](#getHeight--) | 이 Aspose.Imaging.Size의 수직 구성 요소를 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 이 Aspose.Imaging.Size의 수평 구성 요소를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) | 이 Aspose.Imaging.Size 구조에 대한 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 이 Aspose.Imaging.Size의 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | 하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에 추가합니다. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | 두 Aspose.Imaging.Size 구조가 같은지 테스트합니다. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | 두 Aspose.Imaging.Size 구조가 다른지 테스트합니다. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | 하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에서 빼습니다. |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | 지정된 Aspose.Imaging.SizeF 구조를 Aspose.Imaging.Size 구조로 변환하며, Aspose.Imaging.SizeF 구조의 값을 가장 가까운 정수값으로 반올림합니다. |
| [setHeight(int value)](#setHeight-int-) | 이 Aspose.Imaging.Size의 수직 구성 요소를 가져오거나 설정합니다. |
| [setWidth(int value)](#setWidth-int-) | 이 Aspose.Imaging.Size의 수평 구성 요소를 가져오거나 설정합니다. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | 하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에서 빼습니다. |
| [toString()](#toString--) | 이 Aspose.Imaging.Size를 나타내는 사람이 읽을 수 있는 문자열을 생성합니다. |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | 지정된 Aspose.Imaging.Size를 Aspose.Imaging.Point로 변환합니다. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | 지정된 Aspose.Imaging.Size를 Aspose.Imaging.SizeF로 변환합니다. |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | 지정된 Aspose.Imaging.SizeF 구조를 Aspose.Imaging.Size 구조로 변환하며, Aspose.Imaging.SizeF 구조의 값을 다음 낮은 정수값으로 잘라냅니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


지정된 Aspose.Imaging.Point에서 Aspose.Imaging.Size 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 이 Aspose.Imaging.Size를 초기화할 Aspose.Imaging.Point입니다. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


지정된 차원에서 Aspose.Imaging.Size 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int | 새 Aspose.Imaging.Size의 너비 구성 요소입니다. |
| 높이 | int | 새 Aspose.Imaging.Size의 높이 구성 요소입니다. |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 첫 번째 추가할 Aspose.Imaging.Size입니다. |
| size2 | [Size](../../com.aspose.psd/size) | 두 번째 추가할 Aspose.Imaging.Size입니다. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


지정된 Aspose.Imaging.SizeF 구조를 Aspose.Imaging.Size 구조로 변환하며, Aspose.Imaging.Size 구조의 값을 다음 높은 정수값으로 반올림합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 변환할 Aspose.Imaging.SizeF 구조입니다. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 이 Aspose.Imaging.Size와 동일한 차원을 가진 Aspose.Imaging.Size인지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 System.Object입니다. |

**Returns:**
boolean - obj가 Aspose.Imaging.Size이며 이 Aspose.Imaging.Size와 동일한 너비와 높이를 가진 경우 True; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Aspose.Imaging.Size.Width 및 Aspose.Imaging.Size.Height 값이 0으로 설정된 Aspose.Imaging.Size 구조의 새 인스턴스를 가져옵니다.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


이 Aspose.Imaging.Size의 수직 구성 요소를 가져오거나 설정합니다.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


이 Aspose.Imaging.Size의 수평 구성 요소를 가져오거나 설정합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 Aspose.Imaging.Size 구조에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 Aspose.Imaging.Size 구조에 대한 해시 값을 지정하는 정수값입니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이 Aspose.Imaging.Size의 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 첫 번째 추가할 Aspose.Imaging.Size입니다. |
| size2 | [Size](../../com.aspose.psd/size) | 두 번째 추가할 Aspose.Imaging.Size입니다. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


두 Aspose.Imaging.Size 구조가 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 동등 연산자의 왼쪽에 있는 Aspose.Imaging.Size 구조입니다. |
| size2 | [Size](../../com.aspose.psd/size) | 동등 연산자 오른쪽에 있는 Aspose.Imaging.Size 구조체. |

**Returns:**
boolean - size1과 size2의 너비와 높이가 동일하면 true; 그렇지 않으면 false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


두 Aspose.Imaging.Size 구조가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 부등 연산자 왼쪽에 있는 Aspose.Imaging.Size 구조체. |
| size2 | [Size](../../com.aspose.psd/size) | 부등 연산자 오른쪽에 있는 Aspose.Imaging.Size 구조체. |

**Returns:**
boolean - size1과 size2가 너비 또는 높이 중 하나라도 다르면 true; size1과 size2가 동일하면 false.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에서 빼습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 뺄셈 연산자 왼쪽에 있는 Aspose.Imaging.Size 구조체. |
| size2 | [Size](../../com.aspose.psd/size) | 뺄셈 연산자 오른쪽에 있는 Aspose.Imaging.Size 구조체. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


지정된 Aspose.Imaging.SizeF 구조를 Aspose.Imaging.Size 구조로 변환하며, Aspose.Imaging.SizeF 구조의 값을 가장 가까운 정수값으로 반올림합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 변환할 Aspose.Imaging.SizeF 구조입니다. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


이 Aspose.Imaging.Size의 수직 구성 요소를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


이 Aspose.Imaging.Size의 수평 구성 요소를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


하나의 Aspose.Imaging.Size 구조의 너비와 높이를 다른 Aspose.Imaging.Size 구조의 너비와 높이에서 빼습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 뺄셈 연산자 왼쪽에 있는 Aspose.Imaging.Size 구조체. |
| size2 | [Size](../../com.aspose.psd/size) | 뺄셈 연산자 오른쪽에 있는 Aspose.Imaging.Size 구조체. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


이 Aspose.Imaging.Size를 나타내는 사람이 읽을 수 있는 문자열을 생성합니다.

**Returns:**
java.lang.String - 이 Aspose.Imaging.Size를 나타내는 문자열.
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


지정된 Aspose.Imaging.Size를 Aspose.Imaging.Point로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 변환할 Aspose.Imaging.Size. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


지정된 Aspose.Imaging.Size를 Aspose.Imaging.SizeF로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 변환할 Aspose.Imaging.Size. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


지정된 Aspose.Imaging.SizeF 구조를 Aspose.Imaging.Size 구조로 변환하며, Aspose.Imaging.SizeF 구조의 값을 다음 낮은 정수값으로 잘라냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 변환할 Aspose.Imaging.SizeF 구조입니다. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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


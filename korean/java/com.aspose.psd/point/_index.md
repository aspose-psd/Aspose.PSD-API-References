---
title: "Point"
second_title: "Java용 Aspose.PSD API 참조"
description: "2차원 평면에서 점을 정의하는 정수 x 및 y 좌표의 순서쌍을 나타냅니다."
type: docs
weight: 82
url: /ko/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

2차원 평면에서 점을 정의하는 정수 x 및 y 좌표의 순서쌍을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 지정된 좌표를 사용하여  Aspose.Imaging.Point  구조체의 새 인스턴스를 초기화합니다. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Aspose.Imaging.Size 구조체에서 새 인스턴스를 초기화합니다. |
| [Point(int dw)](#Point-int-) | 정수 값으로 지정된 좌표를 사용하여  Aspose.Imaging.Point  구조체의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | 점 형식을 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | 지정된  Aspose.Imaging.Size  를 지정된  Aspose.Imaging.Point  에 추가합니다. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | 지정된  Aspose.Imaging.PointF  의 값을 다음 높은 정수값으로 반올림하여  Aspose.Imaging.Point  로 변환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이  Aspose.Imaging.Point  가 지정된  System.Object  와 동일한 좌표를 포함하는지 여부를 지정합니다. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Aspose.Imaging.Point.X 및 Aspose.Imaging.Point.Y 값이 0으로 설정된  Aspose.Imaging.Point  구조체의 새 인스턴스를 가져옵니다. |
| [getX()](#getX--) | 이  Aspose.Imaging.Point  의 x 좌표를 가져오거나 설정합니다. |
| [getY()](#getY--) | 이  Aspose.Imaging.Point  의 y 좌표를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) | 이  Aspose.Imaging.Point  에 대한 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 이  Aspose.Imaging.Point  가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | 지정된  Aspose.Imaging.Point  로 이  Aspose.Imaging.Point  를 변환합니다. |
| [offset(int dx, int dy)](#offset-int-int-) | 지정된 양만큼 이  Aspose.Imaging.Point  를 변환합니다. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | 주어진  Aspose.Imaging.Size  로  Aspose.Imaging.Point  를 변환합니다. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | 두 개의  Aspose.Imaging.Point  객체를 비교합니다. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | 두 개의  Aspose.Imaging.Point  객체를 비교합니다. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | 주어진  Aspose.Imaging.Size  의 음수만큼  Aspose.Imaging.Point  를 변환합니다. |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | 지정된  Aspose.Imaging.PointF  를 가장 가까운 정수로 반올림하여  Aspose.Imaging.Point  객체로 변환합니다. |
| [setX(int value)](#setX-int-) | 이  Aspose.Imaging.Point  의 x 좌표를 가져오거나 설정합니다. |
| [setY(int value)](#setY-int-) | 이  Aspose.Imaging.Point  의 y 좌표를 가져오거나 설정합니다. |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | 지정된  Aspose.Imaging.Point  에서 지정된  Aspose.Imaging.Size  를 빼는 결과를 반환합니다. |
| [toString()](#toString--) | 이  Aspose.Imaging.Point  를 사람이 읽을 수 있는 문자열로 변환합니다. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | 지정된  Point  구조체를  PointF  구조체로 변환합니다. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | 지정된  Aspose.Imaging.Point  구조체를  Aspose.Imaging.Size  구조체로 변환합니다. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | 지정된  Aspose.Imaging.PointF  를  Aspose.Imaging.Point  로 변환하되,  Aspose.Imaging.Point  의 값을 잘라냅니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


지정된 좌표를 사용하여  Aspose.Imaging.Point  구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 점의 수평 위치입니다. |
| y | int | 점의 수직 위치입니다. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Aspose.Imaging.Size 구조체에서 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 새 점 좌표를 포함합니다. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


정수 값으로 지정된 좌표를 사용하여  Aspose.Imaging.Point  구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dw | int | 새 점에 대한 좌표를 지정하는 32비트 정수입니다. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


점 형식을 나타냅니다.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


지정된  Aspose.Imaging.Size  를 지정된  Aspose.Imaging.Point  에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 추가할 Aspose.Imaging.Point 입니다. |
| size | [Size](../../com.aspose.psd/size) | 점에 추가할 Aspose.Imaging.Size 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


지정된  Aspose.Imaging.PointF  의 값을 다음 높은 정수값으로 반올림하여  Aspose.Imaging.Point  로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 변환할 Aspose.Imaging.PointF 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이  Aspose.Imaging.Point  가 지정된  System.Object  와 동일한 좌표를 포함하는지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 System.Object입니다. |

**Returns:**
boolean - obj가 Aspose.Imaging.Point이며 이 Aspose.Imaging.Point와 동일한 좌표를 가지고 있으면 true입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Aspose.Imaging.Point.X 및 Aspose.Imaging.Point.Y 값이 0으로 설정된  Aspose.Imaging.Point  구조체의 새 인스턴스를 가져옵니다.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


이  Aspose.Imaging.Point  의 x 좌표를 가져오거나 설정합니다.

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


이  Aspose.Imaging.Point  의 y 좌표를 가져오거나 설정합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


이  Aspose.Imaging.Point  에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이  Aspose.Imaging.Point  가 비어 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - Aspose.Imaging.Point.X와 Aspose.Imaging.Point.Y가 모두 0이면 true, 그렇지 않으면 false입니다.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


지정된  Aspose.Imaging.Point  로 이  Aspose.Imaging.Point  를 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 이 Aspose.Imaging.Point를 오프셋하는 데 사용되는 Aspose.Imaging.Point 입니다. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


지정된 양만큼 이  Aspose.Imaging.Point  를 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | int | x좌표를 오프셋할 양입니다. |
| dy | int | y좌표를 오프셋할 양입니다. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


주어진  Aspose.Imaging.Size  로  Aspose.Imaging.Point  를 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 변환할 Aspose.Imaging.Point 입니다. |
| size | [Size](../../com.aspose.psd/size) | 점의 좌표에 추가할 숫자 쌍을 지정하는 Aspose.Imaging.Size 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


두 Aspose.Imaging.Point 객체를 비교합니다. 결과는 두 Aspose.Imaging.Point 객체의 Aspose.Imaging.Point.X 및 Aspose.Imaging.Point.Y 속성 값이 동일한지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 비교할 첫 번째 Aspose.Imaging.Point 입니다. |
| point2 | [Point](../../com.aspose.psd/point) | 비교할 두 번째 Aspose.Imaging.Point 입니다. |

**Returns:**
boolean - point1과 point2의 Aspose.Imaging.Point.X 및 Aspose.Imaging.Point.Y 값이 동일하면 true, 그렇지 않으면 false입니다.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


두 Aspose.Imaging.Point 객체를 비교합니다. 결과는 두 Aspose.Imaging.Point 객체의 Aspose.Imaging.Point.X 또는 Aspose.Imaging.Point.Y 속성 값이 서로 다른지 여부를 지정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 비교할 첫 번째 Aspose.Imaging.Point 입니다. |
| point2 | [Point](../../com.aspose.psd/point) | 비교할 두 번째 Aspose.Imaging.Point 입니다. |

**Returns:**
boolean - point1과 point2의 Aspose.Imaging.Point.X 속성값 또는 Aspose.Imaging.Point.Y 속성값 중 하나라도 다르면 true, 그렇지 않으면 false입니다.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


주어진  Aspose.Imaging.Size  의 음수만큼  Aspose.Imaging.Point  를 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 변환할 Aspose.Imaging.Point 입니다. |
| size | [Size](../../com.aspose.psd/size) | 점의 좌표에서 빼는 숫자 쌍을 지정하는 Aspose.Imaging.Size 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


지정된  Aspose.Imaging.PointF  를 가장 가까운 정수로 반올림하여  Aspose.Imaging.Point  객체로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 변환할 Aspose.Imaging.PointF 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


이  Aspose.Imaging.Point  의 x 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


이  Aspose.Imaging.Point  의 y 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


지정된  Aspose.Imaging.Point  에서 지정된  Aspose.Imaging.Size  를 빼는 결과를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 빼는 대상이 되는 Aspose.Imaging.Point 입니다. |
| size | [Size](../../com.aspose.psd/size) | 점에서 빼는 Aspose.Imaging.Size 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


이  Aspose.Imaging.Point  를 사람이 읽을 수 있는 문자열로 변환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 System.String.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


지정된  Point  구조체를  PointF  구조체로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 변환될 Point 입니다. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


지정된  Aspose.Imaging.Point  구조체를  Aspose.Imaging.Size  구조체로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 변환될 Aspose.Imaging.Point 입니다. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


지정된  Aspose.Imaging.PointF  를  Aspose.Imaging.Point  로 변환하되,  Aspose.Imaging.Point  의 값을 잘라냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 변환할 Aspose.Imaging.PointF 입니다. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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


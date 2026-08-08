---
title: "Rectangle"
second_title: "Java용 Aspose.PSD API 참조"
description: "사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다."
type: docs
weight: 88
url: /ko/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 지정된 위치와 크기로  com.aspose.psd.Rectangle  구조의 새 인스턴스를 초기화합니다. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | 지정된 위치와 크기로  com.aspose.psd.Rectangle  구조의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | 지정된  com.aspose.psd.RectangleF  구조를  com.aspose.psd.Rectangle  구조로 변환합니다. 이때  com.aspose.psd.RectangleF  값들을 다음 높은 정수 값으로 반올림합니다. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | 지정된 점이 이  com.aspose.psd.Rectangle  구조 안에 포함되는지 확인합니다. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | rect 로 표시된 직사각형 영역이 이  com.aspose.psd.Rectangle  구조에 완전히 포함되는지 확인합니다. |
| [contains(int x, int y)](#contains-int-int-) | 지정된 점이 이  com.aspose.psd.Rectangle  구조 안에 포함되는지 확인합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | obj 가 이  com.aspose.psd.Rectangle  구조와 동일한 위치와 크기를 가진  com.aspose.psd.Rectangle  구조인지 테스트합니다. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | 지정된 가장자리 위치로  com.aspose.psd.Rectangle  구조를 생성합니다. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | 지정된 두 점으로부터 새로운  Rectangle  을 생성합니다. |
| [getBottom()](#getBottom--) | 이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.Y  및  com.aspose.psd.Rectangle.Height  속성 값들의 합인 y좌표를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width 및 com.aspose.psd.Rectangle.Height 값이 0으로 설정된 새로운  com.aspose.psd.Rectangle  구조 인스턴스를 가져옵니다. |
| [getHeight()](#getHeight--) | 이  com.aspose.psd.Rectangle  구조의 높이를 가져오거나 설정합니다. |
| [getLeft()](#getLeft--) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다. |
| [getLocation()](#getLocation--) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| [getRight()](#getRight--) | 이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.X 및  com.aspose.psd.Rectangle.Width  속성 값들의 합인 x좌표를 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 이  com.aspose.psd.Rectangle  구조의 크기를 가져오거나 설정합니다. |
| [getTop()](#getTop--) | 이  com.aspose.psd.Rectangle  구조의 상단 가장자리 y좌표를 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 이  com.aspose.psd.Rectangle  구조의 너비를 가져옵니다. |
| [getX()](#getX--) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다. |
| [getY()](#getY--) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 y좌표를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) | 이  com.aspose.psd.Rectangle  구조의 해시 코드를 반환합니다. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | 지정된  com.aspose.psd.Rectangle  구조의 확대된 복사본을 생성하고 반환합니다. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | 이  com.aspose.psd.Rectangle  를 지정된 양만큼 확대합니다. |
| [inflate(int width, int height)](#inflate-int-int-) | 이  com.aspose.psd.Rectangle  를 지정된 양만큼 확대합니다. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | 이  com.aspose.psd.Rectangle  를 자체와 지정된  com.aspose.psd.Rectangle  의 교차 영역으로 교체합니다. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 두 다른  com.aspose.psd.Rectangle  구조의 교차점을 나타내는 세 번째  com.aspose.psd.Rectangle  구조를 반환합니다. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | 이 사각형이 rect와 교차하는지 확인합니다. |
| [isEmpty()](#isEmpty--) | 이  com.aspose.psd.Rectangle  의 모든 숫자 속성이 0값인지 여부를 나타내는 값을 가져옵니다. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | 이  Rectangle  가 최소 부분적으로 보이는지 여부를 나타내는 값을 가져옵니다 |
| [normalize()](#normalize--) | 사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위가 아래보다 작도록 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| [offset(int x, int y)](#offset-int-int-) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 두 com.aspose.psd.Rectangle 구조가 위치와 크기가 같은지 테스트합니다. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 두 com.aspose.psd.Rectangle 구조가 위치 또는 크기가 다른지 테스트합니다. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | 지정된 com.aspose.psd.RectangleF를 가장 가까운 정수값으로 반올림하여 com.aspose.psd.Rectangle로 변환합니다. |
| [setBottom(int value)](#setBottom-int-) | 이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.Y  및  com.aspose.psd.Rectangle.Height  속성 값들의 합인 y좌표를 가져오거나 설정합니다. |
| [setHeight(int value)](#setHeight-int-) | 이  com.aspose.psd.Rectangle  구조의 높이를 가져오거나 설정합니다. |
| [setLeft(int value)](#setLeft-int-) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| [setRight(int value)](#setRight-int-) | 이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.X 및  com.aspose.psd.Rectangle.Width  속성 값들의 합인 x좌표를 가져오거나 설정합니다. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | 이  com.aspose.psd.Rectangle  구조의 크기를 가져오거나 설정합니다. |
| [setTop(int value)](#setTop-int-) | 이  com.aspose.psd.Rectangle  구조의 상단 가장자리 y좌표를 가져오거나 설정합니다. |
| [setWidth(int value)](#setWidth-int-) | 이 com.aspose.psd.Rectangle 구조의 너비를 설정합니다. |
| [setX(int value)](#setX-int-) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다. |
| [setY(int value)](#setY-int-) | 이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 y좌표를 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 com.aspose.psd.Rectangle의 속성을 사람이 읽을 수 있는 문자열로 변환합니다. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | 지정된 com.aspose.psd.RectangleF 값을 잘라내어 com.aspose.psd.Rectangle로 변환합니다. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 두 com.aspose.psd.Rectangle 구조의 합집합을 포함하는 com.aspose.psd.Rectangle 구조를 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


지정된 위치와 크기로  com.aspose.psd.Rectangle  구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | int | 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | int | 사각형의 너비입니다. |
| 높이 | int | 사각형의 높이입니다. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


지정된 위치와 크기로  com.aspose.psd.Rectangle  구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | 직사각형 영역의 왼쪽 위 모서리를 나타내는 com.aspose.psd.Point입니다. |
| size | [Size](../../com.aspose.psd/size) | 직사각형 영역의 너비와 높이를 나타내는 com.aspose.psd.Size입니다. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


지정된  com.aspose.psd.RectangleF  구조를  com.aspose.psd.Rectangle  구조로 변환합니다. 이때  com.aspose.psd.RectangleF  값들을 다음 높은 정수 값으로 반올림합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 변환될 com.aspose.psd.RectangleF 구조입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


지정된 점이 이  com.aspose.psd.Rectangle  구조 안에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 테스트할 com.aspose.psd.Point입니다. |

**Returns:**
boolean - 이 메서드는 point가 이 com.aspose.psd.Rectangle 구조 내에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


rect 로 표시된 직사각형 영역이 이  com.aspose.psd.Rectangle  구조에 완전히 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 테스트할 com.aspose.psd.Rectangle입니다. |

**Returns:**
boolean - 이 메서드는 rect가 이 com.aspose.psd.Rectangle 구조 내에 완전히 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


지정된 점이 이  com.aspose.psd.Rectangle  구조 안에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |

**Returns:**
boolean - 이 메서드는 x와 y로 정의된 점이 이 com.aspose.psd.Rectangle 구조 내에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj 가 이  com.aspose.psd.Rectangle  구조와 동일한 위치와 크기를 가진  com.aspose.psd.Rectangle  구조인지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 System.Object입니다. |

**Returns:**
boolean - 이 메서드는 obj가 com.aspose.psd.Rectangle 구조이며 해당 구조의 com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width, com.aspose.psd.Rectangle.Height 속성이 이 com.aspose.psd.Rectangle 구조의 대응 속성과 동일하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


지정된 가장자리 위치로  com.aspose.psd.Rectangle  구조를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | int | 이 com.aspose.psd.Rectangle 구조의 왼쪽 위 모서리의 x좌표입니다. |
| top | int | 이 com.aspose.psd.Rectangle 구조의 왼쪽 위 모서리의 y좌표입니다. |
| right | int | 이 com.aspose.psd.Rectangle 구조의 오른쪽 아래 모서리의 x좌표입니다. |
| 하단 | int | 이 com.aspose.psd.Rectangle 구조의 오른쪽 아래 모서리의 y좌표입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


지정된 두 점으로부터 새로운  Rectangle  를 생성합니다. 생성된  Rectangle  의 두 수직선은 전달된 point1과 point2와 동일합니다. 일반적으로 이는 반대 꼭짓점이 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 새 직사각형에 대한 첫 번째 Point. |
| point2 | [Point](../../com.aspose.psd/point) | 새 직사각형에 대한 두 번째 Point. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.Y  및  com.aspose.psd.Rectangle.Height  속성 값들의 합인 y좌표를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle의 com.aspose.psd.Rectangle.Y와 com.aspose.psd.Rectangle.Height를 합한 y좌표입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width 및 com.aspose.psd.Rectangle.Height 값이 0으로 설정된 새로운  com.aspose.psd.Rectangle  구조 인스턴스를 가져옵니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


이  com.aspose.psd.Rectangle  구조의 높이를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle 구조의 높이입니다.
### getLeft() {#getLeft--}
```
public int getLeft()
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle 구조의 왼쪽 가장자리 x좌표입니다.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.X 및  com.aspose.psd.Rectangle.Width  속성 값들의 합인 x좌표를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle의 com.aspose.psd.Rectangle.X와 com.aspose.psd.Rectangle.Width의 합인 x좌표입니다.
### getSize() {#getSize--}
```
public Size getSize()
```


이  com.aspose.psd.Rectangle  구조의 크기를 가져오거나 설정합니다.

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


이  com.aspose.psd.Rectangle  구조의 상단 가장자리 y좌표를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle 구조체의 상단 가장자리 y좌표입니다.
### getWidth() {#getWidth--}
```
public int getWidth()
```


이  com.aspose.psd.Rectangle  구조의 너비를 가져옵니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle 구조체의 너비입니다.
### getX() {#getX--}
```
public int getX()
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle 구조체의 왼쪽 위 모서리 x좌표입니다.
### getY() {#getY--}
```
public int getY()
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 y좌표를 가져오거나 설정합니다.

**Returns:**
int - 이 com.aspose.psd.Rectangle 구조체의 왼쪽 위 모서리 y좌표입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이  com.aspose.psd.Rectangle  구조의 해시 코드를 반환합니다.

**Returns:**
int - 이 사각형에 대한 해시 코드를 나타내는 정수입니다.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


지정된 com.aspose.psd.Rectangle 구조체의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 com.aspose.psd.Rectangle 구조체는 수정되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 시작할 com.aspose.psd.Rectangle입니다. 이 사각형은 수정되지 않습니다. |
| x | int | 이 com.aspose.psd.Rectangle를 수평으로 확대할 양입니다. |
| y | int | 이 com.aspose.psd.Rectangle를 수직으로 확대할 양입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


이  com.aspose.psd.Rectangle  를 지정된 양만큼 확대합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 이 직사각형을 확대할 양. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


이  com.aspose.psd.Rectangle  를 지정된 양만큼 확대합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 너비 | int | 이 com.aspose.psd.Rectangle를 수평으로 확대할 양입니다. |
| 높이 | int | 이 com.aspose.psd.Rectangle를 수직으로 확대할 양입니다. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


이  com.aspose.psd.Rectangle  를 자체와 지정된  com.aspose.psd.Rectangle  의 교차 영역으로 교체합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 교차할 com.aspose.psd.Rectangle입니다. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


두 다른 com.aspose.psd.Rectangle 구조체의 교차점을 나타내는 세 번째 com.aspose.psd.Rectangle 구조체를 반환합니다. 교차점이 없으면 빈 com.aspose.psd.Rectangle가 반환됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | 교차할 첫 번째 직사각형. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | 교차할 두 번째 직사각형. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


이 사각형이 rect와 교차하는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 테스트할 사각형. |

**Returns:**
boolean - 교차점이 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이  com.aspose.psd.Rectangle  의 모든 숫자 속성이 0값인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 com.aspose.psd.Rectangle의 com.aspose.psd.Rectangle.Width, com.aspose.psd.Rectangle.Height, com.aspose.psd.Rectangle.X 및 com.aspose.psd.Rectangle.Y 속성이 모두 0이면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


이  Rectangle  가 최소 부분적으로 보이는지 여부를 나타내는 값을 가져옵니다

**Returns:**
boolean - 이 Rectangle이 최소한 부분적으로 보이면 true, 그렇지 않으면 false입니다.
### normalize() {#normalize--}
```
public void normalize()
```


사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위가 아래보다 작도록 정규화합니다.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


이 사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | 위를 오프셋할 양입니다. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


이 사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 수평 오프셋입니다. |
| y | int | 수직 오프셋입니다. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


두 com.aspose.psd.Rectangle 구조가 위치와 크기가 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | 동등 연산자 왼쪽에 있는 com.aspose.psd.Rectangle 구조체입니다. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | 동등 연산자 오른쪽에 있는 com.aspose.psd.Rectangle 구조체입니다. |

**Returns:**
boolean - 두 com.aspose.psd.Rectangle 구조체가 com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width 및 com.aspose.psd.Rectangle.Height 속성이 모두 동일하면 true를 반환합니다.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


두 com.aspose.psd.Rectangle 구조가 위치 또는 크기가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | 부등 연산자 왼쪽에 있는 com.aspose.psd.Rectangle 구조체입니다. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | 부등 연산자 오른쪽에 있는 com.aspose.psd.Rectangle 구조체입니다. |

**Returns:**
boolean - 두 com.aspose.psd.Rectangle 구조체의 com.aspose.psd.Rectangle.X, com.aspose.psd.Rectangle.Y, com.aspose.psd.Rectangle.Width 또는 com.aspose.psd.Rectangle.Height 속성 중 하나라도 다르면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


지정된 com.aspose.psd.RectangleF를 가장 가까운 정수값으로 반올림하여 com.aspose.psd.Rectangle로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 변환할 com.aspose.psd.RectangleF입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.Y  및  com.aspose.psd.Rectangle.Height  속성 값들의 합인 y좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle의 com.aspose.psd.Rectangle.Y와 com.aspose.psd.Rectangle.Height의 합인 y좌표입니다. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


이  com.aspose.psd.Rectangle  구조의 높이를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle 구조체의 높이입니다. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle 구조체의 왼쪽 가장자리 x좌표입니다. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | 이 com.aspose.psd.Rectangle 구조체의 왼쪽 위 모서리를 나타내는 Point입니다. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


이  com.aspose.psd.Rectangle  구조의  com.aspose.psd.Rectangle.X 및  com.aspose.psd.Rectangle.Width  속성 값들의 합인 x좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle의 com.aspose.psd.Rectangle.X와 com.aspose.psd.Rectangle.Width의 합인 x좌표입니다. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


이  com.aspose.psd.Rectangle  구조의 크기를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | 이 com.aspose.psd.Rectangle 구조체의 너비와 높이를 나타내는 com.aspose.psd.Size입니다. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


이  com.aspose.psd.Rectangle  구조의 상단 가장자리 y좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle 구조체의 상단 가장자리 y좌표입니다. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


이 com.aspose.psd.Rectangle 구조의 너비를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle 구조체의 너비입니다. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle 구조의 왼쪽 위 모서리의 x좌표입니다. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


이  com.aspose.psd.Rectangle  구조의 왼쪽 위 모서리 y좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 com.aspose.psd.Rectangle 구조의 왼쪽 위 모서리의 y좌표입니다. |

### toString() {#toString--}
```
public String toString()
```


이 com.aspose.psd.Rectangle의 속성을 사람이 읽을 수 있는 문자열로 변환합니다.

**Returns:**
java.lang.String - 이 com.aspose.psd.Rectangle 구조체의 위치, 너비 및 높이를 포함하는 문자열입니다.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


지정된 com.aspose.psd.RectangleF 값을 잘라내어 com.aspose.psd.Rectangle로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 변환할 com.aspose.psd.RectangleF입니다. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


두 com.aspose.psd.Rectangle 구조의 합집합을 포함하는 com.aspose.psd.Rectangle 구조를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | 합집합할 첫 번째 사각형. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | 합집합할 두 번째 사각형. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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


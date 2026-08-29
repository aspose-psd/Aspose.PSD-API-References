---
title: "RectangleF"
second_title: "Java용 Aspose.PSD API 참조"
description: "사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자를 저장합니다."
type: docs
weight: 89
url: /ko/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자를 저장합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 지정된 위치와 크기로  com.aspose.psd.RectangleF  구조체의 새 인스턴스를 초기화합니다. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 지정된 위치와 크기로  com.aspose.psd.RectangleF  구조체의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | 지정된 점이 이  com.aspose.psd.RectangleF  구조체에 포함되는지 확인합니다. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | rect 로 표시된 직사각형 영역이 이  com.aspose.psd.RectangleF  구조체에 완전히 포함되는지 확인합니다. |
| [contains(float x, float y)](#contains-float-float-) | 지정된 점이 이  com.aspose.psd.RectangleF  구조체에 포함되는지 확인합니다. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | 현재 직사각형 값을 나누어 매트릭스의 수직 및 수평 스케일 값을 변환하고 결과 값을 가진 새로운 [RectangleF](../../com.aspose.psd/rectanglef) 인스턴스를 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | obj 가 이  com.aspose.psd.RectangleF 와 동일한 위치와 크기를 가진 com.aspose.psd.RectangleF 인지 테스트합니다. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | 지정된 위치에 좌상단과 우하단 모서리를 갖는  com.aspose.psd.RectangleF  구조체를 생성합니다. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 지정된 두 점으로부터 새로운  Rectangle  을 생성합니다. |
| [getBottom()](#getBottom--) | 이  com.aspose.psd.RectangleF  구조체의 com.aspose.psd.RectangleF.Y 와 com.aspose.psd.RectangleF.Height 의 합인 y 좌표를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | com.aspose.psd.RectangleF.X , com.aspose.psd.RectangleF.Y , com.aspose.psd.RectangleF.Width 및 com.aspose.psd.RectangleF.Height 값이 0으로 설정된  com.aspose.psd.RectangleF  구조체의 새 인스턴스를 가져옵니다. |
| [getHeight()](#getHeight--) | 이  com.aspose.psd.RectangleF  구조체의 높이를 가져오거나 설정합니다. |
| [getLeft()](#getLeft--) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 가장자리 x 좌표를 가져오거나 설정합니다. |
| [getLocation()](#getLocation--) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| [getRight()](#getRight--) | 이 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.X와 com.aspose.psd.RectangleF.Width의 합인 x 좌표를 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 이 com.aspose.psd.RectangleF의 크기를 가져오거나 설정합니다. |
| [getTop()](#getTop--) | 이 com.aspose.psd.RectangleF 구조체의 상단 가장자리 y 좌표를 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 이 com.aspose.psd.RectangleF 구조체의 너비를 가져오거나 설정합니다. |
| [getX()](#getX--) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 x 좌표를 가져오거나 설정합니다. |
| [getY()](#getY--) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 y 좌표를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) | 이 com.aspose.psd.RectangleF 구조체의 해시 코드를 가져옵니다. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | 지정된 com.aspose.psd.RectangleF 구조체의 확대된 복사본을 생성하고 반환합니다. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | 이 com.aspose.psd.RectangleF를 지정된 양만큼 확대합니다. |
| [inflate(float x, float y)](#inflate-float-float-) | 이 com.aspose.psd.RectangleF 구조체를 지정된 양만큼 확대합니다. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | 이 com.aspose.psd.RectangleF 구조체를 자체와 지정된 com.aspose.psd.RectangleF 구조체와의 교차 영역으로 교체합니다. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 두 사각형의 교차 영역을 나타내는 com.aspose.psd.RectangleF 구조체를 반환합니다. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | 이 사각형이 rect와 교차하는지 확인합니다. |
| [isEmpty()](#isEmpty--) | 이 com.aspose.psd.RectangleF의 com.aspose.psd.RectangleF.Width 또는 com.aspose.psd.RectangleF.Height 속성이 0인지 여부를 나타내는 값을 가져옵니다. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | 현재 사각형 값을 곱하여 변환 행렬의 수직 및 수평 스케일 값을 변환하고, 결과 값을 가진 새로운 [RectangleF](../../com.aspose.psd/rectanglef) 인스턴스를 반환합니다. |
| [normalize()](#normalize--) | 사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위가 아래보다 작도록 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| [offset(float x, float y)](#offset-float-float-) | 이 사각형의 위치를 지정된 양만큼 조정합니다. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | / 연산자를 구현합니다. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 두 com.aspose.psd.RectangleF 구조체가 위치와 크기가 같은지 테스트합니다. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 두 com.aspose.psd.RectangleF 구조체가 위치 또는 크기가 다른지 테스트합니다. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | * 연산자를 구현합니다. |
| [setBottom(float value)](#setBottom-float-) | 이  com.aspose.psd.RectangleF  구조체의 com.aspose.psd.RectangleF.Y 와 com.aspose.psd.RectangleF.Height 의 합인 y 좌표를 가져오거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 이  com.aspose.psd.RectangleF  구조체의 높이를 가져오거나 설정합니다. |
| [setLeft(float value)](#setLeft-float-) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 가장자리 x 좌표를 가져오거나 설정합니다. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| [setRight(float value)](#setRight-float-) | 이 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.X와 com.aspose.psd.RectangleF.Width의 합인 x 좌표를 가져오거나 설정합니다. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | 이 com.aspose.psd.RectangleF의 크기를 가져오거나 설정합니다. |
| [setTop(float value)](#setTop-float-) | 이 com.aspose.psd.RectangleF 구조체의 상단 가장자리 y 좌표를 가져오거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 이 com.aspose.psd.RectangleF 구조체의 너비를 가져오거나 설정합니다. |
| [setX(float value)](#setX-float-) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 x 좌표를 가져오거나 설정합니다. |
| [setY(float value)](#setY-float-) | 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 y 좌표를 가져오거나 설정합니다. |
| [toRectangle_internalized()](#toRectangle-internalized--) | [RectangleF](../../com.aspose.psd/rectanglef)를 잘린 사각형 값으로 [Rectangle](../../com.aspose.psd/rectangle) 구조체로 변환합니다. |
| [toString()](#toString--) | 이 com.aspose.psd.RectangleF의 속성을 사람이 읽을 수 있는 문자열로 변환합니다. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | 지정된 com.aspose.psd.Rectangle 구조를 com.aspose.psd.RectangleF 구조로 변환합니다. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 두 사각형을 합친 합집합을 포함할 수 있는 가장 작은 가능한 세 번째 사각형을 생성합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


지정된 위치와 크기로  com.aspose.psd.RectangleF  구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 사각형의 왼쪽 위 모서리의 x 좌표입니다. |
| y | float | 사각형의 왼쪽 위 모서리의 y 좌표입니다. |
| 너비 | float | 사각형의 너비입니다. |
| 높이 | float | 사각형의 높이입니다. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


지정된 위치와 크기로  com.aspose.psd.RectangleF  구조체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | 직사각형 영역의 왼쪽 위 모서리를 나타내는 com.aspose.psd.PointF입니다. |
| size | [SizeF](../../com.aspose.psd/sizef) | 직사각형 영역의 너비와 높이를 나타내는 com.aspose.psd.SizeF입니다. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


지정된 점이 이  com.aspose.psd.RectangleF  구조체에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 테스트할 com.aspose.psd.PointF입니다. |

**Returns:**
boolean - 이 메서드는 point 매개변수로 표시된 점이 이 com.aspose.psd.RectangleF 구조 내에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


rect 로 표시된 직사각형 영역이 이  com.aspose.psd.RectangleF  구조체에 완전히 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 테스트할 com.aspose.psd.RectangleF입니다. |

**Returns:**
boolean - 이 메서드는 rect로 표시된 직사각형 영역이 이 com.aspose.psd.RectangleF가 나타내는 직사각형 영역에 완전히 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


지정된 점이 이  com.aspose.psd.RectangleF  구조체에 포함되는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |

**Returns:**
boolean - x와 y로 정의된 점이 이 com.aspose.psd.RectangleF 구조 내에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


현재 직사각형 값을 나누어 매트릭스의 수직 및 수평 스케일 값을 변환하고 결과 값을 가진 새로운 [RectangleF](../../com.aspose.psd/rectanglef) 인스턴스를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| transformMatrix | double[] | 레이어 변환 행렬입니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj 가 이  com.aspose.psd.RectangleF 와 동일한 위치와 크기를 가진 com.aspose.psd.RectangleF 인지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 System.Object입니다. |

**Returns:**
boolean - obj가 com.aspose.psd.RectangleF이며 그 X, Y, Width, Height 속성이 이 com.aspose.psd.RectangleF의 해당 속성과 동일하면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


지정된 위치에 좌상단과 우하단 모서리를 갖는  com.aspose.psd.RectangleF  구조체를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | float | 직사각형 영역의 왼쪽 위 모서리의 x 좌표입니다. |
| top | float | 직사각형 영역의 왼쪽 위 모서리의 y 좌표입니다. |
| right | float | 직사각형 영역의 오른쪽 아래 모서리의 x 좌표입니다. |
| 하단 | float | 직사각형 영역의 오른쪽 하단 모서리의 y좌표. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


지정된 두 점으로부터 새로운 Rectangle을 생성합니다. 생성된 Rectangle의 두 꼭짓점은 전달된 point1과 point2와 동일합니다. 일반적으로 이는 반대쪽 꼭짓점이 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 새 직사각형에 대한 첫 번째 Point. |
| point2 | [PointF](../../com.aspose.psd/pointf) | 새 직사각형에 대한 두 번째 Point. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


이  com.aspose.psd.RectangleF  구조체의 com.aspose.psd.RectangleF.Y 와 com.aspose.psd.RectangleF.Height 의 합인 y 좌표를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.Y와 com.aspose.psd.RectangleF.Height의 합인 y좌표.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


com.aspose.psd.RectangleF.X , com.aspose.psd.RectangleF.Y , com.aspose.psd.RectangleF.Width 및 com.aspose.psd.RectangleF.Height 값이 0으로 설정된  com.aspose.psd.RectangleF  구조체의 새 인스턴스를 가져옵니다.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


이  com.aspose.psd.RectangleF  구조체의 높이를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 높이.
### getLeft() {#getLeft--}
```
public float getLeft()
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 가장자리 x 좌표를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 왼쪽 가장자리의 x좌표.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


이 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.X와 com.aspose.psd.RectangleF.Width의 합인 x 좌표를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.X와 com.aspose.psd.RectangleF.Width의 합인 x좌표.
### getSize() {#getSize--}
```
public SizeF getSize()
```


이 com.aspose.psd.RectangleF의 크기를 가져오거나 설정합니다.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


이 com.aspose.psd.RectangleF 구조체의 상단 가장자리 y 좌표를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 위쪽 가장자리의 y좌표.
### getWidth() {#getWidth--}
```
public float getWidth()
```


이 com.aspose.psd.RectangleF 구조체의 너비를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 너비.
### getX() {#getX--}
```
public float getX()
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 x 좌표를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리의 x좌표.
### getY() {#getY--}
```
public float getY()
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 y 좌표를 가져오거나 설정합니다.

**Returns:**
float - 이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리의 y좌표.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 com.aspose.psd.RectangleF 구조체의 해시 코드를 가져옵니다.

**Returns:**
int - 이 com.aspose.psd.RectangleF의 해시 코드.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


지정된 com.aspose.psd.RectangleF 구조체의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 직사각형은 수정되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 복사될 com.aspose.psd.RectangleF. 이 직사각형은 수정되지 않습니다. |
| x | float | 직사각형 복사본을 수평으로 확대할 양. |
| y | float | 직사각형 복사본을 수직으로 확대할 양. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


이 com.aspose.psd.RectangleF를 지정된 양만큼 확대합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 이 직사각형을 확대할 양. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


이 com.aspose.psd.RectangleF 구조체를 지정된 양만큼 확대합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 이 com.aspose.psd.RectangleF 구조체를 수평으로 확대할 양. |
| y | float | 이 com.aspose.psd.RectangleF 구조체를 수직으로 확대할 양. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


이 com.aspose.psd.RectangleF 구조체를 자체와 지정된 com.aspose.psd.RectangleF 구조체와의 교차 영역으로 교체합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 교차할 직사각형. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


두 직사각형의 교차를 나타내는 com.aspose.psd.RectangleF 구조체를 반환합니다. 교차가 없으면 빈 com.aspose.psd.RectangleF가 반환됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | 교차할 첫 번째 직사각형. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | 교차할 두 번째 직사각형. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


이 사각형이 rect와 교차하는지 확인합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 테스트할 사각형. |

**Returns:**
boolean - 이 메서드는 교차가 있으면 true를 반환합니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이 com.aspose.psd.RectangleF의 com.aspose.psd.RectangleF.Width 또는 com.aspose.psd.RectangleF.Height 속성이 0인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 속성은 이 com.aspose.psd.RectangleF의 com.aspose.psd.RectangleF.Width 또는 com.aspose.psd.RectangleF.Height 속성값이 0이면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


현재 사각형 값을 곱하여 변환 행렬의 수직 및 수평 스케일 값을 변환하고, 결과 값을 가진 새로운 [RectangleF](../../com.aspose.psd/rectanglef) 인스턴스를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| transformMatrix | double[] | 레이어 변환 행렬입니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
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




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


이 사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | 위치를 오프셋하는 양. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


이 사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 위치를 수평으로 오프셋하는 양. |
| y | float | 위치를 수직으로 오프셋하는 양. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


/ 연산자를 구현합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 그 사각형. |
| 구분자 | float | 구분자. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


두 com.aspose.psd.RectangleF 구조체가 위치와 크기가 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | 동등 연산자 왼쪽에 있는 com.aspose.psd.RectangleF 구조체. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | 동등 연산자 오른쪽에 있는 com.aspose.psd.RectangleF 구조체. |

**Returns:**
boolean - 두 지정된 com.aspose.psd.RectangleF 구조체가 com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width 및 com.aspose.psd.RectangleF.Height 속성이 모두 동일하면 true를 반환합니다.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


두 com.aspose.psd.RectangleF 구조체가 위치 또는 크기가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | 부등 연산자 왼쪽에 있는 com.aspose.psd.RectangleF 구조체. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | 부등 연산자 오른쪽에 있는 com.aspose.psd.RectangleF 구조체. |

**Returns:**
boolean - 두 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width 또는 com.aspose.psd.RectangleF.Height 속성 중 하나라도 서로 다르면 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


* 연산자를 구현합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 그 사각형. |
| 배수 | float | 배수. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


이  com.aspose.psd.RectangleF  구조체의 com.aspose.psd.RectangleF.Y 와 com.aspose.psd.RectangleF.Height 의 합인 y 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


이  com.aspose.psd.RectangleF  구조체의 높이를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 가장자리 x 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


이 com.aspose.psd.RectangleF 구조체의 com.aspose.psd.RectangleF.X와 com.aspose.psd.RectangleF.Width의 합인 x 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


이 com.aspose.psd.RectangleF의 크기를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


이 com.aspose.psd.RectangleF 구조체의 상단 가장자리 y 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


이 com.aspose.psd.RectangleF 구조체의 너비를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 x 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


이 com.aspose.psd.RectangleF 구조체의 왼쪽 위 모서리 y 좌표를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


[RectangleF](../../com.aspose.psd/rectanglef)를 잘린 사각형 값으로 [Rectangle](../../com.aspose.psd/rectangle) 구조체로 변환합니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


이 com.aspose.psd.RectangleF의 속성을 사람이 읽을 수 있는 문자열로 변환합니다.

**Returns:**
java.lang.String - 이 com.aspose.psd.RectangleF 구조체의 위치, 너비 및 높이를 포함하는 문자열.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


지정된 com.aspose.psd.Rectangle 구조를 com.aspose.psd.RectangleF 구조로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 변환할 com.aspose.psd.Rectangle 구조체. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


두 사각형을 합친 합집합을 포함할 수 있는 가장 작은 가능한 세 번째 사각형을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | 합집합할 첫 번째 사각형. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | 합집합할 두 번째 사각형. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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


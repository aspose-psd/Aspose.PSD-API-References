---
title: "TextShape"
second_title: "Java용 Aspose.PSD API 참조"
description: "텍스트 형태를 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.aspose.psd.shapes/textshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

텍스트 형태를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextShape()](#TextShape--) | TextShape 클래스의 새 인스턴스를 초기화합니다. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-) | TextShape 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 객체의 경계를 가져옵니다. |
| [getCenter()](#getCenter--) | 형상의 중심을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | 텍스트를 그리는 데 사용되는 글꼴을 가져오거나 설정합니다. |
| [getLeftBottom()](#getLeftBottom--) | 왼쪽 하단 사각형 점을 가져옵니다. |
| [getLeftTop()](#getLeftTop--) | 왼쪽 상단 사각형 점을 가져옵니다. |
| [getRectangleHeight()](#getRectangleHeight--) | 사각형 높이를 가져옵니다. |
| [getRectangleWidth()](#getRectangleWidth--) | 사각형 너비를 가져옵니다. |
| [getRightBottom()](#getRightBottom--) | 오른쪽 하단 사각형 점을 가져옵니다. |
| [getRightTop()](#getRightTop--) | 오른쪽 상단 사각형 점을 가져옵니다. |
| [getSegments()](#getSegments--) | 형상 세그먼트를 가져옵니다. |
| [getText()](#getText--) | 그려진 텍스트를 가져오거나 설정합니다. |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 가져오거나 설정합니다. |
| [hasSegments()](#hasSegments--) | 형상에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFont(Font value)](#setFont-com.aspose.psd.Font-) | 텍스트를 그리는 데 사용되는 글꼴을 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 그려진 텍스트를 가져오거나 설정합니다. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.psd.StringFormat-) | 텍스트 형식을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 지정된 변환을 모양에 적용합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextShape() {#TextShape--}
```
public TextShape()
```


TextShape 클래스의 새 인스턴스를 초기화합니다.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.psd.RectangleF-com.aspose.psd.Font-com.aspose.psd.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


TextShape 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 그릴 텍스트. |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 텍스트 사각형. |
| font | [Font](../../com.aspose.psd/font) | 사용할 글꼴. |
| stringFormat | [StringFormat](../../com.aspose.psd/stringformat) | 문자열 형식. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


객체의 경계를 가져옵니다.

값: 객체의 경계입니다.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


객체의 경계를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경계가 계산되기 전에 적용할 행렬입니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


객체의 경계를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경계가 계산되기 전에 적용할 행렬입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 객체에 사용할 펜입니다. 이는 객체의 경계 크기에 영향을 줄 수 있습니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


형상의 중심을 가져옵니다.

값: 형태의 중심입니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public Font getFont()
```


텍스트를 그리는 데 사용되는 글꼴을 가져오거나 설정합니다.

값: 텍스트를 그리는 데 사용되는 글꼴.

**Returns:**
[Font](../../com.aspose.psd/font)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


왼쪽 하단 사각형 점을 가져옵니다.

값: 왼쪽 하단 사각형 점입니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


왼쪽 상단 사각형 점을 가져옵니다.

값: 왼쪽 상단 사각형 점입니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


사각형 높이를 가져옵니다.

값: 사각형 높이입니다.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


사각형 너비를 가져옵니다.

값: 사각형 너비입니다.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


오른쪽 하단 사각형 점을 가져옵니다.

값: 오른쪽 하단 사각형 점입니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


오른쪽 상단 사각형 점을 가져옵니다.

값: 오른쪽 상단 사각형 점입니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


형상 세그먼트를 가져옵니다.

값: 모양 세그먼트.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getText() {#getText--}
```
public String getText()
```


그려진 텍스트를 가져오거나 설정합니다.

값: 그린 텍스트.

**Returns:**
java.lang.String
### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


텍스트 형식을 가져오거나 설정합니다.

값: 텍스트 형식.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


형상에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다.

값:  True  , 그렇지 않으면  false  .

**Returns:**
boolean
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




### setFont(Font value) {#setFont-com.aspose.psd.Font-}
```
public void setFont(Font value)
```


텍스트를 그리는 데 사용되는 글꼴을 가져오거나 설정합니다.

값: 텍스트를 그리는 데 사용되는 글꼴.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Font](../../com.aspose.psd/font) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


그려진 텍스트를 가져오거나 설정합니다.

값: 그린 텍스트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.psd.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


텍스트 형식을 가져오거나 설정합니다.

값: 텍스트 형식.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.psd/stringformat) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


지정된 변환을 모양에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 적용할 변환. |

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


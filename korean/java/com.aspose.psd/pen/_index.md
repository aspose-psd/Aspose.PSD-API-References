---
title: "Pen"
second_title: "Java용 Aspose.PSD API 참조"
description: "선, 곡선 및 도형을 그리는 데 사용되는 객체를 정의합니다."
type: docs
weight: 77
url: /ko/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

선, 곡선 및 도형을 그리는 데 사용되는 객체를 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | 지정된 색상으로 Pen 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | 지정된 Color 및 Pen.Width 속성을 사용하여 Pen 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | 지정된 Brush 로 Pen 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | 지정된 Brush 및 Pen.Width 로 Pen 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 이 Pen의 정렬을 가져옵니다. |
| [getBrush()](#getBrush--) | 이 Pen의 속성을 결정하는 Brush를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 이 Pen의 색상을 가져옵니다. |
| [getCompoundArray()](#getCompoundArray--) | 복합 펜을 지정하는 값 배열을 가져옵니다. |
| [getCustomEndCap()](#getCustomEndCap--) | 이 Pen으로 그린 선의 끝에 사용할 사용자 지정 캡을 가져옵니다. |
| [getCustomStartCap()](#getCustomStartCap--) | 이 Pen으로 그린 선의 시작에 사용할 사용자 지정 캡을 가져옵니다. |
| [getDashCap()](#getDashCap--) | 이 Pen으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져옵니다. |
| [getDashOffset()](#getDashOffset--) | 선의 시작점부터 대시 패턴 시작점까지의 거리를 가져옵니다. |
| [getDashPattern()](#getDashPattern--) | 사용자 지정 대시와 공백 배열을 가져옵니다. |
| [getDashStyle()](#getDashStyle--) | 이 Pen으로 그린 점선에 사용되는 스타일을 가져옵니다. |
| [getEndCap()](#getEndCap--) | 이 Pen으로 그린 선의 끝에 사용되는 캡 스타일을 가져옵니다. |
| [getLineJoin()](#getLineJoin--) | 이 Pen으로 그린 연속된 두 선의 끝에 대한 조인 스타일을 가져옵니다. |
| [getMiterLimit()](#getMiterLimit--) | 각진 모서리에서 조인 두께의 제한을 가져옵니다. |
| [getOpacity()](#getOpacity--) | 객체의 불투명도를 가져옵니다. |
| [getPenType()](#getPenType--) | 이 Pen으로 그린 선의 스타일을 가져옵니다. |
| [getStartCap()](#getStartCap--) | 이 Pen으로 그린 선의 시작에 사용되는 캡 스타일을 가져옵니다. |
| [getTransform()](#getTransform--) | 이 Pen에 대한 기하학적 변환 복사본을 가져옵니다. |
| [getWidth()](#getWidth--) | 그리기에 사용되는 Graphics 객체 단위로 이 Pen의 너비를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | 이  Pen  의 변환 행렬을 지정된  Matrix  로 곱합니다. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | 이  Pen  의 변환 행렬을 지정된  Matrix  로 지정된 순서대로 곱합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | 이  Pen  의 기하 변환 행렬을 단위 행렬로 재설정합니다. |
| [rotateTransform(float angle)](#rotateTransform-float-) | 지정된 각도만큼 로컬 기하 변환을 회전시킵니다. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 지정된 각도만큼 로컬 기하 변환을 지정된 순서대로 회전시킵니다. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 지정된 배율로 로컬 기하 변환을 스케일링합니다. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 지정된 배율로 로컬 기하 변환을 지정된 순서대로 스케일링합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 이  Pen  의 정렬을 설정합니다. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | 이  Pen  의 속성을 결정하는  Brush  를 설정합니다. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 이  Pen  의 색상을 설정합니다. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 복합 펜을 지정하는 값 배열을 설정합니다. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | 이  Pen  로 그린 선의 끝에 사용할 사용자 정의 캡을 설정합니다. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | 이  Pen  로 그린 선의 시작에 사용할 사용자 정의 캡을 설정합니다. |
| [setDashCap(int value)](#setDashCap-int-) | 이  Pen  로 그린 점선의 대시 끝에 사용되는 캡 스타일을 설정합니다. |
| [setDashOffset(float value)](#setDashOffset-float-) | 선의 시작부터 대시 패턴 시작까지의 거리를 설정합니다. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | 사용자 정의 대시와 공백의 배열을 설정합니다. |
| [setDashStyle(int value)](#setDashStyle-int-) | 이  Pen  로 그린 점선에 사용되는 스타일을 설정합니다. |
| [setEndCap(int value)](#setEndCap-int-) | 이  Pen  로 그린 선의 끝에 사용되는 캡 스타일을 설정합니다. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | 이  Pen  로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다. |
| [setLineJoin(int value)](#setLineJoin-int-) | 이  Pen  로 그린 두 연속 선의 끝에 대한 조인 스타일을 설정합니다. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 각진 코너에서 조인의 두께 제한을 설정합니다. |
| [setOpacity(float value)](#setOpacity-float-) | 객체의 불투명도를 설정합니다. |
| [setStartCap(int value)](#setStartCap-int-) | 이  Pen  로 그린 선의 시작에 사용되는 캡 스타일을 설정합니다. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 이  Pen  의 기하 변환 복사본을 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 그리기에 사용되는 Graphics 객체의 단위로 이  Pen  의 너비를 설정합니다. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 지정된 차원과 지정된 순서에 따라 로컬 기하 변환을 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


지정된 색상으로 Pen 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 이 Pen의 색을 나타내는 Color 구조체입니다. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


지정된 Color 및 Pen.Width 속성을 사용하여 Pen 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 이 Pen의 색을 나타내는 Color 구조체입니다. |
| 너비 | float | 이 Pen의 너비를 나타내는 값입니다. |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


지정된 Brush 로 Pen 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 이 Pen의 채우기 속성을 결정하는 Brush입니다. |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


지정된 Brush 및 Pen.Width 로 Pen 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 이 Pen의 특성을 결정하는 Brush입니다. |
| 너비 | float | 새 Pen의 너비입니다. |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


이 Pen의 정렬을 가져옵니다.

**Returns:**
int - 이 Pen의 정렬을 나타내는 PenAlignment입니다.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


이 Pen의 속성을 결정하는 Brush를 가져옵니다.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


이 Pen의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


복합 Pen을 지정하는 값 배열을 가져옵니다. 복합 Pen은 평행선과 간격으로 구성된 복합 라인을 그립니다.

**Returns:**
float[] - 복합 배열을 지정하는 실수 배열입니다. 배열의 요소는 오름차순이어야 하며 0보다 작지 않고 1보다 크지 않아야 합니다.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


이 Pen으로 그린 선의 끝에 사용할 사용자 지정 캡을 가져옵니다.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


이 Pen으로 그린 선의 시작에 사용할 사용자 지정 캡을 가져옵니다.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


이 Pen으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져옵니다.

**Returns:**
int - 이 Pen으로 그린 점선의 시작과 끝에 사용되는 대시 캡 스타일을 나타내는 DashCap 값 중 하나입니다.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


선의 시작점부터 대시 패턴 시작점까지의 거리를 가져옵니다.

**Returns:**
float - 선의 시작점부터 대시 패턴 시작점까지의 거리입니다.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


사용자 지정 대시와 공백 배열을 가져옵니다.

**Returns:**
float[] - 점선에서 교차하는 대시와 공백의 길이를 지정하는 실수 배열입니다.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


이 Pen으로 그린 점선에 사용되는 스타일을 가져옵니다.

**Returns:**
int - 이 Pen으로 그린 점선에 사용되는 스타일을 나타내는 DashStyle입니다.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


이 Pen으로 그린 선의 끝에 사용되는 캡 스타일을 가져옵니다.

**Returns:**
int - 이 Pen으로 그린 선의 끝에 사용되는 캡 스타일을 나타내는 LineCap 값 중 하나입니다.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


이 Pen으로 그린 연속된 두 선의 끝에 대한 조인 스타일을 가져옵니다.

**Returns:**
int - 이 Pen으로 그린 두 연속 선의 끝 연결 스타일을 나타내는 LineJoin입니다.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


각진 모서리에서 조인 두께의 제한을 가져옵니다.

**Returns:**
float - 마이터 코너에서 연결부의 두께 제한값입니다.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


객체의 불투명도를 가져옵니다. 값은 0과 1 사이여야 합니다. 0 값은 객체가 완전히 보임을 의미하고, 1 값은 객체가 완전히 불투명함을 의미합니다.

**Returns:**
float - 불투명도 값.
### getPenType() {#getPenType--}
```
public int getPenType()
```


이 Pen으로 그린 선의 스타일을 가져옵니다.

**Returns:**
int - 이 Pen으로 그린 선의 스타일을 지정하는 PenType 열거형입니다.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


이 Pen으로 그린 선의 시작에 사용되는 캡 스타일을 가져옵니다.

**Returns:**
int - 이 Pen으로 그린 선의 시작에 사용되는 캡 스타일을 나타내는 LineCap 값 중 하나입니다.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


이 Pen에 대한 기하학적 변환 복사본을 가져옵니다.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


그리기에 사용되는 Graphics 객체 단위로 이 Pen의 너비를 가져옵니다.

**Returns:**
float - 이 Pen의 너비입니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


이  Pen  의 변환 행렬을 지정된  Matrix  로 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 변환 행렬을 곱할 Matrix 객체입니다. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


이  Pen  의 변환 행렬을 지정된  Matrix  로 지정된 순서대로 곱합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 변환 행렬을 곱할 Matrix입니다. |
| order | int | 곱셈 연산을 수행할 순서입니다. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


이  Pen  의 기하 변환 행렬을 단위 행렬로 재설정합니다.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


지정된 각도만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


지정된 각도만큼 로컬 기하 변환을 지정된 순서대로 회전시킵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. |
| order | int | 회전 행렬을 추가하거나 앞에 삽입할지 지정하는 MatrixOrder입니다. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


지정된 계수만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링하는 비율. |
| sy | float | y축 방향으로 변환을 스케일링하는 비율. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


지정된 배율로 로컬 기하 변환을 지정된 순서대로 스케일링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | float | x축 방향으로 변환을 스케일링하는 비율. |
| sy | float | y축 방향으로 변환을 스케일링하는 비율. |
| order | int | 스케일링 행렬을 추가하거나 앞에 삽입할지 지정하는 MatrixOrder. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


이  Pen  의 정렬을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 Pen의 정렬을 나타내는 PenAlignment. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


이  Pen  의 속성을 결정하는  Brush  를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | 이 Pen의 속성을 결정하는 Brush. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


이  Pen  의 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 이 Pen의 색을 나타내는 Color 구조체. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


복합 펜을 지정하는 값 배열을 설정합니다. 복합 펜은 평행선과 간격으로 구성된 복합 라인을 그립니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float[] | 복합 배열을 지정하는 실수 배열입니다. 배열의 요소는 오름차순이어야 하며 0보다 작지 않고 1보다 크지 않아야 합니다. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


이  Pen  로 그린 선의 끝에 사용할 사용자 정의 캡을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | 이 Pen으로 그린 선의 끝에 사용되는 캡을 나타내는 CustomLineCap. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


이  Pen  로 그린 선의 시작에 사용할 사용자 정의 캡을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | 이 Pen으로 그린 선의 시작에 사용되는 캡을 나타내는 CustomLineCap. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


이  Pen  로 그린 점선의 대시 끝에 사용되는 캡 스타일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 Pen으로 그린 점선의 대시 시작과 끝에 사용되는 캡 스타일을 나타내는 DashCap 값 중 하나. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


선의 시작부터 대시 패턴 시작까지의 거리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 선의 시작부터 대시 패턴이 시작되는 지점까지의 거리. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


사용자 정의 대시와 공백의 배열을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float[] | 점선에서 교대로 나타나는 대시와 공백의 길이를 지정하는 실수 배열. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


이  Pen  로 그린 점선에 사용되는 스타일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 Pen으로 그린 점선에 사용되는 스타일을 나타내는 DashStyle. |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


이  Pen  로 그린 선의 끝에 사용되는 캡 스타일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 Pen으로 그린 선의 끝에 사용되는 캡 스타일을 나타내는 LineCap 값 중 하나. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


이  Pen  로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startCap | int | 이 Pen으로 그린 선의 시작에 사용할 캡 스타일을 나타내는 LineCap. |
| endCap | int | 이 Pen으로 그린 선의 끝에 사용할 캡 스타일을 나타내는 LineCap. |
| dashCap | int | 이 Pen으로 그린 점선의 시작 또는 끝에 사용할 캡 스타일을 나타내는 LineCap. |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


이  Pen  로 그린 두 연속 선의 끝에 대한 조인 스타일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 Pen으로 그린 연속된 두 선의 끝에 대한 연결 스타일을 나타내는 LineJoin. |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


각진 코너에서 조인의 두께 제한을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 각진 코너에서 연결부의 두께 제한. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


객체의 불투명도를 설정합니다. 값은 0과 1 사이여야 합니다. 0 값은 객체가 완전히 보임을 의미하고, 1 값은 객체가 완전히 불투명함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 불투명도 값. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


이  Pen  로 그린 선의 시작에 사용되는 캡 스타일을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 이 Pen으로 그린 선의 시작에 사용되는 캡 스타일을 나타내는 LineCap 값 중 하나. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


이  Pen  의 기하 변환 복사본을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | 이 Pen에 대한 기하학적 변환을 나타내는 Matrix의 복사본. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


그리기에 사용되는 Graphics 객체의 단위로 이  Pen  의 너비를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 이 Pen의 너비. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


지정된 치수만큼 로컬 기하학적 변환을 이동시킵니다. 이 메서드는 변환 앞에 이동을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


지정된 차원과 지정된 순서에 따라 로컬 기하 변환을 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dx | float | x 방향 평행 이동 값입니다. |
| dy | float | y 방향 평행 이동 값입니다. |
| order | int | 평행 이동을 적용할 순서(앞에 삽입 또는 뒤에 추가)입니다. |

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

